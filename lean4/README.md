# Evertophy — Lean 4 Formal Verification Archive

[🇬🇧 English](README.md) | [🇹🇷 Türkçe](README_TURKISH.md)

This folder holds every Lean 4 source produced in the Evertophy programme between September and October 2026, packed as four ZIP archives. One of them, the **Claude Lean Archive**, contains the canonical formal package **Evertophy-Formal RUN-19**, which is the package behind the statement in the main README: *269 theorem declarations, 46 in the isolated production core and 223 in the archive, with complete proofs.*

On **7 November 2026** all four archives were unpacked and rebuilt from scratch with the official Lean 4.12.0 toolchain. This document records what was checked, what passed, what did not, and how each result was derived.

> **Scope, stated up front.** These are results about the *encoded system*: they show that the type and algebraic skeleton written down in Lean is internally consistent and that the stated theorems follow from the stated definitions. They are not a physical verification of Evertophy. The canonical numerical-prediction counter remains **0/10**.

---

## 1. Status at a glance

| Item | Result (rebuild of 2026-11-07) |
|---|---|
| Canonical package | Evertophy-Formal **RUN-19** (inside `Evertophy_Claude_Lean_Arsivi_20261009.zip`, folder `A_Kanonik_RUN19/`) |
| Toolchain | Lean **4.12.0** (commit `dc2533473114`), Lake 5.0.0 · **no Mathlib** |
| Modules compiled | **32 / 32** · errors **0** · warnings **0** · no source file left uncompiled |
| Theorem declarations | **269** = **46** production core (`Core/`) + **223** archive |
| `sorry` / `admit` / project `axiom` | **0 / 0 / 0** |
| Axioms actually used by theorems | Only Lean's standard kernel axioms: `propext` (54 theorems), `Quot.sound` (25), `Classical.choice` (11). **No** `sorryAx`, **no** `native_decide` (`Lean.ofReduceBool`), **no** custom axiom |
| Production isolation | `Core/` modules import only `Core/` modules |
| Integrity | Archive manifest 76/76 · RUN-19 internal manifest 45/45 · original RUN-19 ZIP SHA-256 `f380f0df…ea560c8` matches the value recorded in V24 |

---

## 2. Contents of this folder

| File | Size | SHA-256 | Role | Status |
|---|---|---|---|---|
| `Evertophy_Claude_Lean_Arsivi_20261009.zip` | 95,893 B | `e6e8a4032346f4c3192b6d1b1c0acf38737e1af53c640552bd2a4fdbdd2f215f` | **Canonical archive.** RUN-19 package, V23 type system, cross-compilation fixes, superseded versions | ✅ Fully verified (see §3–§6) |
| `Evertophy_Lean_Derlemesi_Kimi_20261009.zip` | 9,790 B | `d477e4f4cdde2ae55fbfa8eabc585ddd869955d6f818e951aff280f5f13d7930` | Kimi's partial collection | ⚠️ 4 files identical to RUN-19 and compile; 5 marathon fragments do not (see §8.2) |
| `Evertophy_Lean_Kodlari_20261009_ChatGPT(Evertophy 20261003 Codex).zip` | 1,123,570 B | `4c290018586a75dc427d52d8504e93f437ee66920a24368b63a9752e002ff43d` | Codex collection of Lean excerpts quoted inside project documents | ℹ️ Excerpts, not a buildable project (see §8.3) |
| `Evertophy_Lean_Tum_Erisilebilir_Kaynaklar_20261009_ChatGPT(Dusunce Dedeyleri 202609).zip` | 7,221,113 B | `4355aafa1602dbfe1d9c47f8dbd921731600eb378eb5ed46fba574fb8f5977e5` | Complete source collection: RUN-19 copy, 27 original packages, 311 code blocks from text archives | ✅ RUN-19 copy byte-identical; historical packages rebuild (see §8.4) |

The four archives overlap heavily. Everything that the formal claims rest on is in the first one.

---

## 3. The canonical package: Evertophy-Formal RUN-19

### 3.1 Structure

The package is split into a **production core** and an **archive**:

- **Production core** — library `Core`, namespace `EvCore`, default build target. Seven modules, 46 theorems. It imports **no** archive module and uses **none** of the superseded definitions (`adjacent`, `K2_cp_mass`, `GlobalPole.Ux`, `metricOK`, Float intervals).
- **Archive** — libraries `Evertophy`, `Claude`, `V03`, `V24`. Twenty-five modules, 223 theorems. They record the development history, including rulings that were later superseded. Conflicts between old and current definitions are not hidden: they are stated as theorems in `V24/Quarantine.lean`.

### 3.2 How to build

```bash
# inside A_Kanonik_RUN19/Evertophy-Formal  (Lean 4.12.0 and lake on PATH)
lake build                          # production core (default target)
lake build Evertophy Claude V03 V24 # archive
```

From the root of the unpacked Claude archive, `bash PAKET_DOGRULA.sh` runs the whole check (A: RUN-19, B: V23 type system, C: cross-compilation fixes) on a temporary copy without touching the sources.

---

## 4. Derivation chain

### 4.1 Production core: import chain

Each module imports only the one before it:

```
Core.Production → Core.Extended → Core.Roles → Core.GateLock → Core.Final → Core.GateLockGen → Core.GateLockChar
   (RUN-12)          (RUN-13)        (RUN-14)      (RUN-14)        (RUN-16)       (RUN-17)            (RUN-18)
```

`import Core.Production` gives the basic semantics; `import Core.GateLockChar` gives the full production stack.

### 4.2 Archive: dependency graph

```
Evertophy.Phase ─┬─► Evertophy.Quantity ─► Evertophy.Time ─┐
                 │                                          ├─► Evertophy.Consistency ─► Claude.Sonnet
Evertophy.Range ─┼──────────────────────────────────────────┘
                 ├─► V24.Global ─────────┐
                 ├─► V24.Patches ────────┤
                 ├─► V24.Absence         ├─► V24.Quarantine
                 └─► V24.Types ─┬─► V24.Production ─► V24.BridgeNoGo ─┘
                                └─► V24.Ledger

V03.StampSpec ─┬─► V03.Assoc
               ├─► V03.QSigma
               ├─► V03.Archive ◄─┐
               ├─► V03.Omega   ◄─┴─ V03.Interval
               └─► V24.StampAssoc ─► V24.Rewrite ─► V24.Confluence ─► V24.Idem

V24.Topology   (standalone)
```

### 4.3 Development history (RUN-03 → RUN-19)

Each run answered a specific finding from the cross-AI audit rounds. The header comment of every module records which run and which finding it addresses.

| Run | Module(s) | What was added or corrected | Trigger |
|---|---|---|---|
| pre-RUN | `Evertophy.Phase/Quantity/Range/Time/Consistency`, `V03.*` | Phase ontology, banded quantities, Range formalism, emergent time, stamp monoid specification and associativity | V23 period; ChatGPT-GPTs v0.3 specification; Fable build certification |
| — | `V03.Interval` | Exact (integer) interval arithmetic | Fable finding: Float breaks associativity through rounding |
| RUN-03 | `V24.StampAssoc`, `V24.Patches` | General associativity of the stamp monoid for all words (not a finite scan); K2 split into dimension label vs. rest mass | ChatGPT Q3 task |
| RUN-04 | `V24.Topology` | Line vs. circle adjacency (path vs. K3) | ChatGPT S¹ counter-example |
| RUN-05 | `V24.Absence` | Two distinct absences: undefined in c₀, dissolved in c⁺ | Author's direct input (2026-09-24) |
| RUN-06 | `V24.Rewrite`, `V24.Types` | Termination of rewriting and a single normal form; type corrections | ChatGPT round 5 |
| RUN-07 | `V24.Confluence` | Full Church–Rosser property | Missing lemma: every word reduces to its normal form |
| RUN-08 | `V24.Idem`, `V24.Production` | Complete classification of idempotents; phase-indexed value type with band payload | Wolfram P0 and ChatGPT Math & Physics |
| RUN-09 | `V24.BridgeNoGo` | Cₘ readout bridge that preserves the cause of absence; non-uniqueness of the bridge under the frozen admissibility set | ChatGPT round 8 |
| RUN-10 | `V24.Ledger` | Missing data is epistemic, not ontological absence; machine-readable status ledger | Round 9 consensus |
| RUN-11 | `V24.Quarantine` | Every legacy API related to its production counterpart by a theorem | ContextSeed Run10 "critical formal debt" |
| RUN-12 | `Core.Production` | **Production core created**, free of every legacy module | Wolfram RUN-11 migration list (P0 + P1) |
| RUN-13 | `Core.Extended` | Band multiplication soundness, zero-band and empty-intersection guards, trace policy | Wolfram acceptance criteria C, D, E |
| RUN-14 | `Core.Roles`, `Core.GateLock` | Role types and typed Cₘ readout; Cₘ-only physical primitives cannot cross any gate | Kimi round 13 (V77-5); ChatGPT round 13 §7 |
| RUN-16 | `Core.Final` | X crosses every gate as meta-coordination, which is not physical transport | Last two optional partial items |
| RUN-17 | `Core.GateLockGen` | General form of the gate lock by native-phase set, four cases | ChatGPT Thought Experiments DD-16-03 |
| RUN-18 | `Core.GateLockChar` | Full characterisation: gate-locked ⟺ at most one native phase; archive count is monotone in provenance order | ChatGPT-DD D-04 / Wolfram round 17 §5 |
| RUN-19 | assurance tools | Isolation checker v2.1, adversarial matrix (14/14), negative regression test | Final package; all Lean sources from RUN-08 to RUN-18 are carried over byte-identically |

RUN-11 to RUN-15 original ZIPs were not found in any collection; their sources survive unchanged inside the later cumulative packages.

### 4.4 Logical chain of the main results

**Stamp monoid (archive algebra).**

```
StampSpec: M = ⟨s, s′, κ₀ₘ, κ₊ₘ | κ² = κ⟩, normalize
  → StampAssoc: mulW_assoc            (associativity for all words)
  → Rewrite:   step_decreases, normalize_irred, unique_normal_form
  → Confluence: star_to_normalize, church_rosser
  → Idem:      normalize_is_irred, idempotent_iff   (Idem(M) = {e, κ₀ₘ, κ₊ₘ})
```

Because there is no erase primitive, the archive algebra is a monoid, not a group, and its lock stamps are idempotent.

**Gate lock (what may cross between phases).**

```
Production: gate_full_K3, gate_symm, gate_irrefl     (full bidirectional triangle, no self-loops)
  + NativeOK licence: transport needs the quantity to be native at both ends
  → GateLock:     cm_only_gate_locked                 (Cₘ-only primitives cross no gate)
                  gate_lock_does_not_block_readout    (transport ≠ readout)
  → GateLockGen:  never_native_locked, single_native_locked, all_native_crosses, transport_is_gen
  → GateLockChar: gate_locked_iff_at_most_one         (locked ⟺ at most one native phase)
```

Cₘ-only primitives are physical time, 3-D space, the metric, intrinsic speed, the c boundary and rest mass. Because a gate always joins two *different* phases and these quantities are native only to Cₘ, none of them can be transported. The lock does not stop effects sourced in c⁺ from being *read* in Cₘ.

**Two absences.** `Core.Production` encodes Cₘ-only values as a phase-indexed type with three constructors (`undefined0`, `presentCm`, `dissolvedPlus`), so a value of the wrong phase cannot be built; `c0_undefined` and `cp_dissolved` follow. The archive module `V24.Absence` states the distinction directly as `two_absences_distinct`.

---

## 5. Module inventory

### 5.1 Production core — 46 theorems

| Module | Theorems | Content |
|---|---|---|
| `Core/Production.lean` | 17 | Full K3 gate (`gate_full_K3`, `gate_symm`, `gate_irrefl`); transport separate from gate; X crosses every gate; K2 as label only; source phase ≠ native licence; Cₘ-only value type (`c0_undefined`, `cp_dissolved`); Uₓ is not a pole; metric only in Cₘ; sound integer band arithmetic (`add_sound`, `neg_sound`, `inter_sound`); a point inside a band is never rejected; `strict_discrete_unique` |
| `Core/Extended.lean` | 9 | Band multiplication soundness; zero band is not invertible; empty intersection ≠ [0,0]; +∞ upper end is present in Cₘ; trace not derived from dissolution; toy midpoint selector |
| `Core/Roles.lean` | 4 | A c⁺-sourced event read in Cₘ is present; an observation in c⁺ is necessarily dissolved; transport ≠ readout; generic band conversion |
| `Core/GateLock.lean` | 3 | `cm_only_gate_locked`, `only_labels_cross`, `gate_lock_does_not_block_readout` |
| `Core/Final.lean` | 3 | Trace policy for sealed records; X meta-crosses every gate; meta-crossing ≠ physical transport |
| `Core/GateLockGen.lean` | 5 | General gate lock by native-phase set (none, one, two, all) |
| `Core/GateLockChar.lean` | 5 | `gate_locked_iff_at_most_one`; counter-examples to the older "witness" form; archive count monotone and strict under append |

### 5.2 Archive — 223 theorems

| Module | Theorems | Module | Theorems |
|---|---|---|---|
| `Evertophy/Phase.lean` | 31 | `V24/Global.lean` | 25 |
| `Evertophy/Consistency.lean` | 20 | `V24/Absence.lean` | 10 |
| `Evertophy/Time.lean` | 12 | `V24/Patches.lean` | 10 |
| `Evertophy/Range.lean` | 3 | `V24/Types.lean` | 9 |
| `Evertophy/Quantity.lean` | 0 | `V24/StampAssoc.lean` | 8 |
| `Claude/Sonnet.lean` | 0 (sensitivity bounds via `#eval`) | `V24/Quarantine.lean` | 8 |
| `V03/Assoc.lean` | 15 | `V24/BridgeNoGo.lean` | 6 |
| `V03/StampSpec.lean` | 14 | `V24/Confluence.lean` | 5 |
| `V03/QSigma.lean` | 9 | `V24/Ledger.lean` | 5 |
| `V03/Interval.lean` | 6 | `V24/Production.lean` | 5 |
| `V03/Archive.lean` | 5 | `V24/Rewrite.lean` | 5 |
| `V03/Omega.lean` | 4 | `V24/Topology.lean` | 5 |
| | | `V24/Idem.lean` | 3 |

**Legacy theorems in the archive.** Some archive theorems encode rulings that the current canon has replaced. For example, `Evertophy/Phase.lean` still contains `chain_no_skip_fwd : adjacent .c0 .cp = false` (linear chain) and `K2_cp_mass : carriable .cp Dim.mass = true`. They are kept unchanged for SHA stability. `V24/Quarantine.lean` records each conflict as a theorem (`legacy_adjacent_conflicts`, `legacy_K2_scoped`, `legacy_GlobalPole_superseded`, …), and the production core uses none of them.

---

## 6. Independent rebuild of 7 November 2026

### 6.1 Environment

- Linux x86_64 sandbox in Anthropic's cloud, clean session.
- Lean 4.12.0 downloaded from the official release page `github.com/leanprover/lean4/releases/v4.12.0`.
- Each ZIP unpacked into its own empty directory; builds run on copies.

### 6.2 Checks and results

| # | Check | Method | Result |
|---|---|---|---|
| 1 | Production build | `lake build` | ✅ success, 0 warnings |
| 2 | Archive build | `lake build Evertophy Claude V03 V24` | ✅ success, 0 warnings |
| 3 | Nothing skipped | Every `.lean` source compared with the produced `.olean` files | ✅ 32/32 compiled |
| 4 | Theorem count | Source-level count of `theorem` declarations, comments removed | ✅ 269 (46 + 223) |
| 5 | Theorem count, cross-check | All theorem constants read from the compiled Lean environment | 335 = 269 declared + 66 generated automatically by Lean (`ofNat_toCtorIdx` and `DecidableEq` proofs from `deriving`, and `Prop` fields of structures such as `Band.valid`). The 269 figure is the correct count of declared theorems |
| 6 | Axiom audit | A Lean metaprogram imported all 32 modules and ran `collectAxioms` on every theorem | ✅ no `sorryAx`, no `Lean.ofReduceBool`, no project axiom; only `propext`, `Quot.sound`, `Classical.choice` |
| 7 | Text scan | `sorry`, `admit`, `axiom`, `native_decide`, `unsafe`, `implemented_by`, `extern` | ✅ none in RUN-19 |
| 8 | Isolation | Imports of all `Core/` modules | ✅ only `Core.*` |
| 9 | Integrity | `sha256sum -c` on both manifests; SHA-256 of the original RUN-19 ZIP | ✅ 76/76, 45/45, `f380f0df9f55afff16a9c3f38a72d1b8cde1c96c02e050ef30ace7283ea560c8` |
| 10 | Duplicate copy | RUN-19 inside the ChatGPT full archive vs. the Claude archive | ✅ byte-identical (`diff -r` empty) |
| 11 | Content spot-check | Statements of the results cited in the main README located in the source | ✅ `unique_normal_form`, `church_rosser`, `mulW_assoc`, `idempotent_iff`, `two_absences_distinct`, `cm_only_gate_locked`, `gate_locked_iff_at_most_one` |
| 12 | Document-only theorems | `mpb_c0`, `mpb_cp`, `mpb_Cm` (V24 §570.3, "Fable Lean test") appear in the documents but in no Lean source. Recompiled against RUN-19's `Evertophy.Phase` | ✅ pass; depend on no axioms |

### 6.3 Nature of the proofs

By an automatic count, 176 of the 269 theorems have one-step proofs (`decide`, `rfl`, `trivial` or `simp`). These are direct checks of finite definitions written by the author: they confirm that the encoding says what it is meant to say. The structurally substantial results, such as associativity, termination, unique normal forms, Church–Rosser, the idempotent classification and the gate-lock characterisation, are proved by induction and case analysis.

### 6.4 What this rebuild does not establish

- It was carried out by Claude. The original packages were also compiled by Claude, so this is not the "U40-B" check (independent build on a different machine by a different provider). A rebuild by a third party remains open.
- The packages' own Python assurance scripts (isolation checker, adversarial matrix, regression) were not re-executed; the same properties were checked by independent methods (checks 3, 6, 7, 8).
- Two Qwen/Kimi files that import Mathlib could not be compiled because the Mathlib cache servers were unreachable from the sandbox. Both are incomplete for independent reasons (§8), so this does not affect any conclusion.

---

## 7. Other material in the Claude archive

| Folder | Content | Status |
|---|---|---|
| `B_V23_Tip_Sistemi/` | V23-period (September 2026) phase-aware dimension and range type system: `Core`, `Dim`, `FormalCore`, `Kimi5`, `V23`, `Fail` · 22 theorems + 46 `example` | ✅ Five files compile. ✅ `Fail.lean` fails as intended: it is a negative test showing that a dimensionless Γ does not give `dt` the dimension of time. ⚠️ **Superseded rulings:** `FormalCore.lean` encodes `timeMode .c0 = .zero` (current canon: T(c₀) = ⊥₀ ≠ 0), `adjacent .c0 .cp = false` (current canon: full triangle) and `carriable .cp Dim.mass = true` (current canon: rest mass is Cₘ-only). These files are a historical record, not current canon. ℹ️ `V23.lean` uses `native_decide` in two `example`s on Float values; no theorem depends on it |
| `C_Capraz_Derleme_Duzeltmeleri/` | `ChatGPT_Run01_fixed.lean` (10 theorems; `Rat` → `Int`), `Qwen_b5_nomathlib.lean` (Mathlib-free `ChartOK` part; `by decide` → `fun h => h`), and the diff | ✅ Both compile |
| `D_Tarihsel_Surumler/` | `Topology_RUN04_eski.lean` and 16 historical `lakefile` versions | ✅ The RUN-04 Topology compiles. ℹ️ Its theorem name `circle_has_no_interior_max` overstated the content and was renamed `euler_circle_zero_disk_one` in RUN-06 |

---

## 8. The other three archives: status and archive records

### 8.1 Summary of defects found

None of the items below is part of the 269-theorem claim, and none is named in the published documents (main README, Core Ontology minor16, V24 minor20).

| File | Found in | Defect | Status / replacement |
|---|---|---|---|
| `ChatGPT_Run01.lean` (original) | ChatGPT full archive (MiniLab folders) | Compile error at 63:12: "typeclass instance problem is stuck" | Superseded by `ChatGPT_Run01_fixed.lean` (Claude archive, C), which compiles |
| `b5.lean` (Qwen) | ChatGPT full archive | `X_deriv` has no proof body; `decide` applied to a `Prop` without a `Decidable` instance. Fails even with Mathlib | Mathlib-free part superseded by `Qwen_b5_nomathlib.lean` (C). `X` as a logistic function is a retired reading |
| `b2.lean` (Qwen) = `formal_core_v02_snmario.lean` (Kimi) | both | Three `sorry`. `arrow_from_monotone_sealing` is **false as stated**: the hypothesis `0 < Ndot` is declared as a `variable` but not used in the statement, so Lean does not include it, and the claim fails for negative `Ndot`. `global_quotient_link : Nonempty GlobalLevel` is vacuous (`Unit ≃ Unit`) and asserts a U₀–U₊ correspondence, which conflicts with the Principle of Silence. Treats X(x) as a logistic function (retired) | Historical draft (FORMAL-CORE v0.2, September marathon). Not to be cited |
| `snippet_bridge_nonunique.lean` (Kimi) | Kimi | Proof is the placeholder `...` | Proven counterpart: `bridge_non_uniqueness` in `V24/BridgeNoGo.lean` |
| `snippet_phase_absence.lean` (Kimi) | Kimi | Uses undefined `restMassAdmissible`, `Context` | Proven counterparts: `metric_only_Cm` (Core), `cp_no_rest_mass` (`V24/Patches.lean`) |
| `snippet_resolve_is_admissible.lean` (Kimi) | Kimi | Signature only; `State`, `ResolveX`, `Syntax` undefined | Open target, never proven |
| `snippet_exp_deriv.lean` (Kimi) | Kimi | Same content as `b5.lean` | As for `b5.lean` |
| `PhaseRange_Candidate_UNCOMPILED.lean` | ChatGPT full archive | None: it compiles, and its three theorems depend on no axioms. Only the file name is misleading | Historical candidate |
| `V24_Run05/06/07_*_Candidate.lean` | ChatGPT full archive | None: they compile. Run07 lists its proof targets inside a comment; the proofs live in `V24/Confluence.lean` and `V24/Idem.lean` | Historical candidates |
| `Evertophy_Formal_Core_v0_1.lean` (2026-09-13) | ChatGPT full archive | None: compiles; 20 theorems, no axioms | Precursor of `B_V23_Tip_Sistemi/FormalCore.lean` |

### 8.2 Kimi collection (`Evertophy_Lean_Derlemesi_Kimi_20261009.zip`)

- 9 Lean files; manifest 10/10.
- `lean_erken_arsiv/Assoc.lean`, `Omega.lean` and `lean_oturum_parcalari/Absence_Tur5.lean`, `BridgeNoGo.lean` are **byte-identical** to `V03/Assoc`, `V03/Omega`, `V24/Absence` and `V24/BridgeNoGo` in RUN-19 and compile.
- The five `lean_maraton_snmario/` files are fragments quoted in the September marathon report. Kimi's own manifest labels the archive "partial" and states that no Lean toolchain was available. Their defects are listed in §8.1.

### 8.3 Codex collection (`...ChatGPT(Evertophy 20261003 Codex).zip`)

- 23 excerpts extracted byte-for-byte from project documents (V24 minor18, Core minor11, a Codex report), labelled `EXTRACTED_NOT_TYPECHECKED` by the collector. They are not modules: most are signatures listed in the text without proofs.
- 5 compile on their own; 18 are signatures or fragments.
- They mention 49 theorem names. 45 exist under the same name in RUN-19; `gate_symmetric_1/2/3` is shorthand for three RUN-19 theorems; `mpb_c0/cp/Cm` exist only in the document and were recompiled successfully (§6.2, check 12).

### 8.4 ChatGPT full source collection (`...ChatGPT(Dusunce Dedeyleri 202609).zip`)

- Manifest 1409/1409.
- `01_START_HERE_RUN19/` is byte-identical to the RUN-19 package in the Claude archive.
- `02_UNIQUE_LEAN/` and `05_PACKAGE_TREES/` hold 586 Lean files. Of these, 481 are byte-identical to RUN-19 files, 23 to files in the Claude archive's B and C folders, 48 are `lakefile`s, and **8 distinct contents** remain; each of the 8 is listed in §8.1.
- Rebuild of all 36 historical package trees: 14 build as they are. The other 22 are MiniLab working folders that contain only a few files while their `lakefile` names modules stored elsewhere (error "no such file or directory"). After supplying the missing modules from RUN-19, whose contents are byte-identical, **all 22 build**.
- `03_ARCHIVE_CODE_BLOCKS/` holds 311 code blocks taken from text archives. They are quotations, not modules: 7 compile on their own and the rest lack their surrounding definitions. Of 344 theorem mentions, 329 have a theorem of the same name in RUN-19 and 7 in an older package; the remaining 8 are the items explained in §8.1 and §8.3. One block contains `sorry` (the `b2` draft).
- `04_ORIGINAL_PACKAGES/` keeps 27 original ZIPs, including RUN-08, 09, 10, 16, 17, 18 and 19.

---

## 9. Reproducing the check

```bash
# 1. Lean 4.12.0 (no Mathlib needed)
#    https://github.com/leanprover/lean4/releases/tag/v4.12.0

# 2. Unpack the canonical archive
unzip Evertophy_Claude_Lean_Arsivi_20261009.zip
cd Evertophy_Claude_Lean_Arsivi_20261009

# 3. One-command check (works on a temporary copy)
bash PAKET_DOGRULA.sh

# 4. Or build RUN-19 by hand
cd A_Kanonik_RUN19/Evertophy-Formal
lake build
lake build Evertophy Claude V03 V24

# 5. Integrity
sha256sum -c SHA256_MANIFEST.txt
```

To repeat the axiom audit, compile a file that imports every module and runs `#print axioms <theorem>` (or `Lean.collectAxioms`) for each theorem. A correct result lists only `propext`, `Quot.sound` and `Classical.choice`.

---

## 10. Record

- **Programme:** Evertophy — Uğur Yılmaz · Independent Researcher, Istanbul · ORCID [0009-0007-2243-5581](https://orcid.org/0009-0007-2243-5581)
- **Lean code:** written with AI assistance (mainly Claude; cross-audit by ChatGPT, Kimi, Wolfram, Qwen and others), under the author's direction. See the AI-use note in the [main README](../README.md).
- **Archives dated:** 2026-10-09 · **Independent rebuild:** 2026-11-07 (Lean 4.12.0)
- **Companion records:** Core Ontology DOI [10.5281/zenodo.23806039](https://doi.org/10.5281/zenodo.23806039) · V24 rolling master DOI [10.5281/zenodo.23744787](https://doi.org/10.5281/zenodo.23744787)
- **Status:** formal consistency of the encoded system ≠ physical verification · counter **0/10**
