# Evertophy — Lean 4 Biçimsel Doğrulama Arşivi

[🇬🇧 English](README.md) | [🇹🇷 Türkçe](README_TURKISH.md)

Bu klasör, Evertophy programında Eylül–Ekim 2026 arasında üretilen tüm Lean 4 kaynaklarını dört ZIP arşivi olarak barındırır. Bunlardan biri olan **Claude Lean Arşivi**, kanonik biçimsel paket **Evertophy-Formal RUN-19**'u içerir. Ana README'deki şu ifadenin dayandığı paket budur: *46'sı yalıtılmış üretim çekirdeğinde, 223'ü arşivde olmak üzere toplam 269 teorem bildirimi, eksiksiz kanıtlarla.*

**7 Kasım 2026** tarihinde dört arşivin tamamı açıldı ve resmî Lean 4.12.0 araç zinciriyle sıfırdan yeniden derlendi. Bu belge neyin denetlendiğini, neyin geçtiğini, neyin geçmediğini ve her sonucun nasıl elde edildiğini kayıt altına alır.

> **Kapsam, en baştan.** Buradaki sonuçlar *kodlanmış sistem* hakkındadır: Lean'de yazılmış tip ve cebir iskeletinin kendi içinde tutarlı olduğunu ve belirtilen teoremlerin belirtilen tanımlardan çıktığını gösterir. Evertophy'nin fiziksel doğrulaması değildir. Kanonik sayısal öngörü sayacı **0/10**'dur.

---

## 1. Özet durum

| Öğe | Sonuç (2026-11-07 yeniden derlemesi) |
|---|---|
| Kanonik paket | Evertophy-Formal **RUN-19** (`Evertophy_Claude_Lean_Arsivi_20261009.zip` içinde, `A_Kanonik_RUN19/` klasörü) |
| Araç zinciri | Lean **4.12.0** (commit `dc2533473114`), Lake 5.0.0 · **Mathlib yok** |
| Derlenen modül | **32 / 32** · hata **0** · uyarı **0** · derlenmeden kalan kaynak dosya yok |
| Teorem bildirimi | **269** = **46** üretim çekirdeği (`Core/`) + **223** arşiv |
| `sorry` / `admit` / proje `axiom` | **0 / 0 / 0** |
| Teoremlerin gerçekte kullandığı aksiyomlar | Yalnızca Lean'in standart çekirdek aksiyomları: `propext` (54 teorem), `Quot.sound` (25), `Classical.choice` (11). `sorryAx` **yok**, `native_decide` (`Lean.ofReduceBool`) **yok**, özel aksiyom **yok** |
| Üretim izolasyonu | `Core/` modülleri yalnızca `Core/` modüllerini içe aktarır |
| Bütünlük | Arşiv manifesti 76/76 · RUN-19 iç manifesti 45/45 · özgün RUN-19 ZIP'inin SHA-256 değeri `f380f0df…ea560c8`, V24'teki kayıtla birebir aynı |

---

## 2. Klasör içeriği

| Dosya | Boyut | SHA-256 | Rol | Durum |
|---|---|---|---|---|
| `Evertophy_Claude_Lean_Arsivi_20261009.zip` | 95.893 B | `e6e8a4032346f4c3192b6d1b1c0acf38737e1af53c640552bd2a4fdbdd2f215f` | **Kanonik arşiv.** RUN-19 paketi, V23 tip sistemi, çapraz derleme düzeltmeleri, geçersiz kılınmış sürümler | ✅ Tam doğrulandı (bkz. §3–§6) |
| `Evertophy_Lean_Derlemesi_Kimi_20261009.zip` | 9.790 B | `d477e4f4cdde2ae55fbfa8eabc585ddd869955d6f818e951aff280f5f13d7930` | Kimi'nin kısmi derlemesi | ⚠️ 4 dosya RUN-19 ile aynı ve derlenir; 5 maraton parçası derlenmez (bkz. §8.2) |
| `Evertophy_Lean_Kodlari_20261009_ChatGPT(Evertophy 20261003 Codex).zip` | 1.123.570 B | `4c290018586a75dc427d52d8504e93f437ee66920a24368b63a9752e002ff43d` | Proje belgelerinde alıntılanan Lean parçalarının Codex derlemesi | ℹ️ Alıntılardır, derlenebilir bir proje değildir (bkz. §8.3) |
| `Evertophy_Lean_Tum_Erisilebilir_Kaynaklar_20261009_ChatGPT(Dusunce Dedeyleri 202609).zip` | 7.221.113 B | `4355aafa1602dbfe1d9c47f8dbd921731600eb378eb5ed46fba574fb8f5977e5` | Tam kaynak koleksiyonu: RUN-19 kopyası, 27 özgün paket, metin arşivlerinden 311 kod bloğu | ✅ RUN-19 kopyası bayt düzeyinde aynı; tarihsel paketler yeniden derlenir (bkz. §8.4) |

Dört arşiv büyük ölçüde örtüşür. Biçimsel iddiaların dayandığı her şey ilk arşivdedir.

---

## 3. Kanonik paket: Evertophy-Formal RUN-19

### 3.1 Yapı

Paket bir **üretim çekirdeği** ve bir **arşiv** olarak ikiye ayrılır:

- **Üretim çekirdeği** — `Core` kütüphanesi, `EvCore` ad alanı, varsayılan derleme hedefi. Yedi modül, 46 teorem. Hiçbir arşiv modülünü içe aktarmaz ve geçersiz kılınmış tanımların (`adjacent`, `K2_cp_mass`, `GlobalPole.Ux`, `metricOK`, Float aralıklar) **hiçbirini** kullanmaz.
- **Arşiv** — `Evertophy`, `Claude`, `V03`, `V24` kütüphaneleri. Yirmi beş modül, 223 teorem. Sonradan geçersiz kılınan hükümler dahil gelişim geçmişini kayıt altında tutar. Eski ve güncel tanımlar arasındaki çelişkiler gizlenmez; `V24/Quarantine.lean` içinde teorem olarak yazılmıştır.

### 3.2 Derleme

```bash
# A_Kanonik_RUN19/Evertophy-Formal içinde  (Lean 4.12.0 ve lake PATH'te)
lake build                          # üretim çekirdeği (varsayılan hedef)
lake build Evertophy Claude V03 V24 # arşiv
```

Açılmış Claude arşivinin kök klasöründe `bash PAKET_DOGRULA.sh` komutu tüm denetimi (A: RUN-19, B: V23 tip sistemi, C: çapraz derleme düzeltmeleri) kaynaklara dokunmadan geçici bir kopya üzerinde çalıştırır.

---

## 4. Türetim zinciri

### 4.1 Üretim çekirdeği: içe aktarım zinciri

Her modül yalnızca bir öncekini içe aktarır:

```
Core.Production → Core.Extended → Core.Roles → Core.GateLock → Core.Final → Core.GateLockGen → Core.GateLockChar
   (RUN-12)          (RUN-13)        (RUN-14)      (RUN-14)        (RUN-16)       (RUN-17)            (RUN-18)
```

`import Core.Production` temel semantiği, `import Core.GateLockChar` tam üretim yığınını verir.

### 4.2 Arşiv: bağımlılık grafiği

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

V24.Topology   (bağımsız)
```

### 4.3 Gelişim geçmişi (RUN-03 → RUN-19)

Her koşu, çapraz yapay zekâ denetim turlarındaki belirli bir bulguya yanıt verdi. Her modülün başlık yorumu, hangi koşuya ve hangi bulguya ait olduğunu kaydeder.

| Koşu | Modül(ler) | Eklenen veya düzeltilen | Tetikleyen |
|---|---|---|---|
| RUN öncesi | `Evertophy.Phase/Quantity/Range/Time/Consistency`, `V03.*` | Faz ontolojisi, bant değerli nicelikler, Range formalizmi, beliren zaman, damga monoidi spesifikasyonu ve birleşme | V23 dönemi; ChatGPT-GPTs v0.3 spesifikasyonu; Fable derleme sertifikası |
| — | `V03.Interval` | Kesin (tam sayı) aralık aritmetiği | Fable bulgusu: Float, yuvarlama yüzünden birleşme özelliğini bozuyor |
| RUN-03 | `V24.StampAssoc`, `V24.Patches` | Damga monoidinin tüm kelimeler için genel birleşmesi (sonlu tarama değil); K2'nin boyut etiketi ve durgun kütle olarak ayrılması | ChatGPT Q3 görevi |
| RUN-04 | `V24.Topology` | Doğru ve çember üzerinde komşuluk (yol ve K3) | ChatGPT S¹ karşı-örneği |
| RUN-05 | `V24.Absence` | İki ayrı yokluk: c₀'da tanımsız, c⁺'ta çözünmüş | Yazarın doğrudan girdisi (2026-09-24) |
| RUN-06 | `V24.Rewrite`, `V24.Types` | Yeniden yazmanın sonlanması ve tek normal form; tip düzeltmeleri | ChatGPT 5. tur |
| RUN-07 | `V24.Confluence` | Tam Church–Rosser özelliği | Eksik lemma: her kelime normal formuna indirgenir |
| RUN-08 | `V24.Idem`, `V24.Production` | İdempotentlerin tam sınıflandırması; bant yüklü faz-indeksli değer tipi | Wolfram P0 ve ChatGPT Math & Physics |
| RUN-09 | `V24.BridgeNoGo` | Yokluk nedenini koruyan Cₘ okuma köprüsü; dondurulmuş kabul kümesi altında köprünün tekil olmaması | ChatGPT 8. tur |
| RUN-10 | `V24.Ledger` | Eksik veri epistemiktir, ontolojik yokluk değildir; makine-okunur statü defteri | 9. tur konsensüsü |
| RUN-11 | `V24.Quarantine` | Her eski API, üretim karşılığına bir teoremle bağlandı | ContextSeed Run10 "kritik biçimsel borç" |
| RUN-12 | `Core.Production` | **Üretim çekirdeği oluşturuldu**; tüm eski modüllerden bağımsız | Wolfram RUN-11 göç listesi (P0 + P1) |
| RUN-13 | `Core.Extended` | Bant çarpımının sağlamlığı, sıfır bant ve boş kesişim korumaları, iz politikası | Wolfram kabul ölçütleri C, D, E |
| RUN-14 | `Core.Roles`, `Core.GateLock` | Rol tipleri ve tipli Cₘ okuması; Cₘ'ye özgü fiziksel ilkeller hiçbir kapıdan geçemez | Kimi 13. tur (V77-5); ChatGPT 13. tur §7 |
| RUN-16 | `Core.Final` | X, meta-koordinasyon olarak her kapıdan geçer; bu fiziksel taşıma değildir | Son iki isteğe bağlı kısmi madde |
| RUN-17 | `Core.GateLockGen` | Kapı kilidinin içsel faz kümesine göre genel biçimi, dört durum | ChatGPT Düşünce Deneyleri DD-16-03 |
| RUN-18 | `Core.GateLockChar` | Tam karakterizasyon: kapı-kilitli ⟺ en fazla bir içsel faz; arşiv sayımı kaynak sırasında monotondur | ChatGPT-DD D-04 / Wolfram 17. tur §5 |
| RUN-19 | güvence araçları | İzolasyon denetçisi v2.1, düşman matrisi (14/14), negatif regresyon testi | Son paket; RUN-08…RUN-18 arası tüm Lean kaynakları bayt düzeyinde aynen taşınmıştır |

RUN-11…RUN-15 özgün ZIP'leri hiçbir koleksiyonda bulunamadı; kaynakları sonraki kümülatif paketlerin içinde değişmeden korunmaktadır.

### 4.4 Ana sonuçların mantıksal zinciri

**Damga monoidi (arşiv cebiri).**

```
StampSpec: M = ⟨s, s′, κ₀ₘ, κ₊ₘ | κ² = κ⟩, normalize
  → StampAssoc: mulW_assoc            (tüm kelimeler için birleşme)
  → Rewrite:   step_decreases, normalize_irred, unique_normal_form
  → Confluence: star_to_normalize, church_rosser
  → Idem:      normalize_is_irred, idempotent_iff   (Idem(M) = {e, κ₀ₘ, κ₊ₘ})
```

Silme temel işlemi bulunmadığı için arşiv cebiri bir grup değil, bir monoiddir ve kilit damgaları idempotenttir.

**Kapı kilidi (fazlar arasında neyin geçebileceği).**

```
Production: gate_full_K3, gate_symm, gate_irrefl     (tam çift yönlü üçgen, kendine döngü yok)
  + NativeOK lisansı: taşıma, niceliğin iki uçta da içsel olmasını gerektirir
  → GateLock:     cm_only_gate_locked                 (Cₘ'ye özgü ilkeller hiçbir kapıdan geçmez)
                  gate_lock_does_not_block_readout    (taşıma ≠ okuma)
  → GateLockGen:  never_native_locked, single_native_locked, all_native_crosses, transport_is_gen
  → GateLockChar: gate_locked_iff_at_most_one         (kilitli ⟺ en fazla bir içsel faz)
```

Cₘ'ye özgü ilkeller; fiziksel zaman, 3B uzay, metrik, içsel hız, c sınırı ve durgun kütledir. Kapı her zaman iki *farklı* fazı bağladığı ve bu nicelikler yalnızca Cₘ'de içsel olduğu için hiçbiri taşınamaz. Kilit, c⁺ kaynaklı etkilerin Cₘ'de *okunmasını* engellemez.

**İki yokluk.** `Core.Production`, Cₘ'ye özgü değerleri üç kuruculu (`undefined0`, `presentCm`, `dissolvedPlus`) faz-indeksli bir tip olarak kodlar; böylece yanlış fazda değer inşa edilemez ve `c0_undefined` ile `cp_dissolved` teoremleri doğrudan çıkar. Arşiv modülü `V24.Absence` ayrımı `two_absences_distinct` olarak doğrudan ifade eder.

---

## 5. Modül envanteri

### 5.1 Üretim çekirdeği — 46 teorem

| Modül | Teorem | İçerik |
|---|---|---|
| `Core/Production.lean` | 17 | Tam K3 kapı (`gate_full_K3`, `gate_symm`, `gate_irrefl`); taşıma kapıdan ayrı; X her kapıdan geçer; K2 yalnızca etiket; kaynak fazı ≠ içsel lisans; Cₘ'ye özgü değer tipi (`c0_undefined`, `cp_dissolved`); Uₓ kutup değildir; metrik yalnızca Cₘ'de; sağlam tam sayı bant aritmetiği (`add_sound`, `neg_sound`, `inter_sound`); bant içindeki nokta asla reddedilmez; `strict_discrete_unique` |
| `Core/Extended.lean` | 9 | Bant çarpımı sağlamlığı; sıfır bant terslenemez; boş kesişim ≠ [0,0]; +∞ üst uç Cₘ'de mevcuttur; iz, çözünmeden türetilmez; oyuncak orta nokta seçicisi |
| `Core/Roles.lean` | 4 | c⁺ kaynaklı olay Cₘ'de okunduğunda mevcuttur; c⁺'taki gözlem zorunlu olarak çözünmüştür; taşıma ≠ okuma; genel bant dönüşümü |
| `Core/GateLock.lean` | 3 | `cm_only_gate_locked`, `only_labels_cross`, `gate_lock_does_not_block_readout` |
| `Core/Final.lean` | 3 | Mühürlü kayıtlar için iz politikası; X her kapıdan meta-geçer; meta-geçiş ≠ fiziksel taşıma |
| `Core/GateLockGen.lean` | 5 | İçsel faz kümesine göre genel kapı kilidi (hiç, bir, iki, hepsi) |
| `Core/GateLockChar.lean` | 5 | `gate_locked_iff_at_most_one`; eski "tanık" biçimine karşı-örnekler; arşiv sayımı ekleme altında monoton ve kesin artan |

### 5.2 Arşiv — 223 teorem

| Modül | Teorem | Modül | Teorem |
|---|---|---|---|
| `Evertophy/Phase.lean` | 31 | `V24/Global.lean` | 25 |
| `Evertophy/Consistency.lean` | 20 | `V24/Absence.lean` | 10 |
| `Evertophy/Time.lean` | 12 | `V24/Patches.lean` | 10 |
| `Evertophy/Range.lean` | 3 | `V24/Types.lean` | 9 |
| `Evertophy/Quantity.lean` | 0 | `V24/StampAssoc.lean` | 8 |
| `Claude/Sonnet.lean` | 0 (`#eval` ile duyarlılık sınırları) | `V24/Quarantine.lean` | 8 |
| `V03/Assoc.lean` | 15 | `V24/BridgeNoGo.lean` | 6 |
| `V03/StampSpec.lean` | 14 | `V24/Confluence.lean` | 5 |
| `V03/QSigma.lean` | 9 | `V24/Ledger.lean` | 5 |
| `V03/Interval.lean` | 6 | `V24/Production.lean` | 5 |
| `V03/Archive.lean` | 5 | `V24/Rewrite.lean` | 5 |
| `V03/Omega.lean` | 4 | `V24/Topology.lean` | 5 |
| | | `V24/Idem.lean` | 3 |

**Arşivdeki eski teoremler.** Bazı arşiv teoremleri, güncel kanonun yerine koyduğu hükümleri kodlar. Örneğin `Evertophy/Phase.lean` hâlâ `chain_no_skip_fwd : adjacent .c0 .cp = false` (doğrusal zincir) ve `K2_cp_mass : carriable .cp Dim.mass = true` teoremlerini içerir. SHA kararlılığı için değiştirilmeden tutulurlar. `V24/Quarantine.lean` her çelişkiyi bir teorem olarak kaydeder (`legacy_adjacent_conflicts`, `legacy_K2_scoped`, `legacy_GlobalPole_superseded`, …); üretim çekirdeği bunların hiçbirini kullanmaz.

---

## 6. 7 Kasım 2026 bağımsız yeniden derlemesi

### 6.1 Ortam

- Anthropic bulutunda Linux x86_64 çalışma alanı, temiz oturum.
- Lean 4.12.0, resmî sürüm sayfasından indirildi: `github.com/leanprover/lean4/releases/v4.12.0`.
- Her ZIP kendi boş klasörüne açıldı; derlemeler kopyalar üzerinde yapıldı.

### 6.2 Denetimler ve sonuçlar

| # | Denetim | Yöntem | Sonuç |
|---|---|---|---|
| 1 | Üretim derlemesi | `lake build` | ✅ başarılı, uyarı 0 |
| 2 | Arşiv derlemesi | `lake build Evertophy Claude V03 V24` | ✅ başarılı, uyarı 0 |
| 3 | Atlanan dosya yok | Her `.lean` kaynağı üretilen `.olean` dosyalarıyla karşılaştırıldı | ✅ 32/32 derlendi |
| 4 | Teorem sayısı | Yorumlar çıkarılarak kaynakta `theorem` bildirimi sayımı | ✅ 269 (46 + 223) |
| 5 | Teorem sayısı, çapraz kontrol | Derlenmiş Lean ortamından tüm teorem sabitleri okundu | 335 = 269 bildirilmiş + Lean'in otomatik ürettiği 66 (`deriving` kaynaklı `ofNat_toCtorIdx` ve `DecidableEq` kanıtları; `Band.valid` gibi yapıların `Prop` alanları). Bildirilmiş teoremlerin doğru sayısı 269'dur |
| 6 | Aksiyom denetimi | Bir Lean metaprogramı 32 modülün tamamını içe aktarıp her teorem için `collectAxioms` çalıştırdı | ✅ `sorryAx` yok, `Lean.ofReduceBool` yok, proje aksiyomu yok; yalnızca `propext`, `Quot.sound`, `Classical.choice` |
| 7 | Metin taraması | `sorry`, `admit`, `axiom`, `native_decide`, `unsafe`, `implemented_by`, `extern` | ✅ RUN-19'da hiçbiri yok |
| 8 | İzolasyon | Tüm `Core/` modüllerinin içe aktarımları | ✅ yalnızca `Core.*` |
| 9 | Bütünlük | İki manifest üzerinde `sha256sum -c`; özgün RUN-19 ZIP'inin SHA-256 değeri | ✅ 76/76, 45/45, `f380f0df9f55afff16a9c3f38a72d1b8cde1c96c02e050ef30ace7283ea560c8` |
| 10 | Kopya karşılaştırması | ChatGPT tam arşivindeki RUN-19 ile Claude arşivindeki | ✅ bayt düzeyinde aynı (`diff -r` boş) |
| 11 | İçerik örneklemesi | Ana README'de atıf yapılan sonuçların ifadeleri kaynakta bulundu | ✅ `unique_normal_form`, `church_rosser`, `mulW_assoc`, `idempotent_iff`, `two_absences_distinct`, `cm_only_gate_locked`, `gate_locked_iff_at_most_one` |
| 12 | Yalnızca belgede geçen teoremler | `mpb_c0`, `mpb_cp`, `mpb_Cm` (V24 §570.3, "Fable Lean testi") belgelerde var, hiçbir Lean kaynağında yok. RUN-19'un `Evertophy.Phase` modülüne karşı yeniden derlendi | ✅ geçti; hiçbir aksiyoma dayanmıyor |

### 6.3 Kanıtların niteliği

Otomatik bir sayıma göre 269 teoremin 176'sı tek adımlı kanıtlardır (`decide`, `rfl`, `trivial` veya `simp`). Bunlar yazarın yazdığı sonlu tanımların doğrudan kontrolüdür: kodlamanın, söylemesi gerekeni söylediğini doğrular. Birleşme, sonlanma, normal form tekliği, Church–Rosser, idempotent sınıflandırması ve kapı kilidi karakterizasyonu gibi yapısal olarak esaslı sonuçlar ise tümevarım ve durum analiziyle kanıtlanmıştır.

### 6.4 Bu yeniden derlemenin göstermediği

- Yeniden derleme Claude tarafından yapıldı. Özgün paketler de Claude tarafından derlenmişti; bu nedenle bu denetim "U40-B" (farklı makinede, farklı sağlayıcıyla bağımsız derleme) yerine geçmez. Üçüncü bir tarafın yeniden derlemesi açık bir adım olarak kalmaktadır.
- Paketlerin kendi Python güvence betikleri (izolasyon denetçisi, düşman matrisi, regresyon) yeniden çalıştırılmadı; aynı özellikler bağımsız yöntemlerle denetlendi (denetim 3, 6, 7, 8).
- Mathlib içe aktaran iki Qwen/Kimi dosyası, Mathlib önbellek sunucularına çalışma alanından erişilemediği için derlenemedi. İkisi de başka nedenlerle zaten tamamlanmamış durumda (§8); bu durum hiçbir sonucu etkilemez.

---

## 7. Claude arşivindeki diğer materyal

| Klasör | İçerik | Durum |
|---|---|---|
| `B_V23_Tip_Sistemi/` | V23 dönemi (Eylül 2026) faz-duyarlı boyut ve aralık tip sistemi: `Core`, `Dim`, `FormalCore`, `Kimi5`, `V23`, `Fail` · 22 teorem + 46 `example` | ✅ Beş dosya derlenir. ✅ `Fail.lean` bilerek derlenmez: boyutsuz Γ ile kurulan `dt`'nin zaman boyutu taşımadığını gösteren negatif testtir. ⚠️ **Geçersiz kılınmış hükümler:** `FormalCore.lean`, `timeMode .c0 = .zero` (güncel kanon: T(c₀) = ⊥₀ ≠ 0), `adjacent .c0 .cp = false` (güncel kanon: tam üçgen) ve `carriable .cp Dim.mass = true` (güncel kanon: durgun kütle yalnızca Cₘ'ye özgüdür) hükümlerini kodlar. Bu dosyalar güncel kanon değil, tarihsel kayıttır. ℹ️ `V23.lean`, Float değerler üzerinde iki `example` içinde `native_decide` kullanır; hiçbir teorem buna dayanmaz |
| `C_Capraz_Derleme_Duzeltmeleri/` | `ChatGPT_Run01_fixed.lean` (10 teorem; `Rat` → `Int`), `Qwen_b5_nomathlib.lean` (Mathlib gerektirmeyen `ChartOK` kısmı; `by decide` → `fun h => h`) ve fark dosyası | ✅ İkisi de derlenir |
| `D_Tarihsel_Surumler/` | `Topology_RUN04_eski.lean` ve 16 tarihsel `lakefile` sürümü | ✅ RUN-04 Topology derlenir. ℹ️ Teorem adı `circle_has_no_interior_max` içeriğini aşan bir iddiaydı; RUN-06'da `euler_circle_zero_disk_one` olarak yeniden adlandırıldı |

---

## 8. Diğer üç arşiv: durum ve arşiv kayıtları

### 8.1 Bulunan kusurların özeti

Aşağıdakilerin hiçbiri 269 teorem iddiasının parçası değildir ve hiçbiri yayımlanmış belgelerde (ana README, Çekirdek Ontoloji minor16, V24 minor20) adıyla geçmez.

| Dosya | Bulunduğu yer | Kusur | Durum / yerine geçen |
|---|---|---|---|
| `ChatGPT_Run01.lean` (özgün) | ChatGPT tam arşivi (MiniLab klasörleri) | 63:12'de derleme hatası: "typeclass instance problem is stuck" | Yerine Claude arşivindeki (C) `ChatGPT_Run01_fixed.lean` geçer; derlenir |
| `b5.lean` (Qwen) | ChatGPT tam arşivi | `X_deriv` teoreminin kanıt gövdesi yok; `decide`, `Decidable` örneği olmayan bir `Prop` üzerinde kullanılmış. Mathlib olsa bile derlenmez | Mathlib gerektirmeyen kısmın yerine `Qwen_b5_nomathlib.lean` (C) geçer. X'in lojistik fonksiyon olarak okunması emekliye ayrılmıştır |
| `b2.lean` (Qwen) = `formal_core_v02_snmario.lean` (Kimi) | ikisinde de | Üç `sorry`. `arrow_from_monotone_sealing` **yazıldığı haliyle yanlıştır**: `0 < Ndot` varsayımı `variable` olarak bildirilmiş ama önermede kullanılmamıştır; Lean bu yüzden onu teoreme dahil etmez ve iddia negatif `Ndot` için çöker. `global_quotient_link : Nonempty GlobalLevel` içeriksizdir (`Unit ≃ Unit` ile kanıtlanır) ve U₀–U₊ arasında bir eşleme ileri sürer; bu Sessizlik İlkesi ile çelişir. X(x)'i lojistik fonksiyon olarak ele alır (emekli) | Tarihsel taslak (FORMAL-CORE v0.2, Eylül maratonu). Atıf yapılmamalı |
| `snippet_bridge_nonunique.lean` (Kimi) | Kimi | Kanıt yerine `...` yer tutucusu var | Kanıtlanmış karşılığı: `V24/BridgeNoGo.lean` içinde `bridge_non_uniqueness` |
| `snippet_phase_absence.lean` (Kimi) | Kimi | Tanımsız `restMassAdmissible`, `Context` kullanılmış | Kanıtlanmış karşılıkları: `metric_only_Cm` (Core), `cp_no_rest_mass` (`V24/Patches.lean`) |
| `snippet_resolve_is_admissible.lean` (Kimi) | Kimi | Yalnızca imza; `State`, `ResolveX`, `Syntax` tanımsız | Açık hedef, hiç kanıtlanmadı |
| `snippet_exp_deriv.lean` (Kimi) | Kimi | `b5.lean` ile aynı içerik | `b5.lean` için geçerli olan geçerlidir |
| `PhaseRange_Candidate_UNCOMPILED.lean` | ChatGPT tam arşivi | Kusur yok: derlenir, üç teoremi hiçbir aksiyoma dayanmaz. Yalnızca dosya adı yanıltıcıdır | Tarihsel aday |
| `V24_Run05/06/07_*_Candidate.lean` | ChatGPT tam arşivi | Kusur yok: derlenirler. Run07 kanıt hedeflerini bir yorum içinde listeler; kanıtlar `V24/Confluence.lean` ve `V24/Idem.lean` içindedir | Tarihsel adaylar |
| `Evertophy_Formal_Core_v0_1.lean` (2026-09-13) | ChatGPT tam arşivi | Kusur yok: derlenir; 20 teorem, aksiyom yok | `B_V23_Tip_Sistemi/FormalCore.lean` dosyasının öncülü |

### 8.2 Kimi derlemesi (`Evertophy_Lean_Derlemesi_Kimi_20261009.zip`)

- 9 Lean dosyası; manifest 10/10.
- `lean_erken_arsiv/Assoc.lean`, `Omega.lean` ile `lean_oturum_parcalari/Absence_Tur5.lean`, `BridgeNoGo.lean`, RUN-19'daki `V03/Assoc`, `V03/Omega`, `V24/Absence` ve `V24/BridgeNoGo` ile **bayt düzeyinde aynıdır** ve derlenir.
- `lean_maraton_snmario/` altındaki beş dosya, Eylül maratonu raporunda alıntılanmış parçalardır. Kimi'nin kendi manifesti arşivi "kısmi" olarak etiketler ve Lean araç zincirinin bulunmadığını belirtir. Kusurları §8.1'de listelenmiştir.

### 8.3 Codex derlemesi (`...ChatGPT(Evertophy 20261003 Codex).zip`)

- Proje belgelerinden (V24 minor18, Çekirdek minor11, bir Codex raporu) bayt düzeyinde çıkarılmış 23 alıntı; derleyici tarafından `EXTRACTED_NOT_TYPECHECKED` olarak etiketlenmiştir. Modül değildir: çoğu, metinde kanıtsız olarak listelenen imzalardır.
- 5'i tek başına derlenir; 18'i imza ya da parçadır.
- 49 teorem adı geçer. 45'i RUN-19'da aynı adla vardır; `gate_symmetric_1/2/3`, RUN-19'daki üç teoremin kısaltmasıdır; `mpb_c0/cp/Cm` yalnızca belgede bulunur ve başarıyla yeniden derlenmiştir (§6.2, denetim 12).

### 8.4 ChatGPT tam kaynak koleksiyonu (`...ChatGPT(Dusunce Dedeyleri 202609).zip`)

- Manifest 1409/1409.
- `01_START_HERE_RUN19/`, Claude arşivindeki RUN-19 paketiyle bayt düzeyinde aynıdır.
- `02_UNIQUE_LEAN/` ve `05_PACKAGE_TREES/` 586 Lean dosyası içerir. Bunların 481'i RUN-19 dosyalarıyla, 23'ü Claude arşivinin B ve C klasörlerindeki dosyalarla bayt düzeyinde aynıdır, 48'i `lakefile`'dır ve geriye **8 farklı içerik** kalır; bu 8 içeriğin her biri §8.1'de yer alır.
- 36 tarihsel paket ağacının tamamı yeniden derlendi: 14'ü olduğu gibi derlenir. Kalan 22'si, yalnızca birkaç dosya içeren ama `lakefile`'ı başka yerde duran modülleri listeleyen MiniLab çalışma klasörleridir ("no such file or directory" hatası). Eksik modüller, içerikleri bayt düzeyinde aynı olan RUN-19 dosyalarından tamamlanınca **22'si de derlenir**.
- `03_ARCHIVE_CODE_BLOCKS/`, metin arşivlerinden alınmış 311 kod bloğu içerir. Bunlar modül değil alıntıdır: 7'si tek başına derlenir, geri kalanların çevre tanımları eksiktir. 344 teorem anışından 329'unun RUN-19'da, 7'sinin daha eski bir pakette aynı adlı karşılığı vardır; kalan 8'i §8.1 ve §8.3'te açıklanan maddelerdir. Bir blok `sorry` içerir (`b2` taslağı).
- `04_ORIGINAL_PACKAGES/` 27 özgün ZIP'i korur; RUN-08, 09, 10, 16, 17, 18 ve 19 bunlar arasındadır.

---

## 9. Denetimi yeniden üretmek

```bash
# 1. Lean 4.12.0 (Mathlib gerekmez)
#    https://github.com/leanprover/lean4/releases/tag/v4.12.0

# 2. Kanonik arşivi açın
unzip Evertophy_Claude_Lean_Arsivi_20261009.zip
cd Evertophy_Claude_Lean_Arsivi_20261009

# 3. Tek komutla denetim (geçici kopya üzerinde çalışır)
bash PAKET_DOGRULA.sh

# 4. Ya da RUN-19'u elle derleyin
cd A_Kanonik_RUN19/Evertophy-Formal
lake build
lake build Evertophy Claude V03 V24

# 5. Bütünlük
sha256sum -c SHA256_MANIFEST.txt
```

Aksiyom denetimini tekrarlamak için tüm modülleri içe aktaran ve her teorem için `#print axioms <teorem>` (ya da `Lean.collectAxioms`) çalıştıran bir dosya derleyin. Doğru sonuç yalnızca `propext`, `Quot.sound` ve `Classical.choice` aksiyomlarını listeler.

---

## 10. Kayıt

- **Program:** Evertophy — Uğur Yılmaz · Bağımsız Araştırmacı, İstanbul · ORCID [0009-0007-2243-5581](https://orcid.org/0009-0007-2243-5581)
- **Lean kodları:** yazarın yönlendirmesiyle yapay zekâ desteğiyle yazıldı (ağırlıkla Claude; ChatGPT, Kimi, Wolfram, Qwen ve diğerleri tarafından çapraz denetim). Bkz. [ana README](../README_TURKISH.md) içindeki yapay zekâ kullanım notu.
- **Arşiv tarihi:** 2026-10-09 · **Bağımsız yeniden derleme:** 2026-11-07 (Lean 4.12.0)
- **Eşlik eden kayıtlar:** Çekirdek Ontoloji DOI [10.5281/zenodo.23806039](https://doi.org/10.5281/zenodo.23806039) · V24 rolling master DOI [10.5281/zenodo.23744787](https://doi.org/10.5281/zenodo.23744787)
- **Statü:** kodlanmış sistemin biçimsel tutarlılığı ≠ fiziksel doğrulama · sayaç **0/10**
