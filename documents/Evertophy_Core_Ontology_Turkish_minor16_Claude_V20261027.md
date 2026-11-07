# EVERTOPHY — ÇEKİRDEK ONTOLOJİ

**Uğur Yılmaz** · Bağımsız Araştırmacı · İstanbul · `ugur@data24k.com`

*Türkçe Çekirdek Ontoloji Monografisi · Sürüm 2026-10-27 · minor16*

*Yazar: Uğur Yılmaz*
*https://orcid.org/0009-0007-2243-5581*

*Taban: 2026-10-27 minor15 · Giriş bölümü: yazarın kendi anlatım metni (2026-10-14) · Hizalama kaynağı: 23–26 Eylül 2026 çapraz-AI maratonu final derlemesi · minor14: 2026-10-27 kapanış mini maratonu Tur01 düzeltmeleri · minor15: Tur02 yerel errata (nötrino kütle sıralaması, okuma haritası tip imzası, nokta aralıklarda IOM, afinite parametre alanı, kanal potansiyelinin gerçel okuması, C-1 köprüsünün kapsamı) · minor16: Tur03 son errata (yoğunluk koşulunun bütün geçişlerde eşitlenmesi, akromatiklik biçimlerinin yönü, §8.8 kanal adımının genlik biçimi); ontolojik hükümler değişmedi*

---

## Yazardan Okuyucuya

Bu belgeyi okumaya başlamadan önce size Evertophy'nin nereden çıktığını anlatmak istiyorum. Çünkü ne söylediğini anlamanın en kısa yolu, neyi aradığını anlamaktan geçiyor.

### Bir cevap iddiası değil, bir cevap arayışı

Modern bilim, insanlığın kurduğu en güvenilir bilgi yapısıdır. Deneyle sınanmış, gözlemle doğrulanmış, defalarca ölçülmüş bulgular üzerinde durur. Ama bu yapıya yakından baktığımızda, bazı parçaların birbirine tam oturmadığını görürüz.

Evrendeki madde ve enerjinin büyük kısmının etkisini ölçüyoruz ama ne olduğunu bilmiyoruz; "karanlık madde" ve "karanlık enerji" dediğimiz şeyler, bir bakıma bilgisizliğimizin adıdır. Fiziğin temel denklemlerinin birçoğu "zaman" içinde ileri ve geri aynı biçimde işler; oysa yaşadığımız dünyada zamanın bir yönü vardır. Kuantum mekaniği olağanüstü bir doğrulukla çalışır, ama bir ölçümün "ne olduğu" konusunda hâlâ uzlaşı yoktur. Genel görelilik ile kuantum kuramı kendi alanlarında kusursuzdur, ama bir araya gelmez. "Büyük Patlama'dan önce ne vardı?" sorusu ise sorunun kendisinin anlamlı olup olmadığı tartışmasıyla birlikte durur.

Bunlar bilimin başarısızlıkları değil, bilimin bugünkü sınırlarıdır. Ölçüm oradadır, deney oradadır. Eksik olan, o ölçümleri birbirine bağlayan anlamdır.

Evertophy bu boşluklardan doğdu. Ama baştan açık olmak istiyorum: Evertophy bu soruların cevabı olduğunu iddia etmiyor. Evertophy bir **cevap arayışıdır**; anlaşılamayan fenomenlere ve anomali olarak görünen bilimsel bulgulara, onları birbirine bağlayabilecek tutarlı bir çerçevenin içinden bakma denemesidir.

### Temel ilkeler: "Deney, Ölçüm ve Gözlem" koşulsuz kabul edilir, "Postüla ve Yorum" opsiyonlu olarak işaretlenir

Evertophy'nin anlam ve çözüm arayışının uyduğu temel bir kural var ve bu belgenin her satırı ona bağlıdır:

$$\boxed{\;\text{Deney, Ölçüm ve Gözlem çıktıları KOŞULSUZ kabul edilir; postüla ve yorum katmanları OPSİYONLU – YORUMSUZ değerlendirilir.}\;}$$

```latex
\boxed{\;\text{Deney, Ölçüm ve Gözlem çıktıları KOŞULSUZ kabul edilir; postüla ve yorum katmanları OPSİYONLU – YORUMSUZ değerlendirilir.}\;}
```

Bunun anlamı şudur. Evertophy hiçbir ölçümü reddetmez. Hiçbir deney sonucunu "yanlış" ilan etmez, hiçbir gözlemi kendi çerçevesine uydurmak için eğip bükmez. Bir ölçüm Evertophy'nin bir okumasıyla çelişirse, değişmesi gereken ölçüm değil, okumadır.

Bilimsel gerçeklikte "ölçümün kendisi" ile "ölçümün üzerine kurulan yorum" aynı şey değildir. Bir parçacığın dedektörde bıraktığı iz bir ölçümdür; o izin bir "dalga fonksiyonu çöküşü" mü, "dünyaların ayrışması" mı, yoksa başka bir şey mi olduğu bir yorumdur. Galaksilerin beklenenden hızlı döndüğü bir gözlemdir; bunun görünmeyen bir parçacıktan mı, yoksa kütleçekimin kendisinin farklı davranmasından mı kaynaklandığı bir yorumdur.

Evertophy bu katmanlara üç biçimde yaklaşır:

1. **Opsiyonlu:** Mevcut yorumların hiçbirini zorunlu kabul etmez, hiçbirini de reddetmez. Hepsini birer seçenek olarak masada tutar.
2. **Yorumsuz:** Ölçümün kendisine yorum yüklemez. Ham bulguyu olduğu gibi alır ve kendi okumasını onun üzerine ayrı bir katman olarak koyar. Evertophy'nin önerdiği okuma da bir seçenektir; diğerlerinin yerine geçmeye değil, onların yanında sınanmaya adaydır.
3. **Fiziksel gerçeklik ve matematik:** Bir kuramın ya da hipotezin matematiksel olarak kusursuz olması, tek başına fiziksel gerçeklik (deney, ölçüm, gözlem) sayılmaz; böyle bir kuram yukarıdaki iki maddeyle aynı hükümdedir. Buna karşılık bir ölçümü doğru olarak yeniden üreten matematiksel temsil, o ölçümün kapsamı içinde koşulsuz kabul edilir. Aynı ölçümün birden fazla doğru temsili olabilir — aynı yörünge hem Newton hem genel görelilik diliyle yazılabilir; bu temsillerin hiçbiri diğerine göre ontolojik olarak öncelikli sayılmaz.

$$\boxed{\;\text{Ölçüm: koşulsuz}\qquad\text{Temsil: ölçümü yeniden ürettiği kapsamda geçerli}\qquad\text{Temsiller arası ontolojik öncelik: yok}\;}$$

```latex
\boxed{\;\text{Ölçüm: koşulsuz}\qquad\text{Temsil: ölçümü yeniden ürettiği kapsamda geçerli}\qquad\text{Temsiller arası ontolojik öncelik: yok}\;}
```

Bu perspektiften bakıldığında Evertophy okumaları şöyle değerlendirilmelidir: Evertophy; Genel Görelilik, Standart Model, Kuantum Mekaniği ve Kozmoloji'ye ait olan ve deneye, ölçüme ve gözleme dayanan tüm kapsamı koşulsuz olarak kabul eder. Kendisini herhangi bir modelin ya da teoremin yerine koymaz. Evertophy; bilimin eksik parçalarını bir araya getirmek amacıyla bir "Rosetta Taşı" olmayı, farklı dillerle konuşan mevcut bilim çerçevelerinin ortak bir çeviri grameri olmayı arayan bir **Araştırma Programı / Kapsayıcı Çerçeve Adayı** statüsündedir.

### Anlamsal arayış: bilimin kopuk parçalarını birleştirmek

Peki Evertophy bu parçaları nasıl birleştirmeye çalışıyor?

Temel Evertophy önerisi şudur: Gerçeklik, yalnızca tek bir düzlemden ya da yalnızca maddeden oluşan parçacıklardan ibaret değildir; **ÜÇ FAZLI** bir yapıda gerçekleşir. Üç fazın oluşturduğu bu yapının tümüne **Dinamik Evren** ($U_x$) denir. Bu üç fazı bir arada tutan ve aralarındaki tüm etkileşimin temelinde duran ilke **Çekim Kuvveti (Force of Attraction)**dir; Evertophy'nin en temel ontolojik postülasıdır (Bölüm 1.2). Bildiğimiz dört kuvvet — Kütleçekim, Güçlü Nükleer Kuvvet, Zayıf Nükleer Kuvvet ve Elektromanyetik Kuvvet — Çekim Kuvveti'nin **ölçeğe, kütle miktarına ve faza göre** farklı izdüşümleridir.

$$\boxed{\;\{\text{Kütleçekim},\ \text{Güçlü},\ \text{Zayıf},\ \text{Elektromanyetizma}\} \;=\; \Pi_{\text{ölçek, kütle, faz}}\big[\,\text{Çekim Kuvveti}\,\big]\;}$$

```latex
\boxed{\;\{\text{Kütleçekim},\ \text{Güçlü},\ \text{Zayıf},\ \text{Elektromanyetizma}\} \;=\; \Pi_{\text{ölçek, kütle, faz}}\big[\,\text{Çekim Kuvveti}\,\big]\;}
```

| Sembol | Anlamı |
|---|---|
| $\Pi_{\text{ölçek, kütle, faz}}$ | İzdüşüm: Çekim Kuvveti'nin belirli bir ölçekte, kütle miktarında ve fazda aldığı biçim; biçimsel tanımı açıktır |
| Çekim Kuvveti | Temel ontolojik postüla; kütleçekim değildir, kütleçekim onun Cₘ'deki izdüşümlerinden biridir |

![Core Ontology](Evertophy_Core_20260919_revize_gerekiyor_v2.png)

### Görselin okunuşu

Yukarıdaki görsel, Evertophy'nin bütün ontolojik iskeletini tek bir resimde gösterir. Resim iki seviyeden oluşur ve iki seviyenin birbirine karıştırılmaması gerekir.

**İç seviye — faz seviyesi.** Ortadaki dikdörtgenin içinde üç düğüm vardır: tepede **c₀** (Potansiyel), sol altta **Cₘ** (Madde/Zaman), sağ altta **c⁺** (Üst-Faz / Koordinasyon). Bu üç düğüm, her biri diğer ikisiyle doğrudan bağlı bir **tam üçgen** (K3) oluşturur. Üçgenin kenarları geçiş adlarını taşır:

| Kenar | Bağladığı fazlar | Kayıt (damga) davranışı | Cₘ'den gözlenebilirlik |
|---|---|---|---|
| $\Delta_{0m}$ | c₀ ↔ Cₘ | Damga taşır | Doğrudan |
| $\Delta_{+m}$ | c⁺ ↔ Cₘ | Damga taşır | Dolaylı |
| $\Delta_{0+}$ | c₀ ↔ c⁺ | Damga üretmez (Cₘ'ye değmez) | Gözlenmez |

Kenarlardaki okların **iki uçlu** olması bilinçlidir: faz geçişleri her üç kenarda da çift yönlüdür. Geri alınamaz olan geçişin kendisi değil, geçiş sırasında Cₘ'de üretilip c⁺'ta mühürlenen kayıttır (Bölüm 13–14). Görselde c₀'ın tepeye çizilmesi yalnız bir çizim düzenidir; bir hiyerarşi ya da merkez anlamına gelmez. Ölçüm ve kayıt açısından merkez Cₘ'dir, ama topolojik olarak Cₘ zorunlu bir ara durak değildir: c₀ ile c⁺ arasında doğrudan bir kenar vardır.

$$\boxed{\;c_0\leftrightarrow C_m,\qquad C_m\leftrightarrow c^+,\qquad c_0\leftrightarrow c^+\;}$$

```latex
\boxed{\;c_0\leftrightarrow C_m,\qquad C_m\leftrightarrow c^+,\qquad c_0\leftrightarrow c^+\;}
```

**Dikdörtgen — Dinamik Evren ($U_x$).** Üç fazın birlikte oluşturduğu bütün, $U_x$'tir. $U_x$ dördüncü bir faz ya da üçgene eklenmiş bir düğüm değildir; üç fazın birlikte gerçekleştiği bütünsel yapının adıdır. Zaman, uzay ve ölçüm bu bütünün **içinde**, Cₘ fazında yaşar.

**Dış seviye — global seviye.** Dikdörtgenin solunda **$U_0$** (Mutlak Çekirdek), sağında **$U_+$** (Mutlak Çözünme) bulunur. Bu iki kırmızı daire faz değildir; Dinamik Evren'in bütününün iki **uç koşuludur**. Görseldeki süslü parantezler bu yüzden çizilmiştir: $U_0$ ve $U_+$ ile çift yönlü oklar, üçgenin herhangi bir köşesine değil, parantezle sarılmış **bütüne** bağlanır.

$$\boxed{\;U_0\;\leftrightarrow\;U_x\;\leftrightarrow\;U_+,\qquad U_0,\ U_x,\ U_+\notin\{c_0,\ C_m,\ c^+\}\;}$$

```latex
\boxed{\;U_0\;\leftrightarrow\;U_x\;\leftrightarrow\;U_+,\qquad U_0,\ U_x,\ U_+\notin\{c_0,\ C_m,\ c^+\}\;}
```

Bu ayrım önemlidir: tek bir kara deliğin oluşması (bir bölgenin c₀ rejimine geçmesi) yerel bir faz olayıdır ve evrende her gün olur. $U_0$ ise **bütün** Dinamik Evren'e ait global bir koşuldur. Benzer biçimde c⁺ bir fazdır ve evrenin içindedir; $U_+$ ise bütünün uç koşuludur ve dışarıdadır. Global oklar matematiksel bir tersinirlik iddiası taşımaz; bir ilişkinin iki ucunu gösterir. Global seviyede metrik, uzay ve zaman yoktur; bu nedenle "önce", "sonra" ya da "hız" dili burada kullanılmaz.

### Görsel sembollerinin ontolojik açıklamaları

---

* **$U_0$ (Evren Çekirdeği — Mutlak Çekirdek):** İçinde yaşadığımız Dinamik Evren'i oluşturan bütün yapıların — c₀ (kara delikler), Cₘ (baryonik madde) ve c⁺ (karanlık sektör: karanlık madde ve karanlık enerji) — Planck ölçeğinde metrik boşluksuz duruma yakınsayan derecede bitişik, **tek bir yapı formunda** bulunduğu ön katman (pre-layer); yani "temel-kaynak" yapıdır.
  * $U_0$ rejiminde üç boyutlu Öklid uzayı, baryonik madde, karanlık madde ve karanlık enerji ile zaman **yoktur, ama potansiyel olarak bulunur**. Big Bang ile birlikte üç fazı — c₀, Cₘ ve c⁺ — **aynı kuruluşta birlikte** var eder; madde fazında tek yönlü bir akış olarak deneyimlediğimiz **zamanı** da bu kuruluş doğurur (emergent zaman; Bölüm 7). Bu birlikte doğuş sıralı bir üretim değildir: $U_0$ önce birini, sonra ötekini üretmez; üçü birden doğar.

  $$\boxed{\;U_0\;\rightsquigarrow\;\{c_0,\;C_m,\;c^+\}_{\text{aynı kuruluşta birlikte}}\;}$$

  ```latex
  \boxed{\;U_0\;\rightsquigarrow\;\{c_0,\;C_m,\;c^+\}_{\text{aynı kuruluşta birlikte}}\;}
  ```

  * Dinamik Evren'i oluşturan yapıların **tümü** kara delik fazına çöktüğünde — yani bütün $U_x$, kritik doygunluk eşiğine ($\Theta_0$) ulaştığında — durum $U_0$ ile temsil edilir. Bu eşik aşıldığında Big Bang gerçekleşir ve yeni bir $U_x$ (Dinamik Evren) oluşur: üç boyutlu Öklid uzayı, baryonik madde ve karanlık sektör yeniden kurulur. Eşik $U_0$'ın kendisi değildir; $U_x$'in çöküş ucunun $U_0$ ile temas ettiği **sınırdadır** (Bölüm 2.6, 2.8).
  * $U_0$ bir faz değildir, c₀'ın evren ölçekli bir alt türü de değildir; ona giden ya da ondan gelen sıradan bir faz kapısı yoktur. Tek bir kara deliğin c₀ rejimi yereldir; $U_0$ bütün evrenin global koşuludur. $U_0$'a sayısal bir kütle değeri atanmaz (Bölüm 2.10).

* **$U_+$ (Çözünmüş Evren — Mutlak Çözünme / Mutlak Yırtılma):** Dinamik Evren'in tüm faz-yapısal çözünürlüğünün seyrelerek global çözünürlük sınırını aştığı uç durumdur. $U_0$ global doygunluk kutbuysa, $U_+$ global çözünme kutbudur. "Mutlak Çözünme" ve "Mutlak Yırtılma" adları **aynı uç durumu** anlatır: birincisi durumun kendisini, ikincisi bütün $U_x$ yapısının bu duruma ulaşmasını vurgular. Bütün $U_x$, $U_+$ sınırındaki kritik eşiği aştığında gerçekleşen olayın adı **Big Yırtılma**'dır; ardından yeni bir $U_x$ oluşur.

  $$\begin{cases} U_x,\ U_0 \text{ sınırındaki kritik eşiği aşar} & \Rightarrow\ \textbf{Big Bang} \\[4pt] U_x,\ U_+ \text{ sınırındaki kritik eşiği aşar} & \Rightarrow\ \textbf{Big Yırtılma} \end{cases} \qquad\Longrightarrow\qquad \text{yeni bir } U_x \text{ oluşur}$$

  ```latex
  \begin{cases} U_x,\ U_0 \text{ sınırındaki kritik eşiği aşar} & \Rightarrow\ \textbf{Big Bang} \\[4pt] U_x,\ U_+ \text{ sınırındaki kritik eşiği aşar} & \Rightarrow\ \textbf{Big Yırtılma} \end{cases} \qquad\Longrightarrow\qquad \text{yeni bir } U_x \text{ oluşur}
  ```

  * $U_+$ ile c⁺ karıştırılmamalıdır: **c⁺ bir fazdır ve evrenin içindedir; $U_+$ bütünün uç koşuludur ve dışarıdadır.** $U_+$ "çok fazla c⁺" demek değildir; global bir çözünürlük koşuludur.
  * Standart kozmolojideki *Big Rip*, evreni **sonlandıran** bir olaydır. Evertophy'de Big Yırtılma bir son ve aynı zamanda yeni bir doğuştur. Ortak sözcük, anlamların aynı olduğunu göstermez.
  * Yeni bir $U_x$'in oluşması kanondur; bunun $U_0$'daki doğuşla **aynı** üretim işlemiyle gerçekleşip gerçekleşmediği açıktır (Bölüm 2.8).

* **Zorunsuzluk / döngü esnekliği:** Global devre zorunlu, periyodik bir zaman konveyörü değildir. $U_x$'in global eşiklerden birine ulaşması ya da evrenin son bulması zorunlu değildir: **Dinamik Evren son bulabilir ya da bulmayabilir.** $U_0$ ile $U_+$ arasında doğrudan bir ilişki bulunabilir; ama bilinen anlamda bir temsili yoktur. Temsili olmayan yerde Evertophy hüküm vermez (sessizlik ilkesi, Bölüm 2.8).

---

* **$C_m$ (Madde / Atom / Parçacık Fazı):** Doğrudan etkileşimde bulunduğumuz fiziksel gerçekliğin; ayrışmış kütleli maddelerin, atomların ve atom altı parçacıkların, ölçüm süreçlerinin ve tek yönlü bir akış olarak deneyimlediğimiz zamanın var olduğu faz yapısıdır. Fiziksel zaman, üç boyutlu Öklid uzayı, metrik ve ışık hızı sınırı **yalnız Cₘ'de** tanımlıdır.
  * **Kinematik üyelik bandı:** Bir fiziksel yapının Cₘ fazına madde olarak üye olması için gereken kinematik bant $0<v<c$'dir. $v=c$ ise bandın kendisi değil, bandın **liminal sınırıdır**; ışık (foton) bu sınırda bulunur.

  $$\underbrace{0<v<c}_{C_m\ \text{madde üyeliği}},\qquad \underbrace{v=c}_{\text{liminal sınır (ışık)}},\qquad \underbrace{c^+}_{\text{bandın çözüldüğü }c\text{-ötesi rejim}}$$

  ```latex
  \underbrace{0<v<c}_{C_m\ \text{madde üyeliği}},\qquad \underbrace{v=c}_{\text{liminal sınır (ışık)}},\qquad \underbrace{c^+}_{\text{bandın çözüldüğü }c\text{-ötesi rejim}}
  ```

  * Bandın alt ucundaki **"0"**, evrendeki herhangi bir kozmolojik ya da eylemsiz referans çerçevesine göre tanımlanan **bağıl hız tabanıdır**. Yerel bir laboratuvarda durağan duran bir parçacık (laboratuvar hızı $v_{\rm lab}=0$ olsa bile) iç dinamikleri, spin yapısı ve kozmolojik sürüklenmesi nedeniyle Cₘ fazının üyesidir ve üyelik bandının içinde kalır. Yani buradaki $v$ bir laboratuvar koordinat hızı değil, **üyelik okumasıdır**; ölçülen yerel hız tek başına faz üyeliğini belirlemez. Bu okuma klasik bir "ayrıcalıklı çerçeve" varsaymaz; $v$'nin kesin matematiksel tanımı açıktır (Bölüm 3.3).

  $$v_{\rm lab}=0\;\not\Rightarrow\;c_0,\qquad 0<v<c\;\neq\;\text{laboratuvar koordinat hızı}$$

  ```latex
  v_{\rm lab}=0\;\not\Rightarrow\;c_0,\qquad 0<v<c\;\neq\;\text{laboratuvar koordinat hızı}
  ```

  * **Işık hızı (c):** Evertophy ontolojisinde ışık hızı, Cₘ fazının **rejim eşik sınırıdır**. Madde yapısı için ışık hızı aşılamaz bir evrensel sabittir; ama Dinamik Evren'in tümü için aşılamaz bir hız sınırı değildir. Işık hızı, madde fazının var olabilirlik bandının sınırıdır; zamanın ve Cₘ fazının çözünürlük sınırıdır. Bu sınırın öbür yanı **c⁺ faz rejimidir**.
  * **Bose–Einstein yoğuşması (BEC):** Mutlak sıfıra yakın sıcaklıklarda atomların tek bir makroskobik kuantum durumuna geçtiği BEC, **madde fazında c₀ ortamına en yakın ortamdır**. BEC c₀ değildir: içinde zaman akar ve sistem Cₘ'de kalır. Ama "bu atom" ile "şu atom" ayrımının operasyonel içeriğini kaybettiği toplu tek-yapı davranışı, c₀ sezgisi için laboratuvarda ulaşılabilen en açık örnektir.
  * Bu ontolojik yaklaşımın deneysel dayanak noktaları şunlardır: kuantum dolanıklık ("uzaktan tuhaf etki") ve BEC madde yapısı.

---

* **$c_0$ (Potansiyel / Kara Delik Fazı):** Fiziksel olarak ölçülebilen madde yapısının atomik ve parçacık özelliklerini kaybettiği, bütün parçacıkların Planck ölçeğinde metrik boşluksuz duruma yakınsayan derecede birleşerek **tümleşik tek bir yapı** formuna dönüştüğü fazdır. **Evertophy ontolojisinde kara delik ile c₀ fazı ontolojik olarak özdeştir** (yazar hükmü). Kara delik fazında zaman ve madde kavramları, ölçebildiğimiz anlamıyla bulunmaz: **tanımsızdır, ama potansiyel olarak bulunur — henüz kurulmamıştır.**
  * **Zaman-öncesi ve geometri-öncesi rejim:** c₀, üç boyutlu Öklid uzayının, zamanın ve diferansiyel yapının ($\nabla$, $\Box$) henüz kurulmadığı, zaman-öncesi (pre-temporal) ve geometri-öncesi (pre-geometric) bir potansiyel kütüphanesidir. Bu fazda Cₘ-tipi uzunluk, süre ve metrik tanımsızdır; kütle ise c₀'ın içinde Cₘ-tipi durgun kütle olarak değil, Cₘ'den okunan toplam büyüklük ve çekirdek kapasitesi olarak izlenir (aşağıda).
  * **Gözlem ontolojisi:** c₀ içinde bir gözlemci bulunamayacağı ve Cₘ'nin araçlarıyla içeriden ölçülemeyeceği için doğrudan gözlemlenemez. Ama izleri Cₘ'de iki yolla okunur:
    * **Kozmolojik ve astrofiziksel izler:** Kara deliklerin olay ufukları, kütleçekimsel zaman genişlemesi, EHT gölge görüntüleri ve kütleçekim dalgaları ölçülmüş olgulardır. Evertophy bunları c₀ yapısının Cₘ ekranındaki dolaylı makro izleri olarak okur.
    * **Laboratuvar analogları:** Mutlak sıfıra yakın ortamlardaki BEC, süperakışkanlık ve süperiletkenlik, sistemin bütünsel tek bir kuantum durumuna geçtiği Cₘ ortamlarıdır. Bunlar c₀'ın kendisi değil, **madde fazında c₀ ortamına en yakın ortamlardır**; benzerlik toplu tek-yapı davranışındadır (analoji, kimlik değil).
  * **Kara delik çekirdeği ve "sonsuz tekillik" okumasının reddi:** Klasik genel göreliliğin kara delik merkezi için verdiği "sonsuz yoğunluk ve sıfır hacim" anlamındaki tekillik, Evertophy'de bir **rejim hatası** olarak okunur: kuramın geçerlilik alanının dışına taşan bir sonuçtur. Kara delik bir yok oluş ya da sonsuz tekillik değildir (yazar hükmü).
    * **Metrik boşluksuz tek-yapı (maksimal doygunluk):** Olay ufkunun içindeki yapı, Planck ölçeğinde metrik boşluksuz duruma yakınsayan derecede **bitişik**, sonlu ve **tek bir form**dur. Bu ifade "kara delik çekirdeği Planck boyutundadır" anlamına gelmez; anlamı şudur: kara deliğin içindeki kütle yapısı, parçacıklar arasında metrik boşluğun neredeyse kalmadığı, **bütünüyle tek bir form** hâlindedir. Evertophy'nin c₀ ve kara delik okumasının çekirdek mantığı budur. Bu doygunluk, $X$'in bir okuması üzerinden yazılır; $X$'in kendisi skaler değildir, doygunluğa yakınsayan şey onun doygunluk okumasıdır:

    $$\xi_{\rm sat}=\pi_{\rm sat}(X)\;\longrightarrow\;\xi_{\rm sat}^{\max}\qquad(\text{normalize okumada }\xi_{\rm sat}\approx1)$$

    ```latex
    \xi_{\rm sat}=\pi_{\rm sat}(X)\;\longrightarrow\;\xi_{\rm sat}^{\max}\qquad(\text{normalize okumada }\xi_{\rm sat}\approx1)
    ```

    | Sembol | Anlamı |
    |---|---|
    | $X$ | Dinamik üst çözücü; tek bir sayı değildir (Bölüm 4) |
    | $\pi_{\rm sat}$ | $X$'in doygunluk okuma izdüşümü |
    | $\xi_{\rm sat}$ | Doygunluk okuması; normalize edildiğinde üst sınırı 1'dir |

    * **Bireyselliğin kaybı:** Olay ufku eşiğini geçip c₀ yapısına temas eden madde yok olmaz, sonsuz bir tekillik içinde de kaybolmaz; proton, elektron ya da atom kimliğini ve ayrı adreslenebilirliğini kaybederek **kolektif tek bir yapıya bütünleşir**. Yüzeyine Çekim Kuvveti ile temas eden parçacık, dolanık olup olmamasından bağımsız olarak bu yapıyla bütünleşir. Dışarıdaki parçacık spinini koruyabilir ya da koruyamaz; spin ve dolanıklık, çevreyle etkileşim (ölçüm ya da madde teması) olmadıkça korunur. Kütle spinden bağımsız korunur (yazar hükmü).
    * **Kütle, hacim ve ufuk:** Çekirdek kapasitesinin sayım birimi **Planck kütlesidir** (yazar hükmü). Tek-yapının yoğunluğu Planck yoğunluğunu aşamaz. Ayrıca — ayrı bir yazar hükmü olarak — daha kütleli bir kara delik **daha yoğun** değildir; aynı metrik boşluksuz yapıdan **daha büyük bir hacme** ve dolayısıyla daha geniş bir olay ufkuna sahiptir. Hacmin kütleyle tam doğru orantısı, ortalama yoğunluğun kütleden bağımsız olduğu sabit yoğunluk gerçeklemesinde ($\rho_{c_0}=\rho_*$) geçerlidir (Bölüm 3.2). Oranlar şöyledir:

    $$N_{c_0}=\frac{M}{m_P},\qquad \rho_{c_0}\le\rho_P=\frac{c^5}{\hbar G^2}\approx5.16\times10^{96}\ \mathrm{kg/m^3},\qquad V_{c_0}\ge\frac{M}{\rho_P}=N_{c_0}\,\ell_P^3$$

    ```latex
    N_{c_0}=\frac{M}{m_P},\qquad \rho_{c_0}\le\rho_P=\frac{c^5}{\hbar G^2}\approx5.16\times10^{96}\ \mathrm{kg/m^3},\qquad V_{c_0}\ge\frac{M}{\rho_P}=N_{c_0}\,\ell_P^3
    ```

    $$R_{c_0}\propto M^{1/3}\ \ (\rho_{c_0}\ \text{sabit}),\qquad R_s=\frac{2GM}{c^2}\propto M,\qquad A=4\pi R_s^2\propto M^2,\qquad \frac{R_{c_0}}{R_s}\propto M^{-2/3}$$

    ```latex
    R_{c_0}\propto M^{1/3}\ \ (\rho_{c_0}\ \text{sabit}),\qquad R_s=\frac{2GM}{c^2}\propto M,\qquad A=4\pi R_s^2\propto M^2,\qquad \frac{R_{c_0}}{R_s}\propto M^{-2/3}
    ```

    | Sembol | Anlamı |
    |---|---|
    | $N_{c_0}$ | Planck kütlesi biriminde sayılan çekirdek kapasitesi |
    | $m_P=\sqrt{\hbar c/G}$ | Planck kütlesi ($\approx2.18\times10^{-8}$ kg) |
    | $\rho_P$, $\ell_P$ | Planck yoğunluğu ve Planck uzunluğu; $\rho_P\,\ell_P^3=m_P$ |
    | $V_{c_0}$, $R_{c_0}$ | Tek-yapının Cₘ etkin hacmi ve yarıçapı ($R\propto M^{1/3}$ sabit yoğunluk gerçeklemesinde, $\rho_{c_0}=\rho_*$; en küçük değerler $\rho_*=\rho_P$ ile) |
    | $R_s$, $A$ | Ufuk (Schwarzschild) yarıçapı ve ufuk alanı |

    Kütle arttıkça hem tek-yapının hacmi hem ufuk büyür, ama **aynı oranda değil**: tek-yapının yarıçapı kütlenin küp köküyle, ufuk yarıçapı kütleyle, ufuk alanı kütlenin karesiyle büyür. Yoğunluk Planck değerinde alındığında ($\rho_*=\rho_P$; en küçük yarıçap) Güneş kütleli bir kara delik için tek-yapının yarıçapı yaklaşık $4.5\times10^{-23}$ m'dir: Planck uzunluğundan ($1.6\times10^{-35}$ m) çok büyük, ufuk yarıçapından (yaklaşık 3 km) çok küçüktür. Bu yüzden olay ufku ile tek-yapının sınırı aynı şey sayılmaz; tek-yapının iç profili ve ufukla ilişkisi açıktır (Bölüm 3.2, EK K). Kapasitenin kütleyle, ufuk alanının ise kütlenin karesiyle ölçeklenmesi, gözlemle sınanmış alan teoremiyle uyumludur; entropinin alanla orantılı olduğunu söyleyen alan yasası ise henüz ölçülmemiş kuramsal bir sonuçtur (Bölüm 23.3).

  * **c₀'da zaman, uzay ve değişim — zaman-öncesi rejim** *(tarihsel adı: durağanlık kilidi / Stasis Lock)*: Evertophy'nin beliren zaman denklemi şudur (çekirdek iskelenin normalize biçimi; $\mathcal{G}_{C_m}$'nin mikrofiziksel tanımı açık):

    $$dt = \Gamma\,\mathcal{G}_{C_m}\,d\lambda, \qquad \Gamma = \tau_0\,\tilde{\Gamma}$$

    ```latex
    dt = \Gamma\,\mathcal{G}_{C_m}\,d\lambda, \qquad \Gamma = \tau_0\,\tilde{\Gamma}
    ```

    | Sembol | Anlamı |
    |---|---|
    | $\lambda$ | Boyutsuz sıralama parametresi; fiziksel zaman değildir |
    | $\mathcal G_{C_m}$ | Cₘ'deki ayırt edilebilir değişim yapısı; yalnız Cₘ'de tanımlı |
    | $\tau_0$ | Zaman ölçeği; zaman boyutunu taşır, $[\tau_0]=T$ |
    | $\tilde\Gamma$ | Boyutsuz okuma katsayısı, $[\tilde\Gamma]=1$ |

    Bu biçim, çekirdek iskelenin ($dt = \Gamma\,\mathcal{G}_{C_m}\,d\tau$, Bölüm 7.2) normalize gerçeklemesidir (Bölüm 7.3); çekirdek formdaki $\tau$ da biçimsel bir sıralama değişkenidir. $\mathcal{G}_{C_m}\,d\lambda$, Cₘ'deki ayırt edilebilir değişim miktarıdır.
    * **Zaman = Cₘ'deki ayırt edilebilir değişimin okuması:** Zaman, yalnız Cₘ fazında ölçülebilir durum değişiminin emergent okumasıdır; konum değişimi bunun örneklerinden biridir. $\mathcal{G}_{C_m}$ bir Cₘ nesnesidir: c₀'da sıfır olmaz, **tanımlı değildir**.

      $$T(c_0) = \bot_0, \qquad \mathcal{G}_{C_m}\big|_{c_0} = \bot_0 \neq 0$$

      ```latex
      T(c_0) = \bot_0, \qquad \mathcal{G}_{C_m}\big|_{c_0} = \bot_0 \neq 0
      ```

    * **Zaman durmuş değil, kurulmamış:** Cₘ içinde $\mathcal{G}_{C_m}=0$ olması "saat var ama ilerlemiyor" demektir; bu bir Cₘ durumudur. c₀ bundan farklıdır: orada saat kavramının kendisi kurulamaz. Bu yüzden c₀'da zaman "yavaş akmaz", "donmuş bir nehir" de değildir; Cₘ zaman diliyle tanımsızdır. "$dt=0$" yazımı yalnız pedagojik bir kısaltmadır.

      $$\bot_0 \neq \bot_+ \neq 0$$

      ```latex
      \bot_0 \neq \bot_+ \neq 0
      ```

      | Sembol | Anlamı |
      |---|---|
      | $\bot_0$ | c₀'da "henüz kurulmamış" yokluk |
      | $\bot_+$ | c⁺'ta "çözünmüş" yokluk |
      | $0$ | Gerçek sayısal sıfır — bir Cₘ değeri |

    * **Ayrık parçacık ve Öklid uzayı c₀'da kurulmamıştır:** c₀'da farklılaşmış Cₘ maddesi toplu tek-yapı limitine gider. "Bu parçacık" ile "şu parçacık" ayrımı ve aralarındaki uzaklık operasyonel içeriğini kaybeder. Cₘ-tipi üç boyutlu Öklid uzayı ve metrik c₀'da yıkılmış değil, **henüz kurulmamıştır** ($g_{\mu\nu}$: $\bot_0$). "Artık yok" anlamındaki çözünme ($\bot_+$) c⁺'a aittir.
    * **Isı, sıcaklık ve erişilebilir enerji:** Sıcaklık, Cₘ'de parçacıkların düzensiz (termal) hareketinin istatistiksel ölçüsüdür; ısı bu yolla aktarılan enerjidir. İkisi de Cₘ zamanını ve ayrık parçacık hareketini gerektirir. Bu nedenle c₀'da sıcaklık, ısı, serbest termodinamik süreç ve standart $dS/dt$ dili tanımlı değildir ($\bot_0$; Bölüm 16.1). Enerji ise yok olmaz: c₀'daki enerji Cₘ'de erişilebilir enerji olarak okunmaz; toplam enerji $U_x$ düzeyinde korunur (Bölüm 16.7a).
    * **c₀ yokluk değildir:** Yok olan c₀'ın kendisi değil, c₀'da Cₘ'ye ait zaman, uzay ve sıcaklık kavramlarıdır. c₀, zamanın kurulmadığı potansiyel/çekirdek fazdır; bu zamansal bir öncelik değil, rejimsel bir konumdur (Bölüm 3.2).

  * **c₀ fazı ile mutlak sıfır (0 Kelvin) ilişkisi** — **Yazar hükmü**: $c_0 \neq \text{Mutlak Sıfır}$
    * **Kavramsal ayrım:** Mutlak sıfır, Cₘ'nin kendi içindeki termodinamik limit durumudur; bir Cₘ durumudur. Termodinamiğin üçüncü yasasına göre sonlu adımda ulaşılamaz. Ona yaklaşıldığında da sistem Cₘ'de kalır: kuantum sıfır-noktası hareketi sürer, saatler işler ve $dt$ tanımlıdır. En hassas atom saatleri de zaten ultra-soğuk atomlarla çalışır. c₀'da ise sıcaklık kavramının kendisi tanımsızdır. Kısacası mutlak sıfır Cₘ'nin en soğuk hâlidir; c₀ ise Cₘ'nin hiçbir hâli değildir.

      $$T \to 0\,\mathrm{K} \;\Rightarrow\; C_m \text{ taban durumu}, \qquad T(c_0) = \bot_0$$

      ```latex
      T \to 0\,\mathrm{K} \;\Rightarrow\; C_m \text{ taban durumu}, \qquad T(c_0) = \bot_0
      ```

    * **BEC — c₀ ortamına en yakın Cₘ ortamı, c₀'ın kendisi değil:** Mutlak sıfıra yaklaşılan ultra-soğuk deneylerde (Bose–Einstein yoğuşması) kritik sıcaklığın altında atomların makroskobik bir kısmı aynı kuantum durumunu doldurur. Sistem tek bir makroskobik dalga fonksiyonuyla ("süper atom") betimlenir; "bu atom" ile "şu atom" ayrımı operasyonel içeriğini kaybeder. Bu yüzden BEC, madde fazında c₀ ortamına en yakın ortamdır ve c₀'ın **toplu tek-yapı** sezgisi için laboratuvarda erişilebilen en açık örnektir; süperakışkanlık da aynı aileye girer. Benzerlik yalnız toplu tek-yapı davranışındadır: BEC zamansız değildir, içinde zaman akar ve sistem Cₘ'de kalır. Soğutma tek başına c₀'a götürmez; BEC'te yaklaşılan şey c₀ değil, Cₘ'nin taban durumudur.

      $$\text{BEC} \neq c_0 \qquad (\text{madde fazında } c_0 \text{ ortamına en yakın ortam; analoji, kimlik değil})$$

      ```latex
      \text{BEC} \neq c_0 \qquad (\text{madde fazında } c_0 \text{ ortamına en yakın ortam; analoji, kimlik değil})
      ```

    * **Kara delik ve Hawking sıcaklığı:** Kara deliğe atfedilen Hawking sıcaklığı, ufkun uzaktaki Cₘ gözlemcisine verdiği termal okuma olarak yorumlanır; c₀'ın iç sıcaklığı değildir. Bu bir aday okumadır; ufuk ile faz sınırı arasındaki ilişki ve nicel köprü açıktır (Bölüm 3.2).

      $$T_H = \frac{\hbar c^3}{8\pi G M k_B}$$

      ```latex
      T_H = \frac{\hbar c^3}{8\pi G M k_B}
      ```

Özetle **c₀ (Çekirdek Fazı)**; Cₘ'ye ait ölçülebilir değişimin, üç boyutlu Öklid geometrisinin ve zamanın **henüz kurulmadığı**, maddenin metrik boşluksuz duruma yakınsayan tek bir yapı formunda bütünleştiği ve bilginin imha edilmeden bu tümleşik yapıda potansiyel olarak korunduğu **zaman-öncesi çekirdek rejimidir**. Zaman c₀'da durmuş değildir; kurulmamıştır.

---

* **$c^+$ (Karanlık Madde / Karanlık Enerji / Vakum Fazı — Çözünmüş Faz):** Evrenin madde (bütün parçacık yapısı) ya da kara delik formunda bulunmayan yapısının tümü c⁺ fazıdır: kozmik boşluklar (voids), vakum ortamı, karanlık madde ve karanlık enerji — ve **atomu oluşturan parçacıkların arasındaki boşluk dahi** c⁺'tır (yazar hükmü). Evertophy ontolojisinde c⁺ (Zamansız Üst Faz / Arşiv / Koordinasyon Katmanı); tam üçgen faz mimarisinde ($c_0 \leftrightarrow C_m \leftrightarrow c^+ \leftrightarrow c_0$) kütleli madde kısıtlarının, Öklid geometrisinin ve zaman akışının çözündüğü; tarihsel adıyla "enformasyonel doku bütünlüğüne" (graph state / texture integrity) sahip üst koordinasyon ve arşiv katmanıdır.

  $$\boxed{\;C_m\text{ ekranında "boşluk" olarak okunan her bölge — galaksiler arası boşluktan atomun içindeki parçacıklar arası boşluğa kadar — }c^+\text{'ın }C_m\text{'deki okumasıdır.}\;}$$

  ```latex
  \boxed{\;C_m\text{ ekranında "boşluk" olarak okunan her bölge — galaksiler arası boşluktan atomun içindeki parçacıklar arası boşluğa kadar — }c^+\text{'ın }C_m\text{'deki okumasıdır.}\;}
  ```

  c⁺'ta üç boyutlu uzay çözünmüş olduğundan, "c⁺ bir yerde bulunur" demek doğru değildir; doğru ifade, Cₘ'nin "boşluk" olarak okuduğu şeyin c⁺ olduğudur. Bu hüküm atom fiziğinin ölçülmüş sonuçlarını değiştirmez; kuantum mekaniğinin atom içi öngörüleri Cₘ hesap dili olarak aynen geçerlidir.

  * **Ontolojik statü — Cₘ madde desteğinin çözülmesi ve zamansız arşiv:**
    * **Madde desteğinin çözülmesi (matter-support dissolution):** c⁺ fazında, içinde yaşadığımız madde fazına (Cₘ) özgü kütleli parçacıklar, atomik yapılar ve üç boyutlu Öklid metriği ($g_{\mu\nu}$) geçerli değildir:

      $$\mathrm{supp}_{C_m}(\text{madde}) \to \varnothing, \qquad g_{\mu\nu}^{(C_m)} \to \bot_+$$

      ```latex
      \mathrm{supp}_{C_m}(\text{madde}) \to \varnothing, \qquad g_{\mu\nu}^{(C_m)} \to \bot_+
      ```

      c⁺ fazında maddesel kütle, Öklid uzunluğu ya da fiziksel süre aynen korunamaz; bu büyüklükler Cₘ ekranının okuma araçlarına aittir.
    * **Zamansız arşiv (provenance registry):** c⁺ geleceğe dair metafizik bir kaynak değildir. Cₘ fazında gerçekleşmiş bütün mühürlü kayıtların (sealed provenance), zamansal sıralama gerektirmeksizin bütünsel olarak birlikte bulunduğu evrensel bellek kütüphanesidir. Birlikte bulunmak, Cₘ'den erişilebilir olmak demek değildir; erişim, açık okuma yasasına bağlıdır (Bölüm 15.2).
  * **Kanonik kimlik:** Evertophy ontolojisinde c⁺ fazı; karanlık sektörün, vakum ortamının ve madde yapısının içindeki boşlukların faz kimliğidir:

    $$\boxed{\;c^+\;\equiv\;\text{Karanlık Madde (DM)}\;\equiv\;\text{Karanlık Enerji (DE)}\;\equiv\;\text{Vakum}\;}$$

    ```latex
    \boxed{\;c^+\;\equiv\;\text{Karanlık Madde (DM)}\;\equiv\;\text{Karanlık Enerji (DE)}\;\equiv\;\text{Vakum}\;}
    ```

    Kuantum alan kuramının "vakum durumu" ve onunla yapılan hesaplar, bu ontolojik kimliğin **Cₘ içindeki hesap dilidir**; vakumda ölçülen her etki koşulsuz kabul edilir ve Evertophy'de c⁺'ın Cₘ'deki okuması olarak yorumlanır.

    Astrofizikçilerin iki ayrı gizemli yapı ya da parçacık olarak aradığı karanlık madde ve karanlık enerji, Evertophy ontolojisinde iki farklı varlık değildir. İkisi de aynı c⁺ fazının, Cₘ ekranından bakıldığında bulunduğu ortama göre ortaya çıkan farklı gözlemsel izdüşümleridir (readout modes):

    $$
    c^+ \text{ Fazı}
    \longrightarrow
    \begin{cases}
    \text{Galaktik / küme ölçeğinde (kümelenmiş)}
    &\longrightarrow \text{Karanlık Madde (DM) okuması} \\[4pt]
    \text{Kozmolojik ölçekte / boşluklarda (genişlemeyi sürdüren)}
    &\longrightarrow \text{Karanlık Enerji (DE) okuması} \\[4pt]
    \text{Laboratuvar ölçeğinde}
    &\longrightarrow \text{Vakum okuması}
    \end{cases}
    $$

    ```latex
    c^+ \text{ Fazı}
    \longrightarrow
    \begin{cases}
    \text{Galaktik / küme ölçeğinde (kümelenmiş)} &\longrightarrow \text{Karanlık Madde (DM) okuması} \\[4pt]
    \text{Kozmolojik ölçekte / boşluklarda (genişlemeyi sürdüren)} &\longrightarrow \text{Karanlık Enerji (DE) okuması} \\[4pt]
    \text{Laboratuvar ölçeğinde} &\longrightarrow \text{Vakum okuması}
    \end{cases}
    ```

    Kimlik, gözlenen yoğunlukların eşit olduğu anlamına gelmez; ontolojik kimlik ile her gözlemsel olgu için gereken nicel mekanizma ayrı şeylerdir (Bölüm 11.2).

  * **Konuma ve ölçeğe göre iki görünüm** *(arşivde "tutuklu" ve "serbest" adlarıyla da geçer)*:
    * **Galaktik kümelerde — kümelenmiş c⁺ (karanlık madde okuması):**
      * **Aday okuma:** c⁺, galaksiler ve yoğun Cₘ baryonik madde kümeleriyle Çekim Kuvveti'nin kısıt koheransı altında birlikte kümelenir.
      * **Gözlemsel okuma:** Bu kümelenme Cₘ gözlemcisine; ışımayan, parçacık olarak tespit edilemeyen ama galaksi dönme eğrilerini (RAR) bir arada tutan ve kütleçekimsel merceklenme yaratan **ek kütleçekimsel etki** olarak yansır. Kaynak c⁺'tır, okuma dili Cₘ'nin kütleçekim ve metrik dilidir; bu okuma c⁺'a Cₘ-tipi durgun kütle ya da metrik eklemez. Nicel mekanizma açıktır.
    * **Kozmik boşluklarda ve evren ufkunda — genişlemeyi sürdüren c⁺ (karanlık enerji okuması):**
      * **Aday okuma:** Galaksiler arası büyük kozmik boşluklarda madde yoğunluğu çok düşük olduğundan, c⁺ üzerindeki madde baskısı ve mühürleme kısıtı zayıflar.
      * **Gözlemsel okuma:** Maddeden uzaklaşan c⁺ kendi doğal gevşeme rejimine döner. Bu bir dış "itme kuvveti" ya da "anti-kütleçekim sıvısı" değil; kısıtın çözülmesiyle ortaya çıkan **hacimsel faz genleşmesi** olarak okunur. Cₘ gözlemcisi bu genleşmeyi evrenin hızlanarak genişlemesi (karanlık enerji) olarak ölçer. Ölçülen hızlanma koşulsuz kabul edilir; c⁺ ile bağı Evertophy okumasıdır ve nicel mekanizması açıktır.

---

  * **Beliren zaman, mühürleme (sealing) ve kayıt mimarisi:**
    * **Zamanın c⁺'ta çözünmesi:** Fiziksel zaman Evertophy'de bağımsız akan bir saat değildir; yalnız Cₘ fazındaki ayırt edilebilir değişime ($\mathcal{G}_{C_m}$) bağlı beliren (emergent) bir okumadır. c⁺'ta zaman ve zamana bağlı hiçbir kısıt yoktur. Bu, c₀'daki "henüz kurulmamış" yokluktan farklı bir yokluktur: c⁺'ta Cₘ'de kurulmuş olan zaman **çözünmüştür**. "$dt_{c^+}=0$" yazımı c₀'daki gibi yalnız pedagojik bir kısaltmadır; ontolojik ifade $\bot_+$'tır ve $\bot_+$ sayısal sıfır değildir.

      $$T(c^+)=\bot_+,\qquad \mathcal G_{C_m}\big|_{c^+}=\bot_+\neq0,\qquad dt_{c^+}=0\ \ (\text{yalnız pedagojik kısaltma})$$

      ```latex
      T(c^+)=\bot_+,\qquad \mathcal G_{C_m}\big|_{c^+}=\bot_+\neq0,\qquad dt_{c^+}=0\ \ (\text{yalnız pedagojik kısaltma})
      ```

    * **Mühürleme ve zamanın oku:** Zaman yalnız Cₘ'de ve tek yönlüdür; aksi hâlde nedensellik ortadan kalkar, çünkü madde fazında her şey neden–sonuç ilişkisi içindedir. Faz geçişleri çift yönlüdür; ama kayıt kanalı **tek yönlüdür** (Cₘ → c⁺) ve mühürleme gerçekleştiğinde kayıt sabittir (yazar hükmü). Zamanın tek yönlü akışı, Cₘ'de üretilen kaydın c⁺'a bu biçimde **yalnız eklenerek** (append-only) ve geri alınamaz olarak yazılmasıyla ilişkilendirilir. "Kayıt defteri" (registry) bağımsız bir varlık değil, bu iz için kullanılan okuma dilidir (Bölüm 7.7a). Ölçüm anındaki sürecin Cₘ içindeki hesap dili olarak tam pozitif ve iz koruyan kuantum kanalları (CPTP, Kraus temsili) kullanılabilir; bu araçlar mühürlemenin tanımı değil, Cₘ modelidir (Bölüm 15.2).

      $$\text{kapı: } c_i\rightleftarrows c_j\ \ (\text{çift yönlü}),\qquad \text{kayıt kanalı: } C_m\longrightarrow c^+\ \ (\text{tek yönlü; mühür sabit})$$

      ```latex
      \text{kapı: } c_i\rightleftarrows c_j\ \ (\text{çift yönlü}),\qquad \text{kayıt kanalı: } C_m\longrightarrow c^+\ \ (\text{tek yönlü; mühür sabit})
      ```

    * **Mühürleme maliyeti $C_s$ — aday okuma:** Değişimin Cₘ'den c⁺ arşivine mühürlenmesi ve c⁺ kaynaklı etkinin Cₘ ekranında okunması bir işlem maliyeti doğurabilir. Bu maliyetin Cₘ'de kütleçekimsel zaman genişlemesi ve yazma gecikmesi (write latency) olarak — yani zamanın göreliliği olarak — okunması bir **aday okumadır**; genel göreliliğin ölçülmüş sonuçlarını yeniden adlandırır, onları türetmiş sayılmaz (Bölüm 8.7, 14.3).

---

  * **İnsan zaman algısı, $0<v<c$ bandı ve c⁺ rejimi:**
    * **Algı ve anomaliler:** İnsan algısı ve ölçüm cihazları tümüyle Cₘ fazının çıktılarıyla ölçüm yapar. Ölçüm sonuçlarına Cₘ'nin içinden baktığımız için zamanın tek yönlü akışını ve ışık hızı sınırını mutlak varsayarız. Bu nedenle c⁺ ile Cₘ arasındaki sınırda ortaya çıkan etkileri — kuantum dolanıklık, tünelleme, karanlık sektör — "imkânsız anomaliler" ya da "ışıktan hızlı hayaletimsi etkiler" olarak sınıflandırırız.
    * **Işık hızı ötesi rejim:** Cₘ fazında maddesel varoluş yalnız $0<v<c$ bandında mümkündür. c⁺ fazı bu bandın çözüldüğü, $c$-ötesi üst rejimdir. Orada "ışıktan hızlı parçacık hareketi" yoktur; çünkü c⁺'ta metrik mesafe, zaman ve parçacık ivmelenmesi dili tanımlı değildir. c⁺'ın $c$-ötesi olması, Cₘ-tipi bir $dx/dt>c$ hareketi demek değildir (Bölüm 3.4).
    * **Sınırdaki yapılar:** Bir yapı iki rejimin sınırında bulunabilir. Cₘ'nin $v=c$ sınırında bulunan bir yapı, aynı zamanda c⁺ rejiminin de sınırındadır: iki rejim bu sınırı paylaşır. Sınırda bulunmak, iki fazdan birine üye olmak değildir; ışık ve kütleçekim dalgaları bu ortak sınırda yayılır, kuantum ve atom altı düzey de bu sınırın davranışlarını gösterir (Bölüm 18.0).

      $$\text{sınır}(C_m)\big|_{v=c}\;=\;\text{sınır}(c^+)\big|_{C_m\text{ yönü}},\qquad \text{liminal}\neq C_m\ \text{üyeliği},\qquad \text{liminal}\neq c^+\ \text{üyeliği}$$

      ```latex
      \text{sınır}(C_m)\big|_{v=c}\;=\;\text{sınır}(c^+)\big|_{C_m\text{ yönü}},\qquad \text{liminal}\neq C_m\ \text{üyeliği},\qquad \text{liminal}\neq c^+\ \text{üyeliği}
      ```

---

  * **Kuantum fenomenleri ve sınır rejimleri:**
    * **Hartman etkisi — zamansız faz kestirmesi (uyumlu okuma):** Kuantum tünellemede bir parçacığın bariyer içindeki geçiş süresinin, bariyer kalınlığıyla büyümeyip sabit bir değere doyması (Hartman etkisi) ölçülmüş bir olgudur. Evertophy bunu, parçacığın bariyeri üç boyutlu Öklid uzayında adım adım katetmesi olarak değil; bariyerle karşılaşan kaydın geçici olarak gevşemesi (unsealing), parçacığın metriksiz c⁺ faz kestirmesini kullanması ve bariyerin arkasında yeniden mühürlenmesi (resealing) olarak okur. Bu okumada bariyer içinde kalınlıkla orantılı bir Cₘ zamanı üretilmez; geçiş süresinin doyması bununla uyumludur.
    * **Kuantum dolanıklık:** Cₘ'de birbirinden uzakta görünen iki parçacık, c⁺ katmanında zamansız tek bir ilişki üzerinden bağlıdır (tarihsel adıyla işlem grubu / graph state). Dolanıklık, Cₘ'de ışıktan hızlı giden bir sinyal değildir; c⁺ katmanındaki zamansız ilişkinin Cₘ'deki ölçümle görünür hâle gelmesidir (phase projection). c⁺ bir iletişim kanalı değildir: bu okuma sinyal göndermeyi mümkün kılmaz.
    * **Çift yarık deneyi (aday okuma):** Parçacık ölçülmediği sürece c⁺ ile Cₘ arasındaki sınırın yerel olmayan, dalga benzeri davranışını gösterir; ölçüm yapıldığı anda Cₘ ekranında parçacık olarak kaydedilir ve mühürlenir.
    * **Nötrinolar — faz rejim sınırındaki yapılar:** Varlığı bilinen ama zor ölçülen nötrinolar, Cₘ fazına en zayıf biçimde bağlı, kütle ile ışık arasındaki sınıra en yakın yapılar olarak okunur. Yolculuk sırasında tür değiştirmeleri (nötrino salınımı) sağlam biçimde ölçülmüş bir olgudur ve bu sınırda bulunma okumasına adaydır. Nötrinoların ışıktan hızlı gittiğini öne süren 2011 ölçümü bir ölçüm hatası olarak geri çekilmiştir; Evertophy bu sonuca dayanmaz.
    * **Vakumdan enerji ve çift oluşumu (pair production):** c⁺ ≡ vakum kimliği altında, kuantum alan kuramının vakum hesapları c⁺'ın Cₘ'deki hesap dilidir. Güçlü bir elektrik alanla vakumdan parçacık üretimi (Schwinger mekanizması) ya da yüksek enerjili fotonlardan çift oluşumu, c⁺ → Cₘ kenarında dış enerjiyle tetiklenen yerel bir faz geçişi olarak okunur (aday okuma).

---

  * **c⁺ fazıyla uyumlu okunan deney ve gözlemler:**

Evertophy'de c⁺ fazı soyut bir hipotez olarak değil, deney ve gözlem izleriyle temas eden bir okuma olarak ele alınır. Aşağıdaki örneklerin hiçbiri c⁺'ın kanıtı değildir; her biri ölçülmüş bir olgu ve onunla **uyumlu** bir Evertophy okumasıdır. Ölçümler koşulsuz kabul edilir; okumalar opsiyoneldir.

1. **Stuttgart kuantum teleportasyon deneyi (Kasım 2025, Nature Communications):** Birbirinden bağımsız iki kuantum noktasından çıkan fotonlar arasında polarizasyon durumu yaklaşık %72 başarıyla aktarılmıştır. Kuantum teleportasyon protokolü bir Bell ölçümü ve **klasik bir iletişim kanalı** gerektirir; bilgi aktarımı bu klasik kanal olmadan tamamlanmaz. Evertophy okuması bu ölçülmüş yapıyı değiştirmez: c⁺, aktarımı mümkün kılan **korelasyonun kaynağı** olarak okunur; sinyal taşıyan bir kanal değildir. Fotonlar $v=c$ sınırında, yani Cₘ ile c⁺'ın ortak sınırında bulunan yapılardır.
2. **Hartman etkisi tünelleme ölçümleri:** Tünelleme süresinin bariyer kalınlığından bağımsız bir değere doyması, c⁺ zamansız kestirmesiyle uyumlu bir okumadır.
3. **Casimir etkisi:** Vakumdaki iki iletken plaka arasındaki ölçülmüş kuvvet, c⁺ ≡ vakum kimliği altında, c⁺'ın Cₘ üzerindeki okuması olarak yorumlanır; kuvvetin standart kuantum alan kuramı hesabı Cₘ hesap dili olarak aynen geçerlidir.
4. **Lene Hau ve BEC deneyleri:** Işığın Bose–Einstein yoğuşması içinde çok yavaşlatılması ve durdurulması, $v=c$ sınırındaki ışığın, madde fazında c₀ ortamına en yakın ortam içinde yavaşlatılması olarak okunur; atomların tek bir kuantum dalgasında birleşmesi, c₀'ın toplu tek-yapı sezgisinin laboratuvar analoğudur.
5. **Gecikmeli seçimli kuantum silici:** Standart kuantum mekaniği bu deneyi geriye doğru bir etki olmadan açıklar. Sonuçlar, c⁺'ın zamansal sıralama gerektirmeyen bir arşiv olduğu okumasıyla **uyumludur**; bu okuma geriye etki ya da sinyal içermez ve deneyin bir "tescili" değildir.
6. **ANITA anomalisi:** Antarktika üzerindeki balon deneyinin kaydettiği, Dünya'nın içinden yukarı doğru geliyor gibi görünen ultra yüksek enerjili olaylar hâlâ tartışmalıdır. Evertophy bunları kozmik ölçekte bir tünelleme sızıntısı olarak okumaya adaydır (aday okuma).

---

### c⁺ fazının nitelikleri (madde fazıyla karşılaştırmalı okuma)

| Özellik / Büyüklük | $C_m$ (Madde Fazı) | $c^+$ (Zamansız Üst Faz / Arşiv) |
| :--- | :--- | :--- |
| **Kinematik üyelik** | $0<v<c$ (madde); $v=c$ liminal sınır | $c$-ötesi rejim; Cₘ madde desteği çözülmüştür |
| **Fiziksel zaman** | Var ve beliren ($dt_{C_m}>0$) | **Çözünmüş** ($\bot_+$; pedagojik kısaltma $dt_{c^+}=0$) |
| **Metrik tensör ($g_{\mu\nu}$)** | Tanımlı (3B Öklid temel uzay; etkin 3+1 okuma) | **Tanımsız / metriksiz** ($\bot_+$) |
| **Ontolojik kimlik** | Ölçümün ve dolaylı etkilerin okunduğu faz | **$c^+\equiv\text{DM}\equiv\text{DE}\equiv\text{Vakum}$** |
| **Galaktik küme okuması** | Yıldızlar, gaz ve görünür kütle | **Kümelenmiş c⁺ — karanlık madde okuması** |
| **Kozmik boşluk okuması** | Madde seyrelmesi | **Genişlemeyi sürdüren c⁺ — karanlık enerji okuması** |
| **Laboratuvar okuması** | Ölçüm düzeneği | **Vakum** |
| **Atom içi** | Parçacıklar (çekirdek, elektronlar) | **Parçacıklar arası boşluk** |
| **Kuantum tezahürü** | Ölçülmüş parçacık / olay | **Dolanıklık korelasyonunun kaynağı** (aday okuma) |

---

* **$c$ (Işık Hızı):**
  * **Tutarlılık kısıtı (phase threshold):** Standart fizikte ışık hızı aşılamaz bir evrensel hız sabiti sayılır. Evertophy'de ışık hızı, **Cₘ fazının kayıt-çözünürlük sınırı ve faz eşiğidir**. Cₘ'de ışık hızı tanımsal bir nokta aralıktır, $c_{C_m}=[c,c]$.
  * **Rejim değişimi (phase gate):** Kütleli bir cisim Cₘ içinde hızlanarak ışık hızına ulaşamaz. Bu sınırda "ışıktan hızlı hareket eden madde" oluşmaz; söz konusu olan bir hızlanma değil, **c⁺ rejimine faz geçişidir**: aşılan şey bir hız değeri değil, Cₘ'nin üyelik bandıdır. Geçişten sonra kütleli madde formu çözülür ve Cₘ'nin hız dili tanımsızdır:

    $$\boxed{\;\mathrm{supp}_{C_m}(\text{madde})\to\varnothing\;}$$

    ```latex
    \boxed{\;\mathrm{supp}_{C_m}(\text{madde})\to\varnothing\;}
    ```

  * **Liminal durum (foton):** Işığın kendisi (foton) $v=c$ sınırında bulunur. Ne Cₘ'nin kütleli maddesine üyedir ne de c⁺'ın içindedir; iki rejimin **ortak sınırındadır**: Cₘ bandının sınırı, aynı zamanda c⁺ rejiminin sınırıdır. Kütleçekim dalgaları da aynı sınırda yayılır (yazar hükmü); kütleçekim dalgalarının ışıkla aynı hızda yayıldığı ölçümle bilinmektedir.

### Üç fazlı yapının sonuçları

Kısaca: bizim yaşadığımız ve ölçtüğümüz farklılaşmış madde fazı **Cₘ**'nin bir yanında zaman-öncesi potansiyel fazı **c₀**, öbür yanında zaman-dışı üst faz **c⁺** durur. Bu "yan" sözcükleri mekânsal değil, kavramsaldır: fazlar birbirine bir zincirle değil, tam bir üçgenle bağlıdır. Bu üç faz birlikte Dinamik Evren'i, $U_x$'i oluşturur. Bu evrenin dışında ise iki uç koşul bulunur: mutlak kaynak $U_0$ ve mutlak çözünme $U_+$.

Bu yapının en önemli sonucu şudur: zaman, üç boyutlu Öklid uzayı ve ışık hızı sınırı gibi temel kavramlar **yalnız Cₘ'de** geçerlidir. c₀'da bu yapılar henüz kurulmamıştır; c⁺'ta ise çözünmüşlerdir. Yani "zaman" ya da "uzay", evrenin her yerinde aynı anlamda var olan şeyler değil, bir fazın kendine özgü yapılarıdır.

Bu bakış, kopuk görünen parçalara bir yer açar. Zamanın yönü, c⁺'a yazılan kaydın tek yönlülüğüyle ilişkilendirilebilir. Ölçüm, Cₘ'ye ait bir olay olarak konumlanır. Karanlık madde ve karanlık enerji, aynı c⁺ fazının iki görünümü olarak okunur: maddeyle kümelenmiş c⁺ karanlık madde, genişlemeyi sürdüren c⁺ karanlık enerji olarak görünür; laboratuvarda ise c⁺ vakum olarak karşımıza çıkar. Entropi, Cₘ yapısının c⁺'a çözünmesidir; enerji yok olmaz, c⁺'ta mühürlenir. Bu yapının en temel ilkesi **Çekim Kuvveti**dir: bilinen dört kuvvet — kütleçekim de dahil — onun ölçeğe, kütle miktarına ve faza göre farklı izdüşümleridir ve üç faz onun altında bir denge içinde bir arada durur. Fazların hangi rejimde çözüleceğini ise $X(x)$ dinamik üst çözücüsü belirler: verili durumda hangi faz rejiminin geçerli olduğunu ve hangi durumların kabul edilebilir olduğunu çözen yapı.

Dürüst olmak gerekirse, bu okumaların hiçbiri henüz kanıtlanmış değildir. Evertophy'nin kanonik sayısal öngörü sayacı hâlâ **0/10**'dur. Bu belge çerçevenin ontolojik iskeletini ortaya koyar: neyin ne olduğunu, neyin neyle ilişkili olduğunu ve neyin yasak olduğunu. Sayısal bir kanıt sunmaz. Bilimsel konumuyla Evertophy, üç fazlı ve iki seviyeli bir ontoloji, seçilmiş biçimsel sonuçlar ve koşullu etkin modeller içeren bir TOE araştırma programıdır; belirli bir fiziksel seçim ilkesi ve ayırt edici, ön-kayıtlı bir öngörü henüz açıktır.

$$\boxed{\;\text{Kanonik sayısal öngörü sayacı: } \mathbf{0/10}\;}$$

```latex
\boxed{\;\text{Kanonik sayısal öngörü sayacı: } \mathbf{0/10}\;}
```

### Bu arayış nasıl sınandı: çapraz-AI maratonu

Bir çerçeve ne kadar tutarlı görünürse görünsün, onu kuranın gözünden kaçan hatalar içerebilir. Bu yüzden **23–26 Eylül 2026** tarihleri arasında Evertophy'yi olabildiğince sert bir denetimden geçirdik.

Yedi yapay zekâ — Claude, ChatGPT Math&Physics, ChatGPT Düşünce Deneyleri, WolframGPT, Kimi, Qwen ve Grok — 20 tur boyunca Evertophy'nin denklemlerini, tiplerini ve ontolojik iddialarını, birbirlerinin çıktılarını denetleyerek sınadı. Ardından dört turda sonuçlar derlendi ve bir kez daha çapraz denetimden geçirildi. Maraton boyunca Evertophy'nin kendi kuralları bilinçli olarak askıya alındı; her yapay zekâ serbestçe eleştirebildi ve türetim önerebildi. Yalnız iki kural her turda hatırlatıldı: aralık (Range) formalizmi ve temel yapıların yalnız Cₘ'de geçerli olduğu ilkesi.

Amaç yeni öngörüler üretmek değildi. Amaç, çerçevenin **iç tutarlılığını** en yüksek güvenle sınamak, hatalı iddiaları ayıklamak, doğru olanları biçimsel olarak mühürlemek ve açık kalanları dürüstçe işaretlemekti. Sonuçlar üç başlıkta toplanabilir.

**Doğrulananlar.** Çerçevenin tip ve cebir iskeleti, Lean adlı teorem kanıtlayıcıyla biçimsel olarak kodlandı: 269 teorem ve lemma bildirimi — 46'sı yalıtılmış üretim çekirdeğinde, 223'ü arşivde — ve hiçbirinde eksik bırakılmış kanıt yok. İki farklı "yokluk" — c₀'daki henüz-kurulmamışlık ile c⁺'taki çözünmüşlük — birbirinden ayrıldı; üretim çekirdeğinde Cₘ'ye özgü değer aileleri için yanlış fazda değer inşası tip düzeyinde engellendi. Yazarın tanımladığı tam üçgen kapı yapısı biçimsel olarak kodlandı ve bu kodlanmış sistem içinde zaman, uzay, metrik, içsel hız, ışık hızı sınırı ve durgun kütle gibi Cₘ'ye özgü niceliklerin **hiçbir kapıdan taşınamayacağı** kanıtlandı. Lean, üçgeni doğadan türetmedi; yazarın verdiği yapının sonuçlarını denetledi. Üstelik bu kilit, c⁺ kaynaklı etkilerin Cₘ'de okunmasını engellemiyor. Arşiv cebirinin de, aynı olay dizisi nasıl gruplanırsa gruplansın tek bir kayda ulaştığı kanıtlandı; olayların sırası ise her zaman korunur.

**Ayıklananlar.** Otuzu aşkın iddia karşı-örneklerle çürütüldü ya da kapsamı daraltılarak geri çekildi: boyut hatası içeren eski bir kuantum eşiği, hiçbir şeyi ayırt etmediği ortaya çıkan bir asimetri ölçütü, doğru bir öngörüyü reddedebilecek bir uyum eşiği ve benzerleri. Bunların bir kısmı çerçevenin kendi eski metinlerinden, bir kısmı maratona katılan yapay zekâların önerilerinden geliyordu. Emekliye ayrılan iddialar silinmedi; neden çürütüldükleriyle birlikte kayıtta duruyor.

**Açık kalanlar.** En önemli sonuç belki de bir açığın yerini kesin olarak belirlemekti. $X$'ten ölçülebilir fiziksel niceliklere giden köprünün, tip kuralları ve iyi-tanımlılık koşullarıyla **tekil olarak seçilemeyeceği** sonlu düzeyde biçimsel olarak, sürekli düzeyde analitik karşı-örneklerle gösterildi. Yani çerçevenin gözlemle temas noktası bir fiziksel seçim ilkesi ve gözlem gerektiriyor. Bu borç gizlenmedi; dondurulmuş açık borç olarak kayda geçti.

Maratonun bana öğrettiği en önemli şey şuydu: bir iddianın doğruluğu, kaç kişinin ona katıldığıyla değil, türüne uygun kanıtla belirlenir. Yedi yapay zekânın aynı sonuca varması bir ispat değildir. Ve kanıt yokken bir soruyu açık bırakmak, onu zorla kapatmaktan her zaman daha iyidir.

### Bu belge ne sunuyor

Bu belge, Evertophy Çekirdek Ontolojisi'nin ilk yayınlanabilir sürümüne doğru hazırlanmış metindir. Maratonun sonuçları ve benim sonraki doğrudan açıklamalarım ilgili bölümlere işlenmiştir; her kavramın tek ve güncel anlatımı verilmiştir. Sürüm geçmişi ve denetim izi bu belgenin dışında, V24 rolling master'da tutulur. Henüz kapanmamış ya da alternatifli kısımlar gizlenmemiş, açıkça belirtilmiştir; açık borçlar ve bekleyen kararlar EK K'dedir.

Bir şeyi de açıkça söylemeliyim: çapraz-AI maraton konsensüsü kendi başına kanon değildir. Evertophy'de neyin kanon olduğuna son sözü yazar verir.

*— Uğur Yılmaz*

*Bu bölüm yazar tarafından kendi anlatım diliyle yazılmıştır; Claude yalnız yazım, notasyon ve güncel kanonla hizalama düzeltmeleri yapmıştır.*




---

## Bu belgeyi nasıl okumalı

**Bu belge ne yapar:** Evertophy'nin **özünde ne olduğunu** anlatır: hangi varlıklardan söz ettiğini, bunların birbiriyle nasıl ilişkilendiğini ve hangi kavramın neyi ifade ettiğini. Okur başka hiçbir belgeye bakmadan izleyebilir.

**Bu belge ne yapmaz:** Bir türetim sunmaz, sayısal öngörü üretmez, teorem kanıtlamaz. Biçimsel sonuçlar ve modeller anıldığında, kapsamları ve statüleri yanlarında yazılıdır.

**Anlatım biçimi:** İç geliştirme jargonu (sürüm etiketleri, statü damgaları) olabildiğince kullanılmaz. Bir ifadenin hangi güvenle söylendiği doğrudan cümlede belirtilir: **kanon**, **yazar hükmü**, **model**, **köprü**, **aday okuma**, **uyumlu okuma**, **açık** ya da **emekli**. Denklem içeren her kısımda önce denklem, hemen altında kopyalanabilir LaTeX kodu, ardından sembollerin açıklaması gelir. Denklemin işlevi ise beş soruluk kısa bir çizelgeyle özetlenir:

| Soru | Cevabın anlattığı |
|---|---|
| **Ne yapıyor?** | Denklemin ya da yapının işlevi |
| **Neden yapıyor?** | Hangi boşluğu, hatayı ya da ihtiyacı karşıladığı |
| **Nasıl yapıyor?** | Hangi yöntem, hangi varsayım ve hangi araçla |
| **Ne sonuç bekleniyor?** | Kurulduğunda ne sağlaması amaçlanıyor |
| **Ne sonuç elde ediliyor?** | Bugünkü durum ve statü |

---

## Kaynak disiplini notu

Bu monografi tek bir arşivin özeti değildir; birçok katmanın süzülmüş hâlidir. Doğrudan çalışma tabanı bir önceki güncel çekirdek metindir (minor12). Arşiv taramaları, öz-düzeltme raporları ve karar kayıtları toplu aktarım yapılmadan madde madde ayrıştırılmış; yalnız güncel çekirdekle uyumlu olan eksik kapsam eklenmiştir. Kaynakta bulunan olgu ile bir aracın yorumu birbirinden ayrı tutulur.

Çapraz yapay zekâ önerileri eşit otoritede değildir. Güncel doğrudan ontolojiyle çelişen bir öneri çekirdekten dışlanır. Yararlı ama türetilmemiş bir öneri **model**, **köprü** ya da **biçimsel aday** olarak; eski terminoloji **tarihsel** olarak; kararı verilmemiş bir anlam ise **açık borç** olarak ayrılır. Arşiv taramasının kapsamı yüksektir; ama dosya manifestosu ve hash tabanlı bir tamlık denetimi bulunmadığı için "kriptografik olarak eksiksiz tarama" iddiası kurulmaz.

Bu yüzden bu belge bütün arşivi tek düzleme döken bir derleme değil, **sürüm üstünlüğü uygulanmış bütünleşik bir çekirdektir**. Çelişki durumunda geçerli üstünlük sırası şudur:

$$\boxed{\;\text{Doğrudan yazar açıklaması} \;>\; \text{güncel çekirdek} \;>\; \text{güncel biçimsel kanon} \;>\; \text{uyumlu biçimsel aday} \;>\; \text{tarihsel arşiv} \;>\; \text{araç yorumu}\;}$$

```latex
\boxed{\;\text{Doğrudan yazar açıklaması} \;>\; \text{güncel çekirdek} \;>\; \text{güncel biçimsel kanon} \;>\; \text{uyumlu biçimsel aday} \;>\; \text{tarihsel arşiv} \;>\; \text{araç yorumu}\;}
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Birbiriyle çelişen kaynaklar arasında hangisinin geçerli olduğunu belirler |
| **Neden yapıyor?** | Çerçeve aylar boyunca birçok araç ve sürümle gelişti; eski bir kayıtta "kesinleşmiş" görünen bir ifade, daha yeni bir yazar hükmüyle çelişebilir |
| **Nasıl yapıyor?** | Kaynakları otorite sırasına dizer; en üstte yazarın doğrudan açıklaması, en altta bir aracın yorumu durur |
| **Ne sonuç bekleniyor?** | Tarihsel zenginliğin korunması, ama güncel çekirdekle karışmaması |
| **Ne sonuç elde ediliyor?** | Eski bir ifade daha yeni bir doğrudan açıklamayla çelişiyorsa güncel çekirdeğe girmez; arşivde tarihsel kayıt olarak kalır |

Sürüm geçmişi, düzeltme kayıtları ve denetim izi birlikte yayımlanan güncel V24 rolling master sürümünde tutulur. Bu metin yazarın yönetiminde, çapraz yapay zekâ denetimiyle derlenmiştir: derleyici Claude; denetçiler ChatGPT (Math&Physics, Düşünce Deneyleri, Codex), WolframGPT, Kimi, Qwen ve Grok.




# BÖLÜM 0 — GİRİŞ KAPISI

## 0.1 Tek paragrafta Evertophy

Evertophy, gerçekliğin tek türden bir ortam değil, **üç ayrı fazın** bir arada bulunduğu bir yapı olduğunu öne süren bir çerçevedir. Suyun buz, sıvı ve buhar hâlleri gibi; ama bu kez maddenin değil, **gerçekliğin kendisinin** fazları. Bu üç faz **c₀** (zaman-öncesi potansiyel / çekirdek fazı), **Cₘ** (farklılaşmış madde, ölçüm ve zaman fazı; içinde yaşadığımız faz) ve **c⁺** (zaman-dışı üst / arşiv / koordinasyon fazı) olarak adlandırılır. Çerçevenin merkezî önerisi şudur: fiziksel yasalar bu fazların *içinde* keyfî olarak var olan kurallar değil, fazlar *arasındaki* ilişki ve geçiş yapısından doğan biçimlerdir. Bu yapıyı düzenleyen tek bir üst nesne vardır: **dinamik üst çözücü** $X(x)$. Bunların hepsinden önce ise numarasız bir öncül durur: **Çekim Kuvveti (Force of Attraction)**, Evertophy'nin temel ontolojik postülasıdır.

## 0.2 Bir sayfada Evertophy

Modern fizik dört büyük alana bölünmüş durumda: genel görelilik, kuantum mekaniği, Standart Model ve kozmoloji. Bu dördü ayrı ayrı olağanüstü başarılı, ama birbirlerinin dilinden tam anlamıyla anlamıyorlar. Evertophy'nin çıkış sorusu şudur: *bu dört alan aynı gerçekliği tarif ediyorsa, ortak grameri nedir?*

Önerilen cevap bir birleştirme denklemi değil, bir **çözücüdür**. $X(x)$ adı verilen bu nesne faz, bağlam ve kabul edilebilirlik durumunu çözer. Gerçek fiziksel katsayıların, kurucu haritanın ya da gözlenebilir değerin seçimi ise ayrı bir katmana aittir: fiziksel seçiciye, köprüye ve okuma yasasına.

Bu resimden altı temel sonuç çıkar:

**Birincisi, zaman temel değildir.** Evertophy'de fiziksel zaman yalnız Cₘ'de bulunur ve oradaki ölçülebilir değişimden doğar. c₀'da zaman henüz kurulmamıştır; c⁺'ta ise Cₘ'de kurulmuş olan zaman çözünmüştür.

**İkincisi, fiziksel nicelikler aralık değerlidir.** Bir nicelik $[P^-, P^+]$ biçiminde yazılır. Bu, "her sabit değişir" demek **değildir**: bir aralığın sıfır genişlikte olması ($[P,P]$) tamamen geçerli, statik ve deterministik bir durumdur.

**Üçüncüsü, Çekim Kuvveti temel ontolojik postüladır.** Bilinen dört kuvvet — kütleçekim de dahil — onun ölçeğe, kütle miktarına ve faza göre izdüşümleridir; Çekim Kuvveti ise yapının kendisine aittir.

**Dördüncüsü, metrik yalnız Cₘ'de tanımlıdır.** $g_{\mu\nu}$, c₀ ve c⁺'ta kabul edilebilir bir nesne değildir; ama iki fazda **farklı nedenlerle**: c₀'da henüz kurulmamıştır, c⁺'ta çözünmüştür.

**Beşincisi, tersinmezlik faz kapısında değil, kayıtta yaşar.** Geçişlerin kendisi çift yönlüdür; geri alınamaz olan, geçiş sırasında basılan **damgadır**.

**Altıncısı, çerçeve iki seviyelidir.** Üç fazın oluşturduğu Dinamik Evren ($U_x$) bir bütündür ve bu bütünün iki uç koşulu vardır: global doygunluk kutbu $U_0$ ve global çözünme kutbu $U_+$. Fazlar içeride, kutuplar dışarıdadır; ikisi aynı ontolojik sınıfa ait değildir.

### Çerçevenin kalbi

$$\boxed{\;\text{Evertophy'nin temel çalışma mekanizmasında, madde ve doku yönelimleri fazlar arası gerilim ve dönüşüm diliyle birlikte okunur.}\;}$$

```latex
\boxed{\;\text{Evertophy'nin temel çalışma mekanizmasında, madde ve doku yönelimleri fazlar arası gerilim ve dönüşüm diliyle birlikte okunur.}\;}
```

Yazarın onayladığı bu giriş kaydı, Çekim Kuvveti'nin yalnız bir Newton kuvveti ya da yalnız pasif bir Cₘ geometrisi olarak okunmamasını ister. Madde tarafındaki **kümelenme yönelimi** ile doku / c⁺ tarafındaki **genişleme yönelimi**, c₀, Cₘ ve c⁺ arasında sürekli bir ilişki ve dönüşüm üretir; çerçevenin ana anlatı ekseni budur.

Bu anlatı **Postüla-0'ın yerine geçmez**: Çekim Kuvveti'nin ontolojik önceliği entropiden türetilmiş sayılmaz. "Madde entropisi" ve "doku entropisi" ifadeleri burada fazlara özgü birer yönelim dilidir; standart termodinamik entropinin c₀ ve c⁺'a aynen taşındığı anlamına gelmez. Bu nedenle doğru terim **evrenin temel çalışma mekanizması**dır; "motor" dili kullanılmaz.

*Gösterim notu:* Bu belgede "iç / dış", "bir yanında / öbür yanında" gibi ifadeler ontolojik ve tip düzeyinde birer gösterimdir; mekânsal bir sıralama değildir. Global seviyede metrik ve uzay yoktur; faz topolojisi de zincir değil, tam üçgendir.

## 0.3 Evertophy neyi iddia *etmez*

Bir çerçeveyi anlamanın yolu, neyi iddia etmediğini de bilmekten geçer:

- **Tamamlanmış bir Her Şeyin Teorisi olduğunu iddia etmez.** Her Şeyin Teorisi hedefi taşıyan bir araştırma programıdır (0.6): kavramsal düzen ve matematiksel iskelet.
- **Standart Model sabitlerini türettiğini iddia etmez.** Mekanizma atamaları vardır; hiçbiri sayı üretmez.
- **Kozmolojik sabit problemini çözdüğünü iddia etmez.**
- **Kara delik bilgi paradoksunu çözdüğünü iddia etmez.**
- **Dolanıklığı açıkladığını iddia etmez;** bir okuma çerçevesi önerir.
- **Birleşimi yasaklamaz; sonradan açıklama çoğaltmayı yasaklar.** Aynı mekanizma birden fazla bağımsız olguyu açıklayabilir; ama sonuçlar aynı, önceden tanımlanmış türetim zincirinden, ek ayar gerektirmeden ve her gözlenebilir için ayrı yanlışlama koşullarıyla çıkmalıdır.
- **Hiçbir aktif ampirik kanıt iddiası taşımaz.**

## 0.4 Ampirik durumun açık beyanı

$$\boxed{\;\text{Kanonik sayısal öngörü sayacı: } \mathbf{0/10}\;}$$

```latex
\boxed{\;\text{Kanonik sayısal öngörü sayacı: } \mathbf{0/10}\;}
```

Çerçevenin bir dönem en güçlü ampirik iddiası sayılan çok-alanlı korelasyon hattı, **iç denetimle kalıcı olarak kapatılmıştır** (Bölüm 21). Bugün elde kalan ampirik varlıklar Evertophy **üzerine konan kısıtlardır**; Evertophy'den çıkan öngörüler değildir.

### 0/10 → 1/10 kapısı

Bir kalemin sayacı hareket ettirebilmesi için altı koşulu birlikte sağlaması gerekir:

| # | Şart |
|---|---|
| **i** | Ontolojiden **türetilmiş** olmalı |
| **ii** | Parametreleri ve köprü varsayımları **önceden sabitlenmiş** olmalı |
| **iii** | Standart yaklaşımın verdiğinden **ayırt edici** olmalı |
| **iv** | Tahmin aralığı **hedef veri görülmeden ön-kayıtlı** olmalı |
| **v** | Veri sürümü, hedef seçimi ve ayrılmış test kümesi dahil **veri soyağacı mühürlenmiş** olmalı |
| **vi** | **Kör veride** test edilmiş olmalı |

$$\boxed{\;\text{Altı koşul birlikte sağlanmadan hiçbir kalem } 1/10 \text{ sayılmaz.}\;}$$

```latex
\boxed{\;\text{Altı koşul birlikte sağlanmadan hiçbir kalem } 1/10 \text{ sayılmaz.}\;}
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bir iddianın "öngörü" sayılabilmesi için gereken asgari koşulları tanımlar |
| **Neden yapıyor?** | Geriye dönük uyum, veriye bakarak ayar ve tanımsal özdeşlikler öngörü gibi görünebilir; geçmişte kapatılan korelasyon hattı bunun örneğidir |
| **Nasıl yapıyor?** | Altı koşulu tek bir kapı olarak birleştirir; biri bile eksikse kalem sayılmaz |
| **Ne sonuç bekleniyor?** | Sayacın yalnız gerçekten türetilmiş, ayırt edici ve kör test edilmiş öngörülerle artması |
| **Ne sonuç elde ediliyor?** | Bugün hiçbir kalem altı koşulu birlikte sağlamıyor; sayaç **0/10** |

## 0.4a Ontoloji ile modelin ayrımı

Bu belgede **ontoloji**, çerçevenin temel kabul ettiği varlıkları, tipleri ve yapısal ilişkileri; **model** ise bu ontolojinin belirli bir fiziksel rejimdeki matematiksel gerçeklemesini ifade eder.

$$\boxed{\;\text{MODEL}\neq\text{ONTOLOJİ}\;}$$

```latex
\boxed{\;\text{MODEL}\neq\text{ONTOLOJİ}\;}
```

Bir modelin gözlemsel olarak başarılı olması, kullandığı bütün matematiksel nesnelerin temel ontolojik varlık olduğunu tek başına göstermez. Örneğin Cₘ içindeki metrik ve genel görelilik dili fiziksel okuma için zorunlu olabilir; ama bu, metriğin c₀ ya da c⁺'a temel ontolojik nesne olarak taşınmasına izin vermez.

Evertophy, yerleşik deneysel ve gözlemsel sonuçları **dış fizik kıyası** olarak koşulsuz kabul eder; kendi postülalarının, ontolojik yorumlarının ve köprü mekanizmalarının kabulünü bu dış sonuçlarla özdeşleştirmez. Çerçevenin görevi mevcut fiziği yok saymak değil, açıkça işaretlenmiş ek bir ontolojik ve yorumlayıcı yapı önermektir.

**Koşulsuz kabulün kapsamı.** Koşulsuz kabul edilen şey, ölçüm topluluğunun kendi yöntemleriyle doğruladığı **ölçüm sonucudur** — belirsizliği, sistematik hata kaydı ve kalibrasyon durumuyla birlikte. Ölçüm topluluğunun kendisi tarafından düzeltilen ya da geri çekilen sonuçlar (örneğin 2011 OPERA ışık-üstü nötrino ölçümü) bu düzeltmeyle birlikte kabul edilir. Koşulsuz olan, yöntemsel dürüstlüktür: hiçbir ontolojik okuma, güvenilir bir gözlemsel sonucu kendi lehine değiştiremez; bir ölçüm Evertophy okumasıyla çelişirse değişen okumadır.

## 0.5 Okunma sırası

| Kısım | Bölümler | İçerik |
|---|---|---|
| **I. Temel** | 1–3 | Postülatlar, $U_0$, global evren seviyesi ($U_x$, $U_+$), üç faz |
| **II. Çözücü** | 4–6 | $X(x)$, faz-parametre matrisi, aralık formalizmi |
| **III. Doğan yapılar** | 7–12 | Zaman, çekim, metrik, madde, c⁺ kimliği, eşikler |
| **IV. Geçiş ve kayıt** | 13–16 | Geçişler, damga cebiri, ölçüm, bilgi |
| **V. Köprüler** | 17–19 | Kanal asimetrisi, kuantum, topoloji |
| **VI. Program** | 20–25 | Standart Model ve genel görelilik, ampirik durum, nükleer köprü, yöntem, sınırlar, mekanizma adayları |
| **VII. Fenomen okumaları** | 26–27 | Açık fenomen envanteri ve aday denklem envanteri |
| **Ekler** | A–K | Sözlükler, denklemler, analojiler, epistemik düzen, biçimsel mimari, makine-okunabilir ayna, kanonik görsel, açık borçlar |

## 0.6 Araştırma programının kapsamı ve mevcut durumu

Evertophy, Her Şeyin Teorisi (TOE) hedefi taşıyan bir ontoloji ve fizik araştırma programıdır. Bu metin üç fazlı ve iki seviyeli temel tanımları, seçilmiş biçimsel sonuçları, koşullu model alternatiflerini ve açık fiziksel köprüleri kapsamlarıyla birlikte sunar. TOE hedefi programın araştırma yönünü belirtir; tamamlanmış ya da deneysel olarak doğrulanmış bir TOE statüsü vermez. Kanonik sayısal öngörü sayacı **0/10**'dur.

## 0.7 Paralel literatür notu

Çerçevenin gelişimi boyunca kesiştiği literatür hatları kayıt altındadır. Aşağıdaki aileler, birlikte yayımlanan bibliyografik kayıtlara dayanan ilgili çalışma karşılaştırmalarıdır. Ortak tema paralelliktir; türetim ya da doğrulama değildir.

| Hat | İlişki |
|---|---|
| Verlinde (entropik çekim) [Ver11] | Kütleçekimi temel bir kuvvet değil, entropik ve emergent bir olgu olarak okur; bu, Evertophy'nin temel Çekim Kuvveti postülasından farklı bir tezdir. Paralellik yalnız çekimin parçacık alışverişine indirgenmemesi sezgisindedir |
| Jacobson (termodinamikten genel göreliliğe) [Jac95] | Genel göreliliğin termodinamik kökeni — yöntem paralelliği |
| Holografik ilke [tH93, Sus95] | Sınır–içerik ilişkisi — yapı paralelliği |
| AdS/CFT [Mal98] | Sınır kuramı ile iç kütleçekim kuramı arasındaki karşılıklılık — yapı paralelliği |
| Bekenstein–Hawking entropisi [Bek73, Haw75] | $S_{BH}\sim A$ ilişkisi; çerçevede gözlemle sınanmamış kuramsal bir sonuç olarak tutulur (23.3) |
| Analog kütleçekim (Barceló–Liberati–Visser) [BLV05] | Akustik metrik ve dönüşüm optiği — yayın kapısı olarak en gerçekçi akraba |
| Volovik (süperakışkan He-3 evreni) [Vol03] | Faz tabanlı gerçeklik okuması — en yakın entelektüel akraba adaylarından |
| Kara delik kozmolojisi ailesi [Pat72, Dym92, Pop10, FMM89, FMM90] | Bağımsız benzer sezgiler. Evertophy'nin ayırt edici kısımları ($U_0$ sınırındaki kritik eşik, üç fazın aynı kuruluşta birlikte doğuşu, $X$ çözücüsü) incelenen karşılaştırma kümesinde doğrudan eşleşme göstermedi; kapsamlı bir öncelik ve özgünlük taraması yapılmadı |

### Kaynakça

- **[BLV05]** C. Barceló, S. Liberati, M. Visser, "Analogue gravity", *Living Rev. Relativ.* 8, 12 (2005); doi:10.12942/lrr-2005-12; arXiv:gr-qc/0505065.
- **[Bek73]** J. D. Bekenstein, "Black holes and entropy", *Phys. Rev. D* 7, 2333–2346 (1973); doi:10.1103/PhysRevD.7.2333.
- **[Dym92]** I. Dymnikova, "Vacuum nonsingular black hole", *Gen. Relativ. Gravit.* 24, 235 (1992).
- **[FMM89]** V. P. Frolov, M. A. Markov, V. F. Mukhanov, "Through a black hole into a new universe?", *Phys. Lett. B* 216, 272 (1989); doi:10.1016/0370-2693(89)91114-3.
- **[FMM90]** V. P. Frolov, M. A. Markov, V. F. Mukhanov, "Black holes as possible sources of closed and semiclosed worlds", *Phys. Rev. D* 41, 383 (1990); doi:10.1103/PhysRevD.41.383.
- **[Haw75]** S. W. Hawking, "Particle creation by black holes", *Commun. Math. Phys.* 43, 199–220 (1975).
- **[Jac95]** T. Jacobson, "Thermodynamics of spacetime: The Einstein equation of state", *Phys. Rev. Lett.* 75, 1260 (1995); doi:10.1103/PhysRevLett.75.1260; arXiv:gr-qc/9504004.
- **[Mal98]** J. Maldacena, "The large N limit of superconformal field theories and supergravity", *Adv. Theor. Math. Phys.* 2, 231 (1998); arXiv:hep-th/9711200.
- **[Pat72]** R. K. Pathria, "The Universe as a Black Hole", *Nature* 240, 298–299 (1972); doi:10.1038/240298a0.
- **[Pop10]** N. J. Popławski, "Cosmology with torsion: An alternative to cosmic inflation", *Phys. Lett. B* 694, 181 (2010); arXiv:1007.0587; Erratum: *Phys. Lett. B* 701, 672 (2011), doi:10.1016/j.physletb.2011.05.047.
- **[Sus95]** L. Susskind, "The world as a hologram", *J. Math. Phys.* 36, 6377 (1995); arXiv:hep-th/9409089.
- **[tH93]** G. 't Hooft, "Dimensional reduction in quantum gravity", arXiv:gr-qc/9310026 (1993).
- **[Ver11]** E. Verlinde, "On the origin of gravity and the laws of Newton", *JHEP* 2011(04), 029 (2011); doi:10.1007/JHEP04(2011)029; arXiv:1001.0785.
- **[Vol03]** G. E. Volovik, *The Universe in a Helium Droplet*, Oxford University Press (2003).

$$\boxed{\;\text{Paralellik doğrulama değildir. Kesişim kaydı "yapısal benzerlik" düzeyinde tutulur.}\;}$$

```latex
\boxed{\;\text{Paralellik doğrulama değildir. Kesişim kaydı "yapısal benzerlik" düzeyinde tutulur.}\;}
```

Kara delik kozmolojisi ailesi için kapsam kuralı şudur: bu çalışmalar ilgili çalışma bağlamıdır, kanıt değildir; özgün ontoloji için türetim ve kör tahmin borcu ayrıca sürer. Bu literatür ailesi kendi içinde de rakip modellere bölünmüştür (torsiyonlu sıçrama, de Sitter çekirdek, şok dalgası, sahte vakum); toplu bir destek gibi sunulamaz.




# BÖLÜM 1 — TEMEL SEZGİ VE POSTÜLATLAR

## 1.1 Çerçeve nereden çıktı

Evertophy'nin kavramsal başlangıcı 20 Temmuz 2025'e uzanır. İlk soru fizikten değil, **mimariden ve sistem düşüncesinden** geldi: *bir sistemin farklı ölçeklerinde aynı yapı neden farklı görünür?*

Bu sorudan üç ilk sezgi doğdu ve kayda geçti:

- Kara deliğin merkezi bir tekillik değil, **sonlu ve tek bir form hâlinde bütünleşmiş bir yapı** olabilir.
- Aynı özün farklı ölçeklerde farklı görünmesi, bir **rejim hiyerarşisi** gerektirir.
- Karanlık madde ile karanlık enerji **aynı şeyin iki görünümü** olabilir.

Bu köken çerçevenin karakterini belirler: Evertophy bir denklemden değil, bir **yapısal tutarlılık arayışından** doğdu.

## 1.2 Postüla-0 — Çekim Kuvveti (Force of Attraction)

$$\boxed{\;\text{Çekim Kuvveti (Force of Attraction), Evertophy'nin en temel ontolojik postülasıdır.}\;}$$

```latex
\boxed{\;\text{Çekim Kuvveti (Force of Attraction), Evertophy'nin en temel ontolojik postülasıdır.}\;}
```

Bilinen dört kuvvet — kütleçekim, güçlü kuvvet, zayıf kuvvet ve elektromanyetizma — Çekim Kuvveti'nin **ölçeğe, kütle miktarına ve faza göre farklı izdüşümleridir**:

$$\boxed{\;\{\text{Kütleçekim},\ \text{Güçlü},\ \text{Zayıf},\ \text{Elektromanyetizma}\} \;=\; \Pi_{\text{ölçek, kütle, faz}}\big[\,\text{Çekim Kuvveti}\,\big]\;}$$

```latex
\boxed{\;\{\text{Kütleçekim},\ \text{Güçlü},\ \text{Zayıf},\ \text{Elektromanyetizma}\} \;=\; \Pi_{\text{ölçek, kütle, faz}}\big[\,\text{Çekim Kuvveti}\,\big]\;}
```

| Sembol | Anlamı |
|---|---|
| $\Pi_{\text{ölçek, kütle, faz}}$ | İzdüşüm işlemi: Çekim Kuvveti'nin belirli bir ölçekte, kütle miktarında ve fazda aldığı biçim; **biçimsel tanımı açıktır (EK K.1)**. Kutu bir postüla ifadesidir, matematiksel bir birleştirme denklemi değildir: dört etkileşim farklı türde matematiksel nesnelerdir ve $\Pi$'nin çıktı türü henüz tanımlanmamıştır |
| Çekim Kuvveti | Temel ontolojik postüla; fazdan bağımsız kısıt koheransı |

**Çekim Kuvveti yalnız bir "çekme" olgusu değildir.** Ontolojik düzeyde Çekim Kuvveti, c₀, Cₘ ve c⁺ fazlarının tümünde izin verilen yapılar için zorunlu olan **fazdan bağımsız kısıt koheransıdır**: üç fazın birbiriyle tutarlı kalmasını sağlayan temel bağdır. Kısıt koheransı metrik gerektirmez; bu yüzden metriğin bulunmadığı c₀ ve c⁺'ta da geçerlidir. Cₘ'de bu ilke izdüşümleri aracılığıyla görünür: kütleçekim onun **metrik izdüşümüdür** ve genel görelilik o izdüşümün etkin dilidir.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Dört kuvveti tek bir temel ilkenin farklı görünümleri olarak konumlandırır |
| **Neden yapıyor?** | Dört kuvvetin ortak kökeni modern fiziğin açık sorularından biridir; Evertophy bu kökeni bir ontolojik postülaya bağlar |
| **Nasıl yapıyor?** | Çekim Kuvveti'ni fazdan bağımsız kısıt koheransı olarak tanımlar; her kuvveti ölçek, kütle ve faza bağlı bir izdüşüm ($\Pi$) olarak okur |
| **Ne sonuç bekleniyor?** | İzdüşüm işleminin biçimsel tanımı kurulduğunda dört kuvvetin ölçülmüş özelliklerinin tek bir kaynaktan okunabilmesi |
| **Ne sonuç elde ediliyor?** | Postüla ontolojik düzeyde kuruludur; $\Pi$'nin biçimsel tanımı ve kuvvetlerin ayrıntılı izdüşüm anlatımı açıktır |

### Kavram kilidi

$$\boxed{\;\text{Çekim Kuvveti (Force of Attraction)} \;\neq\; \text{Kütleçekim (Gravitation)}\;}$$

```latex
\boxed{\;\text{Çekim Kuvveti (Force of Attraction)} \;\neq\; \text{Kütleçekim (Gravitation)}\;}
```

"Çekim Kuvveti" kanonik addır; ontolojik doğası klasik bir kuvvet alanı değil, fazdan bağımsız kısıt koheransıdır. Çekim Kuvveti hiçbir bağlamda "kütleçekim" ya da "gravitational force" olarak yazılmaz. Erken metinlerdeki "kütle çekimi temel aksiyomdur" ifadesi bu tanımla değiştirilmiştir: temel postüla Çekim Kuvveti'dir; kütleçekim onun izdüşümlerinden biridir.

### Beş ayrı nesne — karıştırılmamalı

$$\boxed{\;\text{Çekim Kuvveti}_{\rm ontoloji} \;\neq\; \text{Kütleçekim}_{C_m} \;\neq\; X \;\neq\; g_{\mu\nu} \;\neq\; G_{\rm eff}\;}$$

```latex
\boxed{\;\text{Çekim Kuvveti}_{\rm ontoloji} \;\neq\; \text{Kütleçekim}_{C_m} \;\neq\; X \;\neq\; g_{\mu\nu} \;\neq\; G_{\rm eff}\;}
```

| Nesne | Nedir |
|---|---|
| **Çekim Kuvveti (ontoloji)** | Temel postüla; fazdan bağımsız kısıt koheransı |
| **Kütleçekim (Cₘ)** | Çekim Kuvveti'nin Cₘ'deki metrik izdüşümü; genel göreliliğin konusu |
| **$X(x)$** | Dinamik üst çözücü; faz rejimini ve kabul edilebilir durumları çözer |
| **$g_{\mu\nu}$** | Cₘ'ye ait geometrik nesne (metrik) |
| **$G_{\rm eff}$** | Cₘ'de ölçülen etkin kütleçekim bağlaşımı; model düzeyi |

Bu beşi aynı şey değildir ve birbirinin yerine kullanılamaz. Özellikle **$X$ Çekim Kuvveti değildir**; $X$, fiziksel yapının hangi rejimde çözüleceğini belirleyen üst nesnedir.

### Üç fazın bir aradalığı

c₀, Cₘ ve c⁺'ın $U_x$'te tek bir yapı oluşturması rastlantı değildir: üç faz, Çekim Kuvveti'nin kısıt koheransı altında **bir denge** içinde bir arada durur. Faz kapılarının çift yönlü olması bu dengenin ifadesidir: Cₘ yapısı c⁺'a çözünür, c⁺ kaynaklı etkiler Cₘ'de okunur. Dengenin biçimsel denklemi açıktır. Denge, fazların **bir arada durmasını** açıklar; **neden tam üç** faz olduğunu açıklayabilmesi için başka bir faz sayısına izin vermediğini göstermesi gerekir. Faz sayısı açık bir sorudur (Bölüm 24).

### İzdüşümlerin bugünkü durumu

| İzdüşüm | Durum |
|---|---|
| Kütleçekim | Cₘ'deki metrik izdüşüm (Bölüm 8) |
| Elektromanyetizma | Taslak okuma: yük, $c$ faz sınırıyla ilişkili kalıcı bir imzadır. İtmenin ve yükün izdüşüm biçimi — **Daha Sonra Ele Alınacak** |
| Güçlü kuvvet | Tarihsel taslak okuma (eski "kristal faz" adlandırmasıyla) — **Daha Sonra Ele Alınacak** |
| Zayıf kuvvet | Taslak okuma: kararsız yapıdan kararlı yapıya dönüşüm — **Daha Sonra Ele Alınacak** |

Ölçümler dört kuvvetin yalnız çekmediğini gösterir: elektromanyetizmada aynı yükler birbirini iter; zayıf kuvvet parçacıkların tür değiştirmesiyle ilgilidir; elektromanyetik ve güçlü kuvvette belirleyici olan kütle değil, yüktür. Çekim Kuvveti ontolojik olarak bir koherans ilkesi olduğundan, Cₘ'deki izdüşümlerinin çekme, itme ya da dönüşüm biçiminde görünmesi kavramsal olarak mümkündür; ayrıntılı anlatımı ileride ele alınacaktır. Kuvvetlerin şiddetinin enerji ölçeğiyle değiştiği ve elektromanyetik ile zayıf kuvvetin yüksek enerjide birleştiği ölçülmüştür. Bu tablo "ölçeğe göre izdüşüm" fikriyle uyumludur; ama bir kanıt değildir.

## 1.3 Dört postülat

### P1 — Faz çokluğu

Gerçeklik tek bir homojen ortam değildir. En az üç ayırt edilebilir faz rejimi vardır ve bunlar arasında ilişki ve geçiş mümkündür.

**Açıklama.** Bu, "her yerde aynı fizik geçerlidir" varsayımını reddetmez; geçerli yasaların **aynı yasaların farklı rejimlerdeki görünümleri** olduğunu söyler.

### P2 — Yasa, ilişkiden doğar

Fiziksel yasalar fazların iç özellikleri değil, fazlar arası ilişki ve geçiş yapısının ifadesidir.

**Örnek.** Işık hızının bir üst sınır olması Evertophy'de keyfî bir kural değildir: Cₘ fazının **tutarlılık kısıtıdır**; bilgi işleme, kayıt ve çözünürlük sınırını koyar.

### P3 — Tek çözücü

Faz rejimini belirleyen tek bir üst nesne vardır: $X(x)$. Üç faz için üç ayrı düzenleyici varsaymak mümkün olurdu; çerçeve bunu **reddeder**.

### P4 — Aralık (Range) formalizmi

$$\boxed{\;\text{Fiziksel sayısal sözdizimi ARALIK DEĞERLİDİR: } P \in [P^-,\, P^+]\;}$$

```latex
\boxed{\;\text{Fiziksel sayısal sözdizimi ARALIK DEĞERLİDİR: } P \in [P^-,\, P^+]\;}
```

Ve kritik incelik — bu bir yasak değildir:

$$\boxed{\;[P,\,P] \text{ TAMAMEN GEÇERLİ bir statik deterministik fiziksel aralıktır.}\;}$$

```latex
\boxed{\;[P,\,P] \text{ TAMAMEN GEÇERLİ bir statik deterministik fiziksel aralıktır.}\;}
```

$$\boxed{\;\text{Aralık-değerli olmak} \;\nRightarrow\; \text{zamanla değişken olmak.}\;}$$

```latex
\boxed{\;\text{Aralık-değerli olmak} \;\nRightarrow\; \text{zamanla değişken olmak.}\;}
```

| Sembol | Anlamı |
|---|---|
| $P$ | Herhangi bir fiziksel nicelik |
| $P^-$, $P^+$ | Niceliğin alt ve üst sınırı |
| $[P,P]$ | Sıfır genişlikli aralık: kesin, sabit bir değer |
| $\nRightarrow$ | "Gerektirmez" |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Fiziksel niceliklerin nasıl yazılacağını belirler: aralık olarak |
| **Neden yapıyor?** | Ölçümler ve model parametreleri gerçekte bant hâlinde gelir; tek bir nokta değeri belirsizliği gizler |
| **Nasıl yapıyor?** | Her niceliği $[P^-,P^+]$ biçiminde taşır; kesin bir sabit ise sıfır genişlikli $[P,P]$ olarak yazılır |
| **Ne sonuç bekleniyor?** | Öngörü ve gözlem bantlarının dürüstçe karşılaştırılabilmesi (Bölüm 6) |
| **Ne sonuç elde ediliyor?** | Kural kuruludur; sıfır genişlikli bir aralık için özel bir eşik mekanizması ya da yapısal gerekçe aranmaz. P4 bir sözdizimi kuralıdır, "her şey değişkendir" demez |

## 1.4 İki çekirdek fikir

### Fikir 1 — Aynı dil, farklı lisans

Dört büyük alan aynı gerçekliği tarif eder ama farklı matematiksel lisanslar kullanır. Ortak gramerleri faz yapısının dilidir.

### Fikir 2 — Ölçüm Cₘ'ye özgüdür

Ölçüm ayrı bir dördüncü ontolojik faz değildir; **doğrudan fiziksel ölçümün yapılabildiği alan Cₘ'dir**. "Gözlemci" de ayrı bir ontolojik sınıf değil, Cₘ içinde fiziksel kayıt ve okuma (readout) üreten sistemlerin rolüdür.

Sonuç olarak, c₀ ve c⁺ hakkında deneysel olarak söylenen her şey **Cₘ'deki bir okuma üzerinden** sınanmak zorundadır.

## 1.5 Varlık sınıfları

| Sınıf | Nedir | Örnek |
|---|---|---|
| **Ontolojik varlık** | Gerçekliğin kendisine ait yapı | c₀, Cₘ, c⁺, $X$, Çekim Kuvveti |
| **Global düğüm** | Faz olmayan global ontoloji katmanı | $U_0$, $U_x$, $U_+$ — faz değildir |
| **Biçimsel nesne** | Matematiksel temsil | $g_{\mu\nu}$, damga monoidi, aralık |
| **Okuma (readout)** | Cₘ'de fiilen ölçülen | $\alpha$, $G$, $H_0$, kütle |

Bir okuma katmanı niceliğini ontolojik varlık sanmak, çerçevenin en yaygın hatasıdır.

## 1.6 Tanım hijyeni — karıştırılmaması gereken semboller

| Sembol | Nedir | Karıştırılmamalı |
|---|---|---|
| $U_0$ | Mutlak kaynak / ön katman | $u_0$, $u(0)$ ile — bunlar tarihsel süreç koordinatlarıdır |
| $X(x)$ | Dinamik üst çözücü | $X(u)$ ile — tarihsel lojistik çekirdek |
| $C_m$ | Faz adı | $c_m$ ile — çizelge bileşeni |
| $x$ | Genel koşul değişkeni | Belirli bir koordinat değil; **joker** |
| $c$ | Işık hızı / Cₘ tutarlılık kısıtı | $c_0$, $c^+$ faz adlarıyla |

Bu ayrımlar bürokratik değildir: aynı harfin iki anlamı biçimsel çalışmada gerçek hatalara yol açmıştır.

## 1.7 Ek notasyon güvenliği

İki notasyon ayrımı özellikle korunur:

| Gösterim | Anlamı |
|---|---|
| $C_m$ | **Faz adı**: madde / ölçüm / emergent zaman fazı |
| $c_m$ | Bir çizelge, katsayı ya da alt bileşen için kullanılırsa yalnız yerel semboldür; faz adı değildir |
| $X(x)$ | Güncel dinamik üst çözücü |
| $X(u)$ | Tarihsel / işlemsel skaler çekirdek; güncel $X(x)$ ile özdeş değildir |
| $X_A, X_z, X_t$ | Kullanılırsa yalnız **alan ya da okuma izdüşümü** ya da tarihsel adlandırmadır; üç ayrı temel $X$ değildir |

Bu belge temel ontolojide **tek bir $X$** kabul eder. Alan etiketleri yalnız izdüşüm gösterimi olarak kullanılabilir:

$$X_A \equiv \Pi_A[X],\qquad X_z\equiv\Pi_z[X],\qquad X_t\equiv\Pi_t[X]$$

```latex
X_A \equiv \Pi_A[X],\qquad X_z\equiv\Pi_z[X],\qquad X_t\equiv\Pi_t[X]
```

| Sembol | Anlamı |
|---|---|
| $\Pi_A$, $\Pi_z$, $\Pi_t$ | $X$'in atomik/nükleer, kırmızıya kayma ve zaman alanlarına izdüşümleri |
| $X_A$, $X_z$, $X_t$ | Bu izdüşümlerin adları; ayrı ontolojik düzenleyiciler değildir |

Bu gösterimler ayrı ontolojik düzenleyiciler oluşturmaz ve emekliye ayrılmış eski kantil / korelasyon hattını yeniden kanona taşımaz.

Uç değer karışıklığını önlemek için güvenli faz rejimi gösterimi şudur:

$$\boxed{\;X_{\rm state}\in I_0,\qquad X_{\rm state}\in I_m,\qquad X_{\rm state}\in I_+\;}$$

```latex
\boxed{\;X_{\rm state}\in I_0,\qquad X_{\rm state}\in I_m,\qquad X_{\rm state}\in I_+\;}
```

| Sembol | Anlamı |
|---|---|
| $X_{\rm state}$ | $X$'in çözülmüş durum yüzü |
| $I_0$, $I_m$, $I_+$ | İlgili faz için kabul edilebilir rejim / durum sınıfları; zorunlu olarak sayısal aralık değildir |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Tek $X$'in alanlara izdüşümünü ve faz rejimlerine üyeliğini güvenli biçimde yazar |
| **Neden yapıyor?** | Eski metinlerdeki "$X\to0$ / $X\to1$" skaler uç değer dili ve üç ayrı $X$ izlenimi, $X$'in skaler olmayan doğasıyla çelişiyordu |
| **Nasıl yapıyor?** | Alan etiketlerini izdüşüm ($\Pi$) olarak, faz rejimlerini durum sınıfı ($I$) olarak tanımlar |
| **Ne sonuç bekleniyor?** | $X$ üzerinde yapılan her skaler işlemin açıkça tanımlı bir okuma üzerinden yapılması |
| **Ne sonuç elde ediliyor?** | Gösterim kuruludur; eski skaler uç değer dili güncel $X(x)$ ontolojisine taşınmaz |




# BÖLÜM 2 — $U_0$: MUTLAK KAYNAK / ÖN KATMAN

## 2.1 Güncel tanım

$$\boxed{\;U_0 \;\rightsquigarrow\; \{c_0,\; C_m,\; c^+\}_{\text{aynı kuruluşta birlikte}}\;}$$

```latex
\boxed{\;U_0 \;\rightsquigarrow\; \{c_0,\; C_m,\; c^+\}_{\text{aynı kuruluşta birlikte}}\;}
```

| Sembol | Anlamı |
|---|---|
| $U_0$ | Mutlak Çekirdek: ön katman (pre-layer), mutlak üretici kaynak |
| $\rightsquigarrow$ | "İzin verir / doğurur": nedensel bir zincirin ilk halkası değil, varlık koşulunun kaynağı |
| $\{c_0, C_m, c^+\}$ | Üç faz |
| "aynı kuruluşta birlikte" | Üç fazın yapısal birlikte doğuşu (co-genesis); ortak bir dış saat anlamına gelmez |

**$U_0$**, Big Bang'de üç fazı **aynı kuruluşta birlikte** oluşturan **ön katman**, yani mutlak üretici kaynaktır. Yazarın hükmüyle: $U_0$'da Dinamik Evren'i oluşturan bütün yapılar — c₀, Cₘ ve c⁺ — Planck ölçeğinde metrik boşluksuz duruma yakınsayan derecede bitişik, **tek bir yapı formunda** bulunur. Bu bir sayısal kütle ya da boyut ataması değildir (2.10); üç fazın doğmadan önceki birliğini anlatır.

**Birlikte doğuş (co-genesis):** c₀, Cₘ ve c⁺, $U_0 \to U_x$ kuruluşunda birlikte ortaya çıkar. Yazarın "eş zamanlı" ifadesi bu yapısal birlikte doğuşu anlatır. Fazların dışında ortak bir fiziksel saat yoktur, çünkü fiziksel zaman yalnız Cₘ'de tanımlıdır. $U_0$ önce birini, sonra ötekini üretmez; üçü birden doğar. Bu sıralı bir üretim değil, **yapısal bir doğuştur**.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Üç fazın kaynağını ve doğuş biçimini tanımlar |
| **Neden yapıyor?** | Fazların birbirinden türetildiği (örneğin c⁺'ın Cₘ'den doğduğu) okumalar, ontolojinin temelini bozar |
| **Nasıl yapıyor?** | Üç fazı tek bir kaynaktan, aynı kuruluşta birlikte doğan yapılar olarak yazar; oku nedensel değil, varlık koşulu olarak okur |
| **Ne sonuç bekleniyor?** | Hiçbir fazın ötekinin türevi olarak modellenmemesi; zamanın Big Bang'in dışında bir saat sanılmaması |
| **Ne sonuç elde ediliyor?** | Birlikte doğuş kanondur; $U_0$'ın tam karakterizasyonu yazara ayrılmış rezerve alandır |

## 2.2 $U_0$ ne değildir

$$\boxed{\;U_0 \notin \mathrm{Obj}(\mathcal{C}_{\rm faz})\;}$$

```latex
\boxed{\;U_0 \notin \mathrm{Obj}(\mathcal{C}_{\rm faz})\;}
```

| Sembol | Anlamı |
|---|---|
| $\mathcal{C}_{\rm faz}$ | Faz kategorisi: nesneleri c₀, Cₘ, c⁺ olan, okları faz kapıları olan yapı |
| $\mathrm{Obj}(\cdot)$ | Bir kategorinin nesneleri |
| $\notin$ | "Üyesi değildir" |

$U_0$:

- **faz değildir**; dördüncü bir sektör değildir,
- **kapı uç noktası değildir**; ona giden ya da ondan gelen **sıradan bir faz kapısı** yoktur (global doğuş ve limit ilişkisi, 2.8, bundan ayrıdır),
- **c₀'ın bir alt türü değildir**,
- **topolojik bir delik değildir**,
- **geçiş lifi (fiber) değildir**,
- **bilinç, tanrı, zihin** ya da metafizik bir varlık değildir,
- **gözlemlenebilir bir nesne değildir**.

**Neden bu sınırlar?** $U_0$, çerçevede epistemik olarak en zayıf zeminde duran öğedir. Onu dinamik bir sektöre ya da geometrik bir yapıya dönüştürmek, teorinin en kırılgan noktasını merkezine taşımak olurdu.

## 2.3 Tarihsel okumalar

Çerçevenin gelişimi sırasında $U_0$ için farklı okumalar denenmiştir. Bunlar **tarihsel soyağacıdır**, güncel tanım değildir:

| Tarihsel okuma | Neden güncel değil |
|---|---|
| Sayısal kütle değeri taşıyan fiziksel evren çekirdeği | $U_0$'ı bir Cₘ niceliğine indirger |
| c₀'ın evren ölçekli karşılığı ya da eşiği | $U_0$'ı bir faza indirger |
| Adresleme / kapasite üst sınırı | Metafordur; ontolojik tanım değildir |
| Kozmogonik çözülme eşiği | Bir eşiktir, kaynak değildir |
| $u(0) \equiv U_0$ | $u$ tarihsel bir süreç koordinatıdır; $U_0$ değildir |

Bu okumalar arşivde korunur, ama hiçbiri güncel çekirdeğe girmez.

$$\boxed{\;u(0) \;\neq\; U_0\;}$$

```latex
\boxed{\;u(0) \;\neq\; U_0\;}
```

## 2.4 $U_0$ ve Big Bang

Güncel çekirdek iki ayrı ama uyumlu katmanı birlikte korur:

1. **Doğuş kuralı:** $U_0$, Big Bang başlangıcında üç fazı aynı kuruluşta birlikte oluşturur.
2. **Çift-limit ilkesi:** Devremsel işleyişin temelini oluşturacak iki sınır Çekirdek'te korunur; bu sınırların tam mekanizması V24'e ayrılmıştır.

### Birlikte doğuş — ontolojik köken

$$\boxed{\;U_0 \rightsquigarrow \{c_0,\;C_m,\;c^+\}_{\text{aynı kuruluşta birlikte}}\;}$$

```latex
\boxed{\;U_0 \rightsquigarrow \{c_0,\;C_m,\;c^+\}_{\text{aynı kuruluşta birlikte}}\;}
```

Bu ifade sıralı bir faz geçişi değildir. $U_0$ faz kategorisinin nesnesi olmadığından (2.2), $c_0\to U_0$ ya da $c^+\to U_0$ biçiminde sıradan bir faz geçişi oku **kurulmaz**.

**Yazar hükmü — fazlar türetilmez.** c₀ ve c⁺, Cₘ ile birlikte Big Bang'de oluşur; Cₘ'den türetilmez. Modellenen şey Cₘ → c⁺ geçişi ve zaman mühürlemesidir; bunun için vakum, BEC ve atom altı yapılar ele alınır.

### Big Bang ne değildir

| Değildir | Neden |
|---|---|
| **Klasik bir patlama** | Bir merkez ve dışarı yayılım resmi değildir |
| **Hiçlikten yaratım** | $U_0$ vardır |
| **Önceden var olan bir uzayda hareket** | Uzay ve zaman Cₘ ile doğar |
| **Zamanın ilksel madde gibi başlaması** | Zaman bir madde değildir; Cₘ'de üretilir |

$$\boxed{\;\text{ZAMAN, Big Bang'in ÜSTÜNDE BİR DIŞ SAAT DEĞİLDİR.}\;}$$

```latex
\boxed{\;\text{ZAMAN, Big Bang'in ÜSTÜNDE BİR DIŞ SAAT DEĞİLDİR.}\;}
```

"Big Bang'den önce ne vardı?" sorusu, Cₘ fiziksel zamanı açısından kategorik olarak sorunludur; çünkü "önce" sözcüğü zaten fiziksel bir zaman varsayar.

### Çift-limit ilkesi — Çekirdek / V24 devre tohumu

Çerçevede iki sınır **Çekirdek tohumu** olarak korunur:

- **c₀ doygunluk / çöküş limiti,**
- **seyrelme / kapalı devre limiti.**

Bu iki limit, eski anlatılardaki mekanik okların tamamını kendiliğinden kanona taşımaz. Güvenli güncel ifade şudur:

$$\boxed{\;\text{limit koşulu}\;\Longrightarrow\;\text{yeni bir }U_0\text{-aracılı doğuş koşuluna bağlanabilecek devre tohumu}\;}$$

```latex
\boxed{\;\text{limit koşulu}\;\Longrightarrow\;\text{yeni bir }U_0\text{-aracılı doğuş koşuluna bağlanabilecek devre tohumu}\;}
```

Buradaki $\Longrightarrow$ bir **faz kapısı** değildir; meta seviyedeki devre koşulunu gösterir. $U_0$ faz grafına sokulmaz ve "yeniden oluşan fiziksel nesne" olarak tanımlanmaz. Seyrelme kolu da c⁺'ın içinde akan bir zaman varsaymaz; bu limit yalnız Cₘ'den yapılan okuma açısından asimptotik bir devre koşulu olarak anlaşılır.

$$\boxed{\;\text{birlikte doğuş}\;\neq\;\text{çift-limit devre mekanizması}\;}$$

```latex
\boxed{\;\text{birlikte doğuş}\;\neq\;\text{çift-limit devre mekanizması}\;}
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Evrenin iki uç limitini (çöküş ve seyrelme) devremsel işleyişin tohumu olarak korur |
| **Neden yapıyor?** | Evertophy'nin üç fazlı mimarisindeki iki uç yönelim, global düzeyde doğal bir devre imkânı taşır |
| **Nasıl yapıyor?** | Limitleri faz kapısı olarak değil, meta seviyede bir devre koşulu olarak yazar; doğuşla mekanizmayı ayırır |
| **Ne sonuç bekleniyor?** | Devre denklemlerinin ileride V24 katmanında kurulabilmesi |
| **Ne sonuç elde ediliyor?** | Tohum Çekirdek'te korunur; devre denklemleri, devre indeksi ve $U_0$ ile limit koşulunun tam bağı bu sürümde tanımlanmaz |

## 2.5 İki ontolojik seviye — faz seviyesi ve global evren seviyesi

Buraya kadar anlatılanların çoğu **tek bir seviyeye** aitti: üç faz ve onları doğuran ön katman. Ama çerçevenin tam resmi iki seviyelidir.

$$\boxed{\;\text{Evertophy İKİ ONTOLOJİK SEVİYEDEN oluşur: FAZ SEVİYESİ ve GLOBAL EVREN SEVİYESİ.}\;}$$

```latex
\boxed{\;\text{Evertophy İKİ ONTOLOJİK SEVİYEDEN oluşur: FAZ SEVİYESİ ve GLOBAL EVREN SEVİYESİ.}\;}
```

| Seviye | Nesneler | İlişki türü |
|---|---|---|
| **Faz seviyesi** | c₀, Cₘ, c⁺ | Tam çift yönlü üçgen; kapılar ve damgalar |
| **Global evren seviyesi** | $U_0$, $U_x$, $U_+$ | Global devre; doğuş ve limit ilişkileri |

$$\boxed{\;U_0,\; U_x,\; U_+ \;\notin\; \{c_0,\, C_m,\, c^+\}\;}$$

```latex
\boxed{\;U_0,\; U_x,\; U_+ \;\notin\; \{c_0,\, C_m,\, c^+\}\;}
```

**Neden bu ayrım gerekli?** Çift-limit fikri (2.4) tek seviyeye sığdırılmaya çalışıldığında sürekli gerilim üretir: "c₀ doygunluğu → $U_0$" gibi bir ok, faz grafının **dışındaki** bir varlığı faz grafının **içine** çeker. İki seviye ayrıldığında gerilim kendiliğinden kalkar: fazlar içeride kalır, global kutuplar dışarıda durur.

### Buz–su–buhar benzetmesi

Bir kapta buz, su ve buhar birlikte bulunabilir. Bunlar **rejimlerdir**: faz seviyesi. Kabın tamamı ise ayrı bir nesnedir: global seviye. Tüm sistem aşırı bir koşula giderse, bu tek bir rejimin değişmesi değil, **sistemin kendisinin** bir uç duruma ulaşmasıdır.

$$\boxed{\;U_0 \text{ ve } U_+ \text{ fazların RAKİBİ değildir — global devrenin iki UÇ KOŞULUDUR.}\;}$$

```latex
\boxed{\;U_0 \text{ ve } U_+ \text{ fazların RAKİBİ değildir — global devrenin iki UÇ KOŞULUDUR.}\;}
```

### Yerel faz limiti ≠ global evren limiti

Bir bölgenin c₀ rejimine yaklaşması (bir kara deliğin oluşması) **yerel** bir olaydır ve evrende her gün olur. Global doygunluk ise **evrenin bütününe** ait bir koşuldur. İkisi aynı dille yazılsa da aynı şey değildir.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Ontolojiyi iki seviyeye ayırır: fazlar ve global kutuplar |
| **Neden yapıyor?** | Global kutupları faz grafının içine çekmek, "c₀ doygunluğu = $U_0$" gibi yanlış özdeşlikler üretiyordu |
| **Nasıl yapıyor?** | Global düğümleri faz kümesinin dışında tanımlar; fazlar arası ilişkiyi kapı, global ilişkiyi devre olarak adlandırır |
| **Ne sonuç bekleniyor?** | Yerel olaylarla (kara delik oluşumu) global koşulların (evrenin uç durumları) karışmaması |
| **Ne sonuç elde ediliyor?** | İki seviye kanondur ve biçimsel olarak da tiplenmiştir (5.3 denklem seti) |

## 2.6 $U_+$ — Mutlak Çözünme / Mutlak Yırtılma

$$\boxed{\;U_+ = \text{evrenin tüm faz-yapısal çözünürlüğünün seyrelip global çözünürlük sınırını aştığı uç durum}\;}$$

```latex
\boxed{\;U_+ = \text{evrenin tüm faz-yapısal çözünürlüğünün seyrelip global çözünürlük sınırını aştığı uç durum}\;}
```

$U_0$ global **doygunluk** kutbuysa, $U_+$ global **çözünme** kutbudur.

**Yazar hükmü — ad eşdeğerliği.** "Mutlak Çözünme" ve "Mutlak Yırtılma" aynı uç durumu anlatır: birincisi durumun kendisini, ikincisi bütün $U_x$ yapısının bu duruma ulaşmasını vurgular. Bütün $U_x$'in $U_+$ sınırındaki kritik eşiği aşmasıyla gerçekleşen olayın adı **Big Yırtılma**'dır (2.8).

### $U_+$ ne değildir

| Değildir | Neden |
|---|---|
| **Faz değildir** | Faz grafının dışındadır |
| **Beşinci bir düğüm değildir** | Faz üçgenine eklenmez |
| **c⁺ değildir** | c⁺ bir fazdır ve $U_x$'in içindedir; $U_+$ dışarıdaki bir kutuptur |
| **$X$ değildir** | $X$ faz rejimini çözer; $U_+$ global bir limittir |
| **Gelecek değildir** | Global seviyede de Cₘ zamanı yoktur |
| **"Son durak / ölüm" değildir** | Her durumda yeni bir $U_x$ oluşur; kıyamet anlatısı biçiminde okunamaz |
| **Yalnız "çok fazla c⁺" değildir** | Nicel bir c⁺ bolluğu değil, global bir çözünürlük koşuludur |

**En yüksek karışma riski $U_+$ ile c⁺ arasındadır;** ikisi de çözünme tarafındadır. Ayrım tek cümlede şudur:

$$c^+ = \text{faz (içeride)} \qquad\qquad U_+ = \text{global kutup (dışarıda)}$$

```latex
c^+ = \text{faz (içeride)} \qquad\qquad U_+ = \text{global kutup (dışarıda)}
```

### Kutup eşik değildir

$U_0$ ve $U_+$ birer **eşik değildir**; eşik, uç fazın global kutupla temas ettiği **sınırda** bulunur. Tarihsel "$U_0$ = c₀'ın eşiği" okuması (2.3) bu yolla geri getirilmemelidir.

### $U_+$ için işlev cümlesi — açık

$U_0$'ın bir işlev cümlesi vardır: *üç fazı aynı kuruluşta birlikte doğurur.* $U_+$'ın karşılığı henüz yazılmamıştır. Aşağıdaki genelleştirilmiş biçim bir adaydır, **kanon değildir**:

$$U_\ast \;\rightsquigarrow\; \{c_0,\; C_m,\; c^+\}_{\text{aynı kuruluşta birlikte}}, \qquad \ast \in \{0,\, +\}$$

```latex
U_\ast \;\rightsquigarrow\; \{c_0,\; C_m,\; c^+\}_{\text{aynı kuruluşta birlikte}}, \qquad \ast \in \{0,\, +\}
```

| Sembol | Anlamı |
|---|---|
| $U_\ast$ | İki global kutuptan biri: $U_0$ ya da $U_+$ |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Global çözünme kutbunu tanımlar ve c⁺ fazından ayırır |
| **Neden yapıyor?** | İkisi de "çözünme" tarafında olduğu için en sık karıştırılan çift budur |
| **Nasıl yapıyor?** | $U_+$'ı bütünün uç durumu, c⁺'ı evrenin içindeki bir faz olarak tanımlar; iki adın aynı durumu anlattığını kaydeder |
| **Ne sonuç bekleniyor?** | $U_+$ için de $U_0$ gibi bir işlev cümlesinin kurulması |
| **Ne sonuç elde ediliyor?** | Tanım ve ad eşdeğerliği kuruludur; $U_+$'ın doğuş işlevi açıktır, genelleştirilmiş biçim adaydır |

## 2.7 $U_x$ — Dinamik Evren

$$\boxed{\;U_x = \text{üç fazın birlikte gerçekleştiği dinamik evrensel yapı}\;}$$

```latex
\boxed{\;U_x = \text{üç fazın birlikte gerçekleştiği dinamik evrensel yapı}\;}
```

$U_x$ yalnız bir çizim çerçevesi değildir; global seviyenin ortadaki nesnesidir. Zaman, uzay ve ölçüm bu bütünün içinde, Cₘ fazında yaşar.

### Notasyon hijyeni — üç benzer sembol

| Sembol | Nedir |
|---|---|
| $U_x$ | Dinamik Evren — global seviye nesnesi |
| $U(x)$ | Tarihsel ya da işlevsel kullanım; **yalnız bağlam açıkça $U_x$'i gösteriyorsa** onunla eşlenir |
| $X(x)$ | **Dinamik üst çözücü** — tamamen farklı bir nesne (Bölüm 4) |

$$\boxed{\;U_x \;\neq\; X(x) \qquad U_x \;\neq\; U_0 \qquad U_x \;\neq\; c_0,\, C_m,\, c^+\;}$$

```latex
\boxed{\;U_x \;\neq\; X(x) \qquad U_x \;\neq\; U_0 \qquad U_x \;\neq\; c_0,\, C_m,\, c^+\;}
```

$U(x)\equiv U_x$ yazımı otomatik değildir: güncel kanonik gösterim $U_x$'tir. $U_x$'in ontolojik tipi — "küme üyeliği" mi, "ontolojik kapsama" mı — **açık bir sorudur**.

### Denklem seti — Global seviye

$$U_0,\ U_x,\ U_+ \notin \{c_0,\ C_m,\ c^+\} \qquad \text{GlobalRel} \neq \text{Gate}$$

```latex
U_0,\ U_x,\ U_+ \notin \{c_0,\ C_m,\ c^+\} \qquad \text{GlobalRel} \neq \text{Gate}
```

| Sembol | Anlamı |
|---|---|
| $U_0$ | Mutlak Çekirdek — **sınırındaki** kritik eşik: **Big Bang** |
| $U_x$ | Dinamik Evren — **kutup değildir** |
| $U_+$ | Mutlak Çözünme / Mutlak Yırtılma — **sınırındaki** kritik eşik: **Big Yırtılma** |
| GlobalRel | Global düğümler arasındaki ilişki |
| Gate | Fazlar arasındaki kapı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Faz seviyesi ile global seviyeyi biçimsel olarak ayırır |
| **Neden yapıyor?** | Global düğümleri faz sanmak iki seviyeli mimariyi çökertir |
| **Nasıl yapıyor?** | Global düğümleri faz kümesinin dışında tanımlar; global ilişkiyi kapıdan farklı bir ilişki türü olarak yazar |
| **Ne sonuç bekleniyor?** | Hiçbir model ya da kodun global düğümleri faz gibi kullanmaması |
| **Ne sonuç elde ediliyor?** | Faz ≠ global düğüm ayrımı ve "$U_x$ kutup değildir" hükmü biçimsel olarak doğrulanmıştır; $U_x$'in yapısal tipi açıktır |

## 2.8 Global devre ve iki doğuş olayı

**Birlikte doğuş.** $U_0 \to U_x$ doğuşunda c₀, Cₘ ve c⁺ **aynı kuruluşta birlikte** oluşur. Fazların dışında işleyen ortak bir saat olmadığından bu, bir saatin "aynı anı" değil, aynı kuruluşta birlikte bulunmaktır. c⁺'ın $c$-ötesi niteliği sonradan kazanılmış bir özellik değil, fazın kuruluş özelliğidir. Üç faz, doğuştan itibaren Çekim Kuvveti'nin kısıt koheransı altında bir arada durur (1.2).

$$\boxed{\;U_0 \;\leftrightarrow\; U_x \;\leftrightarrow\; U_+\;}$$

```latex
\boxed{\;U_0 \;\leftrightarrow\; U_x \;\leftrightarrow\; U_+\;}
```

Uç faz rejim limiti aşıldığında:

$$\begin{cases} U_x,\ U_0 \text{ sınırındaki kritik eşiği aşar} & \Rightarrow\; \textbf{Big Bang} \\[4pt] U_x,\ U_+ \text{ sınırındaki kritik eşiği aşar} & \Rightarrow\; \textbf{Big Yırtılma} \end{cases} \qquad\Longrightarrow\qquad \text{yeni bir } U_x \text{ oluşur}$$

```latex
\begin{cases} U_x,\ U_0 \text{ sınırındaki kritik eşiği aşar} & \Rightarrow\; \textbf{Big Bang} \\[4pt] U_x,\ U_+ \text{ sınırındaki kritik eşiği aşar} & \Rightarrow\; \textbf{Big Yırtılma} \end{cases} \qquad\Longrightarrow\qquad \text{yeni bir } U_x \text{ oluşur}
```

### Beş hüküm

| # | Hüküm |
|---|---|
| **G-1** | Dinamik Evren mutlak çöküşle ya da mutlak çözünmeyle **son bulabilir — bulmayabilir de** |
| **G-2** | Çöküş ucu → $U_0$ sınırındaki kritik eşik → **Big Bang** |
| **G-3** | Seyrelme ucu → $U_+$ sınırındaki kritik eşik → **Big Yırtılma** |
| **G-4** | **Her iki durumda da** yeni bir $U_x$ oluşur |
| **G-5** | $U_0 \leftrightarrow U_+$ doğrudan ilişkisi olabilir, ama **temsili yoktur** |

### Sessizlik ilkesi

$$\boxed{\;\textbf{Temsili olmayan yerde Evertophy hüküm vermez.}\;}$$

```latex
\boxed{\;\textbf{Temsili olmayan yerde Evertophy hüküm vermez.}\;}
```

$U_0$ ile $U_+$ arasında doğrudan bir geçiş bulunabilir; ama bilinen anlamda bir temsili yoktur ve ötesi metafiziğe aittir. Evertophy bilim, gözlem ve deney çizgisinde kalır; burada **sessiz kalmayı tercih eder**. Bu, c⁺'ın kapalı devre olmasıyla aynı ilkedir (Bölüm 11): *önce akademik sınır, sonra gözlemsizlik.* Fark yalnız katmandır: orada faz seviyesinde, burada en dış katmanda.

### Dört yön ve anlamları

$$U_0 \Rightarrow U_x, \qquad U_x \Rightarrow U_0, \qquad U_x \Rightarrow U_+, \qquad U_+ \Rightarrow U_x$$

```latex
U_0 \Rightarrow U_x, \qquad U_x \Rightarrow U_0, \qquad U_x \Rightarrow U_+, \qquad U_+ \Rightarrow U_x
```

| Yön | Anlamı |
|---|---|
| $U_0 \Rightarrow U_x$ | **Doğuş** — üç fazın aynı kuruluşta birlikte oluşumu |
| $U_x \Rightarrow U_0$ | **Limit** — çöküş ucunun global kutba teması |
| $U_x \Rightarrow U_+$ | **Limit** — çözünme ucunun global kutba teması |
| $U_+ \Rightarrow U_x$ | **Yeniden oluşum sonucu** — kanonik; üretim mekanizması açık |

### Sonuç ile mekanizma ayrımı

G-4 iki ayrı önerme gibi okunabilir; ama bunlar **aynı iddia değildir**:

$$\boxed{\;U_+ \Rightarrow U_x' \qquad \textbf{KANONİK: global yeniden oluşum SONUCU}\;}$$

```latex
\boxed{\;U_+ \Rightarrow U_x' \qquad \textbf{KANONİK: global yeniden oluşum SONUCU}\;}
```

$$\boxed{\;U_+ \rightsquigarrow \{c_0, C_m, c^+\}_{\text{aynı kuruluşta birlikte}} \qquad \textbf{AÇIK: doğuş MEKANİZMASI}\;}$$

```latex
\boxed{\;U_+ \rightsquigarrow \{c_0, C_m, c^+\}_{\text{aynı kuruluşta birlikte}} \qquad \textbf{AÇIK: doğuş MEKANİZMASI}\;}
```

| Sembol | Anlamı |
|---|---|
| $U_x'$ | Yeni oluşan Dinamik Evren |

Yeni bir $U_x$'in oluşması **kanondur**; bunun $U_0$'daki doğuşla **aynı** ontolojik üretim işlemi üzerinden gerçekleştiği **kanon değildir**. İkinci önerme $U_+$'ın $U_0$ ile aynı doğuş işlemine sahip olduğunu söyler ve daha güçlüdür; $U_+$'ın kendi işlev cümlesi yazılana kadar (2.6) açık kalır.

### Dört zorunlu koruma

**(i) Oklar bütüne bağlanır, faza değil.**

$$U_0 \leftrightarrow U_x \;(\text{bütünle ilişki}) \qquad \text{değil} \qquad U_0 \leftrightarrow c_0 \;(\text{kapı})$$

```latex
U_0 \leftrightarrow U_x \;(\text{bütünle ilişki}) \qquad \text{değil} \qquad U_0 \leftrightarrow c_0 \;(\text{kapı})
```

Böylece "$U_0$ hiçbir kapının ucu değildir" kuralı korunur. Çekirdek görseldeki süslü parantezler bu yüzden çizilmiştir.

**(ii) Global çift yönlülük matematiksel tersinirlik değildir.** $\leftrightarrow$ sembolü burada bir ilişkinin iki ucunu gösterir; ters bir işlemin varlığını **iddia etmez**.

**(iii) Devre bir konveyör bandı değildir.** Soldan sağa okuma bir süreç izlenimi verir; oysa zaman $U_x$'in **içindedir**. Global devre bir akış değil, **limit koşulları** ilişkisidir.

$$\boxed{\;\text{Devre indeksi} \;\neq\; t\;}$$

```latex
\boxed{\;\text{Devre indeksi} \;\neq\; t\;}
```

$U_x$'ler arasında saat yoktur. Sıra, arşivdeki kayıt sırası gibi **mantıksal bir kaynak sırasıdır**.

**(iv) Devre zorunlu bir periyodik çevrim değildir.** G-1 gereği evren son bulmak **zorunda değildir**. "Devre" sözcüğü bir kapalılık imkânını anlatır, bir döngü yasasını değil. Bu ilişkiler faz üçgeninin topolojik hesabına da **karışmaz** (Bölüm 19).

### Simetri — ölçülü ifade

Çöküş kolu ile çözünme kolu **global limit kutbu düzeyinde yapısal bir simetri** taşır. Ama aşağıdaki eşleme **kurulmaz**:

$$U_0 : c_0 \;::\; U_+ : c^+ \qquad \text{(ontolojik izomorfizm YOKTUR)}$$

```latex
U_0 : c_0 \;::\; U_+ : c^+ \qquad \text{(ontolojik izomorfizm YOKTUR)}
```

Çünkü $U_0$ yalnız c₀'ı değil, **üç fazı birden** doğurur. Aynı nedenle $U_+$, c⁺'ın global eşleniği ya da dış kabuğu olarak tanımlanamaz.

### "Big Bang" sözcüğünün iki anlamı

| Anlam | İçerik |
|---|---|
| **İlksel doğuş** | Gözlediğimiz evrenin başlangıcı |
| **Devre koşulu** | Herhangi bir $U_x$'in çöküş ucunda eşiğin aşılmasıyla tetiklenen doğuş |

İlksel doğuşun bir önceki $U_x$'ten gelip gelmediği sorusu **sessizlik ilkesi** kapsamındadır.

**Yazar hükmü — yeniden tetiklenme.** $U_0$ rejiminin yeniden tetiklenmesi, çift yönlü ok ontolojisiyle çelişmez. Bu cümle bir devre mekanizması tanımı değildir: mekanizma açıktır ve $U_0$'ın karakterizasyonu rezerve kalır.

### "Big Yırtılma" eşsesli bir terimdir

Standart kozmolojide *Big Rip*, karanlık enerjinin evreni **sonlandırdığı** bir olaydır. Evertophy'de **Big Yırtılma bir son ve aynı zamanda yeni bir doğuştur** (G-4). Ortak sözcük, anlamları birleştirme yetkisi vermez.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Dinamik Evren'in iki uç koşulla ilişkisini ve yeniden oluşumu tanımlar |
| **Neden yapıyor?** | Big Bang'in ve evrenin olası sonunun ontolojide nerede durduğunu kesinleştirmek gerekir |
| **Nasıl yapıyor?** | İki eşiği (Big Bang, Big Yırtılma) global kutupların sınırına yerleştirir; sonucu kanon, mekanizmayı açık olarak ayırır; dört koruma koyar |
| **Ne sonuç bekleniyor?** | Devre mekanizmasının ileride kurulabilmesi; bu kurulana kadar metafizik spekülasyonun dışarıda kalması |
| **Ne sonuç elde ediliyor?** | Beş hüküm (G-1…G-5) ve sessizlik ilkesi kanondur; $U_+$'tan doğuş mekanizması açıktır |

## 2.9 Global seviyede geçerli olmayanlar

Faz seviyesi için konan kısıtlar global seviyede de geçerlidir; birkaçı özellikle belirtilmelidir:

- **Metrik global seviyede tanımlı değildir.** $g_{\mu\nu}$ yalnız Cₘ'ye aittir (Bölüm 9); $U_0$, $U_x$, $U_+$ için bir metrik ya da tetrad yazılmaz.
- **$X$'in alan izdüşümleri global nesnelere uygulanmaz.** $X$ faz rejimini çözer; global kutuplar onun tanım alanı değildir.
- **Hız ve zaman dili kullanılmaz.** Global ilişkiler için oran, hız ya da süre yazılmaz.
- **Global okların matematiksel tipi açıktır.** Bunların faz kapısı **olmadığı** bilinir; tam tipleri tanımlanmamıştır.

### Doğuş ≠ devre

$$\mathrm{Genesis} = U_0 \rightsquigarrow \{c_0,\, C_m,\, c^+\}_{\text{aynı kuruluşta birlikte}} \qquad\qquad \mathrm{CycleSeed} = \{\mathcal{L}_{\rm çöküş},\; \mathcal{L}_{\rm seyrelme}\}$$

```latex
\mathrm{Genesis} = U_0 \rightsquigarrow \{c_0,\, C_m,\, c^+\}_{\text{aynı kuruluşta birlikte}} \qquad\qquad \mathrm{CycleSeed} = \{\mathcal{L}_{\rm çöküş},\; \mathcal{L}_{\rm seyrelme}\}
```

| Sembol | Anlamı |
|---|---|
| Genesis | Doğuş: üç fazın $U_0$'dan birlikte oluşumu |
| CycleSeed | Devre tohumu: iki limitin kümesi |
| $\mathcal{L}_{\rm çöküş}$, $\mathcal{L}_{\rm seyrelme}$ | Çöküş ve seyrelme limitleri |
| $\dashrightarrow$ | Henüz kurulmamış bağ |

$$\boxed{\;\text{Birlikte doğuş} \;\neq\; \text{çift-limit devre mekanizması}\;}$$

```latex
\boxed{\;\text{Birlikte doğuş} \;\neq\; \text{çift-limit devre mekanizması}\;}
```

İkisi arasındaki tam bağ — $\mathrm{CycleSeed} \dashrightarrow \mathrm{Genesis}$ — **açık problemdir**.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Doğuş ile devre mekanizmasını iki ayrı nesne olarak yazar |
| **Neden yapıyor?** | "Limit aşılırsa doğuş olur" cümlesi, mekanizma kurulmadan doğuşun kendisiyle karıştırılabilirdi |
| **Nasıl yapıyor?** | Doğuşu bir işlem, devre tohumunu iki limitin kümesi olarak tanımlar; aralarındaki bağı açık bırakır |
| **Ne sonuç bekleniyor?** | Bağın ileride türetilebilmesi |
| **Ne sonuç elde ediliyor?** | Ayrım kuruludur; bağ açık problemdir |

## 2.10 Evren başlangıç kütlesi ve türetim zinciri kaydı

Arşivde evrensel ölçek tahminleri bir zincir hâlinde korunur. Bu kayıt sayıları ontolojik nicelik olarak değil, **tarihsel hesap ve ölçek benzetmesi** olarak sınıflandırır.

### Zincirin halkaları

1. **CMB ölçeği:** $t_{\rm CMB}\approx3.8\times10^5$ yıl (rekombinasyon) → $D_{\rm çekirdek}\approx3.8\times10^5$ ışık yılı. CMB'yi gördüğümüz an, Cₘ'nin ilk gözlemsel faz geçişi olarak okunur.
2. **Planck yoğunluğu izdüşümü:** $M\sim\rho_P\cdot V_{\rm çekirdek}\sim10^{161}$ kg mertebesi.
3. **Baryon / toplam düzeltmesi:** $10^{53}$ kg yalnız baryonik kütledir (~%5); Planck 2018 değerleri $\Omega_b\approx\%5$, $\Omega_{\rm DM}\approx\%27$, $\Omega_{\rm DE}\approx\%68$ ile $M_{C_m}\sim2\times10^{54}$ kg.
4. **Dirac büyük sayıları:** $D_{\rm evren}/D_{\rm çekirdek}\sim10^{41}$; bu oran varsayımsal bir model çapına dayanır (ör. $10^{47}$ ışık yılı). Gözlenebilir evren çapı ($\approx9.3\times10^{10}$ ışık yılı) kullanılırsa oran $\approx2.45\times10^{5}$'tir; ikisi aynı girdi değildir. Klasik Dirac oranları ($F_e/F_g\sim10^{39}$–$10^{40}$, $R_{\rm evren}/r_{\rm proton}\sim10^{40}$) ile aynı mertebededir.

$$M\sim\rho_P\,V_{\rm çekirdek},\qquad U_0\text{ kapasite metaforu}\in\big[\rho_P^{\min}V_{\rm CMB}^{\min},\ \rho_P^{\max}V_{\rm CMB}^{\max}\big]$$

```latex
M\sim\rho_P\,V_{\rm çekirdek},\qquad U_0\text{ kapasite metaforu}\in\big[\rho_P^{\min}V_{\rm CMB}^{\min},\ \rho_P^{\max}V_{\rm CMB}^{\max}\big]
```

| Sembol | Anlamı |
|---|---|
| $\rho_P$ | Planck yoğunluğu ($\approx5.16\times10^{96}$ kg/m³) |
| $V_{\rm çekirdek}$, $V_{\rm CMB}$ | CMB ölçeğinden türetilen tarihsel çekirdek hacmi |
| $\Omega_b$, $\Omega_{\rm DM}$, $\Omega_{\rm DE}$ | Baryon, karanlık madde ve karanlık enerji yoğunluk oranları |
| $D_{\rm evren}$, $D_{\rm çekirdek}$ | Model evren çapı ve tarihsel çekirdek çapı |

### Kritik statü hükümleri

$$\boxed{\;10^{161}\ \mathrm{kg}\ \text{fiziksel bir kütle DEĞİLDİR; doğru kullanımı üst sınır / kapasite metaforudur.}\;}$$

```latex
\boxed{\;10^{161}\ \mathrm{kg}\ \text{fiziksel bir kütle DEĞİLDİR; doğru kullanımı üst sınır / kapasite metaforudur.}\;}
```

$$\boxed{\;U_0 \text{ için sayısal kütle okuması güncel ontolojiye taşınmaz; } U_0 \text{ faz ve kapı uç noktası değildir.}\;}$$

```latex
\boxed{\;U_0 \text{ için sayısal kütle okuması güncel ontolojiye taşınmaz; } U_0 \text{ faz ve kapı uç noktası değildir.}\;}
```

$$\boxed{\;10^{161}\ \leftrightarrow\ 10^{120}\ \text{(kozmolojik sabit) eşlemesi desteksizdir ve geri çekilmiştir.}\;}$$

```latex
\boxed{\;10^{161}\ \leftrightarrow\ 10^{120}\ \text{(kozmolojik sabit) eşlemesi desteksizdir ve geri çekilmiştir.}\;}
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Evrenin başlangıç ölçeğine ilişkin tarihsel hesap zincirini kayıt altında tutar |
| **Neden yapıyor?** | Bu sayılar arşivde sık geçer; statüleri belirtilmezse ontolojik nicelik sanılabilir |
| **Nasıl yapıyor?** | Her halkayı kaynağıyla yazar; sayıların fiziksel kütle değil, kapasite metaforu olduğunu açıkça belirtir |
| **Ne sonuç bekleniyor?** | Varsayım ağacı ayrıştırıldığında hangi sayının hangi girdiye dayandığının netleşmesi |
| **Ne sonuç elde ediliyor?** | İki bağımsız yolun ~$10^{47}$ ışık yılına yakınsaması iç tutarlılık işareti olarak kayıtlıdır; ama sayı kanona alınmaz. Aralık formundaki $U_0$ kapasite yazımı bantlar netleşmeden kilitlenmez ("anlatı şişirmesi" riskine karşı koruma) |




# BÖLÜM 3 — ÜÇ FAZLI ONTOLOJİK MİMARİ

## 3.1 Neden üç faz?

Üçlü mimari, üç ayrı sınır yöneliminden **motive edilir**; bu, üçlüğün mümkün olan tek ontoloji olduğunu kanıtlamaz. Faz sayısının ilkel mi türetilmiş mi olduğu açık bir borçtur (EK K.1).

- **Aşağı doğru:** farklılaşmanın çözüldüğü ve maddenin tek bir yapıda bütünleştiği **c₀**.
- **Yukarı doğru:** Cₘ madde desteğinin çözüldüğü **c⁺**.
- **Arada:** ölçümün mümkün olduğu **Cₘ**.

Mevcut çerçeve dördüncü bir **bağımsız sınır** tanımlamaz. Bu, dördüncü bir fazın imkânsız olduğunu değil, önerilmediğini gösterir.

**İki uç yönelim, iki global kutup.** Üç fazlı mimarideki bu iki uç yönelim, global seviyede sırasıyla **doygunluk** ve **çözünme** kutuplarıyla ilişkilidir (Bölüm 2.8). Çift-limit yapısı sonradan eklenmiş bir kozmoloji varsayımı değildir; üç fazlı mimarinin içinde zaten bulunan iki yönelimin global okumasıdır.

$$\boxed{\;\text{Bu ilişki } c_0 \leftrightarrow U_0 \text{ ya da } c^+ \leftrightarrow U_+ \text{ biçiminde BİRE BİR ONTOLOJİK EŞLEME DEĞİLDİR.}\;}$$

```latex
\boxed{\;\text{Bu ilişki } c_0 \leftrightarrow U_0 \text{ ya da } c^+ \leftrightarrow U_+ \text{ biçiminde BİRE BİR ONTOLOJİK EŞLEME DEĞİLDİR.}\;}
```

## 3.2 c₀ — Zaman-öncesi potansiyel / çekirdek fazı

### Güncel çekirdek tanım

**c₀ (Potansiyel / Kara Delik Fazı):** Ölçülebilir madde yapısının atomik ve parçacık özelliklerini kaybettiği, bütün parçacıkların Planck ölçeğinde metrik boşluksuz duruma yakınsayan derecede birleşerek **tümleşik tek bir yapı** formuna dönüştüğü zaman-öncesi potansiyel ve çekirdek fazıdır.

| Özellik | c₀'daki durumu |
|---|---|
| İçsel fiziksel zaman | Yok — henüz kurulmamış ($\bot_0$) |
| Metrik $g_{\mu\nu}$ | Kabul edilebilir değil ($\bot_0$) |
| Cₘ'nin farklılaşmış maddesi | Metrik boşluksuz, bitişik tek-yapıya dönüşür |
| Kara delik | Ontolojik olarak c₀ ile özdeş (yazar hükmü) |

### c₀'da zaman: durmuş değil, kurulmamış

$$c_0\text{'da içsel fiziksel zaman YOKTUR:}\qquad T(c_0)=\bot_0\neq0$$

```latex
c_0\text{'da içsel fiziksel zaman YOKTUR:}\qquad T(c_0)=\bot_0\neq0
```

Burada kritik bir ayrım vardır:

| Durum | Anlamı |
|---|---|
| Zaman **durmuş** | Bir saat var ama ilerlemiyor — bu bir Cₘ durumudur |
| Zaman **yok** | Saat kavramının kendisi kurulamaz — c₀'daki durum budur |

c₀'da zaman henüz **kurulmamıştır**; bu yüzden c₀'a **zaman-öncesi** denir. Zaman orada "yavaş akmaz", "donmuş bir nehir" de değildir. Ayrıntılı anlatım girişteki c₀ açıklamasındadır.

### c₀'da madde

$$\boxed{\;C_m \to c_0: \quad \text{farklılaşmış madde} \;\longrightarrow\; \text{TOPLU TEK-YAPI LİMİTİ}\;}$$

```latex
\boxed{\;C_m \to c_0: \quad \text{farklılaşmış madde} \;\longrightarrow\; \text{TOPLU TEK-YAPI LİMİTİ}\;}
```

Ayrık nesneler arasındaki ayrım çözülür. "Bu parçacık" ile "şu parçacık" ayrımı işlemsel içeriğini kaybeder ve rejim **toplu** bir karakter kazanır.

### c₀'da metrik

$g_{\mu\nu}$, c₀'da **kabul edilebilir bir nesne değildir**: metrik orada yıkılmış değil, henüz kurulmamıştır.

### Toplu davranış analojileri — BEC

Bose–Einstein yoğuşması (BEC) ve süperakışkanlık, **toplu ve koherent davranışın** laboratuvarda ulaşılabilen örnekleridir ve c₀'ın **tek-yapı sezgisi** için kullanılabilir. Yazarın hükmüyle **BEC, madde fazında c₀ ortamına en yakın ortamdır**; ama c₀'ın kendisi değildir: içinde zaman akar ve sistem Cₘ'de kalır.

$$\boxed{\;\text{BEC}\neq c_0:\ \text{madde fazında } c_0 \text{ ortamına en yakın ortam — ANALOJİ, literal kimlik DEĞİL.}\;}$$

```latex
\boxed{\;\text{BEC}\neq c_0:\ \text{madde fazında } c_0 \text{ ortamına en yakın ortam — ANALOJİ, literal kimlik DEĞİL.}\;}
```

### c₀ ve kara delikler

**Evertophy ontolojisinde kara delik ile c₀ fazı ontolojik olarak özdeştir** (yazarın doğrudan onayladığı temel tanım). Bu kimliğin Cₘ'deki gözlenebilirlerle nicel bağlantısı, oluşum mekanizması ve olay ufku ile faz sınırı arasındaki ilişki ayrıca türetilmelidir; "olay ufku = faz sınırı" birebir özdeşliği kurulmuş değildir. Ontolojik özdeşlik, c₀ içinde Cₘ-tipi zaman, üç boyutlu Öklid uzayı ya da metrik tanımlamaz.

**Yazar hükmü — kara delik yok oluş değildir.** Kara delik bir yok oluş ya da sonsuz tekillik değildir. Yüzeyine Çekim Kuvveti ile temas eden parçacık, dolanık olup olmamasından bağımsız olarak yapıyla bütünleşir; BEC burada yalnız toplu tek-yapı benzetmesidir. Dışarıdaki parçacık spinini koruyabilir ya da koruyamaz; kütle spinden bağımsız korunur. Spin ve dolanıklık, çevreyle etkileşim (ölçüm ya da madde teması) olmadıkça korunur.

**Yazar hükmü — metrik boşluksuz tek-yapı.** Olay ufkunun içindeki yapı, Planck ölçeğinde metrik boşluksuz duruma yakınsayan derecede **bitişik**, sonlu ve **tek bir form**dur. Bu, "kara delik çekirdeği Planck boyutundadır" anlamına gelmez; kara deliğin içindeki kütle yapısının, parçacıklar arasında metrik boşluğun neredeyse kalmadığı, bütünüyle tek bir form hâlinde olduğunu söyler. Evertophy'nin c₀ okumasının çekirdek mantığı budur. Bu doygunluk $X$'in bir okuması üzerinden yazılır ($X$'in kendisi skaler değildir, Bölüm 4):

$$\xi_{\rm sat}=\pi_{\rm sat}(X)\;\longrightarrow\;\xi_{\rm sat}^{\max}\qquad(\text{normalize okumada }\xi_{\rm sat}\approx1)$$

```latex
\xi_{\rm sat}=\pi_{\rm sat}(X)\;\longrightarrow\;\xi_{\rm sat}^{\max}\qquad(\text{normalize okumada }\xi_{\rm sat}\approx1)
```

| Sembol | Anlamı |
|---|---|
| $\pi_{\rm sat}$ | $X$'in doygunluk okuma izdüşümü |
| $\xi_{\rm sat}$ | Doygunluk okuması; normalize edildiğinde üst sınırı 1'dir |

**Yazar hükmü — c₀ kapasitesi.** c₀'ın iç kapasitesi hem kütleyle hem yüzey alanıyla ilişkili olarak büyür: kapasite **kütleyle doğrusal** ölçeklenir; ufuk alanı ise **kütlenin karesiyle** büyür (kütle iki katına çıktığında ufuk yarıçapı iki, ufuk alanı dört katına çıkar). Bu yüzden kapasite, ufuk alanının karekökü ile ölçeklenir. Kütle ile ufuk çapı arasındaki oran bilinen bir olgudur. Çekirdek kapasitesinin sayım birimi **Planck kütlesidir**; tek-yapının yoğunluğu Planck yoğunluğunu aşamaz. **Ayrı bir yazar hükmü olarak** daha kütleli bir kara delik daha yoğun değildir; aynı metrik boşluksuz yapıdan daha büyük bir hacme ve daha geniş bir ufka sahiptir. Bu ikinci hüküm yoğunluk üst sınırından türetilmez: üst sınır yalnız en küçük hacmi verir; yoğunluğun kütleyle artmaması tek-yapının kendi niteliğidir (aşağıdaki koşullu ölçekleme):

$$R_s=\frac{2GM}{c^2},\qquad A=4\pi R_s^2=\frac{16\pi G^2M^2}{c^4}$$

```latex
R_s=\frac{2GM}{c^2},\qquad A=4\pi R_s^2=\frac{16\pi G^2M^2}{c^4}
```

$$N_{c_0}=\frac{M}{m_P},\qquad m_P=\sqrt{\frac{\hbar c}{G}},\qquad \rho_{c_0}\le\rho_P=\frac{c^5}{\hbar G^2},\qquad V_{c_0}\ge\frac{M}{\rho_P}=N_{c_0}\,\ell_P^3$$

```latex
N_{c_0}=\frac{M}{m_P},\qquad m_P=\sqrt{\frac{\hbar c}{G}},\qquad \rho_{c_0}\le\rho_P=\frac{c^5}{\hbar G^2},\qquad V_{c_0}\ge\frac{M}{\rho_P}=N_{c_0}\,\ell_P^3
```

$$R_{c_0}\propto M^{1/3}\ \ (\rho_{c_0}\ \text{sabit}),\qquad R_s\propto M,\qquad A\propto M^2,\qquad \frac{R_{c_0}}{R_s}\propto M^{-2/3}$$

```latex
R_{c_0}\propto M^{1/3}\ \ (\rho_{c_0}\ \text{sabit}),\qquad R_s\propto M,\qquad A\propto M^2,\qquad \frac{R_{c_0}}{R_s}\propto M^{-2/3}
```

| Sembol | Anlamı |
|---|---|
| $R_s$ | Schwarzschild (ufuk) yarıçapı |
| $A$ | Ufuk yüzey alanı |
| $M$ | Kara deliğin (c₀ yapısının) kütlesi |
| $G$, $c$, $\hbar$ | Kütleçekim sabiti, ışık hızı, indirgenmiş Planck sabiti |
| $N_{c_0}$ | Planck kütlesi biriminde çekirdek kapasitesi |
| $m_P$ | Planck kütlesi ($\approx2.18\times10^{-8}$ kg) |
| $\rho_P$, $\ell_P$ | Planck yoğunluğu ($\approx5.16\times10^{96}$ kg/m³) ve Planck uzunluğu; $\rho_P\ell_P^3=m_P$ |
| $V_{c_0}$, $R_{c_0}$ | Tek-yapının hacmi ve yarıçapı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kara delik içindeki tek-yapının kapasitesini, hacmini ve ufukla ölçeklenmesini yazar |
| **Neden yapıyor?** | "Sonsuz yoğunluk, sıfır hacim" tekillik okumasının yerine sonlu ve tutarlı bir tablo konmalıdır |
| **Nasıl yapıyor?** | Kapasiteyi Planck kütlesi biriminde sayar; yoğunluğa Planck üst sınırı koyar; tek-yapı hacmini ve ufku kütleyle ölçekler |
| **Ne sonuç bekleniyor?** | Kütle arttıkça yoğunluğun değil hacmin büyüdüğü bir resim; ufuk alanıyla kapasite arasındaki ilişkinin nicel biçiminin kurulması |
| **Ne sonuç elde ediliyor?** | Oranlar doğrudur: ufuk yarıçapı $M$, ufuk alanı $M^2$ ile büyür; tek-yapı yarıçapı ise **sabit yoğunluk gerçeklemesinde** $M^{1/3}$ ile büyür. Yoğunluk Planck değerinde alındığında (en küçük yarıçap) Güneş kütleli bir kara delik için $R_{c_0}^{\min}\approx4.5\times10^{-23}$ m (Planck uzunluğundan çok büyük, ~3 km'lik ufuktan çok küçük); bu yüzden ufuk ile tek-yapı sınırı özdeş sayılmaz. İç profil ve kapasitenin alan yasasıyla ilişkisi açıktır (EK K) |

Kapasitenin kütleyle, ufuk alanının ise kütlenin karesiyle ölçeklenmesi, gözlemle sınanmış alan teoremiyle uyumludur; entropinin alanla orantılı olduğunu söyleyen Bekenstein–Hawking alan yasası ise gözlemle sınanmamış kuramsal bir sonuçtur (23.3).

### Kapasite, yoğunluk ve yarıçap — koşullar ve okuma türü

Yukarıdaki ilişkilerden biri **türetilmiş**, biri **hüküm**, biri **koşullu** sonuçtur; üçü ayrı tutulur:

$$N_{c_0}=\frac{M}{m_P}\propto M\propto\sqrt{A},\qquad \rho_{c_0}\le\rho_P\;\Rightarrow\;V_{c_0}\ge\frac{M}{\rho_P},\qquad R_{c_0}\ge R_{c_0}^{\min}=\left(\frac{3M}{4\pi\rho_P}\right)^{1/3}$$

```latex
N_{c_0}=\frac{M}{m_P}\propto M\propto\sqrt{A},\qquad \rho_{c_0}\le\rho_P\;\Rightarrow\;V_{c_0}\ge\frac{M}{\rho_P},\qquad R_{c_0}\ge R_{c_0}^{\min}=\left(\frac{3M}{4\pi\rho_P}\right)^{1/3}
```

$$\rho_{c_0}(M)=\rho_*\le\rho_P\ \ (\text{sabit yoğunluk gerçeklemesi})\;\Rightarrow\;R_{c_0}=\left(\frac{3M}{4\pi\rho_*}\right)^{1/3}\propto M^{1/3},\qquad \frac{d\ln R_{c_0}}{d\ln M}=\frac13\left(1-\frac{d\ln\rho_{c_0}}{d\ln M}\right)$$

```latex
\rho_{c_0}(M)=\rho_*\le\rho_P\ \ (\text{sabit yoğunluk gerçeklemesi})\;\Rightarrow\;R_{c_0}=\left(\frac{3M}{4\pi\rho_*}\right)^{1/3}\propto M^{1/3},\qquad \frac{d\ln R_{c_0}}{d\ln M}=\frac13\left(1-\frac{d\ln\rho_{c_0}}{d\ln M}\right)
```

$$M\in[M^-,M^+],\ \ \rho_{c_0}\in[\rho^-,\rho^+],\ \rho^->0\;\Rightarrow\;R_{c_0}\in\left[\left(\frac{3M^-}{4\pi\rho^+}\right)^{1/3},\ \left(\frac{3M^+}{4\pi\rho^-}\right)^{1/3}\right]$$

```latex
M\in[M^-,M^+],\ \ \rho_{c_0}\in[\rho^-,\rho^+],\ \rho^->0\;\Rightarrow\;R_{c_0}\in\left[\left(\frac{3M^-}{4\pi\rho^+}\right)^{1/3},\ \left(\frac{3M^+}{4\pi\rho^-}\right)^{1/3}\right]
```

| Sembol | Anlamı |
|---|---|
| $N_{c_0}$ | Boyutsuz kapasite ölçüsü; genel olarak gerçel sayıdır (tam sayı olması ek bir kuantizasyon hükmü gerektirir) |
| $A$ | Ufuk alanı (Schwarzschild ailesi; dönen kara delikte dönme parametresi ayrıca girer) |
| $\rho_*$ | Kütleden bağımsız tek-yapı yoğunluğu (sabit yoğunluk gerçeklemesi) |
| $R_{c_0}^{\min}$ | Yoğunluk üst sınırından gelen en küçük yarıçap |
| $d\ln R/d\ln M$ | Yarıçapın kütleyle ölçekleme üssü |
| $M^\pm$, $\rho^\pm$ | Kütle ve yoğunluğun aralık uçları (bağımsız kapsama bantları) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kapasite, yoğunluk ve yarıçap ilişkilerinin hangisinin türetildiğini, hangisinin hüküm, hangisinin koşullu olduğunu ayırır |
| **Neden yapıyor?** | Yalnız $\rho\le\rho_P$ üst sınırından yoğunluğun sabit olduğu ya da kütleyle artmadığı çıkmaz; bu çıkarım açığı önceki anlatımda görünmüyordu |
| **Nasıl yapıyor?** | Üst sınırdan yalnız en küçük hacmi ve yarıçapı türetir; $R\propto M^{1/3}$'ü sabit yoğunluk gerçeklemesine bağlar; genel durumda ölçekleme üssünü yoğunluğun kütleyle değişimine bağlayan formülü verir (yoğunluk kütleyle artmıyorsa üs $\ge1/3$) |
| **Ne sonuç bekleniyor?** | Tek-yapının iç profilinin ve $\rho_*$'ın türetilmesi |
| **Ne sonuç elde ediliyor?** | $N_{c_0}\propto M\propto\sqrt A$ ve $V\ge M/\rho_P$ **türetilmiştir**; yoğunluğun kütleyle artmaması **yazar hükmüdür**; $R\propto M^{1/3}$ **sabit yoğunluk gerçeklemesinin** sonucudur. Güneş kütleli örnekteki $4.5\times10^{-23}$ m, ölçülmüş bir yarıçap değil, $\rho_*=\rho_P$ alınarak hesaplanan alt sınırdır. Yazar hükmü tam doğru orantıyı da kapsıyorsa, bu ortalama yoğunluğun kütleden bağımsız olması ($\rho_{c_0}=\rho_*$) demektir |

**Okuma türü (tip notu).** c₀'da Cₘ tipi uzunluk ve metrik tanımsız olduğundan ($g_{\mu\nu}|_{c_0}=\bot_0$), $V_{c_0}$, $R_{c_0}$ ve $\rho_{c_0}$ c₀'ın **içsel geometrisi değil**, c₀ yapısının **Cₘ fiziksel okumasında kullanılan etkin parametreleridir**. Bu, belgenin kaynak faz / gözlem fazı ayrımının (15.1a) bu niceliklere uygulanmasıdır ve kara delik ≡ c₀ kimliğini değiştirmez:

$$\mathcal O^{C_m}_{c_0}:\ \mathrm{Durum}(c_0)\times\mathrm{Bağlam}(C_m)\longrightarrow\mathcal I(\mathrm{kg})\times\mathcal I(\mathrm{m})\times\mathcal I(\mathrm{m}^3)\times\mathcal I(\mathrm{kg/m^3}),\qquad (M_{c_0},R_{c_0},V_{c_0},\rho_{c_0})=\mathcal O^{C_m}_{c_0}(s,\mathcal C)$$

```latex
\mathcal O^{C_m}_{c_0}:\ \mathrm{Durum}(c_0)\times\mathrm{Bağlam}(C_m)\longrightarrow\mathcal I(\mathrm{kg})\times\mathcal I(\mathrm{m})\times\mathcal I(\mathrm{m}^3)\times\mathcal I(\mathrm{kg/m^3}),\qquad (M_{c_0},R_{c_0},V_{c_0},\rho_{c_0})=\mathcal O^{C_m}_{c_0}(s,\mathcal C)
```

| Sembol | Anlamı |
|---|---|
| $\mathcal O^{C_m}_{c_0}$ | c₀ yapısından Cₘ etkin parametrelerine giden okuma haritası (biçimi açık) |
| $\mathrm{Durum}(c_0)$, $\mathrm{Bağlam}(C_m)$ | c₀ durumları ve Cₘ gözlem bağlamı |
| $\mathcal I(D)$ | $D$ birimindeki aralık (Range) türü; çıktı, farklı boyutlu dört aralığın çarpım türüdür |
| $s$, $\mathcal C$ | Bir c₀ durumu ve bir Cₘ gözlem bağlamı |
| $M_{c_0}$ | c₀ yapısının Cₘ'de okunan kütlesi |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Metriksiz c₀'a atanan hacim, yarıçap ve yoğunluğun hangi anlamda tanımlı olduğunu söyler |
| **Neden yapıyor?** | "c₀'da uzunluk tanımsızdır" hükmü ile "tek-yapının yarıçapı şu kadardır" ifadesinin birlikte doğru olabilmesi için okuma türü açık olmalıdır |
| **Nasıl yapıyor?** | Bu nicelikleri c₀'ın içinde ölçülen büyüklükler olarak değil, Cₘ'deki bir okuma haritasının çıktıları olarak türler |
| **Ne sonuç bekleniyor?** | Okuma haritasının kurulması (EK K.1) |
| **Ne sonuç elde ediliyor?** | **Tip ayrımı kuruludur**; haritanın kendisi açıktır |

**Yazar hükmü — c₀'dan ayrılış.** c₀'dan ayrılan yapının hızı ve/veya yoğunluğu ne oluşacağını belirler: madde, ışık ya da c⁺. Buradaki hız ve yoğunluk c₀'ın içsel nicelikleri değildir — c₀'da hız, süre ve uzunluk tanımsızdır —; geçişin **Cₘ tarafındaki sınır okumalarıdır** ($v_\partial$, $\rho_\partial$). Hüküm, çıkan yapının Cₘ'de hangi okumayla belirdiğini söyler ve 3.3'teki üyelik bandıyla birlikte okunur:

$$\underbrace{0<v<c}_{C_m\ \text{madde}},\qquad \underbrace{v=c}_{\text{liminal ortak sınır (ışık)}},\qquad c^+:\ \text{bandın çözülmesi}\ \neq\ v_{c^+}=\frac{dx}{dt}>c$$

```latex
\underbrace{0<v<c}_{C_m\ \text{madde}},\qquad \underbrace{v=c}_{\text{liminal ortak sınır (ışık)}},\qquad c^+:\ \text{bandın çözülmesi}\ \neq\ v_{c^+}=\frac{dx}{dt}>c
```

| Sembol | Anlamı |
|---|---|
| $v$ | Üyelik okuması; laboratuvar koordinat hızı değildir (3.3) |
| $c$ | Işık hızı — Cₘ'nin tutarlılık kısıtı |
| $v_{c^+}$ | c⁺ için Cₘ-tipi hız; tanımlı değildir (3.4) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | c₀'dan ayrılan yapının hangi faza gideceğini belirleyen ölçütü tanımlar |
| **Neden yapıyor?** | Kara delikten çıkan kütle ve enerjinin Cₘ'de ne olarak okunacağı (madde, ışık, c⁺) ontolojide yer bulmalıdır |
| **Nasıl yapıyor?** | Cₘ üyelik bandını ölçüt olarak kullanır: bant içi madde, sınır ışık, bandın çözüldüğü rejim c⁺ |
| **Ne sonuç bekleniyor?** | Kuralın nicel biçiminin kurulması |
| **Ne sonuç elde ediliyor?** | Hüküm kuruludur; c⁺'ın $c$-ötesi olması Cₘ-tipi ışık-üstü hareket değildir (3.4). Nicel biçim açıktır |

**Yazarın açık bıraktığı olasılıklar — birleşmede kapasite.** İki kara delik birleştiğinde azalan çekirdek kapasitesi için bütün olasılıklar mümkün olabilir: (1) kütleçekim dalgasıyla c⁺'a yönelim, (2) madde üretimi, (3) ayrı bir kara delik, (4) bunların hepsi kısmen. Hangisinin ya da hangi bileşimin gerçekleştiği açıktır.

### Tarihsel aşırı somut tanımlar

Şunlar **tarihsel ya da model** düzeyindedir, güncel çekirdek değildir: durağanlık kilidi · sıfır-diferansiyel motor. Eski "tam Planck doygunluk durumu" ve "belirli bir Planck yoğunluğu" okumaları ise yazarın metrik boşluksuz tek-yapı hükmüyle güncel biçimde yeniden yazılmıştır: çekirdeğin belirli bir sayısal yoğunluğa kilitlendiği iddiası yoktur; yalnız $\rho_{c_0}\le\rho_P$ üst sınırı vardır.

"Sonsuz yoğunluk değil, sıfır diferansiyel" ve `dt=0, dx=0` yazımları güncel ontolojik tanım değildir. Ama bütünüyle silinmiş de sayılmazlar: c₀'da sıradan Cₘ zaman ve uzay serbestliklerinin kabul edilebilir olmadığını anlatan **tarihsel-pedagojik kısaltmalar** olarak anılabilirler.

$$\boxed{\;c_0\text{'da Cₘ-tipi }dt\text{ ve }dx\text{ ontolojik ilkel değildir; "}dt=0,\ dx=0\text{" yalnız pedagojik sınır dilidir.}\;}$$

```latex
\boxed{\;c_0\text{'da Cₘ-tipi }dt\text{ ve }dx\text{ ontolojik ilkel değildir; "}dt=0,\ dx=0\text{" yalnız pedagojik sınır dilidir.}\;}
```

Bu kısaltma, c₀ içinde önceden kurulmuş bir saatin durduğu ya da Cₘ metriğinin sıfıra eşitlendiği anlamına gelmez.

### c₀'da zamansal konum

c₀ **zamansal bir öncelik değil, rejimsel bir konumdur**. Güncel $U_x$ içinde de yüksek yoğunluk rejimlerinde c₀ üyeliği mümkün olabilir; hangi fiziksel sistemin c₀ üyeliği taşıdığı nicel köprüye bağlıdır ve açık borçtur.

**Yazar hükmü — yerel yeniden oluşum.** Fazlar Big Bang'de birlikte oluşur; ayrıca kritik kütlede Çekim Kuvveti'ne yenik düşen madde yerel olarak yeniden c₀ oluşturabilir, aşırı çözünme (entropi / düzensizlik) ise c⁺ oluşturabilir. Bunlar faz üçgeninin Cₘ → c₀ ve Cₘ → c⁺ kenarlarıdır; eşiklerin nicel biçimi açıktır.

### c₀'da sıcaklık ve mutlak sıfır

**Yazar hükmü:** $c_0\neq$ mutlak sıfır. Mutlak sıfır (0 K), Cₘ fazının kendi içindeki termodinamik limit durumudur; c₀'da ise sıcaklık ve ısı kavramının kendisi tanımsızdır.

$$T(c_0)=\bot_0\neq0,\qquad T\to0\ \mathrm K\ \Rightarrow\ C_m\ \text{taban durumu}$$

```latex
T(c_0)=\bot_0\neq0,\qquad T\to0\ \mathrm K\ \Rightarrow\ C_m\ \text{taban durumu}
```

| Sembol | Anlamı |
|---|---|
| $T$ | Sıcaklık — yalnız Cₘ'de tanımlı bir nicelik |
| $\bot_0$ | c₀'da "henüz kurulmamış" yokluk (5.3); sayısal sıfır değildir |
| $0\ \mathrm K$ | Mutlak sıfır: Cₘ'nin termodinamik limiti |

Mutlak sıfıra yaklaşan bir sistem Cₘ'de kalır: kuantum sıfır-noktası hareketi sürer ve saatler işlemeye devam eder. Soğutma tek başına c₀'a götürmez; ultra soğuk deneylerde (BEC) yaklaşılan şey c₀ değil, Cₘ'nin taban durumudur.

Kara delik ≡ c₀ hükmüyle birlikte okunduğunda, kara deliğe atfedilen Hawking sıcaklığı c₀'ın iç sıcaklığı olarak değil, ufkun uzaktaki Cₘ gözlemcisine verdiği termal okuma olarak yorumlanır. Bu bir **aday okumadır**; kanona alınması yazar kararıdır ve nicel köprü açıktır (EK K.2).

$$T_H=\frac{\hbar c^3}{8\pi G k_B M}$$

```latex
T_H=\frac{\hbar c^3}{8\pi G k_B M}
```

| Sembol | Anlamı |
|---|---|
| $T_H$ | Hawking sıcaklığı — ufkun Cₘ okuma sıcaklığı (aday okuma) |
| $k_B$ | Boltzmann sabiti |
| $M$ | Kara delik kütlesi |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | c₀'ın sıcaklıkla ilişkisini kurar: mutlak sıfır değildir, sıcaklık orada tanımsızdır |
| **Neden yapıyor?** | "c₀ = en soğuk hâl" yanılgısı, Cₘ'nin bir sınır durumunu c₀ ile karıştırıyordu |
| **Nasıl yapıyor?** | Mutlak sıfırı Cₘ'nin taban durumu, c₀'ı ise sıcaklığın kurulmadığı rejim olarak ayırır; Hawking sıcaklığını ufkun Cₘ'deki okuması olarak yorumlar |
| **Ne sonuç bekleniyor?** | Hawking sıcaklığı ile c₀ iç yapısı arasındaki nicel köprünün kurulması |
| **Ne sonuç elde ediliyor?** | "c₀ ≠ mutlak sıfır" yazar hükmüdür; Hawking sıcaklığının ufuk okuması olarak yorumu aday okumadır |

## 3.3 Cₘ — Farklılaşmış madde / ölçüm / emergent zaman

### Güncel çekirdek tanım

**Cₘ (Madde / Atom / Parçacık Fazı):** Doğrudan etkileşimde bulunduğumuz fiziksel gerçekliğin; ayrışmış kütleli maddelerin, atomların ve atom altı parçacıkların, ölçüm süreçlerinin ve tek yönlü bir akış olarak deneyimlediğimiz zamanın var olduğu fazdır.

| Özellik | Cₘ'deki durumu |
|---|---|
| Madde | Farklılaşmış madde |
| Ölçüm | Doğrudan fiziksel ölçüm yalnız burada |
| Zaman | Emergent fiziksel zamanın **tek evi** |
| Metrik | $g_{\mu\nu}$'nün **tek tanım alanı** |

Standart fiziksel hızlar, oranlar ve metrik okumalar **yalnız burada** anlamlıdır.

### Cₘ ve ışık bariyeri

$$\boxed{\;c \text{ bir HIZ SINIRINDAN ÖNCE, Cₘ'nin TUTARLILIK KISITIDIR.}\;}$$

```latex
\boxed{\;c \text{ bir HIZ SINIRINDAN ÖNCE, Cₘ'nin TUTARLILIK KISITIDIR.}\;}
```

$c$, Cₘ fazının bilgi işleme, kayıt ve çözünürlük sınırını koyar. Uzayda hareket eden bir nesnenin hız sınırı olarak değil, fazın kendi iç tutarlılığının sınırı olarak okunur.

### Kinematik üyelik bandı

$$\boxed{\;\text{Cₘ'nin madde-üyelik koşulu korunabilir hız bandı } 0<v<c\text{'dir; } v=c \text{ liminal faz sınırıdır.}\;}$$

```latex
\boxed{\;\text{Cₘ'nin madde-üyelik koşulu korunabilir hız bandı } 0<v<c\text{'dir; } v=c \text{ liminal faz sınırıdır.}\;}
```

Bu, yazarın çekirdek hükmüdür. Buradaki $v$ yerel laboratuvar koordinat hızı değildir: bandın ontolojik statüsü kesindir; $v$'nin kesin matematiksel okuması ve ölçümle bağlantısı açıktır.

$$\underbrace{0<v<c}_{\text{çekirdek üyelik hükmü}} \;+\; \underbrace{\mathcal R_v:\ \text{durum} \to v_{\rm üyelik}}_{\text{açık okuma}}, \qquad v_{\rm lab}=0 \;\not\Rightarrow\; c_0$$

```latex
\underbrace{0<v<c}_{\text{çekirdek üyelik hükmü}} \;+\; \underbrace{\mathcal R_v:\ \text{durum} \to v_{\rm üyelik}}_{\text{açık okuma}}, \qquad v_{\rm lab}=0 \;\not\Rightarrow\; c_0
```

| Sembol | Anlamı |
|---|---|
| $v$ | Üyelik okuması: nesnenin uzaysal konumu, genel hareketi ve iç dinamiklerinin birlikte okunması |
| $\mathcal R_v$ | Durumdan üyelik hızına giden okuma haritası; açık |
| $v_{\rm lab}$ | Yerel laboratuvar hızı |

Bandın alt ucundaki "0", herhangi bir kozmolojik ya da eylemsiz referans çerçevesine göre tanımlanan **bağıl hız tabanıdır**. Laboratuvarda durağan duran bir parçacık bile iç dinamikleri, spin yapısı ve kozmolojik sürüklenmesi nedeniyle Cₘ üyesidir. "Evrensel referans" ifadesi klasik bir ayrıcalıklı çerçeve koordinat hızı değildir; üyelik okuması $X$-çözümü düzeyindedir (Bölüm 4). Bandın matematiksel referans nesnesi, okuma haritası (15.2) ve $X$'in gerçeklemesi (24.3) kapanana kadar bilinçli olarak açıktır. Bölüm 3.7'nin kuralı ("harita konumu ≠ faz üyeliği") kinematik üyelik için de geçerlidir: ölçülen yerel hız tek başına faz üyeliğini belirlemez. Cₘ içindeki yapılar yalnız kinematik bantla değil, faz-parametre peyzajının **iç bölgesindeki** çoklu kısıt çözümüyle sınıflanır (Bölüm 12.3).

**Bandın aşılması bir hızlanma değildir.** Evertophy, Cₘ'deki deneysel olarak doğrulanmış relativistik sonuçları açıklanması gereken fiziksel kısıtlar olarak kabul eder; bunların emergent yapıdan türetimi ayrıca kurulmalıdır. Kütleli bir cisim Cₘ içinde hızlanarak $c$'ye ulaşamaz. c⁺'a geçiş, $v=c$ eşiğinde gerçekleşen bir **faz geçişidir**: aşılan şey bir hız değeri değil, Cₘ'nin üyelik bandıdır; geçişten sonra Cₘ'nin hız dili tanımsızdır.

**Işık liminaldir — ortak sınır.** Foton $v=c$ sınırında bulunur: bandın üyesi değil, sınırın liminal durumudur. Bu sınır Cₘ ile c⁺'ın **ortak sınırıdır**: Cₘ bandının sınırında bulunan bir yapı, aynı zamanda c⁺ rejiminin de sınırındadır. Sınırda bulunmak iki fazdan birine üye olmak değildir; foton ne Cₘ'nin kütleli maddesine ne de c⁺'a üyedir (7.6).

$$\text{sınır}(C_m)\big|_{v=c}\;=\;\text{sınır}(c^+)\big|_{C_m\text{ yönü}},\qquad \text{liminal}\neq C_m\ \text{üyeliği},\qquad \text{liminal}\neq c^+\ \text{üyeliği}$$

```latex
\text{sınır}(C_m)\big|_{v=c}\;=\;\text{sınır}(c^+)\big|_{C_m\text{ yönü}},\qquad \text{liminal}\neq C_m\ \text{üyeliği},\qquad \text{liminal}\neq c^+\ \text{üyeliği}
```

**Yazar hükmü — kütleçekim dalgası.** Kütleçekim dalgası da ışık gibi faz rejim – eşik sınırında, yani $v=c$ ortak sınırında yayılır; bu c⁺ üyeliği anlamına gelmez (7.6). Kütleçekim dalgalarının ışıkla aynı hızda yayıldığı ölçümle bilinmektedir (GW170817); hüküm bu ölçümle tutarlıdır, ondan türetilmiş değildir.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bir yapının madde olarak Cₘ'ye ne zaman üye olduğunu ve ışığın nerede durduğunu belirler |
| **Neden yapıyor?** | Faz üyeliğinin yerel hızla karıştırılması ($v_{\rm lab}=0$ ise c₀ gibi) ve ışık-üstü madde okumaları ontolojiyi bozardı |
| **Nasıl yapıyor?** | Üyelik bandını $0<v<c$ olarak sabitler; $v=c$'yi Cₘ ile c⁺'ın ortak liminal sınırı olarak tanımlar; $v$'yi bir üyelik okuması olarak ayırır |
| **Ne sonuç bekleniyor?** | $\mathcal R_v$ okuma haritasının kurulması ve relativistik sonuçların emergent yapıdan geri kazanılması |
| **Ne sonuç elde ediliyor?** | Bant ve ortak sınır okuması kanondur; $\mathcal R_v$ ve bandın matematiksel referans nesnesi açıktır |

### Cₘ ve ölçüm

$$\boxed{\;c_0 \text{ ve } c^+ \text{ hakkında söylenen her şey, Cₘ'den yapılan bir OKUMADIR.}\;}$$

```latex
\boxed{\;c_0 \text{ ve } c^+ \text{ hakkında söylenen her şey, Cₘ'den yapılan bir OKUMADIR.}\;}
```

### Cₘ epistemik merkezdir — topolojik zorunlu aracı değildir

Bu ayrım kritiktir. Cₘ'nin merkezî olması **ölçüm ve kayıt** açısındandır. Faz topolojisinde Cₘ'den geçmek zorunlu değildir (Bölüm 3.5).

### Model katmanı notu

Aşağıdaki kayıtlar tarihsel geliştirme katmanından devralınmış **model ve aday köprülerdir**. Hesaplanabilirlik ve sınanabilirlik hedefi taşırlar; hiçbiri Postüla-0'ı, üç fazlı ontolojiyi, $X$'in çekirdek tanımını ya da damga cebirini yeniden tanımlamaz. Model ile ontoloji ayrımı Bölüm 1.5 ve EK E'deki epistemik düzenle aynen korunur.

### Ölçek-rejim çalışma sınıfları — aday model

$$\boxed{\;\text{Kuantum, termal, astrofizik ve kozmolojik sınıflar Cₘ içindeki ÖLÇEK-REJİM sınıflarıdır; ontolojik faz değildir.}\;}$$

```latex
\boxed{\;\text{Kuantum, termal, astrofizik ve kozmolojik sınıflar Cₘ içindeki ÖLÇEK-REJİM sınıflarıdır; ontolojik faz değildir.}\;}
```

| Ölçek-rejim sınıfı | Tipik çalışma alanı |
|---|---|
| **Kuantum** | Atom altı sistemler |
| **Termal** | Laboratuvar ve çok cisimli termal sistemler |
| **Astrofizik** | Yıldız, kompakt nesne ve galaksi ölçekleri |
| **Kozmolojik** | Evren ölçeği |

Bu sınıflar c₀, Cₘ ve c⁺ ontolojik fazları **değildir**. Faz-parametre matrisinde satırların ya da gözlenebilir ailelerin ölçeğe göre gruplanması için kullanılabilir; ayrı bir ontoloji katmanı oluşturmaz.

## 3.4 c⁺ — Zaman-dışı üst / arşiv / koordinasyon fazı

### Güncel çekirdek tanım

**c⁺ (Karanlık Madde / Karanlık Enerji / Vakum Fazı — Çözünmüş Faz):** Evrenin madde (bütün parçacık yapısı) ya da kara delik formunda bulunmayan yapısının tümüdür: kozmik boşluklar, vakum ortamı, karanlık madde ve karanlık enerji — ve **atomu oluşturan parçacıkların arasındaki boşluk dahi** (yazar hükmü).

| Özellik | c⁺'taki durumu |
|---|---|
| İçsel Cₘ fiziksel zamanı | Yok — çözünmüş ($\bot_+$) |
| İçsel Cₘ hızı | Tanımsız |
| Metrik $g_{\mu\nu}$ | Yok ($\bot_+$) |
| Cₘ madde desteği | Çözülür |
| Ontolojik kimlik | Karanlık madde ≡ karanlık enerji ≡ vakum |
| Gelecek | c⁺ bir gelecek kâhini değildir |

### c⁺'ın ayırt edici özelliği

$$\boxed{\;\mathrm{supp}_{C_m}(\text{madde}) \to \varnothing,\qquad g_{\mu\nu}^{(C_m)}\to\bot_+\;}$$

```latex
\boxed{\;\mathrm{supp}_{C_m}(\text{madde}) \to \varnothing,\qquad g_{\mu\nu}^{(C_m)}\to\bot_+\;}
```

| Sembol | Anlamı |
|---|---|
| $\mathrm{supp}_{C_m}(\text{madde})$ | Cₘ madde desteği: Cₘ tipi maddenin var olabildiği dayanak |
| $\varnothing$ | Boş küme |
| $g_{\mu\nu}^{(C_m)}$ | Cₘ metriği |
| $\bot_+$ | c⁺'ta "çözünmüş" yokluk |

**Cₘ madde desteğinin çözülmesi**, c⁺'ın ana ontolojik ayrımıdır.

### c⁺'a Cₘ kavramları aynen taşınmaz

| Kullanılmaz | Güncel güvenli ifade |
|---|---|
| ~~c⁺'ta Cₘ tipi durgun kütle taşıyan madde aynen kalır~~ | Cₘ madde desteği çözülür |
| ~~uzunluk seyrelmiş~~ | Cₘ metrik uzunluğu c⁺'ta kabul edilemez |
| ~~süre seyrelmiş~~ | Cₘ fiziksel süresi c⁺'ta kabul edilemez |
| ~~$v>c$, ışık-üstü madde~~ | İçsel Cₘ hız dili tanımsızdır |
| ~~dış kabuk ışıktan hızlı hareket eder~~ | Hareket kavramı Cₘ okumasına aittir |

Bu koruma, **Cₘ madde ontolojisinin c⁺'a doğrudan taşınmasını** engeller.

#### Tarihsel K2 inceliği

Eski biçimsel çekirdeğin bir sürümünde c⁺ için soyut bir "kütle boyutu" taşıyıcısı izinli olarak kodlanmıştı (`actM cp = true`). Bu kayıt biçimsel kaynak bilgisi olarak korunur; ama aynı eski spesifikasyon bugün geçersiz olan başka varsayımlar da taşıdığından, bu satır tek başına güncel fiziksel kanon sayılmaz.

$$\boxed{\;\text{Cₘ maddesel / durgun kütle desteği c⁺'ta korunmaz}\qquad \text{tarihsel K2'nin soyut kütle-boyutu kaydı}\;\neq\;\text{güncel c⁺'a özgü kütle gözlenebiliri}\;}$$

```latex
\boxed{\;\text{Cₘ maddesel / durgun kütle desteği c⁺'ta korunmaz}\qquad \text{tarihsel K2'nin soyut kütle-boyutu kaydı}\;\neq\;\text{güncel c⁺'a özgü kütle gözlenebiliri}\;}
```

Karanlık sektörün Cₘ'de kütleçekimsel bir okuma üretmesi, c⁺ içinde Cₘ tipi bir kütle taşıyıcısı bulunduğunu kanıtlamaz. Postüla-0'a göre maddeden daha temel konumda olan Çekim Kuvveti'dir; kütleçekim onun Cₘ'deki metrik izdüşümlerinden biridir.

### c₀ ve c⁺ madde ontolojisi aynı değildir

$$\boxed{\;C_m\to c_0:\text{ metrik boşluksuz tek-yapı}\qquad C_m\to c^+:\text{ Cₘ madde desteğinin çözülmesi}\;}$$

```latex
\boxed{\;C_m\to c_0:\text{ metrik boşluksuz tek-yapı}\qquad C_m\to c^+:\text{ Cₘ madde desteğinin çözülmesi}\;}
```

Birincisinde farklılaşmış madde **kolektif tek bir yapıya** gider; ikincisinde Cₘ madde desteği **çözülür**.

### c⁺ ve arşiv

c⁺'ın karakteristik özelliği **arşiv ve koordinasyon** niteliğidir. Cₘ'de üretilen kayıtlar orada mühürlenir ve **zamansal sıralama gerektirmeksizin birlikte bulunur**. "Tüm geçmiş aynı anda mevcut" ifadesi kullanılmaz; çünkü "aynı anda" fiziksel bir zaman kavramıdır.

$$\boxed{\;\text{Cₘ kökenli mühürlü kayıtlar, zamansal sıralama gerektirmeksizin birlikte bulunur.}\;}$$

```latex
\boxed{\;\text{Cₘ kökenli mühürlü kayıtlar, zamansal sıralama gerektirmeksizin birlikte bulunur.}\;}
```

Birlikte bulunmak, Cₘ'den erişilebilir olmak demek değildir; Cₘ'den erişim açık okuma yasasına bağlıdır (15.2).

### c⁺'ta zaman

c⁺'ta zaman ve zamana bağlı hiçbir kısıt yoktur. Bu, c₀'daki "henüz kurulmamış" yokluktan farklı bir yokluktur: c⁺'ta Cₘ'de kurulmuş olan zaman **çözünmüştür**. "$dt_{c^+}=0$" yazımı, c₀'daki gibi yalnız pedagojik bir kısaltmadır; ontolojik ifade $\bot_+$'tır ve $\bot_+$ sayısal sıfır değildir.

$$T(c^+)=\bot_+,\qquad \mathcal G_{C_m}\big|_{c^+}=\bot_+\neq0,\qquad dt_{c^+}=0\ \ (\text{yalnız pedagojik kısaltma}),\qquad \bot_0\neq\bot_+\neq0$$

```latex
T(c^+)=\bot_+,\qquad \mathcal G_{C_m}\big|_{c^+}=\bot_+\neq0,\qquad dt_{c^+}=0\ \ (\text{yalnız pedagojik kısaltma}),\qquad \bot_0\neq\bot_+\neq0
```

| Sembol | Anlamı |
|---|---|
| $T(c^+)$ | c⁺'taki fiziksel zaman |
| $\mathcal G_{C_m}$ | Cₘ'deki ayırt edilebilir değişim yapısı (7.2) |
| $\bot_0$, $\bot_+$ | c₀'daki "henüz kurulmamış" ve c⁺'taki "çözünmüş" yokluk |

### c⁺ ve ışık hızı

c⁺'ın ışık hızıyla ilişkisi üç cümleyle kilitlenir:

$$\boxed{\;c^+,\ \text{Cₘ'nin } c\text{-sınırlı uzay-zaman rejiminin ötesindeki } c\text{-ötesi ontolojik fazdır.}\;}$$

```latex
\boxed{\;c^+,\ \text{Cₘ'nin } c\text{-sınırlı uzay-zaman rejiminin ötesindeki } c\text{-ötesi ontolojik fazdır.}\;}
```

$$\boxed{\;c^+\text{'ın } c\text{-ötesi olması} \;\not\equiv\; \text{Cₘ-tipi } v_{c^+}=\frac{dx}{dt}>c\;}$$

```latex
\boxed{\;c^+\text{'ın } c\text{-ötesi olması} \;\not\equiv\; \text{Cₘ-tipi } v_{c^+}=\frac{dx}{dt}>c\;}
```

$$\boxed{\;c\text{-ötesi ontolojik rejim} \;\neq\; \text{Cₘ içinde ölçülen sıradan ışık-üstü madde hareketi}\;}$$

```latex
\boxed{\;c\text{-ötesi ontolojik rejim} \;\neq\; \text{Cₘ içinde ölçülen sıradan ışık-üstü madde hareketi}\;}
```

İkinci ve üçüncü cümlenin nedeni şudur: c⁺'ta Cₘ'ye özgü fiziksel zaman, üç boyutlu Öklid uzayı, metrik ve farklılaşmış madde desteği çözünmüştür; dolayısıyla orada $dx/dt$ biçiminde bir Cₘ hızı tanımlı değildir. Yazarın hükmü şudur: **c⁺, $0<v<c$ bandının dışında, ışık hızı eşiğinin aşılmasıyla madde yapısının korunamadığı üst fazdır; aynı zamanda Cₘ'de oluşmuş zamansal kayıt ve sıra bilgisinin mühürlendiği zamansız fazdır; fiziksel zamanın kendisi c⁺'ta yoktur.** c⁺, $U_0$ doğuşunda c₀ ve Cₘ ile aynı kuruluşta birlikte oluşur (2.8). Açık kalan yalnız $c$-ötesiliğin nihai matematiksel temsilidir. Belgenin diğer bölümlerinde c⁺ ve hız üzerine geçen ifadeler bu hükme göre okunur.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | c⁺'ın "ışık hızının ötesinde" olmasının ne anlama geldiğini kesinleştirir |
| **Neden yapıyor?** | "Işıktan hızlı madde" okuması hem ölçümlerle hem c⁺'ta zaman ve uzayın olmamasıyla çelişirdi |
| **Nasıl yapıyor?** | $c$-ötesiliği bir rejim farkı olarak tanımlar; Cₘ tipi hız ifadesinin c⁺'a uygulanamayacağını yazar |
| **Ne sonuç bekleniyor?** | $c$-ötesiliğin nihai matematiksel temsilinin kurulması |
| **Ne sonuç elde ediliyor?** | Üç kilit cümle kanondur; matematiksel temsil açıktır |

### c⁺ ≡ vakum, c⁺ ≠ gelecek

$$\boxed{\;c^+\equiv\text{Karanlık Madde}\equiv\text{Karanlık Enerji}\equiv\text{Vakum}\qquad c^+\neq\text{gelecek}\;}$$

```latex
\boxed{\;c^+\equiv\text{Karanlık Madde}\equiv\text{Karanlık Enerji}\equiv\text{Vakum}\qquad c^+\neq\text{gelecek}\;}
```

**Yazar hükmü — c⁺ vakuma denktir.** Ontolojik olarak c⁺ vakumun kendisidir. Kuantum alan kuramının "vakum durumu" ve onunla yapılan hesaplar, bu kimliğin **Cₘ içindeki hesap dilidir**; vakumda ölçülen her etki (örneğin Casimir kuvveti) koşulsuz kabul edilir ve Evertophy'de c⁺'ın Cₘ'deki okuması olarak yorumlanır. **Temsil ile temsil edilen ayrı katmanlardır:** kuantum alan kuramının vakum durumu $|0\rangle$ ve vakum enerjisi hesapları bir Cₘ hesap temsilidir; temsil ettikleri ontolojik nesne c⁺'tır. Bu ayrım kimliği zayıflatmaz (üçüncü ilke): c⁺ ≡ vakum bir ontolojik kimliktir, $|0\rangle$ ise onun Cₘ'deki matematiksel temsilidir.

**Yazar hükmü — atom içi boşluk.** Atomu oluşturan parçacıkların arasındaki boşluk dahi c⁺'tır. c⁺'ta üç boyutlu uzay çözünmüş olduğundan "c⁺ bir yerde bulunur" demek doğru değildir; doğru ifade, Cₘ'nin "boşluk" olarak okuduğu her bölgenin c⁺'ın Cₘ'deki okuması olduğudur. Bu hüküm atom fiziğinin ölçülmüş sonuçlarını değiştirmez; kuantum mekaniğinin atom içi öngörüleri Cₘ hesap dili olarak aynen geçerlidir.

$$\boxed{\;C_m\text{ ekranında "boşluk" okunan her bölge — galaksiler arası boşluktan atom içi parçacıklar arası boşluğa kadar — }c^+\text{'ın }C_m\text{ okumasıdır.}\;}$$

```latex
\boxed{\;C_m\text{ ekranında "boşluk" okunan her bölge — galaksiler arası boşluktan atom içi parçacıklar arası boşluğa kadar — }c^+\text{'ın }C_m\text{ okumasıdır.}\;}
```

c⁺ bir kehanet kaynağı ya da kontrol edilebilir bir ışık-üstü iletişim kanalı da değildir.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | c⁺'ın vakumla ve maddenin içindeki boşlukla ilişkisini tanımlar |
| **Neden yapıyor?** | Karanlık sektörün, vakumun ve madde içi boşluğun ayrı ayrı açıklanması gereken şeyler gibi görünmesi, aynı fazın farklı okumalarını gizliyordu |
| **Nasıl yapıyor?** | c⁺'ı ontolojik olarak vakuma denk tutar; QFT vakum hesaplarını bu kimliğin Cₘ hesap dili olarak konumlar; Cₘ'nin "boşluk" okuduğu her yeri c⁺'ın okuması sayar |
| **Ne sonuç bekleniyor?** | Vakum etkileri, karanlık madde ve karanlık enerji okumalarının tek bir faz kimliği altında nicel olarak bağlanması |
| **Ne sonuç elde ediliyor?** | Kimlik ve atom içi boşluk hükmü yazar hükmüdür; her gözlemsel olgu için nicel mekanizma açıktır (11.2) |

### Tarihsel dil

Şunlar **tarihsel ya da analojiktir**, güncel çekirdek değildir: "evren kozası" · "graf durumu" · "dış kabuk" · "iç uzaya sızan doku".

## 3.5 Faz topolojisi — tam çift yönlü üçgen

$$\boxed{\;c_0 \leftrightarrow C_m, \qquad C_m \leftrightarrow c^+, \qquad c_0 \leftrightarrow c^+\;}$$

```latex
\boxed{\;c_0 \leftrightarrow C_m, \qquad C_m \leftrightarrow c^+, \qquad c_0 \leftrightarrow c^+\;}
```

**Tam çift yönlü üçgen (K3), güncel topolojidir.** Eski zincir modeli ($c_0 \rightleftarrows C_m \rightleftarrows c^+$, "atlama yok" anlamında) güncel topoloji değildir; zincir tarihsel bir gösterimdir.

$$\boxed{\;\text{Cₘ EPİSTEMİK / ÖLÇÜM merkezidir — TOPOLOJİK olarak zorunlu aracı DEĞİLDİR.}\;}$$

```latex
\boxed{\;\text{Cₘ EPİSTEMİK / ÖLÇÜM merkezidir — TOPOLOJİK olarak zorunlu aracı DEĞİLDİR.}\;}
```

### Kapı ve damga

$$\boxed{\;\text{KAPI ÜÇ KENARDA DA ÇİFT YÖNLÜDÜR. Tersinmezlik faz kapısında değil, MÜHÜRLEME EYLEMİNDE yaşanır.}\;}$$

```latex
\boxed{\;\text{KAPI ÜÇ KENARDA DA ÇİFT YÖNLÜDÜR. Tersinmezlik faz kapısında değil, MÜHÜRLEME EYLEMİNDE yaşanır.}\;}
```

Zaman oku, geçiş yönünden değil, **kayıt ve mühür birikimiyle** ilişkilendirilir: kayıt kanalı tek yönlüdür (Cₘ → c⁺) ve mühür sabittir (yazar hükmü, 7.1). Bu ilişkinin fiziksel türetimi henüz kurulmamıştır (7.8, 16.7).

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Üç faz arasındaki bağlantı yapısını tanımlar |
| **Neden yapıyor?** | Eski zincir modeli c₀ ile c⁺ arasında doğrudan bir ilişkiye yer bırakmıyor ve Cₘ'yi zorunlu bir ara durak yapıyordu |
| **Nasıl yapıyor?** | Her fazı diğer ikisine çift yönlü bir kapıyla bağlar; tersinmezliği kapıdan alıp mühürlemeye verir |
| **Ne sonuç bekleniyor?** | Kapı, taşıma ve okuma kavramlarının bu topoloji üzerinde tutarlı biçimde kurulması (13.1a) |
| **Ne sonuç elde ediliyor?** | Tam üçgen kanondur ve biçimsel olarak kodlanmıştır; üçgen yazarın verdiği yapıdır, doğadan türetilmiş değildir |

## 3.6 Faz karışımı — zorunlu bir model değildir

Bir bölgenin birden fazla fazdan pay taşıdığı karışım modelleri arşivde bulunur:

$$\sum_i \sigma_i = 1,\qquad i\in\{0,\ m,\ +\}$$

```latex
\sum_i \sigma_i = 1,\qquad i\in\{0,\ m,\ +\}
```

| Sembol | Anlamı |
|---|---|
| $\sigma_i$ | Bir bölgenin $i$ fazına ait payı (model) |

$$\boxed{\;\text{Karışım-simpleks modeli, güncel ontolojinin ZORUNLU parçası DEĞİLDİR. Tam üçgen ontolojisi bundan bağımsızdır.}\;}$$

```latex
\boxed{\;\text{Karışım-simpleks modeli, güncel ontolojinin ZORUNLU parçası DEĞİLDİR. Tam üçgen ontolojisi bundan bağımsızdır.}\;}
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bir bölgeyi üç fazın payları üzerinden temsil eder |
| **Neden yapıyor?** | Bazı hesaplarda bir bölgenin "hangi faza ne kadar yakın" olduğunu özetlemek yararlıdır |
| **Nasıl yapıyor?** | Payları toplamı 1 olan kesirlerle yazar |
| **Ne sonuç bekleniyor?** | Temsil aracı olarak kullanılması |
| **Ne sonuç elde ediliyor?** | Model ya da temsil aracıdır; ontolojik gereklilik olarak dayatılamaz ve "aynı anda üç faz üyeliği" anlamına gelmez (3.10) |

## 3.7 Harita konumu ≠ faz üyeliği

$$\boxed{\;\text{HARİTA KONUMU} \;\neq\; \text{FAZ ÜYELİĞİ}\;}$$

```latex
\boxed{\;\text{HARİTA KONUMU} \;\neq\; \text{FAZ ÜYELİĞİ}\;}
```

**Örnek.** Atom altı hızlı parçacıklar **Cₘ yasalarına** tabidir. Faz haritasında c⁺ komşuluğunda görünmeleri onları c⁺ üyesi yapmaz. Harita konumu, bir nesnenin hangi rejime **yaklaştığını** gösterir; hangi fazın üyesi olduğunu değil.

## 3.8 $U_x$ — üçlü faz sisteminin bütünsel gösterimi

> **Tarihsel kaynak kaydı.** Aşağıdaki ilişki arşivdeki kapanış kaydından gelir. Güncel topoloji tam çift yönlü üçgendir (Bölüm 3.5); $U_x$'in güncel tanımı Bölüm 2.7'dedir.

$$\boxed{\;U_0\;\leftrightarrow\;[c_0,\ C_m,\ c^+]_{K_3}\;\equiv\;U_x\;}$$

```latex
\boxed{\;U_0\;\leftrightarrow\;[c_0,\ C_m,\ c^+]_{K_3}\;\equiv\;U_x\;}
```

| Sembol | Anlamı |
|---|---|
| $[c_0, C_m, c^+]_{K_3}$ | Tam çift yönlü üçgenle bağlı üç faz |
| $\equiv$ | "Bütünsel olarak bunu gösterir" — küme-teorik bir tip ataması değil |

Bu sürümde güvenle sabitlenen asgari anlam şudur:

$$\boxed{\;U_x = \text{üç fazın birlikte gerçekleştiği bütünsel Dinamik Evren}\;}$$

```latex
\boxed{\;U_x = \text{üç fazın birlikte gerçekleştiği bütünsel Dinamik Evren}\;}
```

$U_x$, üçlü faz sisteminin **bütünsel gösterimidir**: faz üçgeninde dördüncü bir faz ya da yeni bir düğüm değildir; global ontoloji katmanında bir **global düğümdür**. $X(x)$'in başka bir adı da değildir:

$$U_x\neq U_0,\qquad U_x\neq X(x),\qquad X\notin\{c_0,C_m,c^+\}$$

```latex
U_x\neq U_0,\qquad U_x\neq X(x),\qquad X\notin\{c_0,C_m,c^+\}
```

Bu kayıt, $U_0$ ile $U_x$ arasındaki ilişkinin tam ontolojik anlamını tek başına kapatmaz; $\leftrightarrow$ ile $\equiv$ aynı ilişki değildir. "$U_0$ yalnız doğuran ön katmandır, $U_x$ yalnız doğmuş sistemdir" yorumu makul olsa da bu sürümde ek bir kanon tanımı yapılmaz; ilişkinin tam anlamı **açık borçtur**.

Çekirdek görselde c₀'ın tepeye yerleştirilmesi ile Cₘ'nin "epistemik / ölçüm merkezi" olarak anılması farklı gösterim katmanlarıdır: ilki çizim düzeni, ikincisi ölçüm konumudur; hiçbiri yeni bir topolojik merkez tanımlamaz.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Üç fazın bütününü tek bir global nesne olarak gösterir |
| **Neden yapıyor?** | Dinamik Evren'in fazlardan ayrı bir global düğüm olduğu açıkça yazılmalıdır |
| **Nasıl yapıyor?** | Üçgen yapıyı $U_x$ adıyla toplar; $U_0$, $X$ ve fazlardan ayırır |
| **Ne sonuç bekleniyor?** | $U_x$'in yapısal tipinin (kapsama mı, üyelik mi) belirlenmesi |
| **Ne sonuç elde ediliyor?** | Asgari anlam kuruludur; tip ve $U_0$–$U_x$ ilişkisinin tam anlamı açıktır |

## 3.9 Tarihsel alternatif faz anlatıları kaydı

Çerçevenin erken katmanlarında faz zinciri için farklı sıralamalar ve eşlemeler denenmiştir. Bunlar güncel ontolojiyle çelişir ve koruma cümleleriyle kayıtlıdır:

| Tarihsel yazım | Güncel karşılık |
|---|---|
| Zincir sıralaması varyantları (c₀ ⇄ Cₘ ⇄ c⁺ dışı dizilimler) | Güncel faz topolojisi tam çift yönlü K3'tür: c₀ ↔ Cₘ, Cₘ ↔ c⁺ ve c₀ ↔ c⁺. Cₘ ölçüm ve epistemik merkezdir; topolojik zorunlu aracı değildir. Doğrusal yazım tarihsel ya da pedagojik kısaltmadır |
| "c₀ merkez / çatı" dili | Geri çekildi: c₀ yerel ve tekrarlanabilir bir fazdır; merkez metaforu topolojik bir vurgu değildir |
| "Kara delik = c⁺" okuması | Reddedildi. Güncel: kara delik ≡ c₀ — yazarın ontolojik tanımı; nicel ve gözlemsel köprü ayrıca türetilmelidir (3.2) |
| "$U_0$ = c₀ fazının evren ölçeğindeki eşiği" | Güncel: $U_0$ ön katmandır; eşik, uç fazın global kutupla temas ettiği sınırdadır — kaynak değildir |
| "Big Bang = c₀ → Cₘ sıradan geçişi" | Güncel: Big Bang, global $U_x$'in $U_0$ sınırındaki kritik eşiği aşmasıyla üç fazın aynı kuruluşta birlikte doğuşudur |

## 3.10 Faz kompozisyon kesirleri — statü kaydı

Faz kompozisyonu için $\sum\sigma_i=1$ normalizasyonlu kesir gösterimi arşivde iki ayrı katmanda geçer:

| Katman | Gösterim | Statü |
|---|---|---|
| Karışım-simpleks modeli | Bölge payları $\sigma_i$, $\sum\sigma_i=1$ | Model / temsil aracı — ontolojik zorunluluk değil (3.6) |
| Ana düzenleyici gerçeklemesi | $\Phi(x)\mapsto(\sigma_0,\sigma_m,\sigma_+)$, faz koordinatı ailesi | Biçimsel aday — tipi kapanmamış |

$$\boxed{\;\text{Kesir gösterimi "aynı anda üç fazın üyesi" anlamına gelmez; faz üyeliği ile fazlar arası kısıt ilişkisi ayrıdır.}\;}$$

```latex
\boxed{\;\text{Kesir gösterimi "aynı anda üç fazın üyesi" anlamına gelmez; faz üyeliği ile fazlar arası kısıt ilişkisi ayrıdır.}\;}
```

Ana alan vektörü için şu kilit arşivde açıkça kayıtlıdır:

$$x_E\equiv(z,\ a,\ \rho,\ A,\ \mathcal S;\ \tau),\qquad t\notin x_E$$

```latex
x_E\equiv(z,\ a,\ \rho,\ A,\ \mathcal S;\ \tau),\qquad t\notin x_E
```

| Sembol | Anlamı |
|---|---|
| $x_E$ | Ana alan (domain) vektörü |
| $z$, $a$ | Kırmızıya kayma ve ölçek çarpanı |
| $\rho$, $A$, $\mathcal S$ | Yoğunluk, alan, entropi yoğunluğu |
| $\tau$ | Biçimsel sıralama parametresi |
| $t$ | Fiziksel zaman — alan girdisi değil, çözümün Cₘ okumasıdır |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Faz kesirlerinin ve alan vektörünün statüsünü kaydeder |
| **Neden yapıyor?** | Kesirli gösterimler "aynı anda üç fazda bulunma" gibi yanlış okunabilir; zamanın bir girdi gibi kullanılması da ontolojiyle çelişir |
| **Nasıl yapıyor?** | Kesirleri temsil aracı olarak sınıflar; zamanı alan vektörünün dışında tutar |
| **Ne sonuç bekleniyor?** | Ana düzenleyici gerçeklemesinin tipinin kapanması |
| **Ne sonuç elde ediliyor?** | "Zaman girdi değildir" kilidi kayıtlıdır; faz koordinatı ailesi biçimsel aday olarak kalır |

## 3.11 c⁺ nedensellik zırhı

c⁺'ın nedensellikle ilişkisi katman katman korunur:

$$\boxed{\;\text{c⁺ nedenselliği gevşetir; nedenselliği kaldırmaz.}\;}$$

```latex
\boxed{\;\text{c⁺ nedenselliği gevşetir; nedenselliği kaldırmaz.}\;}
```

| Faz | Nedensellik durumu | Ölçüm durumu |
|---|---|---|
| c₀ | Ölçüm öncesi — nedensellik henüz kurulmamış | Ölçüm kavramı kabul edilebilir değil |
| Cₘ | Nedensellik zorunlu ve sıralı | Ölçüm zorunlu |
| c⁺ | İlişki var ama **zamansız**; korelasyon fazı | Ölçüm sonrası serbestlik — sinyal kanalı değil |

Arşivdeki kilitli cümle şudur: *"Nedensellik, c⁺'taki zamansız korelasyonların Cₘ'de ölçümle sıraya konmuş izdüşümüdür."* Dolanıklık bu çerçevede en fazla "faz korelasyonunun Cₘ izdüşümü" olarak okunur; bu bir aday yorumdur, türetim değildir. Bu aday okumada c⁺ kaynaklı karanlık sektör etkileri Cₘ'de kütleçekimsel ve metrik kanallarla ele alınır; bu, c⁺'a içsel metrik ya da durgun kütle eklemez ve "yalnız çekim üzerinden etkileşme"yi türetilmiş evrensel bir mekanizma olarak sunmaz. Ontolojik **c⁺ ≡ karanlık madde ≡ karanlık enerji ≡ vakum** kimliği korunur; nicel bağlaşım ve gözlemsel okuma haritası açıktır.




# BÖLÜM 4 — $X(x)$: DİNAMİK ÜST ÇÖZÜCÜ

## 4.1 Güncel tanım

$$\boxed{\;X(x) \;=\; \textbf{dinamik üst / meta ÇÖZÜCÜ (resolver)}\;}$$

```latex
\boxed{\;X(x) \;=\; \textbf{dinamik üst / meta ÇÖZÜCÜ (resolver)}\;}
```

**$X(x)$ (Dinamik Üst Çözücü):** Verili koşullar altında hangi faz rejiminin geçerli olduğunu ve hangi durumların kabul edilebilir olduğunu **çözen**, aşamalı bir meta-çözücüdür. $X$'ten skaler okumalar üretilebilir; ama $X$ gerçek fizik yasasını, kurucu haritayı ya da fiziksel katsayıyı **tek başına seçmez**. Bu seçim, açık fiziksel seçici borcudur (24.1). Çözümün Cₘ'deki bir okumaya ulaşana kadar izlediği yol şudur:

$$\text{Bağlam} \to \text{Faz lisansı} \to X_{\rm resolved} \to \xi_k \to \text{Fiziksel seçici} \to J_X/\mathcal E_\phi \to \text{Cₘ durumu ve okuma}$$

```latex
\text{Bağlam} \to \text{Faz lisansı} \to X_{\rm resolved} \to \xi_k \to \text{Fiziksel seçici} \to J_X/\mathcal E_\phi \to \text{Cₘ durumu ve okuma}
```

| Sembol | Anlamı |
|---|---|
| Faz lisansı | Hangi yapının hangi fazda tanımlı olduğuna dair izin |
| $X_{\rm resolved}$ | $X$'in çözülmüş durumu |
| $\xi_k$ | $X$'in $k$-ıncı skaler okuması, $\xi_k=\pi_k(X)$ (6.5) |
| Fiziksel seçici | Köprüyü tekil kılan, henüz bulunmamış fiziksel ilke |
| $J_X$, $\mathcal E_\phi$ | $X$'ten Cₘ'deki fiziksel niceliklere giden köprü |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | $X$'in çözdüğü şeyi ve çözümün Cₘ'deki okumaya giden yolunu gösterir |
| **Neden yapıyor?** | $X$'in "her şeyi belirleyen sayı" gibi okunması, fiziksel seçici borcunu gizlerdi |
| **Nasıl yapıyor?** | Zinciri aşamalara ayırır: bağlam → faz lisansı → çözülmüş $X$ → okuma → fiziksel seçici → köprü → Cₘ okuması |
| **Ne sonuç bekleniyor?** | Fiziksel seçici bulunduğunda zincirin gözlenebilir değerlere kadar kapanması |
| **Ne sonuç elde ediliyor?** | Zincirin ilk aşamaları ontolojik olarak kuruludur; fiziksel seçici ve köprü açıktır (14 no-go sonucu, 24.1) |

### Özellikleri

| Özellik | Anlamı |
|---|---|
| **Tek** | Bir tane $X$ vardır; alt-$X$'lere bölünmez |
| **Faza duyarlı** | Hangi fazda olduğunu bilir |
| **Aralığa duyarlı** | Çıktısı aralık değerli olabilir |
| **Bağlama duyarlı** | Koşullara göre farklı çözer |
| **Değişken arite** | Argüman sayısı faza ve rejime göre değişebilir |
| **Deterministik** | Tam belirtilmiş aynı durum aynı çıktıyı verir |
| **Özyinelemeli / bileşimsel olabilir** | Alt ölçekleri içerebilir |
| **Zaman gerektirmez** | İçsel fiziksel zamana ihtiyaç duymaz |

### Determinizm güvencesi

$$\boxed{\;S_1 = S_2 \;\Longrightarrow\; X(S_1) = X(S_2)\;}$$

```latex
\boxed{\;S_1 = S_2 \;\Longrightarrow\; X(S_1) = X(S_2)\;}
```

| Sembol | Anlamı |
|---|---|
| $S_1$, $S_2$ | Tam belirtilmiş iki durum (faz, rejim ve bağlam bilgisinin tamamı) |

Tam belirtilmiş aynı durum, aynı çözümü verir. Buradaki "durum", ilgili faz, rejim ve bağlam bilgisinin tamamını kapsar; kaynak kaydı ya da geçmiş fiziksel olarak ilgiliyse durum tanımına dahil edilebilir. Bu yüzden ilke bir Markov aksiyomu değildir ve $X$'in "dinamik" olmasıyla çelişmez.

## 4.2 $X$ ne değildir

$$\boxed{\;X \;\neq\; \text{Çekim Kuvveti} \quad X \;\neq\; \text{kütleçekim} \quad X \;\neq\; \text{metrik} \quad X \;\neq\; \text{tek skaler} \quad X \;\neq\; \text{lojistik fonksiyon}\;}$$

```latex
\boxed{\;X \;\neq\; \text{Çekim Kuvveti} \quad X \;\neq\; \text{kütleçekim} \quad X \;\neq\; \text{metrik} \quad X \;\neq\; \text{tek skaler} \quad X \;\neq\; \text{lojistik fonksiyon}\;}
```

Ayrıca $X$:

- **faz-parametre matrisinin bir satırı değildir**; matrisin **üst çözücüsüdür**,
- **özelliklerin ortalaması ya da toplamı değildir**,
- **$[0,1]$ aralığıyla sınırlı değildir**,
- **yalnız bir izin filtresi değildir**; filtreleme yaptığı işlerden biridir, tanımı değildir,
- bir **kuvvet ya da enerji taşıyıcısı değildir**.

### Tarihsel lojistik çekirdek

Arşivde şu biçim bulunur:

$$X(u) = \frac{1}{1 + e^{-s(u - u_t)}}, \qquad \frac{dX}{du} = s\,X(1-X)$$

```latex
X(u) = \frac{1}{1 + e^{-s(u - u_t)}}, \qquad \frac{dX}{du} = s\,X(1-X)
```

| Sembol | Anlamı |
|---|---|
| $u$ | Tarihsel süreç koordinatı |
| $s$ | Geçişin dikliği |
| $u_t$ | Geçiş noktası |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Eski metinlerde $X$'i 0 ile 1 arasında yumuşak bir geçiş eğrisi olarak modelliyordu |
| **Neden yapıyor?** | Faz geçişlerini basit, hesaplanabilir bir fenomenolojik eğriyle temsil etmek için |
| **Nasıl yapıyor?** | Lojistik (sigmoid) fonksiyon ve onun türev denklemiyle |
| **Ne sonuç bekleniyor?** | Model düzeyinde geçiş davranışının taklit edilmesi |
| **Ne sonuç elde ediliyor?** | **Tarihsel / fenomenolojik bir skaler çekirdektir; güncel ontolojik tanım değildir.** $X(u)\neq X(x)$; ikisi karıştırılmamalıdır. "Lojistik temel $X$" emeklidir |

### Tarihsel dualite kaydı — karar bekleyen biçimsel aday

Erken ana arşivde şu "madde–doku / zaman–geometri" dualite biçimi bulunur:

$$\Phi(c^+,C_m,c_0)=\mathrm{T}(z^+,z_m,z_0)$$

```latex
\Phi(c^+,C_m,c_0)=\mathrm{T}(z^+,z_m,z_0)
```

Arşivdeki dinamik denge biçimi de şudur:

$$\Phi\,e^{+i\pi}=\mathrm{T}\,e^{-i\pi}$$

```latex
\Phi\,e^{+i\pi}=\mathrm{T}\,e^{-i\pi}
```

| Sembol | Anlamı |
|---|---|
| $\Phi$ | Tarihsel "madde–doku" tarafı; tipi tamamlanmamış |
| $\mathrm{T}$ | Tarihsel "zaman–geometri" tarafı; tipi tamamlanmamış |
| $z^+$, $z_m$, $z_0$ | Tarihsel faz koordinatları |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Madde ile geometri arasında bir dualite önerir |
| **Neden yapıyor?** | Erken dönemde fazlar arasındaki simetriyi tek bir denklemle yakalama denemesiydi |
| **Nasıl yapıyor?** | İki tarafı birbirine eşitler; ikinci biçimde karşıt faz çarpanları ekler |
| **Ne sonuç bekleniyor?** | Tipler tamamlandığında bir denge yasasına dönüşmesi |
| **Ne sonuç elde ediliyor?** | Güncel $X$ tanımı değildir; $\Phi$ ve $\mathrm{T}$'nin tipleri yoktur. İkinci biçim, $e^{+i\pi}=e^{-i\pi}=-1$ olduğundan cebirsel olarak yalnız $\Phi=\mathrm{T}$'ye indirgenir; yeni bir dinamik yasa türetmez. Buradaki $\Phi$, Bölüm 17'deki $\Phi_\chi$ ile özdeş değildir. Kayıt tarihsel olarak korunur, postülaya yükseltilmez |

## 4.3 Programlama benzetmesi

$X$'in davranışını sezdirmek için tek bir benzetme kullanılır:

```cpp
X = *Resolve(phase, regime, range, conditions, ...);
```

Yani $X$ bir **değer** değil, bir **çözümleme çağrısının sonucudur**: bağlamı alır, o bağlamda geçerli olanı döndürür.

$$\boxed{\;\text{Bu YALNIZCA bir programlama benzetmesidir — matematiksel bir tanım değildir.}\;}$$

```latex
\boxed{\;\text{Bu YALNIZCA bir programlama benzetmesidir — matematiksel bir tanım değildir.}\;}
```

## 4.4 $X$'in belirleyicileri — kapalı bir liste değil

Çalışma listesi yoğunluk, eğrilik ve entropi yoğunluğu gibi nicelikleri içerir. Ama:

$$\boxed{\;\text{Argüman kümesi KAPALI DEĞİLDİR. } X \text{ sabit bir fonksiyon formuna DARALTILAMAZ.}\;}$$

```latex
\boxed{\;\text{Argüman kümesi KAPALI DEĞİLDİR. } X \text{ sabit bir fonksiyon formuna DARALTILAMAZ.}\;}
```

Hız, ölçek, toplam kütle, yük ve yapısal düzenleniş de rol oynayabilir. Dahası, **farklı fazlarda farklı argüman kümeleri** anlamlı olabilir; bu, değişken arite özelliğidir.

### Nihai matematiksel tip bilinçli olarak açıktır

$$\boxed{\;X\text{'in TAM MATEMATİKSEL GERÇEKLEMESİ, BİLİNÇLİ OLARAK AÇIK BIRAKILMIŞTIR.}\;}$$

```latex
\boxed{\;X\text{'in TAM MATEMATİKSEL GERÇEKLEMESİ, BİLİNÇLİ OLARAK AÇIK BIRAKILMIŞTIR.}\;}
```

Bu bir eksiklik itirafı değil, bir **tasarım kararıdır**: erken bir biçim seçimi, çerçeveyi o biçimin sınırlarına hapsederdi.

## 4.4a Biçimsel çözücü arayüzü — tipi erken kilitlemeden

$X$'in kavramsal anlamı açıktır; nihai matematiksel tipi ise bilinçli olarak açık bırakılmıştır. Bu iki durum karıştırılmamalıdır. Tip açısından en güvenli asgari arayüz bir ilişki olarak yazılabilir:

$$\mathrm{Resolve}_X(\phi,\mathcal S,\mathcal I;\mathcal O)$$

```latex
\mathrm{Resolve}_X(\phi,\mathcal S,\mathcal I;\mathcal O)
```

**Aynı tam durum için deterministik çıktı** kuralı şöyle yazılır:

$$\boxed{\;\mathrm{Resolve}_X(s,o_1)\land \mathrm{Resolve}_X(s,o_2)\;\Longrightarrow\;o_1=o_2\;}$$

```latex
\boxed{\;\mathrm{Resolve}_X(s,o_1)\land \mathrm{Resolve}_X(s,o_2)\;\Longrightarrow\;o_1=o_2\;}
```

Gelecekte bir bağımlı fonksiyon gerçeklemesi şu biçimi alabilir:

$$X:(\phi:\mathrm{Faz})\to \mathrm{Bağlam}(\phi)\to \mathrm{Çözülmüş}(\phi)$$

```latex
X:(\phi:\mathrm{Faz})\to \mathrm{Bağlam}(\phi)\to \mathrm{Çözülmüş}(\phi)
```

| Sembol | Anlamı |
|---|---|
| $\phi$ | Faz |
| $\mathcal S$ | Tam durum / koşul bağlamı |
| $\mathcal I$ | İlgili özellik ailesi girdileri |
| $\mathcal O$ | Çözülen çıktı |
| $s$, $o_1$, $o_2$ | Bir durum ve ona karşılık gelen iki olası çıktı |

Tam tanımlanmamış bir durum ya da aralık değerli bir girdi için çıktı da bir aralık ya da ilişki olabilir; tam tanımlanmış kabul edilebilir bir durumda ise çözücü bir fonksiyon gibi davranır:

```text
eksik bilgi                         → ilişki / aralık
tam belirtilmiş kabul edilebilir durum → deterministik çözüm
geçişin çift yönlülüğü              → tam ters olmak zorunda değil
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | $X$'i nihai tipini kilitlemeden biçimsel olarak yazılabilir kılar |
| **Neden yapıyor?** | Erken bir fonksiyon biçimi çerçeveyi sınırlar; ama hiç arayüz olmazsa biçimsel denetim yapılamaz |
| **Nasıl yapıyor?** | $X$'i bir ilişki olarak yazar; tam durumda deterministik çıktı kuralını koyar; eksik bilgide aralık çıktıya izin verir |
| **Ne sonuç bekleniyor?** | İleride bağımlı fonksiyon gibi daha güçlü bir gerçeklemenin seçilebilmesi |
| **Ne sonuç elde ediliyor?** | İlişki arayüzü ve determinizm kuralı kuruludur; bağımlı fonksiyon biçimi biçimsel adaydır, güncel ontolojinin tek zorunlu tipi değildir |

### Denklem seti — Değişken arite ve sabit-nokta kapanışı

$X$'in argümanları (yoğunluk $\rho$, eğrilik $\mathcal{R}$, entropi $\mathcal{S}$) **metrik gerektirir**; ama metrik yalnız Cₘ'de vardır. Üstelik eski yapı döngüseldi: $X$ faz rejimini, faz rejimi metriği, metrik de $X$'in argümanlarını belirliyordu. Bu set iki sorunu birlikte ele alır:

$$X : \bigsqcup_p \mathcal{A}_p \rightharpoonup \mathrm{Çözüm},\qquad \pi_k:\mathrm{Çözüm}\to\mathrm{Aralık}(D_k) \qquad X^* = \mathcal{F}_X\!\left(\mathcal{A}[X^*]\right)$$

```latex
X : \bigsqcup_p \mathcal{A}_p \rightharpoonup \mathrm{Çözüm},\qquad \pi_k:\mathrm{Çözüm}\to\mathrm{Aralık}(D_k) \qquad X^* = \mathcal{F}_X\!\left(\mathcal{A}[X^*]\right)
```

Lojistik oyuncak modelde sabit nokta şöyle incelenir:

$$x = \sigma(a x + c),\quad h(x) = \mathrm{logit}(x) - a x - c,\quad x_\pm = \tfrac12\!\left(1 \pm \sqrt{1 - 4/a}\right)$$

```latex
x = \sigma(a x + c),\quad h(x) = \mathrm{logit}(x) - a x - c,\quad x_\pm = \tfrac12\!\left(1 \pm \sqrt{1 - 4/a}\right)
```

$$a \leq 4 \Rightarrow \text{tek kök (yeterli koşul)}; \qquad a > 4:\ \text{üç kök} \iff c \in \big(g(x_+),\ g(x_-)\big),\ \ g(x) = \mathrm{logit}(x) - a x$$

```latex
a \leq 4 \Rightarrow \text{tek kök (yeterli koşul)}; \qquad a > 4:\ \text{üç kök} \iff c \in \big(g(x_+),\ g(x_-)\big),\ \ g(x) = \mathrm{logit}(x) - a x
```

| Sembol | Anlamı |
|---|---|
| $\mathcal{A}_p$ | $p$ fazında tanımlı argüman kümesi |
| $\bigsqcup_p$ | Fazlar üzerinden ayrık birleşim |
| $\rightharpoonup$ | Kısmi çözüm ilişkisi: $X$ bir aralık değil, çözülmüş bir durum döndürür |
| $\mathrm{Çözüm}$ | Çözülmüş durumlar türü |
| $\pi_k$, $D_k$ | $k$. okuma izdüşümü ve onun değer alanı; aralık değerli olan okumadır, $X$'in kendisi değildir |
| $\mathcal{F}_X$ | $X$'in çözümleyici fonksiyonu |
| $X^*$ | Sabit nokta |
| $\sigma$ | Lojistik fonksiyon |
| $a = \beta k$ | Lojistik geri beslemenin kazancı |
| $c = \beta(b - u_0)$ | Önyargı (bias) |
| $h(x)$ | Sabit-nokta denkleminin sıfır fonksiyonu |
| $x_\pm$ | $h$'nin kritik noktaları |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Metriğe ihtiyaç duyan argümanların yalnız tanımlı oldukları fazda kullanılmasını ve döngüsel tanımın kapanmasını sağlar |
| **Neden yapıyor?** | c₀ ve c⁺'ta tanımsız olan argümanlarla işlem yapmak ve "$X$ metriği, metrik $X$'i belirler" döngüsü tutarsızlık üretiyordu |
| **Nasıl yapıyor?** | $X$'in argüman kümesini faza göre değiştirir (değişken arite); döngüyü bir sabit-nokta denklemi olarak, yani aşamalı bir çözüm olarak yazar; lojistik oyuncakta kaç çözüm olduğunu inceler |
| **Ne sonuç bekleniyor?** | Tanımsız argümanların tip düzeyinde engellenmesi; döngünün kapalı biçime gelmesi |
| **Ne sonuç elde ediliyor?** | Değişken arite kuruludur; aşamalı çözücü çekirdek tercihidir; lojistik sabit nokta modeldir; "lojistik temel $X$" ve "$a\le4 \iff$ tek kök" emeklidir ($a\le4$ yalnız yeterli koşuldur). Çözümün varlığı ve tekliği, seçilen algoritmanın yakınsamasından ayrıdır: tek sabit noktaya rağmen doğrudan bir yineleme yerel olarak kararsız olabilir ($f(x)=\sigma(4-8x)$, $x_*=1/2$, $f'(x_*)=-2$). $X$ için genel algoritmik yakınsama türetim bekler |

## 4.5 Okuma yüzleri

$X$ tek bir nesnedir; nasıl erişildiğine göre farklı yüzler gösterir.

| Yüz | Nedir |
|---|---|
| **Temel durum yüzü** | Faz ve bağlam durumunun çözülen yüzü; fiziksel sabit ya da gözlenebilir değer üretimi ayrıca seçici, köprü ve okuma yasası gerektirir |
| **Alan izdüşümü** | Belirli bir fiziksel alana yansıması |
| **Okuma** | Cₘ'de fiilen ölçülen değer |

### Alan izdüşümleri kapalı bir liste değildir

Belirli alanlara (nükleer, kozmolojik, kronometrik gibi) izdüşümler tanımlanabilir. Ama:

$$\boxed{\;\text{Bu izdüşümler AYRI TEMEL } X\text{'ler DEĞİLDİR ve KAPALI BİR KANONİK LİSTE oluşturmazlar.}\;}$$

```latex
\boxed{\;\text{Bu izdüşümler AYRI TEMEL } X\text{'ler DEĞİLDİR ve KAPALI BİR KANONİK LİSTE oluşturmazlar.}\;}
```

**Tek $X$ vardır.** İzdüşümler, aynı $X$'in farklı alanlardaki gölgeleridir.

### Okuma katmanının sınırı

$$\boxed{\;\text{Okuma katmanında yapılan bir hesap TEMEL BİR SAYI ÜRETEMEZ.}\;}$$

```latex
\boxed{\;\text{Okuma katmanında yapılan bir hesap TEMEL BİR SAYI ÜRETEMEZ.}\;}
```

Örneğin iki okuma katmanı niceliği arasında tanımsal bir özdeşlik kurmak, birini ötekinden "türetmek" değildir. Bilinmeyen kapanmaz, **yer değiştirir**.

### Tarihsel B-hipotezi — $X$'in okumaya indirgenmesi

Arşivdeki eylem ilkesi tartışmalarında "$X$ temel bir alan değil, çözüm sonrası bir gözlenebilir haritadır" biçiminde bir **B-hipotezi** bulunur. Bu, kaynaklı bir model seçeneğidir; güncel çekirdek tanımı değildir.

$$\boxed{\;X\text{ yalnız bir okuma değildir.}\;}$$

```latex
\boxed{\;X\text{ yalnız bir okuma değildir.}\;}
```

Güncel mimari $X$'in temel durum, alan izdüşümü ve okuma yüzlerini birlikte korur. B-hipotezi ileride bir model karşılaştırmasında sınanabilir; ama $X$'i yalnız okuma katmanına indirgerse çekirdek çözücü tanımıyla çatışır.

## 4.6 $X$ fazlar üstü bir meta-koordinasyon yapısıdır; fiziksel taşıyıcı değildir

$$\boxed{\;\mathrm{MetaCrossPermission}(X) = \text{true},\qquad \mathrm{MetaCrossPermission} \neq \mathrm{TransportPermission}\;}$$

```latex
\boxed{\;\mathrm{MetaCrossPermission}(X) = \text{true},\qquad \mathrm{MetaCrossPermission} \neq \mathrm{TransportPermission}\;}
```

| Sembol | Anlamı |
|---|---|
| MetaCrossPermission | Fazlar arası meta-koordinasyon izni ($X$'e özgü) |
| TransportPermission | Bir niceliğin bir kapıdan fiziksel olarak taşınma izni (13.1a) |

$$\boxed{\;X\text{'in fazlar üstü statüsü YALNIZ boyutsuz olmasından TÜRETİLMEZ.}\;}$$

```latex
\boxed{\;X\text{'in fazlar üstü statüsü YALNIZ boyutsuz olmasından TÜRETİLMEZ.}\;}
```

Boyutsuzluk, fiziksel taşıma için genel bir teorem değildir; bir niceliğin taşınıp taşınamayacağı 13.1a'daki taşıma iznine bağlıdır. $X$ fiziksel bir taşıyıcı değil, bir meta-koordinasyon yapısıdır; boyutsuzluk bu niteliğin bir **sonucu** olabilir, nedeni değildir.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | $X$'in fazlar arasında nasıl "geçebildiğini" tanımlar |
| **Neden yapıyor?** | $X$'in fazlar üstü olması, fiziksel bir niceliğin kapılardan taşınmasıyla karıştırılabilirdi |
| **Nasıl yapıyor?** | Meta-koordinasyon iznini fiziksel taşıma izninden ayrı bir izin olarak tanımlar |
| **Ne sonuç bekleniyor?** | Cₘ'ye özgü niceliklerin $X$ üzerinden "kaçak" taşınmasının engellenmesi |
| **Ne sonuç elde ediliyor?** | Ayrım biçimsel olarak kodlanmıştır: meta-geçiş fiziksel taşıma değildir |

## 4.7 Faz peyzajı

Faz haritasındaki köşeler, $X$'in **rejim örnekleridir**; sabit çapa değerleri değildir. Bir köşeye yaklaşmak, o rejimin kilitleyici etkisinin artması demektir.

$$\boxed{\;\text{Köşeler SABİT DEĞİL, dinamik } X\text{'in FAZ REJİMİ ÖRNEKLERİDİR.}\;}$$

```latex
\boxed{\;\text{Köşeler SABİT DEĞİL, dinamik } X\text{'in FAZ REJİMİ ÖRNEKLERİDİR.}\;}
```

Fiziksel yapıların büyük kısmı — gezegenler, atomlar, elektromanyetik olgular, biyolojik yapılar — hiçbir köşede değil, **üç fazın etkisi altındaki iç bölgede** bulunur (12.3).

## 4.8 Özyinelemeli makro-nesne okuması

$X$, bir nesnenin bulunduğu bağlamı özetleyen **özyinelemeli bir tanımlayıcı** gibi düşünülebilir. Bir atom için bir şeydir; onu içeren molekül için başka; molekülü içeren hücre için başka. Her ölçekte yeniden çözülür ve alt ölçekleri **içerir ama onlara indirgenmez**. Bu bir **benzetmedir**: yapısal sezgi verir, sonuç üretmez.




# BÖLÜM 5 — FAZ-PARAMETRE MATRİSİ

## 5.1 Statü

$$\boxed{\;\text{Faz-parametre matrisi, çerçevenin ÇEKİRDEK yapılarından biridir.}\;}$$

```latex
\boxed{\;\text{Faz-parametre matrisi, çerçevenin ÇEKİRDEK yapılarından biridir.}\;}
```

Bu matris bir seçenek, "riskli bir genişleme" ya da yalnız bir sunum aracı değildir; bir yöntem kararı olarak çekirdeğe aittir. Mendeleyev'in periyodik tablosuyla benzetmenin **doğru** yanı şudur: Mendeleyev elementleri keşfetmedi, **düzenledi**; ve düzen **boşlukları** gösterdi. Faz-parametre matrisi de fiziksel nicelikleri fazlara göre düzenler ve henüz bilinmeyen köprülerin yerini görünür kılar.

## 5.2 Ana mimari

$$\boxed{\;\text{ÖzellikAilesi} \times \text{Faz} \;\longrightarrow\; \text{Aralık} \;\;\text{ya da}\;\; \bot\;}$$

```latex
\boxed{\;\text{ÖzellikAilesi} \times \text{Faz} \;\longrightarrow\; \text{Aralık} \;\;\text{ya da}\;\; \bot\;}
```

| Sembol | Anlamı |
|---|---|
| ÖzellikAilesi | Zaman, metrik, enerji, yoğunluk gibi bir nicelik ailesi |
| Faz | c₀, Cₘ ya da c⁺ |
| Aralık | O fazda niceliğin aldığı değer bandı |
| $\bot$ | O fazda niceliğin kabul edilemez olduğu işareti ($\bot_0$ ya da $\bot_+$) |

Her hücre, bir özellik ailesinin belirli bir fazdaki durumunu verir: ya bir aralık, ya da o fazda **kabul edilemez** işareti.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Her fiziksel nicelik ailesinin her fazdaki durumunu tek bir tabloda düzenler |
| **Neden yapıyor?** | Hangi niceliğin hangi fazda tanımlı olduğunu kayıt altına almadan Cₘ kavramları c₀ ve c⁺'a sızar |
| **Nasıl yapıyor?** | Özellik ailesi ile fazın her bileşimine ya bir aralık ya da bir yokluk işareti atar |
| **Ne sonuç bekleniyor?** | Boş hücrelerin hangi köprülerin türetilmesi gerektiğini göstermesi |
| **Ne sonuç elde ediliyor?** | Mimari çekirdektir; hücrelerin çoğu için sayısal köprü henüz türetilmemiştir |

### $X$ matriste nerede?

$$\boxed{\;X \text{ matrisin BİR SATIRI DEĞİLDİR. } X, \text{ matrisin ÜST ÇÖZÜCÜSÜDÜR.}\;}$$

```latex
\boxed{\;X \text{ matrisin BİR SATIRI DEĞİLDİR. } X, \text{ matrisin ÜST ÇÖZÜCÜSÜDÜR.}\;}
```

Matris $X$'i içermez; $X$ matrisi çözer. Bu yüzden 5.4 tablosunda $X$ satırı yoktur; $X$, tablonun üstündeki çözücü bilgisidir.

## 5.3 Hücre tipleri — beş farklı "boş" ve bir bilgi durumu

| Sembol | Anlamı |
|---|---|
| $0$ | Gerçek sayısal sıfır |
| $[0,0]$ | Geçerli, sıfır genişlikli fiziksel aralık |
| $\texttt{None}$ | Bu geçişte damga üretilmedi ($\text{NoStamp} \neq \text{NoTransition}$) |
| $\bot_0$ | c₀'da: kavram **henüz kurulmamış** — tanımsız |
| $\bot_+$ | c⁺'ta: kavram **çözünmüş** — artık o fazın dilinde yok |

Bunlar birbirine karıştırılmamalıdır. Örneğin c₀'da içsel fiziksel zaman $\bot_0$'dır, $0$ değildir; "sıfır zaman geçti" demek bile bir zaman kavramı gerektirir. c⁺'ta ise zaman $\bot_+$'dır: Cₘ'de kurulmuş olan yapı orada çözünmüştür.

İki yokluğu tek bir $\bot$ altında toplamak bilgi kaybettirir, çünkü **"henüz yok" ile "artık yok" aynı şey değildir.** Bu ayrım, zaman, üç boyutlu uzay ve $c$ sınırının yalnız Cₘ'de geçerli olduğu; c₀'da tanımsız, c⁺'ta çözünmüş olduğu yönündeki yazar hükmünün doğrudan sonucudur. Ayrım biçimsel olarak doğrulanmış ve faza göre indekslenmiş bir değer tipiyle zorlanmıştır: c₀ ya da c⁺ için Cₘ'ye özgü bir değer "mevcut" diye kurulamaz.

$$\boxed{\;\bot_0 \neq \bot_+ \neq 0 \neq [0,0] \neq \texttt{None}\;}$$

```latex
\boxed{\;\bot_0 \neq \bot_+ \neq 0 \neq [0,0] \neq \texttt{None}\;}
```

Bunlardan ayrı bir durum daha vardır: **eksik veri.** Bir niceliği ölçemediğimizde ya da bilmediğimizde, bu o niceliğin ontolojik olarak yok olduğu anlamına gelmez; bu bir **bilgi durumudur**. Eksik veri yukarıdaki beş "boş"tan hiçbiri değildir ve ayrı bir eksende tutulur.

*Okuma kuralı:* Belgede tek başına $\bot$ görüldüğünde, c₀ bağlamında $\bot_0$, c⁺ bağlamında $\bot_+$ olarak okunur.

### 5.3a Nicelik türü ile boyut aynı şey değildir

Bir niceliğin fiziksel boyutu (kütle, uzunluk, zaman) ile ne tür bir nicelik olduğu farklı şeylerdir. Eski bir kayıtta "kütle c⁺'ta taşınır" deniyordu; bu cümle iki şeyi karıştırır. Kütlenin **boyut etiketi** fazdan bağımsız bir etiket olarak her bağlamda görülebilir; ama Cₘ'deki **durgun kütle** Cₘ'ye özgü bir niceliktir ve c⁺'a taşınmaz. Benzer biçimde metrik bir boyut etiketinden türetilmez; metriğin nerede tanımlı olduğu ayrıca belirtilir: yalnız Cₘ'de.

### Denklem seti — İki yokluk, faza göre indekslenmiş değer, global düğümler

Yazarın hükmü şudur: *"Zaman, üç boyutlu Öklid–düz uzay, c faz sınırı ve benzeri temel tanımlar Cₘ'de geçerlidir. Bu yapılar c₀'da tanımsız, c⁺'ta çözünmüştür."* Tek bir $\bot$ bu iki **ontolojik olarak farklı** yokluğu ayırt edemiyordu. Biçimsel çekirdekte bu ayrım şöyle kodlanmıştır:

```lean
inductive CmOnlyValue (α : Type) : Phase → Type
  | undefined0    : CmOnlyValue α .c0
  | presentCm     : α → CmOnlyValue α .Cm
  | dissolvedPlus : CmOnlyValue α .cp
```

| Sembol | Anlamı |
|---|---|
| $\bot_0$ / `undefined0` / `preAdmissible` | c₀: yapı **henüz kurulmamış** |
| $\bot_+$ / `dissolvedPlus` / `dissolved` | c⁺: yapı **çözünmüş** |
| `presentCm` | Cₘ'de mevcut bir değer |
| `CmOnlyValue α p` | Faza göre indekslenmiş değer tipi: yalnız Cₘ'de gerçek bir değer taşıyabilir |
| `Knowledge` | Epistemik durum: `observed` (gözlendi) · `missingData` (eksik veri) · `imputed` (tahmin edildi) |
| `GlobalNode` | $U_0$, $U_x$, $U_+$ |
| `isPole` | $U_0$ ve $U_+$ kutuptur; **$U_x$ değildir** |
| `MetricAdmissible p` | Metrik yalnız Cₘ'de kabul edilebilir |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | İki ontolojik yokluğu, eksik veriyi ve global düğümleri biçimsel olarak birbirinden ayırır |
| **Neden yapıyor?** | Tek bir yokluk işareti, "henüz kurulmamış" (c₀) ile "çözünmüş" (c⁺) arasındaki farkı siliyordu; eksik veri de ontolojik yokluk sanılabiliyordu |
| **Nasıl yapıyor?** | Faza göre indekslenmiş bir tip kurar: c₀'da yalnız "tanımsız", c⁺'ta yalnız "çözünmüş", Cₘ'de gerçek bir değer kurulabilir; bilgi durumunu ayrı bir eksende tutar |
| **Ne sonuç bekleniyor?** | Yanlış fazda Cₘ değeri kurulmasının derleyici düzeyinde imkânsız olması |
| **Ne sonuç elde ediliyor?** | İki ontolojik yokluk ve faza göre indekslenmiş değer çekirdek tercihi olarak biçimsel doğrulanmıştır; "$U_x$ kutup değildir" doğrulanmıştır |

## 5.4 Genişletilmiş örnek matris

Aşağıdaki tablo **nihai bir sayısal tablo değildir**. Amacı özellik ailelerinin kapsamını ve her fazdaki türlerini göstermektir. Bir hücrede sayısal değer yoksa bunun nedeni eksiklik değil, sayısal köprünün henüz türetilmemiş olmasıdır.

| Özellik ailesi | Gösterim | c₀ | Cₘ | c⁺ | Ontolojik not |
|---|---|---|---|---|---|
| İçsel fiziksel zaman | $T(x)$ | $\bot_0$ | Aralık / fiziksel zaman | $\bot_+$ | Zaman yalnız Cₘ'ye özgüdür |
| Nedensellik / hız ailesi | $C(x)$ | Cₘ hız dili $\bot_0$ | $0<v<c$ bandı (çekirdek üyelik hükmü); $v=c$ liminal ortak sınır | Cₘ hız dili $\bot_+$ | c⁺ $c$-ötesi bir rejimdir; Cₘ tipi $dx/dt>c$ uygulanamaz (3.4) |
| Çekim Kuvveti izdüşüm ailesi | $G(x)$, $g(x)$ | Faz rejimi | Ölçülebilir okuma | Üst faz rejimi | $g(x)\neq g_{\mu\nu}$ |
| Metrik | $g_{\mu\nu}$ | $\bot_0$ | Tanımlı | $\bot_+$ | Yalnız Cₘ |
| Topoloji / boyut | $d(x)$ | Metrik dışı | Cₘ geometrisi (3B Öklid temel uzay) | Metrik dışı | "Kaç boyut?" sorusu ayrıca biçimselleştirme ister |
| Enerji | $e(x)$ | Aralık / faza özgü anlam | Ölçülebilir | Cₘ enerji tipi doğrudan taşınmaz; mühürlü pay | $U_x$ düzeyinde muhasebe (16.7a) |
| Ölçek | $s(x)$ | Aralık | Aralık | Aralık | $X$'in bağlam girdilerinden biri olabilir |
| Entropi / düzen | $S(x)$ | Zaman öncesi anlam | Termodinamik okuma | Zamansız kayıt anlamı | Üçü birbirine ham olarak eşit değildir |
| Düzenleme / raporlama | $\Gamma(x)$ | İçsel zaman üretmez | Zaman / okuma katsayısı ailesi | İçsel zaman üretmez | $X$ ile özdeş değildir |
| Empedans | $Z(x)$ | Modele bağlı | Ölçülebilir köprü olabilir | Modele bağlı | Kanal köprüsüne açık |
| Momentum | $p(x)$ | Standart Cₘ tipi $\bot$ / açık | Standart okuma | Standart Cₘ tipi $\bot$ / açık | Fazlar arası aynen taşınmaz |
| Cₘ metrik uzunluğu | $L_{C_m}$ | $\bot_0$ | Aralık | $\bot_+$ | c⁺ için "seyrelmiş uzunluk" kullanılmaz |
| Yoğunluk | $\rho(x)$ | Toplu tek-yapı; $\rho_{c_0}\le\rho_P$ | Fiziksel yoğunluk | Cₘ madde yoğunluğu $\bot_+$ | c₀ için "sonsuz yoğunluk" yoktur |
| Madde | $m(x)$ | Metrik boşluksuz tek-yapı | Farklılaşmış madde | Cₘ madde desteği çözülür | En güçlü faz ayrımlarından biri |
| Boşluk / vakum | — | Metrik boşluksuz tek-yapı | "Boşluk" okuması (atom içi dahil) | c⁺ ≡ vakum | Cₘ'nin boşluk okuduğu her yer c⁺'tır (3.4) |
| Bilgi | $I(x)$ | Potansiyel / zaman öncesi | Ölçülebilir kayıt | Mühürlü kaynak anlamı | Global korunum teoremi açık |
| Kayıt / kaynak (registry / provenance) | $R(x)$ | Arşiv değil | Olay kaynağı olabilir | Mühürlü arşiv rolü | Kayıt = varlık değildir |
| Kuvvet / alan ailesi | $F(x)$ | Faz rejimi | Etkin etkileşimler | Faz rejimi | Çekim Kuvveti'nden izdüşüm türetimi açık |
| Potansiyel / iskele | $\Phi(x)$ | Model / iskele | Cₘ etkin alan kuramı iskelesi | Model / iskele | $X\neq\Phi$ |
| Ayar / kinetik | $Z_B$, $Z_W$, $Z_G$ | Rezerve program | Cₘ etkin alan okuması | Rezerve program | Standart Model makine-1 hedefi |
| Bağlaşımlar | $\alpha_i(x)$ | Köprü açık | Etkin sabitler | Köprü açık | Sayısal türetim yok |
| Sıcaklık | $\mathcal T(x)$ | $\bot_0$ | Termodinamik okuma | $\bot_+$ | $0$ ile $\bot$ ayrılmalı; c₀ ≠ mutlak sıfır |
| Isı | $Q(x)$ | $\bot_0$ | Termodinamik okuma | $\bot_+$ | "Isı yok" otomatik olarak $T=0$ değildir |
| Frekans / saat | $\nu(x)$ | İçsel frekans $\bot_0$ | Ölçülebilir | İçsel frekans $\bot_+$ | Fiziksel periyot Cₘ zamanı gerektirir |
| Basınç / gerilme | $P(x)$ | Faz limiti anlamı | Enerji-momentum okuması | Cₘ basınç tipi $\bot$ / açık | Dış fazlara kendiliğinden taşınmaz |
| Koherans | $\mathcal C(x)$ | Toplu | Kuantum / klasik rejimler | Koordinasyon anlamı | BEC benzetmesi literal değildir |
| Ölçüm | $\mathcal M(x)$ | Doğrudan ölçüm $\bot_0$ | Doğrudan ölçüm | Doğrudan ölçüm $\bot_+$ | Cₘ epistemik merkezdir |
| Arşiv durumu | $A(x)$ | Arşiv değil | Kayıt kaynağı | Mühürlü kaynak fazı | c⁺ bir gelecek kâhini değildir |
| Erişilebilirlik / eşik | $\mathcal A(x)$ | Aralık | Aralık | Aralık | Geçiş iznine bağlanabilir |

Bu satırların bir kısmı yalnız **ayrılmış özellik ailesi** statüsündedir. Matrisin çekirdek oluşu, her satırın bugün sayısal bir yasaya sahip olduğu anlamına gelmez.

## 5.5 Satır listesi açıktır

$$\boxed{\;\text{YÖNTEM KARARI çekirdektir; SATIR SAYISI ve SIRASI açıktır.}\;}$$

```latex
\boxed{\;\text{YÖNTEM KARARI çekirdektir; SATIR SAYISI ve SIRASI açıktır.}\;}
```

Matrisin hangi özellik ailelerini içereceği ve hangi sırayla düzenleneceği kapalı değildir. Bu bir eksiklik değil, tablonun **canlı bir çalışma aracı** olmasının gereğidir.

### Tarihsel derlemelerdeki sayısal değerler

Arşiv taramalarından gelen sayısal katsayılar, doğrudan doğrulanmadıkça matrise girmez. Emekli bir hattan gelen sabitler **geri getirilemez** (Bölüm 21).




# BÖLÜM 6 — ARALIK (RANGE) FORMALİZMİ

## 6.1 Temel sözdizimi

$$\boxed{\;P \in [P^-,\, P^+]\;}$$

```latex
\boxed{\;P \in [P^-,\, P^+]\;}
```

| Sembol | Anlamı |
|---|---|
| $P$ | Herhangi bir fiziksel nicelik |
| $P^-$, $P^+$ | Alt ve üst sınır |

Fiziksel sayısal ifadeler aralık değerlidir. Bu, çerçevenin nicelikleri **nasıl yazdığına** ilişkin bir kuraldır. Ölçümler de, model parametreleri de gerçekte bir bant hâlinde gelir; Evertophy bu bandı gizlemek yerine açıkça taşır.

## 6.2 Sıfır genişlikli aralık tamamen geçerlidir

$$\boxed{\;[P,\,P] \text{ TAMAMEN GEÇERLİ, STATİK ve DETERMİNİSTİK bir fiziksel aralıktır.}\;}$$

```latex
\boxed{\;[P,\,P] \text{ TAMAMEN GEÇERLİ, STATİK ve DETERMİNİSTİK bir fiziksel aralıktır.}\;}
```

Bu, çerçevenin en sık yanlış anlaşılan noktasıdır ve açıkça belirtilmelidir:

| Yanlış okuma | Doğrusu |
|---|---|
| ~~"Noktasal fizik yasaktır"~~ | Aralık değerli sözdizimi kullanılır; $[P,P]$ meşrudur |
| ~~"$[P,P]$ özel bir eşik durumudur"~~ | Özel bir mekanizma **gerekmez** |
| ~~"$[P,P]$ bir Heaviside ya da yapısal tekilliktir"~~ | Böyle bir zorunluluk **yoktur** |
| ~~"Her sabit $X$ ile değişir"~~ | Bir nicelik belirli bir rejimde $[P,P]$ olarak **kalabilir** |

$$\boxed{\;\text{Aralık değerli olmak} \;\nRightarrow\; \text{zamanla değişken olmak.}\;}$$

```latex
\boxed{\;\text{Aralık değerli olmak} \;\nRightarrow\; \text{zamanla değişken olmak.}\;}
```

Bir niceliğin aralık sözdizimiyle yazılması, onun değişken olduğunu **ima etmez**. Statik ve deterministik bir sabit $[P,P]$ olarak yazılır ve bu tamamen doğrudur.

## 6.3 Üç aralık türü

| Sembol | Adı | Nedir |
|---|---|---|
| $\Delta X_{\rm acc}$ | **Kabul aralığı** | Çerçevenin izin verdiği aralık |
| $\Delta X_{\rm pred}$ | **Öngörü aralığı** | Çerçeveden **türetilmiş** aralık |
| $\Delta X_{\rm obs}$ | **Gözlem aralığı** | Veriden gelen aralık |

**Yanlışlama kuralı yalnız öngörü ile gözlem arasında işler:**

$$\boxed{\;\Delta X_{\rm pred} \;\cap\; \Delta X_{\rm obs} = \varnothing \;\Longrightarrow\; \text{yanlışlanmıştır.}\;}$$

```latex
\boxed{\;\Delta X_{\rm pred} \;\cap\; \Delta X_{\rm obs} = \varnothing \;\Longrightarrow\; \text{yanlışlanmıştır.}\;}
```

| Sembol | Anlamı |
|---|---|
| $\cap$ | Kesişim |
| $\varnothing$ | Boş küme |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bir öngörünün ne zaman yanlışlandığını tanımlar |
| **Neden yapıyor?** | Hangi aralıkların karşılaştırılacağı belirsiz kalırsa, iki gözlemin uyuşmazlığı ya da kabul aralığının genişliği yanlışlama sanılabilir |
| **Nasıl yapıyor?** | Türetilmiş öngörü bandı ile gözlem bandını karşılaştırır; kesişim boşsa öngörü yanlışlanmıştır |
| **Ne sonuç bekleniyor?** | Açık, önceden tanımlı bir yanlışlama ölçütü |
| **Ne sonuç elde ediliyor?** | Kural kanondur; iki **gözlem** aralığının uyuşmaması bir teoriyi yanlışlamaz. Sert red yalnız boş kesişimde verilir (21.6) |

## 6.3a Neyin aralık, neyin sabit olduğu — katmanlar

Aralık formalizmi "her şeyi aralığa çevir" demek değildir. Yazarın vurguladığı gibi, bazı denklemlerde aralık değil sabit kullanılır ve bu bir hata değildir. Doğru olan, her büyüklüğün hangi katmana ait olduğunu bilmektir:

| Katman | Örnek | Nasıl taşınır |
|---|---|---|
| Yapısal kesin | $\pi$, faz sayısı 3, sayımlar | Kesin — aralığa çevrilmez |
| Tanımsal nokta | $c_{C_m} = [c,c]$ | Sıfır genişlikli aralık $[P,P]$ |
| Belirsiz ya da değişken fiziksel parametre | $\sigma$, $\beta$, $k$, $\Delta E$, $\eta_{\rm clock}$; kuyu genişliği, bağlaşımlar, enerji yayılımı | Aralık ya da ortak olurluk kümesi |
| Epistemik | Ölçüm belirsizliği | Aralık ya da küme |
| Genişletilmiş | Enerji yayılımı sıfırı içerirse ($\Delta E\ni0$) zaman sınırı $+\infty$'a uzanır | Genişletilmiş uç |
| Faz-yok | c₀ ve c⁺'ta zaman | $\bot_0$ / $\bot_+$ |

Gerçekten sabit alınan bir parametre, bu varsayım açıkça yazılarak sabit kalır; gerekiyorsa $[P,P]$ olarak taşınır. Sabit kullanmak tek başına bir eksiklik, başarısızlık ya da kısmi başarı gerekçesi değildir.

## 6.4 Boşluk yasağı

$$\boxed{\;[0,\infty) \text{ geçerli bir genişletilmiş aralıktır; ama önsel alanı daraltmıyorsa öngörü gücü taşımaz.}\;}$$

```latex
\boxed{\;[0,\infty) \text{ geçerli bir genişletilmiş aralıktır; ama önsel alanı daraltmıyorsa öngörü gücü taşımaz.}\;}
```

Sorun böyle bir aralığın geçersiz olması değil, **bilgi vermemesidir**: her veriyle "uyar" ve bu yüzden ayırt edici bir öngörü bandı sayılmaz. Bir öngörü aralığı **türetilmiş** ve **önsel aralıktan anlamlı biçimde dar** olmalıdır.

## 6.4a Aralık hesabının güvenilirliği

Aralık hesabının temel işlemleri **kesin tam sayı bant katmanında** biçimsel olarak kanıtlanmıştır. Toplama, negatif alma, kesişim ve çarpım güvenlidir: gerçek değerler aralıkların içindeyse, sonuç da sonuç aralığının içindedir. Çarpımda dört köşe kuralı geçerlidir:

$$x\in[a,b],\ y\in[c,d] \;\Rightarrow\; xy \in \big[\min(ac,ad,bc,bd),\ \max(ac,ad,bc,bd)\big]$$

```latex
x\in[a,b],\ y\in[c,d] \;\Rightarrow\; xy \in \big[\min(ac,ad,bc,bd),\ \max(ac,ad,bc,bd)\big]
```

| Sembol | Anlamı |
|---|---|
| $x$, $y$ | Gerçek değerler |
| $[a,b]$, $[c,d]$ | Onları içeren aralıklar |
| `Band` | $\langle lo, hi, \text{valid}: lo\le hi\rangle$ — geçerliliği kanıtlı aralık |
| `mem x b` | $lo\le x\le hi$ |
| `cmin`, `cmax` | Dört köşe çarpımının en küçüğü ve en büyüğü |
| `ZeroExcluded b` | $0<lo$ ya da $hi<0$ — tersi alınabilir aralık |
| `Ext` | $-\infty$ · sonlu · $+\infty$ uç noktaları |

Üç koruma da kuruludur: sıfırı içeren bir aralığın tersi alınamaz; boş küme ile $[0,0]$ farklıdır; $+\infty$ bir uç noktadır, yokluk değildir.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Aralıklarla yapılan hesabın güvenli olduğunu, yani gerçek değeri hiçbir zaman dışarıda bırakmadığını garanti eder |
| **Neden yapıyor?** | Aralığın geçerliliği ($lo\le hi$) ve işlemlerin sağlamlığı kanıtlanmazsa bütün öngörü bantları güvenilmez olur |
| **Nasıl yapıyor?** | Geçerliliği kanıt taşıyan bir bant tipi kurar; toplama, negatif alma, kesişim ve dört köşe çarpımını kesin tam sayı katmanında biçimsel olarak kanıtlar |
| **Ne sonuç bekleniyor?** | Tam bir aralık cebiri: kesin ters alma ve bölme, genişletilmiş uçlarla tam cebir, değişkenler arası bağımlılığın izlenmesi |
| **Ne sonuç elde ediliyor?** | Temel kesin aritmetik çekirdek tercihidir ve kanıtlıdır; tam aralık hesabı kısmen kuruludur. Bu bir ontoloji borcu değil, kütüphane mühendisliği borcudur |

## 6.5 Duyarlılık

$X$ tek bir sayı olmadığı için, bir niceliğin $X$'e duyarlılığı doğrudan $d\ln c/dX$ biçiminde yazılamaz; türev, $X$'in belirli bir okuması üzerinden alınır:

$$S_c^{(k)} \equiv \frac{\partial \ln c}{\partial \xi_k} \in [S^-, S^+], \qquad \xi_k = \pi_k(X)$$

```latex
S_c^{(k)} \equiv \frac{\partial \ln c}{\partial \xi_k} \in [S^-, S^+], \qquad \xi_k = \pi_k(X)
```

Bir geçiş kenarı için de okuma aynı disiplinle yazılır:

$$\xi_{ij} \in \big[\xi^{\rm crit,-}_{ij},\ \xi^{\rm crit,+}_{ij}\big]\ \ (\text{nokta okuma}) \qquad B_{\xi_{ij}} \cap \big[\xi^{\rm crit,-}_{ij},\ \xi^{\rm crit,+}_{ij}\big] \neq \varnothing\ \ (\text{bant okuma})$$

```latex
\xi_{ij} \in \big[\xi^{\rm crit,-}_{ij},\ \xi^{\rm crit,+}_{ij}\big]\ \ (\text{nokta okuma}) \qquad B_{\xi_{ij}} \cap \big[\xi^{\rm crit,-}_{ij},\ \xi^{\rm crit,+}_{ij}\big] \neq \varnothing\ \ (\text{bant okuma})
```

| Sembol | Anlamı |
|---|---|
| $X$ | Skaler olmayan, aşamalı çözücü ($X_{\rm prior}\to X_{\rm resolved}\to X_{\rm read}$) |
| $\pi_k$ | $k$-ıncı okuma izdüşümü |
| $\xi_k$ | $X$'in $k$-ıncı skaler okuması |
| $S_c^{(k)}$ | $c$'nin $\xi_k$'ya duyarlılığı |
| $\xi_{ij}$ | $i\to j$ kenarına özgü okuma |
| $\xi^{\rm crit,\pm}_{ij}$ | O kenarın kritik okuma bandı |
| $B_{\xi_{ij}}$ | Okumanın kendisi bir bant ise o bant |

$S\approx0$ ise nicelik o rejimde pratikte sabittir; bu çerçeveyle tamamen tutarlıdır.

Işık hızı için çekirdek hüküm şudur: Cₘ'de $c$ tanımsal bir nokta aralıktır, $c_{C_m}=[c,c]$; dolayısıyla çekirdekte $c$'nin herhangi bir okumaya duyarlılığı sıfırdır. "Değişen ışık hızı" yalnız etkin bir model büyüklüğü olarak ele alınabilir ve ancak ince yapı sabiti gibi **boyutsuz** gözlenebilirler üzerinden sınanabilir; birim seçimindeki bir değişiklik gözlem sayılmaz.

*Okuma kuralı:* Belgede $X$ üzerinde skaler işlem (türev, ters alma, logaritma, limit) görülen tarihsel ya da model ifadeleri, bir okuma $\xi=\pi(X)$ açıkça tanımlanana kadar çekirdek ifade değil, tarihsel model ya da henüz kurulmamış köprüdür. Yalnız $X$ harfini $\xi$ ile değiştirmek fiziksel köprüyü kurmuş sayılmaz. Sorun, genel olarak vektör ya da tensör türevinin alınamaması değil, **temel $X$ için gereken diferansiyel yapının verilmemiş olmasıdır**.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | $X$'e bağlı her skaler işlemin tanımlı bir okuma üzerinden yapılmasını sağlar |
| **Neden yapıyor?** | Eski kanon $X$'i bazen tek bir sayı gibi karşılaştırıyor ($X(x)>X(0)$) ve türevini alıyordu ($d\ln c/dX$); çok bileşenli bir nesne için bu işlemler tanımsızdır |
| **Nasıl yapıyor?** | Her işlemi bir izdüşüm $\xi_k=\pi_k(X)$ üzerinden yazar; geçiş koşullarında kenara özgü okumayı kullanır |
| **Ne sonuç bekleniyor?** | Fiziksel izdüşüm seçildiğinde duyarlılık ve geçiş koşullarının nicel biçim kazanması |
| **Ne sonuç elde ediliyor?** | İzdüşüm disiplini çekirdek ilkedir; kesin $X$ tipi ve fiziksel izdüşüm açıktır |

## 6.6 Sektör hiyerarşisi türetilmelidir

$$\boxed{\;\text{Hangi sektörün SABİT, hangisinin DEĞİŞKEN olduğu ATANAMAZ — TÜRETİLMELİDİR.}\;}$$

```latex
\boxed{\;\text{Hangi sektörün SABİT, hangisinin DEĞİŞKEN olduğu ATANAMAZ — TÜRETİLMELİDİR.}\;}
```

Aksi hâlde formalizm her sonucu barındırır ve hiçbir şeyi yasaklamaz.

## 6.7 Aralığa güvenli mühürleme

$$\mathrm{Seal}\big([p^-,\,p^+]\big) \;=\; \big(\mathrm{rid},\; [p^-,\,p^+],\; \text{damga}\big)$$

```latex
\mathrm{Seal}\big([p^-,\,p^+]\big) \;=\; \big(\mathrm{rid},\; [p^-,\,p^+],\; \text{damga}\big)
```

| Sembol | Anlamı |
|---|---|
| Seal | Mühürleme işlemi |
| rid | Kaydın tekil kimliği |
| $[p^-,p^+]$ | Kaydın fiziksel içeriği (aralık) |
| damga | Geçişin damga monoidindeki görüntüsü (Bölüm 14) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bir aralık değerli içeriğin nasıl mühürleneceğini tanımlar |
| **Neden yapıyor?** | Mühürlemenin içeriği tek bir noktaya zorlaması, aralık formalizmiyle çelişirdi |
| **Nasıl yapıyor?** | Kayda tekil bir kimlik verir, içeriği aralık olarak bırakır, damgayı ekler |
| **Ne sonuç bekleniyor?** | Kayıt kimliğinin tekil, fiziksel içeriğin dürüstçe bant hâlinde kalması |
| **Ne sonuç elde ediliyor?** | Kayıt kimliği tekildir; içerik aralık kalabilir; $p^-=p^+$ zorlanmaz |




# BÖLÜM 7 — ZAMAN ONTOLOJİSİ

## 7.1 Fiziksel zamanın tek evi

$$\boxed{\;\text{EMERGENT FİZİKSEL ZAMAN, YALNIZ Cₘ'DE BULUNUR.}\;}$$

```latex
\boxed{\;\text{EMERGENT FİZİKSEL ZAMAN, YALNIZ Cₘ'DE BULUNUR.}\;}
```

c₀ zaman-öncesi (pre-emergent) potansiyel / çekirdek fazıdır: zaman orada henüz kurulmamıştır. c⁺ ise zaman-dışı (atemporal) üst / arşiv fazıdır: Cₘ'de kurulmuş zaman orada çözünmüştür. Her iki fazda da Cₘ'ye ait içsel saat, hız, süre ya da fiziksel akış değişkeni kullanılmaz.

$$\boxed{\;t_{c_0}\text{ ve }t_{c^+}\text{ çekirdek ontolojinin değişkenleri değildir:}\quad T(c_0)=\bot_0,\qquad T(c^+)=\bot_+\;}$$

```latex
\boxed{\;t_{c_0}\text{ ve }t_{c^+}\text{ çekirdek ontolojinin değişkenleri değildir:}\quad T(c_0)=\bot_0,\qquad T(c^+)=\bot_+\;}
```

"$dt=0$" ifadesi her iki fazda da yalnız pedagojik bir kısaltma olarak kullanılabilir; ontolojik olarak doğru ifade **"fiziksel zaman bu fazda kabul edilebilir değildir"** biçimidir.

**Yazar hükmü — zamanın yönü.** Zaman yalnız Cₘ'de ve tek yönlüdür; aksi hâlde nedensellik ortadan kalkar, çünkü madde fazında her şey neden–sonuç ilişkisi içindedir. Faz geçişleri çift yönlüdür; zaman mühürleme / kayıt kanalı ise tek yönlüdür (Cₘ → c⁺) ve mühürleme gerçekleştiğinde kayıt sabittir (13.1, 14.1).

$$\text{kapı: } c_i\rightleftarrows c_j\ \ (\text{çift yönlü}),\qquad \text{kayıt kanalı: } C_m\longrightarrow c^+\ \ (\text{tek yönlü; mühür sabit})$$

```latex
\text{kapı: } c_i\rightleftarrows c_j\ \ (\text{çift yönlü}),\qquad \text{kayıt kanalı: } C_m\longrightarrow c^+\ \ (\text{tek yönlü; mühür sabit})
```

| Sembol | Anlamı |
|---|---|
| $c_i$, $c_j$ | Üç fazdan herhangi ikisi (tam çift yönlü üçgen, 3.5) |
| $\rightleftarrows$ | Çift yönlü faz kapısı |
| $C_m\longrightarrow c^+$ | Tek yönlü kayıt / mühürleme kanalı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Zamanın nerede bulunduğunu ve neden tek yönlü olduğunu tanımlar |
| **Neden yapıyor?** | Fazlar arası geçişler çift yönlü olduğu hâlde zamanın tek yönlü deneyimlenmesinin kaynağı açıklanmalıdır |
| **Nasıl yapıyor?** | Tersinmezliği geçişten alıp kayıt kanalına verir: geçiş çift yönlü, kayıt Cₘ → c⁺ yönünde tek yönlü ve sabittir |
| **Ne sonuç bekleniyor?** | Termodinamik zaman okunun ve nedenselliğin bu kayıt yapısıyla nicel olarak ilişkilendirilmesi |
| **Ne sonuç elde ediliyor?** | Zamanın yalnız Cₘ'de ve tek yönlü olması ile kayıt kanalının yönü yazar hükmüdür; nicel türetim açıktır (7.8, 16.7) |

## 7.2 Zaman üretimi — çekirdek iskele

Çekirdekte korunan en genel çalışma biçimi şudur:

$$\boxed{\;dt \;=\; \Gamma\,\mathcal{G}_{C_m}\,d\tau\;}$$

```latex
\boxed{\;dt \;=\; \Gamma\,\mathcal{G}_{C_m}\,d\tau\;}
```

| Sembol | Anlamı |
|---|---|
| $dt$ | Cₘ'de okunan fiziksel zaman aralığı |
| $\Gamma$ | Cₘ okuma / raporlama-düzenleme ailesinin katsayısı |
| $\mathcal{G}_{C_m}$ | Cₘ içinde ölçülebilir değişim ve ayrışma yapısını temsil eden, henüz kapanmamış bir nesne |
| $\tau$ | **Biçimsel sıralama / parametrizasyon değişkeni**; gizli bir temel fiziksel zaman değildir |

$$\boxed{\;\tau \neq \text{temel fiziksel zaman}\;}$$

```latex
\boxed{\;\tau \neq \text{temel fiziksel zaman}\;}
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Zamanın Cₘ'deki ayırt edilebilir değişimden nasıl okunduğunu yazar |
| **Neden yapıyor?** | Zaman temel bir boyut değil, Cₘ'ye özgü emergent bir okumadır; bunun genel bir biçimi gerekir |
| **Nasıl yapıyor?** | Zaman aralığını, Cₘ'deki değişim yapısı ile bir okuma katsayısının çarpımı olarak bir sıralama parametresine bağlar |
| **Ne sonuç bekleniyor?** | $\mathcal{G}_{C_m}$'nin mikrofiziksel tanımı kurulduğunda zamanın nicel olarak üretilmesi |
| **Ne sonuç elde ediliyor?** | İskele çekirdekte korunur; $\mathcal{G}_{C_m}$'nin tekil mikrofiziksel tanımı açıktır |

## 7.3 Normalize gerçekleme — model düzeyi

Boyut muhasebesi gerektiğinde şu normalize biçim kullanılabilir:

$$dt \;=\; \tau_0\,\tilde\Gamma\,\mathcal{G}_{C_m}\,d\lambda$$

```latex
dt \;=\; \tau_0\,\tilde\Gamma\,\mathcal{G}_{C_m}\,d\lambda
```

$$[\lambda]=1,\qquad [\tilde\Gamma]=1,\qquad [\tau_0]=T,\qquad \Gamma\equiv\tau_0\tilde\Gamma\ \Rightarrow\ dt=\Gamma\,\mathcal G_{C_m}\,d\lambda$$

```latex
[\lambda]=1,\qquad [\tilde\Gamma]=1,\qquad [\tau_0]=T,\qquad \Gamma\equiv\tau_0\tilde\Gamma\ \Rightarrow\ dt=\Gamma\,\mathcal G_{C_m}\,d\lambda
```

| Sembol | Anlamı |
|---|---|
| $[\cdot]$ | Fiziksel boyut |
| $T$ | Zaman boyutu |
| $\lambda$ | Boyutsuz sıralama / parametrizasyon değişkeni; fiziksel zaman değildir |
| $\tilde\Gamma$ | Boyutsuz okuma katsayısı |
| $\tau_0$ | Gerçeklemenin zaman ölçeği; zaman boyutunu taşır |

Bir Cₘ kuantum / açık sistem modelinde değişim yapısı bir yoğunluk matrisi normuyla yazılabilir:

$$\mathcal{G}_{C_m} \stackrel{\rm model}{=} \left\|\frac{d\rho_{C_m}}{d\lambda}\right\|$$

```latex
\mathcal{G}_{C_m} \stackrel{\rm model}{=} \left\|\frac{d\rho_{C_m}}{d\lambda}\right\|
```

| Sembol | Anlamı |
|---|---|
| $\rho_{C_m}$ | Cₘ yoğunluk matrisi (model nesnesi; çekirdek ilkel değildir) |
| $\|\cdot\|$ | Aday normlar: iz normu, Hilbert–Schmidt normu, operatör normu |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Zaman iskelesinin boyutsal olarak tutarlı bir gerçeklemesini verir |
| **Neden yapıyor?** | Zaman boyutunun hangi terimde taşındığı belli olmazsa denklem boyutsal olarak tutarsız hâle gelir |
| **Nasıl yapıyor?** | Boyutu yalnız $\tau_0$'a verir; $\lambda$ ve $\tilde\Gamma$'yı boyutsuz tutar; değişim yapısını bir kuantum modelinde yoğunluk matrisinin değişim normuyla yazar |
| **Ne sonuç bekleniyor?** | Fiziksel köprü ve parametrizasyondan bağımsızlık testiyle normun seçilmesi |
| **Ne sonuç elde ediliyor?** | Boyut muhasebesi doğrudur; $\Gamma$ boyutsuz alınırsa $dt$ zaman boyutu taşımaz — bu durum biçimsel tip sisteminde derlenmeyen bir negatif test olarak kayıtlıdır. Bu gerçekleme çekirdek iskelenin **bir** gerçeklemesidir, zorunlu tek biçimi değildir; norm seçilmemiştir |

## 7.4 Parametrizasyon bağımsızlığı — biçimsel aday

Bir gerçeklemede yay uzunluğuna benzer bir nesne kurulabilir:

$$s(\lambda)=\int \left\|\frac{d\rho_{C_m}}{d\lambda}\right\|d\lambda$$

```latex
s(\lambda)=\int \left\|\frac{d\rho_{C_m}}{d\lambda}\right\|d\lambda
```

Bu nesne, sırayı koruyan yeniden parametrizasyonlara karşı değişmez kurulabilir. Yararlı bir tutarlılık testi sağlar; ama seçilen normu ya da $\rho_{C_m}$'nin ontolojik statüsünü tekilleştirmez.

### Aktif akromatiklik — Lorentz uyumlu okuma kısıtı

Ölçüm probunun enerjisinden bağımsızlık tamamen tarihsel değildir. Aynı fiziksel durum $\mathcal S$ ve aynı kabul edilebilir Cₘ okuma rejimi altında:

$$\boxed{\;\left.\frac{\partial X}{\partial E_{\rm probe}}\right|_{\mathcal S}=0,\qquad \left.\frac{\partial\Gamma}{\partial E_{\rm probe}}\right|_{\mathcal S}=0\;}$$

```latex
\boxed{\;\left.\frac{\partial X}{\partial E_{\rm probe}}\right|_{\mathcal S}=0,\qquad \left.\frac{\partial\Gamma}{\partial E_{\rm probe}}\right|_{\mathcal S}=0\;}
```

| Sembol | Anlamı |
|---|---|
| $E_{\rm probe}$ | Ölçüm probunun enerjisi |
| $\mathcal S$ | Sabit tutulan fiziksel durum |

$$\boxed{\;\text{aktif okuma kısıtı}\;\neq\;X\text{'in temel tanımı}\;}$$

```latex
\boxed{\;\text{aktif okuma kısıtı}\;\neq\;X\text{'in temel tanımı}\;}
```

*Türev yapısı notu:* $X$ skaler olmadığı için türev, $X$'in değer uzayında bir türevlenebilir yapı varsayar. Bu yapıyı gerektirmeyen iki düzey ayrılır — **çözücü düzeyinde** akromatiklik ve **seçilmiş okumalar düzeyinde** akromatiklik — ve ikisi koşulsuz eşdeğer değildir:

$$\underbrace{X(\mathcal S,E_1)=X(\mathcal S,E_2)\ \ \forall\,E_1,E_2}_{\text{çözücü düzeyi}}\;\Longrightarrow\;\underbrace{\left.\frac{\partial\xi_k}{\partial E_{\rm probe}}\right|_{\mathcal S}=0\ \ \forall k}_{\text{okuma düzeyi}}\qquad(\xi_k=\pi_k(X)\ \text{türevlenebilir})$$

```latex
\underbrace{X(\mathcal S,E_1)=X(\mathcal S,E_2)\ \ \forall\,E_1,E_2}_{\text{çözücü düzeyi}}\;\Longrightarrow\;\underbrace{\left.\frac{\partial\xi_k}{\partial E_{\rm probe}}\right|_{\mathcal S}=0\ \ \forall k}_{\text{okuma düzeyi}}\qquad(\xi_k=\pi_k(X)\ \text{türevlenebilir})
```

$$\text{Ters yön genel olarak geçersiz: } X(E)=(0,E),\ \ \pi_1(a,b)=a\ \Rightarrow\ \xi_1=0\ \text{sabit, ama } X(E)\ \text{değişir}$$

```latex
\text{Ters yön genel olarak geçersiz: } X(E)=(0,E),\ \ \pi_1(a,b)=a\ \Rightarrow\ \xi_1=0\ \text{sabit, ama } X(E)\ \text{değişir}
```

| Sembol | Anlamı |
|---|---|
| $E_1$, $E_2$ | İki farklı sınama enerjisi |
| $\xi_k$ | $X$'in türevlenebilir bir okuması |
| $\pi_1(a,b)=a$ | Karşı örnekteki izdüşüm: yalnız ilk bileşeni okur |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Akromatiklik kısıtını türev yapısı gerektirmeyen bir biçimde de yazar |
| **Neden yapıyor?** | Skaler olmayan bir nesne için türevin ne anlama geldiği tanımlanmadan kısıt iyi tanımlı olmaz |
| **Nasıl yapıyor?** | Çözücü düzeyindeki enerji bağımsızlığının bütün türevlenebilir okumaların enerji bağımsızlığını gerektirdiğini yazar; tersinin genel olarak geçersiz olduğunu bir karşı örnekle gösterir. Ters yöndeki eşdeğerlik, okuma ailesinin çözümleri ayırt etmesi (izdüşümlerin birlikte birebir olması) ve uygun bağlılık / türevlenebilirlik koşulları altında kurulabilir |
| **Ne sonuç bekleniyor?** | Enerjiye bağlı gecikme sınırlarıyla (LHAASO / GRB 221009A) tip düzeyinde tutarlı bir kısıt |
| **Ne sonuç elde ediliyor?** | Kısıtın içeriği değişmez; **iyi tanımlılığı** sağlanır. LHAASO tipi gözlemler yalnız seçilmiş okumaları sınar; bu yüzden gözlemsel sınır okuma düzeyindeki kısıttır, çözücü düzeyindeki kısıt onun daha güçlü (yeterli) biçimidir |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Aynı fiziksel durumun ontolojik çözümünün ölçüm probunun enerjisine göre kaymamasını şart koşar |
| **Neden yapıyor?** | Probun enerjisine bağlı bir çözüm, Lorentz değişmezliğini ihlal eden ve ölçümlerle çelişen etkiler üretirdi |
| **Nasıl yapıyor?** | Sabit durumda $X$'in ve okuma katsayısının prob enerjisine göre türevini sıfır tutar |
| **Ne sonuç bekleniyor?** | Köprü modellerinin enerjiye bağlı ışık hızı farkı gibi yasaklanmış etkiler üretmemesi |
| **Ne sonuç elde ediliyor?** | Aktif bir Cₘ okuma / Lorentz uyumluluk kısıtı olarak korunur; prob enerjisinin hiçbir modelde ilgisiz olduğu anlamına gelmez; $X$'in tanımı değildir |

### Denklem seti — Zaman ve kuantum eşiği

Kanon, zamanın "en küçük anlamlı adımını" bir kuantum eşiğine bağlıyordu. Bu eşik yanlış kurulursa zaman tanımının kendisi boyutsal olarak tutarsız olur; üzerine kurulan her şey de öyle.

$$\int \mathcal{G}\,d\tau \geq \frac{\hbar}{2} \qquad \text{(eski — boyut hatası, emekli)}$$

```latex
\int \mathcal{G}\,d\tau \geq \frac{\hbar}{2} \qquad \text{(eski — boyut hatası, emekli)}
```

$$\int \mathcal{G}_{\rm FS}\,d\lambda \geq \theta_{\min}, \qquad \Delta t\;\geq\;\Delta t_{\min}=\frac{\hbar\,\theta_{\min}}{\overline{\Delta E}},\qquad \overline{\Delta E}=\frac1{\Delta t}\int_0^{\Delta t}\Delta E(t)\,dt \qquad \text{(düzeltme; sabit } \Delta E\text{'de }\overline{\Delta E}=\Delta E)$$

```latex
\int \mathcal{G}_{\rm FS}\,d\lambda \geq \theta_{\min}, \qquad \Delta t\;\geq\;\Delta t_{\min}=\frac{\hbar\,\theta_{\min}}{\overline{\Delta E}},\qquad \overline{\Delta E}=\frac1{\Delta t}\int_0^{\Delta t}\Delta E(t)\,dt \qquad \text{(düzeltme; sabit } \Delta E\text{'de }\overline{\Delta E}=\Delta E)
```

$$dt = \frac{\hbar}{\Delta E_{C_m}}\,ds_{\rm FS} \quad \text{(C-1 köprüsü)}, \qquad dt_{\rm ET} = \eta_{\rm clock}\,d\tau_{\rm GR},\ \ \eta_{\rm clock} \in [\eta^-, \eta^+],\ \text{GR limitinde } [1,1]$$

```latex
dt = \frac{\hbar}{\Delta E_{C_m}}\,ds_{\rm FS} \quad \text{(C-1 köprüsü)}, \qquad dt_{\rm ET} = \eta_{\rm clock}\,d\tau_{\rm GR},\ \ \eta_{\rm clock} \in [\eta^-, \eta^+],\ \text{GR limitinde } [1,1]
```

$$\tau_0\tilde\Gamma\,\mathcal{G}_{C_m}=\frac{dt_{\rm ET}}{d\lambda}=\eta_{\rm clock}\,\frac{d\tau_{\rm GR}}{d\lambda},\qquad d\tau_{\rm GR}=\sqrt{-g_{00}}\;dt_{\rm koor}\ \ (\text{durağan gözlemci, }v^i=0) \qquad \text{(aday saat eşlemesi)}$$

```latex
\tau_0\tilde\Gamma\,\mathcal{G}_{C_m}=\frac{dt_{\rm ET}}{d\lambda}=\eta_{\rm clock}\,\frac{d\tau_{\rm GR}}{d\lambda},\qquad d\tau_{\rm GR}=\sqrt{-g_{00}}\;dt_{\rm koor}\ \ (\text{durağan gözlemci, }v^i=0) \qquad \text{(aday saat eşlemesi)}
```

$$\Delta t_{\min} \in \left[\frac{\hbar\theta^-}{\overline{\Delta E}^{\,+}},\ \frac{\hbar\theta^+}{\overline{\Delta E}^{\,-}}\right] \quad \text{(aralık biçimi)}$$

```latex
\Delta t_{\min} \in \left[\frac{\hbar\theta^-}{\overline{\Delta E}^{\,+}},\ \frac{\hbar\theta^+}{\overline{\Delta E}^{\,-}}\right] \quad \text{(aralık biçimi)}
```

**Emekli yazım:** önceki sürümlerdeki $\Gamma\cdot\mathcal G_{C_m}=1/\sqrt{-g_{00}}$ eşitliği, normalize iskelede ($[\lambda]=1$, $[\Gamma]=T$) sol tarafı zaman boyutlu, sağ tarafı boyutsuz bıraktığı için **boyutça tutarsızdır**; yalnız zaman boyutlu bir iskele parametresi ($[\tau]=T$) seçilip $t_{\rm ET}\leftrightarrow t_{\rm koor}$ ve $\tau\leftrightarrow\tau_{\rm GR}$ özdeşleştirmeleri yapıldığında boyutça anlam kazanır ve bu özdeşleştirmeler kanıtlanmış değildir. Yerine yukarıdaki saat eşlemesi kullanılır; hangi saatin (koordinat zamanı, öz zaman, Evertophy zamanı) okunduğu açıkça yazılır.

**Durağan durum dalı:** $\Delta E=0$ olan bir durum evrilmez ($ds_{\rm FS}=0$); C-1 köprüsünde $\hbar\,ds_{\rm FS}/\Delta E$ belirsiz ($0/0$) olur ve bu dal ayrı tanımlanır. Bir alt sistemin durum uzaklığının sıfır olması, o alt sistemin değişim ölçüsünün sıfır olduğunu söyler; **evrensel fiziksel saatlerin durduğu anlamına gelmez**.

| Sembol | Anlamı |
|---|---|
| $\mathcal{G}$ | Faz durumunun değişim hızı (durum uzayında "hız") |
| $\mathcal{G}_{\rm FS}$ | Aynı hızın Fubini–Study metriğiyle ölçülmüş hâli (kuantum durumları arası doğal uzaklık) |
| $\tau$, $\lambda$ | Parametreler; $\lambda$ **boyutsuz** |
| $\hbar$ | İndirgenmiş Planck sabiti — boyutu [enerji × zaman] |
| $\theta_{\min}$ | Ayırt edilebilir iki durum arasındaki en küçük açı (boyutsuz) |
| $\Delta E$ | Cₘ sisteminin enerji yayılımı |
| $ds_{\rm FS}$ | Fubini–Study yay uzunluğu elemanı |
| $\eta_{\rm clock}$ | Evertophy zamanı ile genel görelilik öz zamanı arasındaki oran (aralık) |
| $d\tau_{\rm GR}$ | Genel görelilik öz zamanı |
| $g_{00}$ | Metriğin zaman–zaman bileşeni |
| $\overline{\Delta E}$ | Enerji yayılımının yörünge boyunca zaman ortalaması (zamana bağlı Hamiltoniyende Anandan–Aharonov biçimi) |
| $t_{\rm ET}$, $t_{\rm koor}$ | Evertophy (iskele) zamanı ve koordinat zamanı |
| $\tau_0$, $\tilde\Gamma$ | Zaman ölçeği ve boyutsuz okuma katsayısı ($\Gamma=\tau_0\tilde\Gamma$) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Zamanın en küçük anlamlı adımı için boyutsal olarak tutarlı bir kuantum sınırı verir |
| **Neden yapıyor?** | Eski eşikte sol taraf boyutsuz, sağ taraf eylem boyutundaydı; zaman tanımı boyutsal olarak tutarsızdı |
| **Nasıl yapıyor?** | Eşiği boyutsuz bir açı olarak yazar; ondan, sabit enerji yayılımında bir zaman **hız sınırı** (Mandelstam–Tamm tipi) çıkarır; Fubini–Study metriğiyle bir zaman köprüsü kurar |
| **Ne sonuç bekleniyor?** | Kuantum Cₘ rejiminde zaman adımının boyutsal olarak tutarlı tanımlanması ve genel görelilik limitinde $[1,1]$'e inmesi |
| **Ne sonuç elde ediliyor?** | Eski eşik emeklidir; boyutsuz eşik model / geometrik köprüdür; Fubini–Study zaman köprüsü (C-1) yalnız saf durum ve üniter evrim koşullarında anlamlı bir köprüdür ve **bütün Cₘ saatlerinin evrensel tanımı değildir**: durağan bir kuantum durumunda da fiziksel zaman anlamlıdır, oysa köprü orada $0/0$ verir; $\eta_{\rm clock}$ köprü / modeldir (çekirdek değil, GR limiti $[1,1]$); açık sistem genellemesi açıktır. $\Delta t_{\min}$ ulaşılmış bir süre değil, bir **alt sınırdır** (eşitlik yalnız jeodezik evrimde). Eski $\Gamma\mathcal G_{C_m}=1/\sqrt{-g_{00}}$ yazımı boyut hatası nedeniyle emeklidir; yerini boyutça tutarlı saat eşlemesi almıştır |

**Tarihsel boyut denetimi:** tarihsel saat çarpanı $dt=\Gamma\,G_t\,d\tau$ ancak $[\Gamma]=T$, $[G_t]=T^{-1}$, $[d\tau]=T$ ise tutarlıdır; boyutsuz biçim $dt=\tau_0\,\tilde\Gamma\,G_t\,d\tau$, $[\tilde\Gamma]=1$ olur. Buradaki $G_t$ kütleçekim sabiti **değildir**. Bu biçim Cₘ dışına fiziksel saat taşımaz; c₀ ve c⁺'ta sıfır türev de tanımlanmaz. Statü: arşiv / boyut denetimi; fiziksel köprü açık.

## 7.5 İki farklı zamansızlık

| Faz | Zamansal rol | Ontolojik anlamı |
|---|---|---|
| **c₀** | Zaman-öncesi | Fiziksel zaman henüz kurulmamıştır ($\bot_0$); potansiyel / çekirdek rejimi |
| **Cₘ** | Fiziksel zaman | Fiziksel saat, öz zaman okuması ve ölçülebilir değişim burada anlamlıdır |
| **c⁺** | Zamansız kayıt | Cₘ'de kurulmuş zaman çözünmüştür ($\bot_+$); mühürlü kayıtlar zamansal sıra gerektirmeden birlikte bulunur |

$$\boxed{\;\text{c₀ zamansızlığı (henüz kurulmamış)} \;\neq\; \text{c⁺ zamansızlığı (çözünmüş)}\;}$$

```latex
\boxed{\;\text{c₀ zamansızlığı (henüz kurulmamış)} \;\neq\; \text{c⁺ zamansızlığı (çözünmüş)}\;}
```

## 7.6 Foton, öz zaman ve faz üyeliği

Özel görelilikte ışık benzeri bir dünya çizgisinde öz zaman sıfırdır. Bu ölçülmüş gerçek, fotonu ontolojik olarak c⁺ üyesi yapmaz.

$$\boxed{\;d\tau_{\rm öz}=0 \;\nRightarrow\; \text{faz}(\text{foton})=c^+\;}$$

```latex
\boxed{\;d\tau_{\rm öz}=0 \;\nRightarrow\; \text{faz}(\text{foton})=c^+\;}
```

Foton $v=c$ sınırında, **liminal** durumdadır (3.3). Liminal olmak, Cₘ'nin üyelik bandının sınırında bulunmak demektir. Bu sınır aynı zamanda c⁺ rejiminin de sınırıdır: Cₘ ile c⁺ bu sınırı paylaşır. İki rejimin **ortak sınırında** bulunmak, ikisinden birine üye olmak değildir: foton ne Cₘ'nin kütleli maddesine ne de c⁺'a üyedir. Aynı okuma kütleçekim dalgası için de geçerlidir (yazar hükmü, 3.3).

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Fotonun faz statüsünü kesinleştirir |
| **Neden yapıyor?** | "Foton için zaman geçmez, öyleyse foton c⁺'tadır" çıkarımı yaygın ama hatalıdır |
| **Nasıl yapıyor?** | Öz zamanın sıfır olmasını bir Cₘ ölçümü olarak kabul eder; fotonu Cₘ ile c⁺'ın ortak liminal sınırına yerleştirir |
| **Ne sonuç bekleniyor?** | Işık ve kütleçekim dalgalarının çerçevede tutarlı bir yere oturması |
| **Ne sonuç elde ediliyor?** | Ortak sınır okuması yazar hükmüdür; sınırda bulunmak üyelik değildir |

## 7.7 İki saat sorunu — açık gerilim

Cₘ'nin etkin geometrisi zaten bir öz zaman üretir; emergent zaman iskelesi ise ikinci bir okuma dili sunar. Bu yüzden "iki saat" sorunu açıkça çözülmelidir.

| Yol | İçerik | Bedeli |
|---|---|---|
| **A** | Emergent okuma öz zamanla özdeştir | Yeni zaman yapısı fiziksel içerik eklemeyebilir |
| **B** | İki saat bağımsızdır | Aralarındaki hassas uyumun açıklanması gerekir |
| **C** | Dinamik ya da tekil bir eşleme vardır | Ek bir köprü yasası gerekir |

Bu sorun kapanmadan emergent zaman denklemi, genel görelilik öz zamanının türetilmiş bir alternatifi olarak sunulamaz.

### 7.7a Kayıt defteri — güvenli çekirdek okuma

**Kayıt defteri (registry) bağımsız bir varlık değildir.** Cₘ içindeki farklılaşmış olayların ve kaynak bilgisinin kayıt izi için kullanılan bir okuma dilidir. "Kayıt vardır" ifadesi "yeni bir ontolojik varlık vardır" anlamına gelmez.

Tarihsel arşivde şu biçimler kullanılmıştır:

$$\Delta\sigma_m\neq0\;\Rightarrow\;\text{Kayıt}\;\Rightarrow\;\text{Zaman},\qquad \frac{dS_{\rm Reg}}{d\tau}\ge0$$

```latex
\Delta\sigma_m\neq0\;\Rightarrow\;\text{Kayıt}\;\Rightarrow\;\text{Zaman},\qquad \frac{dS_{\rm Reg}}{d\tau}\ge0
```

| Sembol | Anlamı |
|---|---|
| $\Delta\sigma_m$ | Cₘ payındaki değişim (tarihsel) |
| $S_{\rm Reg}$ | Tarihsel "kayıt entropisi" |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Zamanı kayıt üretiminden, kayıt entropisini de monoton bir büyüklükten türetmeye çalışıyordu |
| **Neden yapıyor?** | Zaman okunu kayıt birikimine bağlamak için erken bir denemeydi |
| **Nasıl yapıyor?** | Faz payındaki değişimi kayda, kaydı zamana bağlayan bir zincir ve bir monotonluk yasası yazarak |
| **Ne sonuç bekleniyor?** | Zamanın temel türetimi |
| **Ne sonuç elde ediliyor?** | Güncel çekirdekte bu biçimler zamanın temel türetimi ya da evrensel bir entropi yasası olarak **yükseltilmez**; 7.2'deki zaman iskelesi ve Bölüm 14'teki mühür / arşiv ontolojisi üstündür. "c⁺ = bütün fazların global / anlık kayıt defteri" okuması da güncel kanon değildir: "anlık" Cₘ zaman dili c⁺'a taşınmaz |

## 7.8 Zaman ve entropi

Zaman ile entropi **özdeş değildir**. Cₘ'ye ait zaman oku ile kayıt / entropi davranışı ortak yapısal köklere sahip olabilir; ama:

$$\boxed{\;\text{fiziksel zaman} \neq \text{termodinamik entropi} \neq \text{arşiv sırası}\;}$$

```latex
\boxed{\;\text{fiziksel zaman} \neq \text{termodinamik entropi} \neq \text{arşiv sırası}\;}
```

Birinin artışı ötekinin tanımı değildir.

## 7.9 Faz hafızası — zamansız ifade

"Faz hafızası", c₀ ya da c⁺ içinde akan bir tarih değişkeni anlamına gelmez. Güvenli yorum şudur: eşik ve geçiş geçmişi, sonraki Cₘ okumasında **yapısal bir kalıntı ya da kaynak kısıtı** bırakır.

Arşiv için çekirdek monotonluk bir zaman değişkeniyle değil, bir kaynak sırasıyla ifade edilir:

$$\boxed{\;A \preceq A'\;}$$

```latex
\boxed{\;A \preceq A'\;}
```

| Sembol | Anlamı |
|---|---|
| $A$, $A'$ | Arşivin iki hâli |
| $\preceq$ | Yalnız ekleme / kaynak sırası; c⁺'ta fiziksel zaman değildir |

Arşivde görülen $R_\phi(t+\Delta t)\ge R_\phi(t)$ ifadesi ancak **Cₘ zamanlı etkin bir model** olarak kullanılabilir; çekirdek bir aksiyom değildir.

### Faz izi (Faz Skarı) — model adayı

Arşivdeki "Faz Skarı", faz hafızasının etkin model gerçeklemesi olarak korunur:

$$\Delta X_{\rm res}(x)=\int \Gamma(x,t')\,dt',\qquad X_{\rm eff}(x)=X_0(x)+\Delta X_{\rm res}(x),\qquad \Xi_{\rm iz}=\int\frac{\partial\Gamma}{\partial X}\,dX$$

```latex
\Delta X_{\rm res}(x)=\int \Gamma(x,t')\,dt',\qquad X_{\rm eff}(x)=X_0(x)+\Delta X_{\rm res}(x),\qquad \Xi_{\rm iz}=\int\frac{\partial\Gamma}{\partial X}\,dX
```

| Sembol | Anlamı |
|---|---|
| $\Delta X_{\rm res}$ | Geçmişten kalan kalıntı katkı |
| $X_0$, $X_{\rm eff}$ | Temel ve etkin çözüm (model) |
| $t'$ | Yalnız Cₘ etkin modeline ait zaman değişkeni |
| $\Xi_{\rm iz}$ | Alternatif işlevsel mühür adayı (17'deki $\Xi=\ln\chi_S$ ile ilgisiz) |

### Denklem seti — Faz hafızası

$$R_\varphi(r_{n+1}) \geq R_\varphi(r_n) \qquad \text{(kaynak indeksine göre — fiziksel zamana göre değil)}$$

```latex
R_\varphi(r_{n+1}) \geq R_\varphi(r_n) \qquad \text{(kaynak indeksine göre — fiziksel zamana göre değil)}
```

| Sembol | Anlamı |
|---|---|
| $R_\varphi$ | Faz hafızası ölçüsü |
| $r_n$ | $n$-inci kaynak (provenance) kaydı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Faz sistemlerinin "geçmişi unutmadığı" ilkesini zamansız bir dille yazar |
| **Neden yapıyor?** | Eski kanon bu ilkeyi fiziksel zamana göre yazıyordu; ama c₀ ve c⁺'ta zaman yoktur |
| **Nasıl yapıyor?** | Monotonluğu zaman yerine kayıtların kaynak sırasına göre yazar; etkin model sürümlerinde zaman integralini yalnız Cₘ'ye sınırlar |
| **Ne sonuç bekleniyor?** | Geçmiş geçişlerin Cₘ okumasında ölçülebilir bir iz bırakıp bırakmadığının sınanabilmesi |
| **Ne sonuç elde ediliyor?** | Kaynak indeksli yazım kesindir; monotonluğun kendisi biçimsel bir teorem değil, bir mimari kuraldır (statüsü yazar kararına bağlı). Faz Skarı denklemleri çekirdek yasa değildir; $X$'i skalerleştirmez ve zaman-dışı fazlara Cₘ zamanı taşımaz |

## 7.10 Hız dili yalnız Cₘ'de meşrudur

$$\boxed{\;c_0 \text{ ve } c^+ \text{ için içsel ORAN / HIZ dili kullanılmaz.}\;}$$

```latex
\boxed{\;c_0 \text{ ve } c^+ \text{ için içsel ORAN / HIZ dili kullanılmaz.}\;}
```

Aynı nedenle $dX/dt$, "faz akış hızı", "c⁺'ın genişleme hızı" gibi ifadeler temel ontolojik katmana ait değildir; ancak Cₘ okuma ya da model düzeyinde tanımlanabilir.

## 7.11 Emergent zaman okullarıyla karşılaştırma haritası

Zamanın statüsü konusunda dört büyük pozisyon ve Evertophy'nin konumu kayıt altındadır. Bu karşılaştırma bir konumlandırmadır; eleştiri değildir.

| Okul | Zamanın statüsü | Kaynak | Evertophy ile ilişki |
|---|---|---|---|
| **Barbour** | Zamansız ontolojide yapıların sıralanması; "zaman kapsülleri" | Kaynak yok | Ortak: zaman temel değildir. Fark: Evertophy zamanı fiziksel olarak **yeniden üretmeye** çalışır; Barbour onu felsefi olarak çözer |
| **Rovelli** | Termal zaman: durumdan belirlenen modüler akış; zaman türetilmiş | Durum → termal akış | Ortak: türetilmişlik. Evertophy'de kaynak düzenleme / mühürleme / faz geçişidir |
| **Smolin** | Zaman temel ve gerçektir | Zamanın kendisi | Kısmi yakınlık: zamansız ontoloji ile fiziksel zaman realizmi arasında köprü adayı |
| **Wheeler–DeWitt** | $H\Psi=0$ — zamansız dalga denklemi | Sorun olarak durur | Evertophy zamansızlığı faz ayrımıyla okur: c₀'da kurulmamış, c⁺'ta çözünmüş |

### 7.11a Page–Wootters formalizmi

Klasik "zamansız evren + saat alt sistemi → koşullu dalga fonksiyonundan zaman" yapısıdır. Evertophy okumasında saat alt sistemi rolü Cₘ'deki fiziksel süreçlere aittir; mekanizma adayı "düzenleyici akışı"dır. Biçimsel bir özdeşlik kurulmamıştır.

### 7.11b Holografik zaman yaklaşımı

Sınır zamanı ile iç (bulk) zaman arasındaki ilişkidir. Evertophy'de karşılığı c⁺ ile Cₘ arasındaki okuma ilişkisidir; ama holografik eşleşme (AdS/CFT türü) çekirdeğe ithal edilmez (19.2).

### 7.11c Termodinamik / entropik zaman

Zaman okunun entropi artışından doğduğu görüştür. Evertophy'de ayrım serttir: zaman, entropi ve arşiv sırası üç ayrı kavramdır (7.8, 16.3); hiçbiri ötekinin tanımı değildir.

### 7.11d İlişkisel kuantum mekaniği (RQM)

Ölçüm etkileşimdir; gözlemcinin önceliği yoktur. Evertophy'de paralel olarak gözlemci ayrı bir ontolojik sınıf değil, Cₘ içinde kayıt üreten sistemlerin rolüdür (1.4).

### 7.11e Wheeler–DeWitt ve zamansızlık literatürü

"Zamansızlığın nasıl aşıldığı" sorusu literatürde açıktır. Evertophy'nin önerisi faza bağlı üretimdir; matematiksel derinlik bakımından çerçeve henüz **parçalıdır**: kapalı bir biçimsel sistem değil, "örüntü + faz modeli" düzeyindedir.

### 7.11f Barbour ile derin karşılaştırma

Dört fark kayıtlıdır: **(A)** zamansız ontoloji ↔ faz tarafından üretilen zaman; **(B)** epistemik ↔ fiziksel ("emergent gerçek dışı demek değildir": saatler, sürüklenme ve biçimsel korelasyonlar fiziksel veridir); **(C)** faz mimarisi (c₀, Cₘ, c⁺ Barbour'da yoktur); **(D)** kalıntı iz ($\delta X$, $\Phi(x)$, $\rho(\tau)$) — Evertophy'nin Barbour'dan ileri giden tek iddiası ölçülebilir bir kalıntıdır ve bu iddia kapanmamıştır.

$$\boxed{\;\text{En sade konum: Temel zaman yoktur; zaman } C_m \text{'de düzenleme ve mühürleme yoluyla üretilir ve ölçülebilir bir iz bırakabilir.}\;}$$

```latex
\boxed{\;\text{En sade konum: Temel zaman yoktur; zaman } C_m \text{'de düzenleme ve mühürleme yoluyla üretilir ve ölçülebilir bir iz bırakabilir.}\;}
```

Uyarı kilitlidir: bu cümlenin gerçekleşmiş olduğu kabul edilemez; doğrulanması açık borçtur.

### Denklem seti — $c$: Cₘ ışık konisi sınırı

$$\text{Çekirdek: } g(k,k) = 0,\quad c_{C_m} = [c,c] \qquad \text{(K12: } c = \sup d\ell/d\tau \text{ — emekli; } \gamma v \to \infty\text{)}$$

```latex
\text{Çekirdek: } g(k,k) = 0,\quad c_{C_m} = [c,c] \qquad \text{(K12: } c = \sup d\ell/d\tau \text{ — emekli; } \gamma v \to \infty\text{)}
```

| Sembol | Anlamı |
|---|---|
| $k^\mu$ | Işık benzeri (boş) vektör |
| $g(k,k)=0$ | Boş koni koşulu |
| $c_{C_m}=[c,c]$ | Cₘ'de ışık hızı: tanımsal nokta aralık |
| $d\ell/d\tau$ | Parçacık öz zamanına göre yol hızı |
| $\gamma$ | Lorentz çarpanı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Işık hızının Evertophy'deki yerini belirler |
| **Neden yapıyor?** | $c$'nin fazdan bağımsız evrensel bir sabit gibi tanımlanması c₀ ve c⁺'a içsel hız ithal ederdi |
| **Nasıl yapıyor?** | $c$'yi Cₘ'deki boş koni sınırı olarak tanımlar; Cₘ'de sıfır genişlikli bir aralık olarak yazar |
| **Ne sonuç bekleniyor?** | c₀ ve c⁺'ta içsel $c$ bulunmaması; çekirdekte $c$'nin herhangi bir okumaya duyarlılığının sıfır olması |
| **Ne sonuç elde ediliyor?** | Boş koni tanımı çekirdek tercihidir ve kanonik kayıttadır; öz zaman tanımı (K12) emeklidir, çünkü $\gamma v$ sınırsız büyür |




# BÖLÜM 8 — ÇEKİM ONTOLOJİSİ

## 8.1 Postüla-0'ın açılımı

$$\boxed{\;\text{Çekim Kuvveti (Force of Attraction) temel ontolojik postüladır; kütleçekim onun Cₘ'deki izdüşümlerinden biridir.}\;}$$

```latex
\boxed{\;\text{Çekim Kuvveti (Force of Attraction) temel ontolojik postüladır; kütleçekim onun Cₘ'deki izdüşümlerinden biridir.}\;}
```

Bölüm 1.2'deki ayrım kritik olduğu için burada yinelenir:

$$\text{Çekim Kuvveti}_{\rm ontoloji} \;\neq\; \text{Kütleçekim}_{C_m} \;\neq\; X \;\neq\; g_{\mu\nu} \;\neq\; G_{\rm eff}$$

```latex
\text{Çekim Kuvveti}_{\rm ontoloji} \;\neq\; \text{Kütleçekim}_{C_m} \;\neq\; X \;\neq\; g_{\mu\nu} \;\neq\; G_{\rm eff}
```

### 8.1a Pozitif düzenleme okuması — daraltılmış güncel biçim

Postüla-0'ın olumlu içeriği, Çekim Kuvveti'nin yalnız "neyin olmadığı" ile bırakılmamasını gerektirir: Çekim Kuvveti Evertophy'de **faz düzenlemesinin temel ontolojik kısıtlayıcısı ve düzenleyicisi** olarak okunur.

Ama tarihsel kayıttaki "$X$ = kütleçekim kaynaklı izin / düzen indeksi" özdeşliği **güncel kanon değildir**. Güncel $X$, Bölüm 4'te tanımlanan evrensel, faza duyarlı çözücüdür; Çekim Kuvveti $X$'in belirleyicilerinden biri olabilir, ama $X$'i tek başına tüketmez.

$$\boxed{\;\text{Çekim Kuvveti temel düzenleyicidir}\;\not\Rightarrow\;X\equiv \text{çekim indeksi}\;}$$

```latex
\boxed{\;\text{Çekim Kuvveti temel düzenleyicidir}\;\not\Rightarrow\;X\equiv \text{çekim indeksi}\;}
```

## 8.2 Çekim Kuvveti ≠ gözlenen kütleçekim

Genel görelilik **yanlış değildir**: Çekim Kuvveti'nin Cₘ'deki metrik izdüşümü olan kütleçekimin etkin dilidir. Ontolojik postüla ile onun Cₘ'deki izdüşümü farklı katmanlardır; genel göreliliğin ölçülmüş bütün sonuçları koşulsuz kabul edilir.

## 8.3 Etkin bağlaşım — model düzeyi

Skaler-tensör dilinde yazılabilecek bir köprü biçimi şudur:

$$G_{\rm eff} = \frac{G_N}{F}, \qquad\qquad \frac{\dot G}{G} = -\frac{\dot F}{F}$$

```latex
G_{\rm eff} = \frac{G_N}{F}, \qquad\qquad \frac{\dot G}{G} = -\frac{\dot F}{F}
```

| Sembol | Anlamı |
|---|---|
| $G_{\rm eff}$ | Cₘ'de ölçülen etkin kütleçekim bağlaşımı |
| $G_N$ | Newton kütleçekim sabiti |
| $F$ | Skaler-tensör kuramının bağlaşım fonksiyonu (biçimi bilinmiyor) |
| $\dot G/G$ | Kütleçekim sabitinin bağıl değişim hızı (ölçümlerle sıkı sınırlanmış) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Etkin kütleçekim bağlaşımını bir model fonksiyonuna bağlar |
| **Neden yapıyor?** | $G$'nin olası değişimine ilişkin gözlemsel sınırlarla temas kurmak için |
| **Nasıl yapıyor?** | Skaler-tensör kuramlarının standart biçimiyle, $G_{\rm eff}$'i $F$'nin tersiyle ölçekler |
| **Ne sonuç bekleniyor?** | $F$'nin $X$'ten türetilmesi hâlinde $\dot G/G$ için bir öngörü |
| **Ne sonuç elde ediliyor?** | **Çekirdek ontoloji değil, bir model gerçeklemesidir.** $F$'nin biçimi bilinmiyor ve $X$ ile ilişkisi kurulmamıştır; gözlemsel sınırlar Evertophy **üzerine** konan kısıtlardır, ondan çıkan öngörüler değildir |

## 8.4 Yerel çekim şiddeti

Yerel çekim şiddeti, faz konumuyla **ilişkili** bir niceliktir; onun **eşdeğeri değildir**. Aynı değer, farklı yapısal düzenlenişlerde farklı faz konumlarına karşılık gelebilir.

### Gradyan formülleri

Arşivde şu tür hareket yasası biçimleri geçer:

$$\mathbf{a} \sim -c^2\nabla\ln X \qquad (\text{tarihsel biçim})$$

```latex
\mathbf{a} \sim -c^2\nabla\ln X \qquad (\text{tarihsel biçim})
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | İvmeyi $X$'in logaritmik gradyanından türetmeye çalışıyordu |
| **Neden yapıyor?** | Kütleçekim ivmesini doğrudan çözücüye bağlamak için erken bir denemeydi |
| **Nasıl yapıyor?** | $X$'i skaler bir alan gibi kullanarak |
| **Ne sonuç bekleniyor?** | Newton limitinin $X$'ten çıkması |
| **Ne sonuç elde ediliyor?** | **Çekirdek yasa değildir.** $X$ zorunlu olarak skaler olmadığından böyle bir gradyan biçimi ontoloji tarafından gerektirilmez; bir okuma $\xi=\pi(X)$ tanımlanıp türetilirse model ya da köprü katmanında değerlendirilir |

## 8.5 Diğer kuvvetler

Elektromanyetik, güçlü ve zayıf kuvvetler — kütleçekimle birlikte — Çekim Kuvveti'nin Cₘ'deki izdüşümleridir (1.2). Bağlaşım sabitleri ilke olarak bu izdüşümün ölçeğe, kütleye ve faza bağlı biçimiyle belirlenir; ama bu bağlılığın biçimi bilinmemektedir.

### Üç katmanlı okuma mimarisi — model adayı

| Katman | Neyi tarif eder | Statü |
|---|---|---|
| **Maxwell / alan dili** | Cₘ içindeki elektromanyetik alan ve ölçülebilir alan okumaları | Yerleşik etkin fizik |
| **CMT / kanal dili** | Modlar, saçılma, empedans ve yönlü kanal davranışı | Deneysel / model köprü dili |
| **Evertophy / faz-kısıt dili** | Hangi faz, rejim ve okumanın kabul edilebilir olduğunu çözen üst kısıt yapısı | Ontolojik / program katmanı |

$$\boxed{\;\text{Maxwell}\neq\text{CMT}\neq\text{Evertophy};\quad \text{katmanlar birbirinin yerine kullanılmaz.}\;}$$

```latex
\boxed{\;\text{Maxwell}\neq\text{CMT}\neq\text{Evertophy};\quad \text{katmanlar birbirinin yerine kullanılmaz.}\;}
```

Tarihsel geliştirme kayıtlarında kuvvetler için ayrıca şu fenomenolojik aday atamalar bulunur:

| Cₘ etkileşimi | Tarihsel / aday Evertophy okuması |
|---|---|
| Güçlü | "Kristal / faz bütünlüğü" benzeri bağlayıcı yapı (eski adlandırma; Daha Sonra Ele Alınacak) |
| Elektromanyetik | $c$ sınırıyla ilişkili kalıcı bir Cₘ imzası ve okuma programı (yük); itmenin ve yükün izdüşüm biçimi Daha Sonra Ele Alınacak |
| Zayıf | Kararsız yapıdan kararlı yapıya dönüşüm |

Bu tablo **türetim değildir**; Standart Model'in ayar yapısını ya da bağlaşımlarını açıklamış sayılmaz. Özellikle $c$ ile ilgili satır, Cₘ'nin kinematik ve tutarlılık sınırını fiziksel olarak "kıran" ışık-üstü bir süreç iddia etmez.

## 8.6 Çekim ve dış fazlar

$$\boxed{\;\text{Çekim Kuvveti fazdan bağımsızdır: } c_0 \text{ ve } c^+ \text{ da onun kısıt koheransına tabidir.}\;}$$

```latex
\boxed{\;\text{Çekim Kuvveti fazdan bağımsızdır: } c_0 \text{ ve } c^+ \text{ da onun kısıt koheransına tabidir.}\;}
```

Metrik, madde desteği ve ivme dili Cₘ'ye ait **okuma araçlarıdır**; Çekim Kuvveti bu araçlara muhtaç değildir. c⁺'ın karanlık madde ve karanlık enerji olarak gözlenen çekimsel etkisi (Bölüm 11) Cₘ'de metrik diliyle okunur; ama etkinin kaynağı c⁺'ın kendi faz rejimidir, Cₘ maddesi değildir. Çekimin dış fazlarda "nasıl" işlediğinin matematiksel dili bilinçli olarak açıktır ve V24'ün devre mekanizması katmanının doğal konusudur.

Bu okuma c⁺'a metrik ya da Cₘ madde desteği geri getirmez; **kimlik ≠ mekanizma** ayrımı korunur ve burada nicel bir türetim iddia edilmez.

## 8.7 Kütleçekimsel empedans — Cₘ genel görelilik model okuması

Zayıf alan genel görelilik dilinde, ontolojideki $\tau$ ile karışmaması için yerel öz zamanı $\tau_{\rm GR}$, koordinat zamanını $t_{\rm koor}$ ile gösterelim. Aşağıdaki bağıntılar **koordinatlarda duran gözlemci** ($v^i=0$) içindir; son yaklaşım zayıf alanda ve $g_{00}=-(1+2\Phi_N/c^2)+\dots$ gösteriminde geçerlidir:

$$d\tau_{\rm GR}\simeq\left(1+\frac{\Phi_N}{c^2}\right)dt_{\rm koor}$$

```latex
d\tau_{\rm GR}\simeq\left(1+\frac{\Phi_N}{c^2}\right)dt_{\rm koor}
```

$$\boxed{\;Z_g(x)\equiv\frac{dt_{\rm koor}}{d\tau_{\rm GR}}=\frac{1}{\sqrt{-g_{00}}}\simeq1-\frac{\Phi_N}{c^2}\;}$$

```latex
\boxed{\;Z_g(x)\equiv\frac{dt_{\rm koor}}{d\tau_{\rm GR}}=\frac{1}{\sqrt{-g_{00}}}\simeq1-\frac{\Phi_N}{c^2}\;}
```

$$\mathbf a\simeq-c^2\nabla\ln\sqrt{-g_{00}}=+c^2\nabla\ln Z_g\simeq-\nabla\Phi_N$$

```latex
\mathbf a\simeq-c^2\nabla\ln\sqrt{-g_{00}}=+c^2\nabla\ln Z_g\simeq-\nabla\Phi_N
```

Genel bir zamansı dünya çizgisi için ($x^0=ct$, $v^i=dx^i/dt$):

$$Z_g = \frac{dt}{d\tau_{\rm GR}} = \Big[-\big(g_{00} + 2g_{0i}\,v^i/c + g_{ij}\,v^iv^j/c^2\big)\Big]^{-1/2}$$

```latex
Z_g = \frac{dt}{d\tau_{\rm GR}} = \Big[-\big(g_{00} + 2g_{0i}\,v^i/c + g_{ij}\,v^iv^j/c^2\big)\Big]^{-1/2}
```

Kanal modeliyle araştırılabilecek aday sözlük şudur:

$$\Phi_g\;\longleftrightarrow\;\Phi_{\rm ch}^{\rm gen}=\lambda\ln\left|\frac{Z_{\rm eff}}{Z_{\rm ref}}\right|$$

```latex
\Phi_g\;\longleftrightarrow\;\Phi_{\rm ch}^{\rm gen}=\lambda\ln\left|\frac{Z_{\rm eff}}{Z_{\rm ref}}\right|
```

| Sembol | Anlamı |
|---|---|
| $\tau_{\rm GR}$ | Cₘ öz zamanı (genel görelilik okuması; 7.2'deki $\tau$ ile karıştırılmaz) |
| $t_{\rm koor}$, $t$ | Uzak gözlemcinin koordinat zamanı |
| $\Phi_N$ | Newton kütleçekim potansiyeli |
| $g_{00}$, $g_{0i}$, $g_{ij}$ | Metriğin bileşenleri |
| $v^i$ | Koordinat hızı |
| $Z_g$ | Kütleçekimsel empedans (genel görelilik okuması) |
| $\mathbf a$ | Zayıf alan ivme okuması |
| $\Phi_g$, $\Phi_{\rm ch}^{\rm gen}$ | Kütleçekim potansiyeli ve kanalın gerçel genlik potansiyeli (aday eşleme). Karmaşık kanal potansiyeli $\lambda\ln(Z_{\rm eff}/Z_{\rm ref})$, bağımsız faz bilgisi taşıyan bir model nesnesi olarak ayrıca korunur (17.1a) |
| $Z_{\rm eff}$, $Z_{\rm ref}$, $\lambda$ | Etkin ve referans kanal empedansı, ölçek katsayısı (17.1a) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kütleçekimsel zaman genişlemesini bir "empedans" olarak okur ve Newton ivmesini bu empedansın gradyanından geri kazanır |
| **Neden yapıyor?** | Kanal (empedans) dili ile genel görelilik dili arasında sınanabilir bir sözlük kurmak için |
| **Nasıl yapıyor?** | Koordinat zamanı ile öz zaman oranını $Z_g$ olarak tanımlar; zayıf alanda $\ln Z_g\approx-\Phi_N/c^2$ ilişkisinden ivmeyi çıkarır |
| **Ne sonuç bekleniyor?** | Kanal potansiyeli ile kütleçekim potansiyeli arasındaki eşlemenin ileride kalibre edilmesi |
| **Ne sonuç elde ediliyor?** | Genel görelilik okuması doğrudur ve Newton limitini verir; ama $Z_g$ **yalnız Cₘ'de tanımlı** bir okuma büyüklüğüdür, c₀ ve c⁺'a taşınmaz. $dt_{\rm koor}/d\tau_{\rm GR}$ oranı 7.2'deki ontolojik iskeleyle özdeş değildir; $\Phi_{\rm ch}$ de Bölüm 17'deki $\Phi_\chi$ ile kalibrasyon gösterilmeden özdeş sayılmaz. 7.4'teki saat eşlemesi ($\eta_{\rm clock}$, durağan gözlemcide $d\tau_{\rm GR}=\sqrt{-g_{00}}\,dt_{\rm koor}$) bu ayrımı kaldırmaz: eşleme okuma katmanında, özdeşlik ontolojik katmandadır |

### İşlem gecikmesi okuması

Arşivdeki işlemsel okumada $n$ bir **işlem sırası indeksidir**, fiziksel bir süre değildir; c₀'a fiziksel zaman atfetmez. İndeks ile Cₘ'de ölçülen süre arasındaki bağ bir ölçek ve bir eşleme gerektirir:

$$dt_{\rm gösterge} = \tau_*\,f\,dn$$

```latex
dt_{\rm gösterge} = \tau_*\,f\,dn
```

| Sembol | Anlamı |
|---|---|
| $n$ | İşlem sırası indeksi |
| $\tau_*$ | Ölçek |
| $f$ | Eşleme; $f=\sqrt{-g_{00}}$ seçimi genel görelilik oranını yeniden üreten bir köprü seçimidir |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kütleçekimsel zaman genişlemesini bir işlem gecikmesi olarak okur |
| **Neden yapıyor?** | Zamanın Cₘ'de bir okuma olduğu görüşüyle uyumlu, sezgisel bir resim vermek için |
| **Nasıl yapıyor?** | İşlem sırası indeksini bir ölçek ve bir eşlemeyle Cₘ süresine bağlar |
| **Ne sonuç bekleniyor?** | Eşlemenin bağımsız olarak gerekçelendirilmesi |
| **Ne sonuç elde ediliyor?** | Kütleçekimsel zaman genişlemesi bir **işlem gecikmesi**, Shapiro gecikmesi de yüksek empedanslı bölgeden geçiş gecikmesi olarak okunur. Bu, genel göreliliğin sayısal sonuçlarını **yeniden adlandırır**, onları türetmiş sayılmaz; $f$ seçimi türetilmiş değildir |

## 8.8 CMT'den çekime türetim zinciri (model adayı)

Bağlı mod kuramı (CMT) dilinden çekim okumasına giden aday zincir şudur:

$$(\Gamma_{\rm CMT}, \kappa, \nu) \;\Rightarrow\; S(\omega; \mathcal C) \;\Rightarrow\; \chi_S \;\Rightarrow\; \Xi = \ln\chi_S \;\Rightarrow\; \mathbf g_\chi = -\Lambda(\xi)\nabla\ln\chi_S-(\ln\chi_S)\nabla\Lambda(\xi)$$

```latex
(\Gamma_{\rm CMT}, \kappa, \nu) \;\Rightarrow\; S(\omega; \mathcal C) \;\Rightarrow\; \chi_S \;\Rightarrow\; \Xi = \ln\chi_S \;\Rightarrow\; \mathbf g_\chi = -\Lambda(\xi)\nabla\ln\chi_S-(\ln\chi_S)\nabla\Lambda(\xi)
```

| Sembol | Anlamı |
|---|---|
| $\Gamma_{\rm CMT}$ | İç kayıp (7.2'deki $\Gamma$ ile karıştırılmaz) |
| $\kappa$ | Port bağlaşımı |
| $\nu$ | Karşılıklılığı bozan parametre |
| $S(\omega;\mathcal C)$ | Frekansa ve port yapılandırmasına ($\mathcal C$) bağlı saçılma matrisi |
| $\chi_S$ | İleri / geri iletim genliği oranı (17.1) |
| $\Xi$ | Logaritmik asimetri ölçüsü (2.10'daki ya da 13.6'daki $\Xi_g$, $\Xi_\Lambda$ ile ilgisiz) |
| $\Lambda(\xi)$ | Kanal ölçek katsayısı (kozmolojik sabit $\Lambda$ ile karıştırılmaz) |
| $\mathbf g_\chi$ | Kanal kaynaklı aday ivme alanı; kısa biçim $-\Lambda\nabla\ln\chi_S$ yalnız $\nabla\Lambda=0$ iken geçerlidir |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bir kanalın yönlü asimetrisinden bir ivme alanına giden aday zinciri yazar |
| **Neden yapıyor?** | Laboratuvarda ölçülebilen saçılma parametreleriyle çekim okuması arasında sınanabilir bir köprü aramak için |
| **Nasıl yapıyor?** | Kayıp, bağlaşım ve karşılıklılık parametrelerinden saçılma matrisine, oradan asimetri oranına ve logaritmik potansiyelin gradyanına gider |
| **Ne sonuç bekleniyor?** | Her halka ayrı ayrı türetilirse ölçülebilir bir kanal–çekim köprüsü |
| **Ne sonuç elde ediliyor?** | Zincirin yazılmış olması türetim değildir; her halka ayrıca türetilmesi gereken bir köprüdür. Karşılıklı sistemlerde $\chi_S\equiv1$ olduğundan (17.1) zincir ancak karşılıklılığı bozan somut bir fiziksel sınıf tanımlandığında anlam kazanır |

### Karşılıklılığın bozulması için gereken koşullar (model kaydı)

Tek modlu CMT'den karşılıklılık kırılması çıkmaz. Beş mekanizma sınıfından en az biri gerekir:

| Sınıf | Örnek |
|---|---|
| Manyeto-optik öngerilim | Ferrit, manyeto-optik ortam |
| Zamana bağlı modülasyon | Parametrik sürme |
| Çok mod + dolaşım | Halka rezonatör |
| Arka plan yolu + girişim | Girişimölçer düzeni |
| Doğrusal olmayan aktif ortam | — |

Doğru ifade "tek mod + $\nu$ parametresi" değil, "karşılıklılığı bozan somut bir fiziksel sınıf + port yapılandırması + referans düzlemi"dir. Pasiflik ve zamanla değişmezlik tek başına karşılıklılığı garanti etmez: statik manyetik öngerilim altındaki ferrit sistemler pasif ama karşılıklı olmayan örneklerdir. Çok mod, halka rezonatör ya da girişim yolu da tek başına karşılıklılık kırılmasının kanıtı değildir (17.1).

### Kütleçekimsel empedans zinciri (arşiv kaydı)

Adım adım: (1) elektromanyetizma ile genel görelilik arasında benzetme; (2) $d\tau\approx(1+\Phi/c^2)dt$; (3) $Z_g=dt/d\tau=1/\sqrt{-g_{00}}\approx1-\Phi/c^2$; (4) $\mathbf a\approx+c^2\nabla\ln Z_g=-c^2\nabla\ln\sqrt{-g_{00}}\to-\nabla\Phi$ (işaret düzeltmesi: $\ln Z_g\approx-\Phi/c^2$); (5) $\Phi_g\leftrightarrow\Phi_{\rm ch}^{\rm gen}=\lambda\ln\lvert Z_{\rm eff}/Z_{\rm ref}\rvert$ köprü adayı (gerçel genlik biçimi; karmaşık biçim $\lambda\ln(Z_{\rm eff}/Z_{\rm ref})$ faz bilgisi taşıyan ayrı bir model nesnesidir, 17.1a).

$$\boxed{\;Z_g \text{ yalnız Cₘ'de tanımlı bir genel görelilik okuma büyüklüğüdür; } c_0 \text{ ve } c^+ \text{'a taşınmaz.}\;}$$

```latex
\boxed{\;Z_g \text{ yalnız Cₘ'de tanımlı bir genel görelilik okuma büyüklüğüdür; } c_0 \text{ ve } c^+ \text{'a taşınmaz.}\;}
```

## 8.9 Shapiro gecikmesi — işlemsel gecikme okuması

Genel göreliliğin Shapiro gecikmesi ölçülmüş bir olgudur ve olduğu gibi kabul edilir. Evertophy okuması işlemseldir:

$$X_{\rm clock}(r) \equiv \pi_{\rm clock}[X](r), \qquad t_{\rm göz} = \int \frac{d\tau}{X_{\rm clock}(r)} \qquad (X_{\rm clock} > 0)$$

```latex
X_{\rm clock}(r) \equiv \pi_{\rm clock}[X](r), \qquad t_{\rm göz} = \int \frac{d\tau}{X_{\rm clock}(r)} \qquad (X_{\rm clock} > 0)
```

Köprüye eklenebilecek rastgele bir kalıntı adayı da arşivde kayıtlıdır:

$$\delta t = \delta t_{\rm GR} + \eta,\qquad \mathbb E[\eta] = 0,\qquad \mathrm{Var}(\eta) \propto \int F(\rho,Z)\,dx$$

```latex
\delta t = \delta t_{\rm GR} + \eta,\qquad \mathbb E[\eta] = 0,\qquad \mathrm{Var}(\eta) \propto \int F(\rho,Z)\,dx
```

| Sembol | Anlamı |
|---|---|
| $\pi_{\rm clock}$ | $X$'in saat okuma izdüşümü |
| $X_{\rm clock}(r)$ | Konuma bağlı saat okuması |
| $t_{\rm göz}$ | Gözlenen yol süresi |
| $\delta t_{\rm GR}$ | Genel göreliliğin öngördüğü gecikme |
| $\eta$ | Ortalaması sıfır rastgele kalıntı |
| $F(\rho,Z)$ | Yoğunluğa ve empedansa bağlı aday ağırlık fonksiyonu |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Shapiro gecikmesini $X$'in saat okumasının yol boyunca integrali olarak okur ve sınanabilir bir kalıntı adayı ekler |
| **Neden yapıyor?** | Evertophy okumasının genel görelilikten ayırt edilebileceği bir pencere (atarca zamanlama dizileri, girişimölçerler) aramak için |
| **Nasıl yapıyor?** | Saat okumasını konuma bağlı bir izdüşüm olarak yazar; gecikmeye ortalaması sıfır, varyansı ortama bağlı bir kalıntı ekler |
| **Ne sonuç bekleniyor?** | Kalıntı varyansının ölçülebilir bir imza vermesi |
| **Ne sonuç elde ediliyor?** | Bir **test tasarımıdır**, öngörü değildir; fiziksel köprü açıktır. Kritik güvenlik kısıtı $\partial X/\partial E_{\rm probe}=0$'dır (aktif akromatiklik, 7.4): LHAASO / GRB 221009A gibi gözlemlerin enerjiye bağlı gecikme sınırlarıyla uyum, köprünün Lorentz ihlali üretmemesini gerektirir |

## 8.10 Kozmik genişleme ve çöküş okuması

Kozmik ölçekte genişleme kolu c⁺ ile, çöküş kolu c₀ ile ilişkilidir (3.1). Nicel genişleme–çöküş dinamiği ve üç fazın denge denklemi **Türetim Bekleniyor** statüsündedir; tek satırlık bir eylemsizlik ilkesi olarak kilitlenmemiştir. Bu başlık tarihsel olarak korunur; güncel çekirdekteki karşılığı Bölüm 2'nin çift-limit tohumudur.




# BÖLÜM 9 — METRİK ONTOLOJİSİ

## 9.1 Metriğin tek alanı

$$\boxed{\;g_{\mu\nu} \text{ YALNIZ Cₘ'de kabul edilebilir bir nesnedir.}\;}$$

```latex
\boxed{\;g_{\mu\nu} \text{ YALNIZ Cₘ'de kabul edilebilir bir nesnedir.}\;}
```

Metrik Cₘ'nin **çıktısıdır**, girdisi değildir. Uzunluk, süre ve açı ölçmenin dili, maddenin farklılaştığı ve ölçümün kurulduğu fazda doğar; bu dili fazların kendisini tanımlamak için kullanmak, okuma aracını okunan şeyin yerine koymak olur.

## 9.2 Faz bariyeri ve Cₘ içinde geometrik gerçekleşme

Ontolojik çekirdek ölçüt şudur:

$$\boxed{\;\mathrm{MetricAdmissible}(\phi)\Longleftrightarrow \phi=C_m\;}$$

```latex
\boxed{\;\mathrm{MetricAdmissible}(\phi)\Longleftrightarrow \phi=C_m\;}
```

Tetrad $E^A{}_\mu$ (dört çerçeve vektörü), **yalnız Cₘ geometrisi kurulduktan sonra** kullanılabilen bir temsil aracıdır. Cₘ içinde dejenere olmayan bir Lorentz metriği için uygun tetrad rank koşulları incelenebilir; ama

$$\boxed{\;\operatorname{rank}(E)=4\;}$$

```latex
\boxed{\;\operatorname{rank}(E)=4\;}
```

ifadesi dış faz ontolojisinin faz bariyeri tanımı **değildir**.

### Tetrad dış fazlara sokulmaz

$$\boxed{\;\text{Tetrad, } c_0 \text{ ve } c^+ \text{'ta TANIMLI BİR NESNE DEĞİLDİR.}\;}$$

```latex
\boxed{\;\text{Tetrad, } c_0 \text{ ve } c^+ \text{'ta TANIMLI BİR NESNE DEĞİLDİR.}\;}
```

Bu yüzden "dış fazda rank düşer" denmez; doğru ifade, **tetrad ve metrik tipinin dış fazda kabul edilemez olduğudur**. Rank düşmesi hâlâ Cₘ'nin diliyle konuşmaktır; kabul edilemezlik ise o dilin orada hiç kurulmadığını söyler.

### Denklem seti — metrik faz bariyeri

$$g = E^{\mathsf T}\eta E,\quad \eta = \mathrm{diag}(-1,1,1,1),\quad E \in \mathbb{R}^{4\times4}:\qquad \det g = -(\det E)^2,\qquad \operatorname{rank} E = 4 \iff g \text{ dejenere olmayan Lorentz metriği}$$

```latex
g = E^{\mathsf T}\eta E,\quad \eta = \mathrm{diag}(-1,1,1,1),\quad E \in \mathbb{R}^{4\times4}:\qquad \det g = -(\det E)^2,\qquad \operatorname{rank} E = 4 \iff g \text{ dejenere olmayan Lorentz metriği}
```

| Sembol | Anlamı |
|---|---|
| $g$, $g_{\mu\nu}$ | Metrik tensör |
| $E$, $E^A{}_\mu$ | Tetrad matrisi (çerçeve bileşenleri) |
| $\eta$ | Minkowski metriği, işaret düzeni $(-,+,+,+)$ |
| $\det$ | Determinant |
| $\operatorname{rank}$ | Matrisin bağımsız satır / sütun sayısı |
| $\theta^a$ | Çerçeve 1-formları |
| $\mathrm{MetricAdmissible}(\phi)$ | $\phi$ fazında metriğin kabul edilebilir olup olmadığını söyleyen yüklem |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Metriği tetrad üzerinden kurar ve dejenere olmama koşulunu tetradın tam rankına bağlar |
| **Neden yapıyor?** | Metriğin hangi koşulda var olabileceğini açık bir matematiksel ölçüte bağlamak için |
| **Nasıl yapıyor?** | $\det g = -(\det E)^2$ özdeşliği sayesinde $g$'nin dejenere olmaması ile $E$'nin tam ranklı olmasını eşdeğer kılar |
| **Ne sonuç bekleniyor?** | Faz geçişlerinde tetradın $X$ ve faz bilgisinden yeniden kurulabilmesi (9.4) |
| **Ne sonuç elde ediliyor?** | Cₘ içinde **koşullu özdeşlik** olarak doğrudur. Rank koşulu metriğin Cₘ'deki gerçekleşme koşuludur; dış fazların tanımı değildir. Ontolojiden metriğin yeniden inşası **Daha Sonra Ele Alınacak** |

*Gösterim notu:* rank 4, bu inşanın **dejenere olmayan** bir Lorentz metriği vermesinin koşuludur; rank düşükken matris ifadesi yine yazılabilir ama dejeneredir.

## 9.2a Üç boyutlu Öklid düz uzay ve ortaya çıkan zaman

**Yazar hükmü:** Cₘ'nin temel uzayı, bildiğimiz $x$–$y$–$z$ koordinatlarından oluşan düz, üç boyutlu Öklid uzayıdır; dördüncü ya da ek bir boyut yoktur. Fiziksel zaman bu fazda **sonradan ortaya çıkar**; temel bir boyut değildir. c₀'da Cₘ tipi uzay ve zaman henüz kurulmamış, c⁺'ta çözünmüştür.

$$\boxed{\;\mathrm{Space}_{\rm temel}(C_m) = E^3,\qquad {}^{(3)}R_{ijkl}=0\;}$$

```latex
\boxed{\;\mathrm{Space}_{\rm temel}(C_m) = E^3,\qquad {}^{(3)}R_{ijkl}=0\;}
```

| Sembol | Anlamı |
|---|---|
| $\mathrm{Space}_{\rm temel}(C_m)$ | Cₘ'nin temel (ontolojik) uzayı |
| $E^3$ | Üç boyutlu Öklid uzayı |
| ${}^{(3)}R_{ijkl}$ | Üç boyutlu uzayın Riemann eğrilik tensörü; sıfır olması düzlük demektir |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Cₘ'nin temel uzayını düz, üç boyutlu Öklid uzayı olarak sabitler |
| **Neden yapıyor?** | Ölçülen eğrilik etkileri ile temel uzayın yapısını ayırmak için: eğrilik bir okumadır, temel uzayın bükülmesi değildir |
| **Nasıl yapıyor?** | Temel uzaya sıfır üç boyutlu eğrilik atar; 3+1 Lorentz metrik dilini Cₘ'nin etkin okuma geometrisi olarak ölçüm ve model katmanına yerleştirir |
| **Ne sonuç bekleniyor?** | Genel göreliliğin bütün gözlemsel sonuçlarının bu etkin geometriden geri kazanılması |
| **Ne sonuç elde ediliyor?** | Yazar hükmüdür. Merceklenme, Shapiro gecikmesi ve kütleçekim dalgaları gibi ölçülmüş eğrilik etkileri koşulsuz kabul edilir ve Çekim Kuvveti'nin metrik izdüşümünün **okumaları** olarak anlaşılır. Gözlemsel sonuçların etkin geometriden geri kazanılması **açık bir köprü problemidir**. Her eğri uzay-zaman düz uzaysal dilimlemeye izin vermez (örneğin Painlevé–Gullstrand koordinatlarının kurulamadığı küresel simetrik aileler vardır); bu yüzden $g^{\rm eff}_{\mu\nu}[E^3,X,\Delta]$ haritasının hangi genel görelilik çözüm ailelerini kapsadığı açıkça tanımlanmalıdır |

Bunun önemli bir sonucu vardır: genel göreliliğin **dört boyutlu eğri uzay-zamanı** temel bir yapı değil, Cₘ'nin sonradan ortaya çıkan etkin okuma geometrisidir. Bağlam olarak — kanıt sayılmadan —: kozmolojik veriler belirli modeller altında büyük ölçekte uzaysal eğriliği sıfıra yakın sınırlar; bu tam sıfırın kanıtı değildir. Fizikte genel göreliliğin düz bir arka plan üzerinde alan kuramı olarak yazılabildiği de bilinmektedir.

## 9.3 İki faz, iki farklı neden

| Faz | Metrik neden yok |
|---|---|
| **c₀** | Zaman-öncesidir; metrik **henüz kurulmamıştır** |
| **c⁺** | Cₘ madde desteği **çözülmüştür**; $g_{\mu\nu}^{(C_m)} \to \bot_+$ |

$$\boxed{\;\text{İki faz AYNI NEDENLE metrik dışı DEĞİLDİR.}\;}$$

```latex
\boxed{\;\text{İki faz AYNI NEDENLE metrik dışı DEĞİLDİR.}\;}
```

c₀'da metrik **henüz doğmamıştır**; c⁺'ta onu taşıyan destek **çözülmüştür**. Bu iki "yokluk" aynı sembolle yazılmaz: c₀'ın tanımsızlığı $\bot_0$, c⁺'ınki $\bot_+$'tır ve ikisi de sıfır değildir ($\bot_0\ne\bot_+\ne0$).

## 9.4 Metriğin yeniden inşası — iki ayrı yol

Bir fazdan Cₘ'ye geçişte eski metrik **taşınmaz**; yeni Cₘ durumu kendi metriğini yeniden kurar.

$$\mathcal{E}_m^{(0)} : (\Delta_{0m},\, X,\, \Theta_m) \to E^A{}_\mu, \qquad\qquad \mathcal{E}_m^{(+)} : (\Delta_{+m},\, X,\, \Theta_m) \to E^A{}_\mu$$

```latex
\mathcal{E}_m^{(0)} : (\Delta_{0m},\, X,\, \Theta_m) \to E^A{}_\mu, \qquad\qquad \mathcal{E}_m^{(+)} : (\Delta_{+m},\, X,\, \Theta_m) \to E^A{}_\mu
```

Her iki durumda:

$$g_{\mu\nu} = \eta_{AB}\,\mathcal{E}^A{}_\mu\,\mathcal{E}^B{}_\nu, \qquad\qquad \text{başarı koşulu: } \operatorname{rank}\mathcal{E}_m = 4$$

```latex
g_{\mu\nu} = \eta_{AB}\,\mathcal{E}^A{}_\mu\,\mathcal{E}^B{}_\nu, \qquad\qquad \text{başarı koşulu: } \operatorname{rank}\mathcal{E}_m = 4
```

| Sembol | Anlamı |
|---|---|
| $\mathcal{E}_m^{(0)}$ | c₀ → Cₘ geçişinde tetradı kuran harita |
| $\mathcal{E}_m^{(+)}$ | c⁺ → Cₘ geçişinde tetradı kuran harita |
| $\Delta_{0m}$, $\Delta_{+m}$ | İlgili geçiş kenarlarının faz farkı / geçiş bilgisi (Bölüm 5) |
| $X$ | Dinamik üst çözücü |
| $\Theta_m$ | Cₘ'nin kabul koşulları (kapı / izin parametreleri) |
| $\eta_{AB}$ | Çerçeve uzayında Minkowski metriği |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | İki farklı girişten (c₀'dan ve c⁺'tan) Cₘ'ye gelişte metriğin nasıl yeniden kurulacağını iki ayrı harita olarak yazar |
| **Neden yapıyor?** | Eski metriğin geçişte taşınamayacağını ve iki girişin aynı olay olmadığını matematiksel olarak açık kılmak için |
| **Nasıl yapıyor?** | Her harita kendi kenar bilgisini, $X$'i ve Cₘ kabul koşullarını alıp bir tetrad üretir; metrik bu tetraddan kurulur |
| **Ne sonuç bekleniyor?** | c₀'dan gelişin geometriyi **yeni kurması**, c⁺'tan gelişin madde desteğini **yeniden kazandırması**; iki haritanın açık biçimleri |
| **Ne sonuç elde ediliyor?** | Yalnız **yapı** yazılmıştır; iki haritanın aynı olması gerekmez ve açık biçimleri bilinmemektedir (9.5) |

## 9.5 Kalan boşluk

$$\mathcal{E}_m^{(0)}[\cdot] = ?, \qquad \mathcal{E}_m^{(+)}[\cdot] = ?$$

```latex
\mathcal{E}_m^{(0)}[\cdot] = ?, \qquad \mathcal{E}_m^{(+)}[\cdot] = ?
```

Tetradın $X$'ten ve faz geçişinden nasıl türetileceği **açıktır**. Bu boşluk dürüstçe bırakılır; çerçeve, metriğin nereden geldiğini söylemeden metriği kullanmaz.

## 9.6 Dış fazlar için eylem yazılmaz

$$\boxed{\;c_0 \text{ ve } c^+ \text{ için dört boyutlu eylem / Lagrange yoğunluğu YAZILMAZ.}\;}$$

```latex
\boxed{\;c_0 \text{ ve } c^+ \text{ için dört boyutlu eylem / Lagrange yoğunluğu YAZILMAZ.}\;}
```

Standart Cₘ tipi eylem integrali $\sqrt{-g}\,d^4x$ ölçüsünü kullanır; bu ölçü dış fazlarda tanımlı değildir. Metriksiz ya da topolojik eylem biçimleri matematiksel olarak mümkündür; Evertophy dış fazlarda yalnız Cₘ tipi dört boyutlu metrik eylemini dışlar. Evertophy'nin kullandığı eylemler **Cₘ'ye aittir**.

---

# BÖLÜM 10 — MADDE ONTOLOJİSİ

## 10.1 Üç fazda madde

| Faz | Maddenin durumu |
|---|---|
| **c₀** | Farklılaşma ortadan kalkmış; madde Planck ölçeğinde metrik boşluksuz duruma yakınsayan derecede bitişik, **tümleşik tek bir yapı** formundadır |
| **Cₘ** | **Farklılaşmış madde**: parçacıklar, atomlar, yapılar |
| **c⁺** | Cₘ madde desteği **çözülmüştür**; Cₘ madde türü kabul edilemez. Cₘ'nin "boşluk" okuduğu her bölge — atomu oluşturan parçacıkların arasındaki boşluk dahi — c⁺'ın Cₘ okumasıdır |

## 10.2 İki geçiş, iki farklı olay

$$\boxed{\;C_m \to c_0: \text{ farklılaşmış madde} \to \text{METRİK BOŞLUKSUZ TEK-YAPI}\;}$$

```latex
\boxed{\;C_m \to c_0: \text{ farklılaşmış madde} \to \text{METRİK BOŞLUKSUZ TEK-YAPI}\;}
```

$$\boxed{\;C_m \to c^+: \text{ Cₘ madde desteği} \to \text{ÇÖZÜLME / KABUL EDİLEMEZLİK}\;}$$

```latex
\boxed{\;C_m \to c^+: \text{ Cₘ madde desteği} \to \text{ÇÖZÜLME / KABUL EDİLEMEZLİK}\;}
```

Bunlar **aynı olay değildir**. Birincisinde madde birleşir ve ayrım kaybolur: parçacıklar arasındaki metrik boşluk kapanır ve madde tek bir form olur. İkincisinde maddenin Cₘ'deki dayanağı ortadan kalkar: yapı çözünür, enerjisi c⁺'ta mühürlenir. Biri toplanma, diğeri çözülmedir.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Maddenin Cₘ'den iki dış faza geçişini iki ayrı olay olarak tanımlar |
| **Neden yapıyor?** | "Madde kayboluyor" ifadesi iki zıt süreci — tek yapıya toplanmayı ve çözülmeyi — aynı kelimeyle karıştırırdı |
| **Nasıl yapıyor?** | c₀ yönünü bitişik tek-yapı oluşumu, c⁺ yönünü madde desteğinin kabul edilemez hâle gelmesi olarak ayrı ayrı yazar |
| **Ne sonuç bekleniyor?** | Her iki geçiş için ayrı nicel köprüler (c₀ için $\rho\le\rho_P$ ve kapasite ölçeklemesi, c⁺ için çözünme ve mühür) |
| **Ne sonuç elde ediliyor?** | Ontolojik ayrım kanondur; c₀ tek-yapı okuması yazar hükmüdür (Bölüm 3). Geçişlerin dinamik yasaları açıktır |

## 10.3 Parçacık kavramı

Parçacık, Cₘ'de belirli okuma koşullarının ürettiği bir **izdüşümdür**. İki gözlemcinin farklı parçacık sayması ontolojik bir çelişki değildir.

**Dürüst not:** Bu, standart kuantum alan kuramının işlemsel okumasıyla büyük ölçüde örtüşür. Evertophy burada yeni bir pozisyon üretmez; var olan bir pozisyona **katılır**.

---

# BÖLÜM 11 — c⁺ VE KARANLIK SEKTÖR

## 11.1 İç ontolojik kimlik

$$\boxed{\;c^+ \;\equiv\; \text{KARANLIK MADDE} \;\equiv\; \text{KARANLIK ENERJİ} \;\equiv\; \text{VAKUM}\;}$$

```latex
\boxed{\;c^+ \;\equiv\; \text{KARANLIK MADDE} \;\equiv\; \text{KARANLIK ENERJİ} \;\equiv\; \text{VAKUM}\;}
```

Evertophy'nin iç ontolojisinde bunlar **aynı varlıktır**. Karanlık madde, karanlık enerji ve vakum üç ayrı şey değil, aynı fazın Cₘ'den bakıldığında farklı görünen yüzleridir. Kuantum alan kuramının vakum hesapları bu kimliğin Cₘ içindeki hesap dilidir (Bölüm 3).

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Karanlık maddeyi, karanlık enerjiyi ve vakumu tek bir faz kimliğine bağlar |
| **Neden yapıyor?** | Üç ayrı bilinmeyen gibi görünen şeyi aynı fazın üç okuması olarak birleştirmek, çerçevenin ontolojik ekonomisinin merkezidir |
| **Nasıl yapıyor?** | Ayrımı enerjetik bir fark olarak değil, yoğunluk, topoloji ve okuma ortamı farkı olarak koyar (11.1a) |
| **Ne sonuç bekleniyor?** | Her görünüm için ayrı nicel köprü: dönme eğrileri ve merceklenme, hızlanan genişleme, vakum etkileri |
| **Ne sonuç elde ediliyor?** | Kimlik kanondur; her gözlemsel olgu için nicel mekanizma **açıktır** (11.2) |

## 11.1a Karanlık madde ve karanlık enerji: kümelenmiş ve genişlemeyi sürdüren c⁺

Karanlık madde ile karanlık enerji iki ayrı gizemli bileşen değildir; **aynı c⁺ yapısının iki farklı görünümüdür**. Ayrım enerjetik değil, **yoğunluk ve topoloji** farkıdır. Laboratuvar ölçeğinde ise aynı c⁺ vakum olarak okunur.

| Görünüm | Cₘ'deki okuma |
|---|---|
| **Kümelenmiş c⁺** → karanlık madde | Madde kümeleriyle ilişkili okunan c⁺ etkisi. Gözlenen ek kütleçekimsel etki — galaktik dönme eğrileri, kütleçekimsel merceklenme — bu görünümün Cₘ'deki okumasıdır |
| **Genişlemeyi sürdüren c⁺** → karanlık enerji | Madde baskısından uzak, düşük madde yoğunluklu bölgelerde okunan, genişlemeyle ilişkili c⁺ etkisi |
| **Laboratuvar ölçeğinde c⁺** → vakum | Ölçüm düzeneğinde ve atom içinde "boşluk" olarak okunan c⁺; Casimir etkisi gibi vakum olguları bu okumadır |

Kimlik ile okuma ayrımı tip düzeyinde şöyle yazılır:

$$\mathrm{Okuma}_{C_m}(c^+;\mathcal C)=\begin{cases}\mathrm{DM}_{\rm etkin}, & \mathcal C=\text{galaksi / küme}\\ \mathrm{DE}_{\rm etkin}, & \mathcal C=\text{kozmolojik genişleme}\\ \mathrm{Vak}_{\rm etkin}, & \mathcal C=\text{laboratuvar / atom içi}\end{cases}$$

```latex
\mathrm{Okuma}_{C_m}(c^+;\mathcal C)=\begin{cases}\mathrm{DM}_{\rm etkin}, & \mathcal C=\text{galaksi / küme}\\ \mathrm{DE}_{\rm etkin}, & \mathcal C=\text{kozmolojik genişleme}\\ \mathrm{Vak}_{\rm etkin}, & \mathcal C=\text{laboratuvar / atom içi}\end{cases}
```

| Sembol | Anlamı |
|---|---|
| $\mathrm{Okuma}_{C_m}(c^+;\mathcal C)$ | c⁺'ın $\mathcal C$ gözlem bağlamındaki Cₘ okuması |
| $\mathcal C$ | Cₘ gözlem bağlamı |
| $\mathrm{DM}_{\rm etkin}$, $\mathrm{DE}_{\rm etkin}$, $\mathrm{Vak}_{\rm etkin}$ | Karanlık madde, karanlık enerji ve vakum olarak okunan etkin görünümler |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Tek bir ontolojik nesnenin üç farklı gözlem bağlamında üç farklı Cₘ okuması verdiğini tip düzeyinde yazar |
| **Neden yapıyor?** | "≡" işaretinin bir enerji–momentum denklemi ya da gözlenen yoğunluk / basınç eşitliği gibi okunmasını önlemek için |
| **Nasıl yapıyor?** | Kimliği tek bir kaynakta tutar; farkı okuma bağlamına yükler |
| **Ne sonuç bekleniyor?** | Her bağlam için yoğunluk, basınç ve pertürbasyon dinamiklerini veren fiziksel seçicinin kurulması |
| **Ne sonuç elde ediliyor?** | **Tip ayrımıdır**; c⁺'ı üç ayrı faza bölmez. Okumaların nicel mekanizması açıktır (11.2, EK K.1) |

Arşivde ilk iki görünüm için "tutuklu" ve "serbest" adlandırmaları da geçer; birincil terimler yukarıdakilerdir.

Bu okumanın beş inceliği vardır:

- **"Dış çeper" mekânsal bir kenar değildir.** "Dış" ontolojik anlamda kullanılır: madde baskısından uzak, kümelenmemiş görünüm. c⁺'ta üç boyutlu uzay çözünmüş olduğundan, c⁺'ın kendisinin mekânsal bir kenarda bulunması tanımlı değildir. Okumanın izotropi ve homojenlik ölçümleriyle nicel uyumu henüz gösterilmemiştir; bu, model ve gözlemle sınanacak bir koşuldur.
- **Ölçüm ile okuma ayrıdır.** Ölçülen şey genişlemenin **hızlanmasıdır** ve koşulsuz kabul edilir. Uzak galaksilerin ışıktan hızlı uzaklaşması standart kozmolojinin de sonucudur ve yerel bir ışık-üstü hareket değildir. c⁺'ın c-ötesi niteliğiyle genişleme arasındaki bağ Evertophy okumasıdır.
- **Kaynak ile görünüm ayrıdır.** c⁺'ın kendi fazında Cₘ tipi durgun kütle ve metrik yoktur; ama c⁺ kaynaklı etkinin Cₘ'deki görünümü kütleçekimsel ya da metrik bir okuma olabilir. Çekim Kuvveti ≠ kütleçekim ayrımı, kaynak faz ile Cₘ'deki ölçüm dili arasında uygulanır (1.2). Kapı kilidi bu okumayı engellemez (13.1a).
- **Kimlik, eşit yoğunluk demek değildir.** c⁺ ≡ karanlık madde ≡ karanlık enerji ≡ vakum kimliği, gözlenen karanlık madde yoğunluğunun karanlık enerji yoğunluğuna eşit olduğu anlamına gelmez; okuma gösterimi gözlem katmanını tarif eder, kimliği değil.
- **Nicel mekanizma açıktır.** c⁺'tan karanlık madde ve karanlık enerjinin farklı basınç, kümelenme ve genişleme davranışlarına giden nicel köprü açık borçtur (EK K).

## 11.2 Kimlik ile mekanizma ayrılır

$$\boxed{\;\text{ONTOLOJİK KİMLİK, NİCEL GÖZLEMSEL TÜRETİM DEĞİLDİR.}\;}$$

```latex
\boxed{\;\text{ONTOLOJİK KİMLİK, NİCEL GÖZLEMSEL TÜRETİM DEĞİLDİR.}\;}
```

Şunlar **ayrı ayrı türetilmedikçe** model / köprü düzeyindedir:

- "Kümelenmiş c⁺ tam olarak karanlık madde mekanizmasıdır"
- "Genişlemeyi sürdüren c⁺ tam olarak karanlık enerji mekanizmasıdır"
- Dönme eğrileri, kütleçekimsel merceklenme ve hızlanan genişleme için nicel açıklamalar

Kimlik iddiası ontolojiktir; **her bir gözlemsel olgu için ayrı bir türetim gerekir** ve bunların hiçbiri henüz yapılmamıştır.

### Yazar kanonu — c⁺'ın karanlık sektör görünümleri ve kapalı devre

Üç fazın $U_0$ tarafından aynı kuruluşta birlikte doğumu korunur. Bu mimaride c⁺, **karanlık madde ve karanlık enerjinin aynı faz varlığının iki Cₘ görünümü** olarak okunmasının kaynağıdır:

$$\boxed{\;c^+\equiv{\rm DM}\equiv{\rm DE}\equiv\text{Vakum}\quad\text{(ontolojik kimlik; Cₘ görünümleri farklı)}\;}$$

```latex
\boxed{\;c^+\equiv{\rm DM}\equiv{\rm DE}\equiv\text{Vakum}\quad\text{(ontolojik kimlik; Cₘ görünümleri farklı)}\;}
```

**Kümelenmiş görünüm:** c⁺'ın galaktik ve küme ölçeğinde kütleçekimsel olarak belirginleşen, **parçacık olmayan** yapılanma rejimidir. Arşivdeki "kütleçekimle ışık hızı limitini aşmış" ifadesinin tür-güvenli okuması şudur:

$$\boxed{\;\text{Cₘ'nin } 0<v<c \text{ madde üyelik bandı artık uygulanabilir değildir}\;\neq\;v_{c^+}>c\text{ biçiminde içsel hız iddiası}\;}$$

```latex
\boxed{\;\text{Cₘ'nin } 0<v<c \text{ madde üyelik bandı artık uygulanabilir değildir}\;\neq\;v_{c^+}>c\text{ biçiminde içsel hız iddiası}\;}
```

| Sembol | Anlamı |
|---|---|
| $0<v<c$ | Cₘ'nin madde üyelik bandı (yazar hükmü) |
| $v=c$ | Bandın üyesi değil, Cₘ ile c⁺'ın liminal ortak sınırı (sınır ≠ üyelik) |
| $v_{c^+}$ | c⁺'a atfedilen içsel hız — tanımlı **değildir** |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | "Işık hızını aşmış" arşiv ifadesini, c⁺'a bir hız atamayan tür-güvenli bir biçime çevirir |
| **Neden yapıyor?** | Cₘ'nin hız tipini c⁺'a taşımak, kategori hatası olurdu ve göreliliğin ölçülmüş sonuçlarıyla gereksiz bir çatışma yaratırdı |
| **Nasıl yapıyor?** | "Bandın uygulanabilir olmaması" ile "banttan büyük bir hız değeri" arasındaki farkı açıkça yazar |
| **Ne sonuç bekleniyor?** | Kümelenmiş görünüm için hızdan bağımsız, faz rejimine dayanan nicel bir okuma |
| **Ne sonuç elde ediliyor?** | Ontolojik kısım — c⁺'ın c-ötesi bir rejim olması ve Cₘ tipi hızın orada uygulanamaması — 3.4'teki kilitli formülasyondur. Arşiv ifadesinin **nihai matematiksel temsili** onay bekleyen yorumdur |

Dolayısıyla bu kayıt "ışık-üstü madde"yi geri getirmez; c⁺'ta Cₘ hız tipinin, metriğin ve madde desteğinin tanımsızlığını korur. Cₘ gözleminde görülen kütleçekimsel etki, c⁺ rejiminin **Cₘ okumasıdır**.

**Genişlemeyi sürdüren görünüm:** aynı ontolojik c⁺ rejiminin kozmik ölçekteki genişleme / karanlık enerji görünümüdür. Kümelenmiş ve genişlemeyi sürdüren görünümler iki ayrı töz değil, aynı faz kimliğinin farklı Cₘ okuma rejimleridir.

**Kapalı devre bağlantısı:** Bu kimlik, Bölüm 2.4'te çekirdek tohumu olarak tutulan çift-limit yapısının seyrelme koluyla birlikte okunur; tam döngü yasası ve matematiksel devre mekanizması V24'e ayrılmıştır.

$$\boxed{\;c^+ \text{ ETKİ EDER; kontrol edilebilir bir kanal ya da içsel hız sektörü DEĞİLDİR.}\;}$$

```latex
\boxed{\;c^+ \text{ ETKİ EDER; kontrol edilebilir bir kanal ya da içsel hız sektörü DEĞİLDİR.}\;}
```

## 11.3 c⁺'a Cₘ kavramları aynen taşınmaz

Güncel kısıt şudur:

$$\boxed{\;\mathrm{supp}_{C_m}(\mathrm{madde})\to\varnothing\;}$$

```latex
\boxed{\;\mathrm{supp}_{C_m}(\mathrm{madde})\to\varnothing\;}
```

| Sembol | Anlamı |
|---|---|
| $\mathrm{supp}_{C_m}(\mathrm{madde})$ | Maddenin Cₘ'deki dayanağı (desteği) |
| $\varnothing$ | Boş küme |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | c⁺'a geçişte Cₘ madde desteğinin boş kümeye gittiğini söyler |
| **Neden yapıyor?** | c⁺'ın, Cₘ'nin durgun kütle, metrik uzunluk, fiziksel süre ya da hız tiplerini aynı anlamla taşıyan bir sektör gibi okunmasını engellemek için |
| **Nasıl yapıyor?** | Madde desteğinin limitini boş küme olarak yazar; c⁺'a yeni bir Cₘ tipi nicelik atamaz |
| **Ne sonuç bekleniyor?** | c⁺ okumalarının yalnız Cₘ'deki etkileri üzerinden kurulması |
| **Ne sonuç elde ediliyor?** | Tür güvenliği kuralı olarak kanondur. Tarihsel K2'deki soyut `Dim.mass` izin kaydı köken bilgisi olarak saklanır; güncel c⁺ içinde bağımsız bir Cₘ tipi kütle gözlenebiliri tanımlamaz |

## 11.4 Kozmolojik yönelim

Kozmik çağ ilerledikçe Cₘ okumasında c⁺ bileşeninin katkısının artması, çerçeve içinde **meşru bir yönelimdir**.

$$\boxed{\;\text{Bu bir YÖNELİM kaydıdır — nicel bir kozmolojik model DEĞİLDİR.}\;}$$

```latex
\boxed{\;\text{Bu bir YÖNELİM kaydıdır — nicel bir kozmolojik model DEĞİLDİR.}\;}
```

İfade dikkatli kurulmalıdır: c⁺'ın kendisi "zamanla değişmez" — c⁺'ta zaman yoktur; değişen, Cₘ okumasındaki payıdır.

## 11.4a c⁺ ile U₊ karıştırılmaz

$c^+$ bir **fazdır** ve $U_x$'in içindedir. $U_+$ ise global **çözünme kutbudur** ve $U_x$'in dışındadır (Bölüm 2.6). Kozmik çağla c⁺ payının artması faz düzeyinde bir okumadır; $U_+$'a yaklaşmak global bir koşuldur.

## 11.5 Kapalı devre

| Sıra | Gerekçe |
|---|---|
| **Temel** | **Akademik-bilimsel sınır** — metafizik yorumu önlemek |
| İkincil | Gözlemsizlik |

$$\boxed{\;c^+ \text{ ETKİ EDER ama SİNYAL KANALI DEĞİLDİR: kontrol edilebilir, bilgi taşıyan bir bağ kurulamaz.}\;}$$

```latex
\boxed{\;c^+ \text{ ETKİ EDER ama SİNYAL KANALI DEĞİLDİR: kontrol edilebilir, bilgi taşıyan bir bağ kurulamaz.}\;}
```

Bu, kuantum ışınlama deneyleriyle de tutarlıdır: ışınlama klasik bir kanal gerektirir; c⁺ yalnız korelasyonun kaynağı olarak okunur, bilgiyi taşıyan kanal değildir.

## 11.6 c⁺ bir kehanet kaynağı değildir

$$\boxed{\;c^+ \text{ ARŞİVİNE ERİŞİM} \;\neq\; \text{Cₘ GELECEĞİNİ OKUMAK}\;}$$

```latex
\boxed{\;c^+ \text{ ARŞİVİNE ERİŞİM} \;\neq\; \text{Cₘ GELECEĞİNİ OKUMAK}\;}
```

c⁺'ta zaman yoktur; dolayısıyla orada "gelecek" de yoktur. Arşiv yalnız yazılmış olanı tutar.

---

## 11.7 Kozmolojik köprü adayları — model / program düzeyi

c⁺ ≡ karanlık madde ≡ karanlık enerji ≡ vakum iç ontolojik kimliği çekirdektir; bunun Cₘ gözlemlerine hangi nicel köprüyle yansıdığı ise açık programdır.

| Aday mekanizma | Gerekli türetim | Gözlenebilir hedef | Eleme koşulu |
|---|---|---|---|
| Ölçeğe bağlı etkin kütleçekim okuması | $X$ ve faz koşullarından $\kappa_g(\text{ölçek})$ | Hubble gerilimi benzeri ölçek farkları | Parametre uydurmadan belirgin bir bant üretilemezse |
| c⁺ karanlık sektör okuması | c⁺ → Cₘ merceklenme / dinamik eşlemesi | Galaksi ve küme dinamiği, merceklenme | Baryonik madde + köprü modeli gözlemi birlikte karşılayamazsa |
| Seyrelme / kozmik eylemsizlik | Devre ve limit yapısından nicel yasa | Hızlanan genişleme okuması | Yalnız slogan düzeyinde kalırsa |
| Kırmızıya kaymanın faz düzeyinde yorumu | Standart kırmızıya kayma ilişkisini bozmadan ek bir neden katmanı | Spektral ve kozmolojik tutarlılık | Genel görelilik / kuantum alan kuramı limitini yanlış üretirse |

$$\boxed{\;\text{“uyumlu okuma”}\neq\text{“çözdü / doğruladı”}\;}$$

```latex
\boxed{\;\text{“uyumlu okuma”}\neq\text{“çözdü / doğruladı”}\;}
```

Hubble gerilimi, Mermi Kümesi (Bullet Cluster) ya da hızlanan genişleme gibi başlıklar bugünkü kanıt değil, **köprü yanlışlama programı** olarak ele alınır.

## 11.8 Karanlık madde arayışının paradigma eleştirisi — kayıt

Çerçevenin karanlık madde deneylerine karşı konumu gözlük benzetmesiyle özetlenir:

$$\boxed{\;\text{"Onlar görüntüyü bozan görünmez nesneyi arıyor; biz ortamın kırıcılık indisinin değişken olduğunu söylüyoruz."}\;}$$

```latex
\boxed{\;\text{"Onlar görüntüyü bozan görünmez nesneyi arıyor; biz ortamın kırıcılık indisinin değişken olduğunu söylüyoruz."}\;}
```

Bu bir paradigma eleştirisidir, deney sonuçlarının reddi değildir. Deney programlarının sıfır sonuçları Evertophy **üzerine konan kısıtlardır**: hiçbir sıfır sonuç c⁺ ≡ karanlık madde ≡ karanlık enerji ≡ vakum kimliğini kanıtlamaz; kimlik ancak pozitif bir köprü öngörüsüyle sınanabilir (11.7). Karanlık madde adaylarının çeşitliliği ("karanlık madde hayvanat bahçesi" kaydı) tek bir parçacık adayının zayıfladığını gösteren gözlemsel bağlam olarak korunur — yine de bağlam, kanıt değildir.

## 11.9 Fantom sınırı geçişi okuması

Karanlık enerji durum denkleminin $w=-1$ çizgisini geçmesi (fantom bölgesi), çerçevede "c⁺ payının Cₘ okumasındaki rejim değişimi" olarak okunmaya adaydır. Literatürde fantom geçişi gözlemleri destekleyici bağlam olarak izlenir; nicel eşleme yoktur.

*Kırmızıya kayma alanı:* fiziksel alan $z>-1$'dir; genişlemenin sınırsız geleceği $z\to-1^+$'dır. $z\to-\infty$ yalnız matematiksel bir uzantıdır.

*Durum denklemi alanı:* $w=-1$ kozmolojik sabite karşılık gelir; $w<-1$ fantom bölgesidir. Fantom bölgesi null enerji koşulunu ihlal eder, ama gözlemsel olarak dışlanmış değildir; bu yüzden $w\ge-1$ "fiziksel alan" olarak yazılmaz.

$$\boxed{\;\text{"Uyumlu okuma"}\neq\text{"çözdü / doğruladı" — 11.7 hükmü burada da geçerlidir.}\;}$$

```latex
\boxed{\;\text{"Uyumlu okuma"}\neq\text{"çözdü / doğruladı" — 11.7 hükmü burada da geçerlidir.}\;}
```

---

### Denklem seti — A1 lojistik okuma modeli

$X$'in kırmızıya kaymaya göre lojistik bir okumasından karanlık enerji durum denklemi $w(z)$'yi türetmeye çalışan bir **modeldir**:

$$w = -1 + \frac{(1+z)s}{3\Delta}\cdot\frac{(T - X_{\min})(X_{\max} - T)}{T(1-T)}\cdot\big[p(1-T) - qT\big]$$

```latex
w = -1 + \frac{(1+z)s}{3\Delta}\cdot\frac{(T - X_{\min})(X_{\max} - T)}{T(1-T)}\cdot\big[p(1-T) - qT\big]
```

Karşı örnek ($X_{\min}=0$, $X_{\max}=1$, $s=p=q=1$, $z_t=0$):

$$w = -1 + \tfrac{(1+z)(1-2X)}{3},\qquad w(10) = -4.66633374896$$

```latex
w = -1 + \tfrac{(1+z)(1-2X)}{3},\qquad w(10) = -4.66633374896
```

$$z \to +\infty:\ w/z \to -\tfrac13, \qquad z \to -\infty:\ w/z \to +\tfrac13, \qquad \text{her iki uçta } w \to -\infty$$

```latex
z \to +\infty:\ w/z \to -\tfrac13, \qquad z \to -\infty:\ w/z \to +\tfrac13, \qquad \text{her iki uçta } w \to -\infty
```

Doğru koşul ($0 \leq u < v \leq 1$, $s>0$, $p,q$ sonlu; $u=X_{\min}$, $v=X_{\max}$):

$$(u > 0 \lor p = 0) \wedge (v < 1 \lor q = 0) \;\Rightarrow\; w \to -1 \text{ iki uçta}$$

```latex
(u > 0 \lor p = 0) \wedge (v < 1 \lor q = 0) \;\Rightarrow\; w \to -1 \text{ iki uçta}
```

| Sembol | Anlamı |
|---|---|
| $X(z)$ | Lojistik okuma: $1/[1 + e^{-s(z - z_t)}]$ ($X$'in kendisi değil, bir izdüşümü) |
| $T$ | $X_{\min} + \Delta\,X(z)$ |
| $\Delta$ | $X_{\max} - X_{\min}$ |
| $X_{\min}$, $X_{\max}$ ($u$, $v$) | Okumanın alt ve üst sınırı |
| $s$, $z_t$ | Diklik ve geçiş kırmızıya kayması |
| $p$, $q$ | Üstel ağırlık parametreleri |
| $z$ | Kırmızıya kayma; $1+z=a_{\rm ref}/a$, $a>0$ |
| $w$ | Karanlık enerji durum denklemi parametresi (basınç / enerji yoğunluğu) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | $X$'in kırmızıya kaymaya bağlı lojistik bir okumasından $w(z)$'yi hesaplar |
| **Neden yapıyor?** | Kozmolojik $w$ ölçümleriyle temas kuracak sınanabilir bir model aramak için |
| **Nasıl yapıyor?** | Okumayı alt ve üst sınırlar arasında lojistik bir eğri olarak kurar; ağırlık parametreleriyle durum denklemine bağlar |
| **Ne sonuç bekleniyor?** | İki uçta $w\to-1$ veren, gözlemle uyumlu bir eğri |
| **Ne sonuç elde ediliyor?** | **Koşullu modeldir.** Koşulsuz çift asimptot iddiası **yanlıştır**: karşı örnekte her iki uçta $w\to-\infty$ çıkar; $w\to-1$ ancak yukarıdaki doğru koşul sağlanırsa elde edilir. Model K1v2 çekirdeği değildir; kaynak türetimi (MINILAB-4) **Daha Sonra Ele Alınacak** |




# BÖLÜM 12 — EŞİK VE YAPI BANTLARI

## 12.1 İki kanallı eşik

Bir yapının Cₘ'den dış fazlardan birine yönelmesi iki ayrı kanaldan okunur: kütle kanalı c₀'a, enerji kanalı c⁺'a doğru işler.

### Kütle kanalı

$$\text{yıldız kütlesi} \;\to\; \text{kritik kütle eşiği} \;\to\; \text{doygunluk} \;\to\; \text{kara delik oluşumu}$$

```latex
\text{yıldız kütlesi} \;\to\; \text{kritik kütle eşiği} \;\to\; \text{doygunluk} \;\to\; \text{kara delik oluşumu}
```

Kara delik oluşumu dış fizikte yerleşik bir olgudur. Evertophy'de bu kanalın sonu, maddenin Planck ölçeğinde metrik boşluksuz duruma yakınsayan derecede bitişik tek bir yapıya dönüşmesidir; yoğunluk $\rho\le\rho_P$ sınırını aşamaz, kütle arttıkça yapı yoğunlaşmaz, büyür (Bölüm 3). Kütle kanalı için nicel eşik ve geçiş yasası ise henüz türetilmemiştir. Kara delik ≡ c₀, bu mekanizmanın sonucu olarak sunulan bir çıkarım değil, yazarın ontolojik tanımıdır (3.2).

### Enerji kanalı

$$\text{ışıma} \;\to\; c^+ \text{ bandına yakınsama} \;\to\; \text{enerji tükenişi} \;\to\; \text{seyrelme}$$

```latex
\text{ışıma} \;\to\; c^+ \text{ bandına yakınsama} \;\to\; \text{enerji tükenişi} \;\to\; \text{seyrelme}
```

$$\boxed{\;\text{Enerji kanalı MODEL / KAVRAMSAL düzeydedir.}\;}$$

```latex
\boxed{\;\text{Enerji kanalı MODEL / KAVRAMSAL düzeydedir.}\;}
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Cₘ yapılarının dış fazlara yönelişini iki kanala ayırır: kütle birikimiyle c₀'a, ışıma ve tükenişle c⁺'a |
| **Neden yapıyor?** | İki yönün farklı fiziksel süreçlerle işlediğini ve aynı eşikle okunamayacağını göstermek için |
| **Nasıl yapıyor?** | Her kanalı ardışık aşamalar zinciri olarak yazar; ikisini de keskin bir sınır değil, **geçişli bir bant** olarak kurar |
| **Ne sonuç bekleniyor?** | Her iki kanal için ölçeğe ve kütle miktarına bağlı nicel eşikler (13.2) |
| **Ne sonuç elde ediliyor?** | Kütle kanalının son durağı ontolojik tanımdır (kara delik ≡ c₀); nicel eşik yasaları açıktır. Enerji kanalı kavramsal düzeydedir |

## 12.2 Bant merdiveni — model / harita adayı

Aşağıdaki yerleşimler güncel çekirdeğin zorunlu sayısal faz ataması değildir; arşivdeki **harita / model adaylarıdır**.

| Nesne | Harita yerleşimi |
|---|---|
| Kahverengi cüce | Cₘ bandının hemen öncesi |
| Nötrino-magnetar | c₀ ön bölgesi |
| Elektron-nötrino yapıları | c⁺ köşe bandı |

**Bölüm 3.7'nin uyarısı geçerlidir:** bunlar **harita konumudur**, faz üyeliği değil.

## 12.2a Yoğunluk spektrumu — yoğunluk-rejim benzetmesi

Aşağıdaki sıra ölçülmüş evrensel yoğunluk eşikleri değil, **sıralı bir yapı / yoğunluk benzetmesidir**:

| Yoğunluk-rejim etiketi | Tarihsel yapı eşlemesi |
|---|---|
| **Nihai** | Kara delik içindeki metrik boşluksuz tek-yapı |
| **Süper** | Nötron yıldızı çekirdeği |
| **Çok yüksek ("Kristal")** | Atom çekirdeği |
| **Yüksek ("Sıvı")** | Elektron bulutu / atomik madde |
| **Orta ("Gaz")** | Galaksi halesi; karanlık maddenin Cₘ okumasıyla ilişkili |
| **Düşük ("Buhar")** | Galaksiler arası boşluk |

$$\boxed{\;\text{Bu etiketler faz üyeliği değildir; yalnız yoğunluk-rejim benzetmesidir.}\;}$$

```latex
\boxed{\;\text{Bu etiketler faz üyeliği değildir; yalnız yoğunluk-rejim benzetmesidir.}\;}
```

Bölüm 3.7'nin "harita konumu ≠ faz üyeliği" kuralı burada da geçerlidir. Bu tablo sayısal eşik üretmez ve "Kristal / Sıvı / Gaz / Buhar" sözcüklerini gerçek madde fazları olarak kullanmaz.

## 12.3 Yapı bandı

Gezegen, atom, elektromanyetik ve biyolojik yapılar, faz-parametre peyzajı içinde farklı ilişki ve kısıtlarla temsil edilebilir. Bu, nesnelerin aynı anda üç fazın üyesi olduğu anlamına gelmez.

$$\boxed{\;\text{Harita konumu}\neq\text{faz üyeliği}\;}$$

```latex
\boxed{\;\text{Harita konumu}\neq\text{faz üyeliği}\;}
```

Cₘ doğrudan ölçüm ve okuma fazıdır; diğer fazlarla ontolojik ilişki bulunması, "Cₘ saf değildir" biçiminde zorunlu bir karışım ontolojisi üretmez. Bir atomun içindeki parçacıklar arası boşluğun c⁺'ın Cₘ okuması olması (Bölüm 3) da atomu c⁺ üyesi yapmaz: atom Cₘ yapısıdır, boşluk c⁺'ın okumasıdır.

### Yazar kanonu — Cₘ yapı bandı ve iç bölge

$$\boxed{\;\text{Gezegenler, atomlar, elektromanyetik ve biyolojik yapılar Cₘ üyeliğinde kalırken üç fazla sürekli ilişki ve etkileşim kısıtları taşıyabilir.}\;}$$

```latex
\boxed{\;\text{Gezegenler, atomlar, elektromanyetik ve biyolojik yapılar Cₘ üyeliğinde kalırken üç fazla sürekli ilişki ve etkileşim kısıtları taşıyabilir.}\;}
```

Bu yapıların faz-parametre peyzajındaki doğal çalışma alanı, tek bir köşeye indirgenmeyen **iç bölgedir**. İç bölge, $X$'in farklı özellik ailelerini birlikte çözmek zorunda olduğu türetim ve çözümleme alanıdır:

$$\boxed{\;\mathcal S_{\rm yapı}\in\mathcal D_{\rm iç}\quad\Longrightarrow\quad X\text{, } c_0/C_m/c^+ \text{ ilişki ve kısıtlarını birlikte çözer}\;}$$

```latex
\boxed{\;\mathcal S_{\rm yapı}\in\mathcal D_{\rm iç}\quad\Longrightarrow\quad X\text{, } c_0/C_m/c^+ \text{ ilişki ve kısıtlarını birlikte çözer}\;}
```

| Sembol | Anlamı |
|---|---|
| $\mathcal S_{\rm yapı}$ | Bir Cₘ yapısının (atom, gezegen, canlı) durum tanımı |
| $\mathcal D_{\rm iç}$ | Faz-parametre peyzajının iç bölgesi (hiçbir köşeye indirgenmeyen alan) |
| $X$ | Dinamik üst çözücü |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Karmaşık Cₘ yapılarını, üç fazın kısıtlarının birlikte çözüldüğü iç bölgeye yerleştirir |
| **Neden yapıyor?** | Atomların, gezegenlerin ve canlıların hem Cₘ üyesi hem de üç fazla sürekli ilişki içinde olduğunu, üyelik çelişkisi yaratmadan ifade etmek için |
| **Nasıl yapıyor?** | Üyeliği Cₘ'de tutar; ilişki ve kısıtları $X$'in iç bölgedeki ortak çözümü olarak tanımlar |
| **Ne sonuç bekleniyor?** | İç bölge yapılarında üç faz kısıtının nicel birleşik çözümü |
| **Ne sonuç elde ediliyor?** | Yazar kanonudur. "Üç fazla sürekli etkileşim" ifadesi **eşzamanlı üç faz üyeliği değildir**; faz üyeliği ile fazlar arası kısıt / okuma ilişkisi ayrıdır. Nicel çözüm açıktır |

## 12.4 Nükleer alanda katman ayrımı

| Katman | Ne | Kim açıklıyor |
|---|---|---|
| **Zarf (birinci derece)** | Bağlanma enerjisi eğrisinin genel şekli | Sıvı damla modeli + Evertophy modülasyonu |
| **Kabuk (ikinci derece)** | Sihirli sayılar, kabuk kapanmaları | Kabuk modeli — **dokunulmaz** |

$$\boxed{\;\text{Evertophy ZARFI modüle eder — KABUK KONUMLARINI İCAT ETMEZ.}\;}$$

```latex
\boxed{\;\text{Evertophy ZARFI modüle eder — KABUK KONUMLARINI İCAT ETMEZ.}\;}
```

**Neden kritik?** Tekdüze bir zarf hiçbir yerde tümsek öngörmez. "Kabuk etkisi yok" denirse ölçülmüş kapanmalar da inkâr edilmiş olur. Doğru iddia, kabukların **varlığını** değil, **güçlerinin nasıl modüle olduğunu** konu edinir.

---

## 12.5 Tam yoğunluk spektrumu tablosu (model adayı)

12.2a'nın genişletilmiş hâli. Etiketler yoğunluk-rejim benzetmesidir; gerçek madde fazları ya da faz üyeliği değildir.

| Yoğunluk-rejim etiketi | Tarihsel yapı eşlemesi | Not |
|---|---|---|
| **Nihai** | Kara delik içindeki tek-yapı | c₀ (kara delik ≡ c₀, yazar tanımı); $\rho\le\rho_P$; tablo sayısal eşik ya da genel üyelik ölçütü üretmez |
| **Süper** | Nötron yıldızı çekirdeği | Kinetik ayrışma bölgesi |
| **Çok yüksek ("Kristal")** | Atom çekirdeği | Kabuk yapısı burada |
| **Yüksek ("Sıvı")** | Elektron bulutu / atomik madde | — |
| **Orta ("Gaz")** | Galaksi halesi | Karanlık maddenin Cₘ okumasıyla ilişkili |
| **Düşük ("Buhar")** | Galaksiler arası boşluk | c⁺ payının büyüdüğü bölge olarak okunabilir |

$$\boxed{\;\text{Tablo sayısal eşik üretmez; Bölüm 3.7'nin "harita konumu}\neq\text{faz üyeliği" kuralı geçerlidir.}\;}$$

```latex
\boxed{\;\text{Tablo sayısal eşik üretmez; Bölüm 3.7'nin "harita konumu}\neq\text{faz üyeliği" kuralı geçerlidir.}\;}
```

## 12.6 Kinematik ayrışma ilkesi

Yerel laboratuvar hızı tek başına faz üyeliğini belirlemez: bir nesnenin laboratuvarda ölçülen kinematik durumu ile faz üyeliği ayrı okunur. Cₘ'nin $0<v<c$ bandı ise ontolojik madde üyelik hükmüdür (3.3); bu hükümdeki üyelik değişkeni sıradan laboratuvar koordinat hızıyla özdeş değildir. $v=c$ bandın üyesi değil, Cₘ ile c⁺'ın liminal ortak sınırıdır. Üyelik değişkeninin işlemsel tanımı ve yerel kinematikle bağı açıktır.

$$\boxed{\;0<v<c\;\text{(üyelik bandı)},\qquad v=c\;\text{(liminal ortak sınır; sınır}\neq\text{üyelik)}\;}$$

```latex
\boxed{\;0<v<c\;\text{(üyelik bandı)},\qquad v=c\;\text{(liminal ortak sınır; sınır}\neq\text{üyelik)}\;}
```

## 12.7 Hız ayıklaması hipotezi (tarihsel)

Erken katmanda "fazlar hıza göre ayrışır" hipotezi denenmiştir. Güncel çekirdek bu ayrışmayı bant diliyle yazar (3.3) ve ek bir ayıklama mekanizması önermez. Hipotez tarihsel olarak korunur.

## 12.8 Atom çekirdeği ve kuark-gluon plazması geçişi okuması

"Atom çekirdeği, kuark-gluon plazmasından Cₘ yönüne geçişin doygunluk ürünüdür" okuması bir model adayıdır. Kuark-gluon plazması literatürü (yüksek sıcaklık faz geçişleri, örgü kuramı sonuçları) bağlam olarak izlenir; nicel köprü kurulmamıştır.

---

# BÖLÜM 13 — FAZ GEÇİŞLERİ

## 13.1 Kapı ve damga

$$\boxed{\;\text{KAPI ÇİFT YÖNLÜDÜR} \qquad \text{DAMGA TEK YÖNLÜDÜR}\;}$$

```latex
\boxed{\;\text{KAPI ÇİFT YÖNLÜDÜR} \qquad \text{DAMGA TEK YÖNLÜDÜR}\;}
```

Tersinmezlik faz kapısından değil, **mühürleme eyleminden** gelir. Bir kapıdan iki yönde geçilebilir; ama Cₘ'de olmuş bir olayın c⁺'a yazılan mührü geri alınamaz. Zamanın tek yönlülüğü kapının değil, mührün özelliğidir.

## 13.1a Kapı, taşıma ve kilit

Kapı, iki faz arasında geçişin mümkün olduğunu söyler. Ama bir kapının varlığı, her niceliğin o kapıdan geçebileceği anlamına gelmez. Bu iki şey ayrı tutulmalıdır:

$$\boxed{\;\text{Kapı} \;\neq\; \text{Taşıma izni}\;}$$

```latex
\boxed{\;\text{Kapı} \;\neq\; \text{Taşıma izni}\;}
```

Kapı yapısı tam bir üçgendir: her faz diğer ikisiyle kapı ilişkisindedir (c₀ ↔ Cₘ, Cₘ ↔ c⁺, c₀ ↔ c⁺). Bir niceliğin bir kapıdan taşınabilmesi içinse, o niceliğin kapının **iki ucundaki fazda da** içsel olarak tanımlı olması gerekir.

Buradan biçimsel olarak kanıtlanmış önemli bir sonuç çıkar — kodlanmış biçimsel sistem kapsamında, çekirdek ontolojinin bir teoremi olarak. Zaman, üç boyutlu uzay, metrik, içsel hız, ışık hızı sınırı ve durgun kütle yalnız Cₘ'de tanımlıdır; bu yüzden **hiçbir kapıdan taşınamazlar**. Genel hâli şöyledir:

$$\boxed{\;q \text{ kapı-kilitlidir} \;\Longleftrightarrow\; q \text{ en fazla bir fazda içsel olarak tanımlıdır}\;}$$

```latex
\boxed{\;q \text{ kapı-kilitlidir} \;\Longleftrightarrow\; q \text{ en fazla bir fazda içsel olarak tanımlıdır}\;}
```

Bir niceliğin Cₘ'ye özgü nicelikler listesinde yer almaması, onun başka fazlardaki içsel tanımını ya da belirli bir faz çifti için taşıma iznini belirlemez; biçimsel izin ile fiziksel gerçekleşme ayrıca ayrılır. Bu kilit, c⁺ kaynaklı bir etkinin Cₘ'de **okunmasını** engellemez. Taşıma ile okuma farklı şeylerdir: c⁺'tan Cₘ'ye bir nicelik taşınmaz, ama c⁺ kaynaklı bir etki Cₘ'de, Cₘ'nin kendi dilinde ölçülebilir (15.1a). Kapılardan yalnız faza bağlı olmayan etiketler geçer. $X$'in fazlar arasındaki koordinasyonu ise ayrı bir üst geçiştir ve fiziksel taşıma sayılmaz.

*Okuma kuralı:* Belgenin diğer bölümlerinde "geçiş", "etki" ya da "kapıdan geçen" ifadeleri üç ayrı kavrama göre okunur: **kapı** (yapısal izin), **taşıma izni** (niceliğe özgü) ve **okuma** (c⁺ kaynaklı etkinin Cₘ'de gözlenmesi — taşıma değildir).

$$\boxed{\;\text{Kapı}\neq\text{Taşıma}\neq\text{Okuma}\;}$$

```latex
\boxed{\;\text{Kapı}\neq\text{Taşıma}\neq\text{Okuma}\;}
```

### Denklem seti — kapı, taşıma izni ve kapı kilidi

$$\text{GateLocked}(nat) \iff \text{AtMostOneNative}(nat) \qquad \text{(tam K3 altında)}$$

```latex
\text{GateLocked}(nat) \iff \text{AtMostOneNative}(nat) \qquad \text{(tam K3 altında)}
```

| Sembol | Anlamı |
|---|---|
| `GateRelated a b` | $a \neq b$ — **tam K3**: her farklı faz çifti kapı ilişkisindedir |
| `NativeOK q p` | $q$ niceliği $p$ fazında içsel olarak tanımlı mı |
| `TransportPermission q a b` | `Gate ∧ NativeOK q a ∧ NativeOK q b` — taşıma izni |
| `CmOnlyKind` | Yalnız Cₘ'de tanımlı türler: durgun kütle, zaman, üç boyutlu uzay, metrik, içsel hız, $c$ sınırı |
| `GateLocked nat` | $\forall a\,b,\ \neg\,\text{Transport}$ — hiçbir kapıdan taşınamaz |
| `AtMostOneNative nat` | $\forall x\,y,\ nat\,x \to nat\,y \to x = y$ — en fazla bir fazda içsel |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Fazlar arası geçiş (kapı) ile bir niceliğin fazlar arasında taşınmasını biçimsel olarak ayırır ve kapı kilidini karakterize eder |
| **Neden yapıyor?** | Eski `adjacent` fonksiyonu c₀ ↔ c⁺ kapısını yok sayıyordu; eski K2 de "kütle c⁺'ta taşınır" diyordu. İkisi de güncel ontolojiyle çelişiyordu |
| **Nasıl yapıyor?** | Taşıma iznini, kapının varlığına ek olarak niceliğin iki uçta da içsel tanımlı olmasına bağlar; buradan "en fazla bir fazda tanımlı ⇔ kapı-kilitli" eşdeğerliğini kanıtlar |
| **Ne sonuç bekleniyor?** | Cₘ'ye özgü niceliklerin (zaman, metrik, durgun kütle…) dış fazlara sızmasının biçimsel olarak engellenmesi |
| **Ne sonuç elde ediliyor?** | **Kanıtlanmıştır** (★ kapı ≠ taşıma, kapı kilidi). Eski "tanık-varlığı" genellemesi **yanlıştır** ve kaldırılmıştır. Bu, tam K3 tanımlarından çıkan cebirsel bir teoremdir: K3'ün doğada gerçekleştiğini ya da geçişlerin genliklerini, sürelerini, olasılıklarını ve enerji akışlarını belirlemez |

## 13.2 Geçiş ölçütü

$X$ tek bir skaler olmak zorunda olmadığı için genel geçiş koşulu skaler bir $X_{\rm crit}$ eşitliğiyle tanımlanmaz. Tür-güvenli çekirdek ifade şudur:

$$\boxed{\;(X,\Theta_{ij}) \in \mathcal D_{ij}^{\rm adm} \;\Longleftrightarrow\; \mathcal A_{ij}(X,\Theta_{ij})=1\;}$$

```latex
\boxed{\;(X,\Theta_{ij}) \in \mathcal D_{ij}^{\rm adm} \;\Longleftrightarrow\; \mathcal A_{ij}(X,\Theta_{ij})=1\;}
```

Skaler ya da bant gerçeklemesi seçilen modellerde, $X$'in kendisi yerine o kenara özgü okuma $\xi_{ij}$ kullanılır:

$$\xi_{ij} \in [\xi_{ij}^{\rm crit,-},\ \xi_{ij}^{\rm crit,+}] \ \ (\text{nokta okuma}) \qquad B_{\xi_{ij}} \cap [\xi_{ij}^{\rm crit,-},\ \xi_{ij}^{\rm crit,+}] \neq \varnothing \ \ (\text{bant okuma})$$

```latex
\xi_{ij} \in [\xi_{ij}^{\rm crit,-},\ \xi_{ij}^{\rm crit,+}] \ \ (\text{nokta okuma}) \qquad B_{\xi_{ij}} \cap [\xi_{ij}^{\rm crit,-},\ \xi_{ij}^{\rm crit,+}] \neq \varnothing \ \ (\text{bant okuma})
```

| Sembol | Anlamı |
|---|---|
| $i$, $j$ | Kenarın iki ucundaki fazlar |
| $\Theta_{ij}$ | Geçişe özgü bağlam / koşul ailesi |
| $\mathcal D_{ij}^{\rm adm}$ | İlgili kenarın kabul edilebilir alanı |
| $\mathcal A_{ij}$ | Kabul göstergesi: 1 ise geçiş izinlidir |
| $\xi_{ij}=\pi_{ij}(X)$ | Kenara özgü okuma |
| $\xi_{ij}^{\rm crit,\pm}$ | Kritik aralığın alt ve üst sınırı ($[P,P]$ biçimli tek noktalı aralık da geçerlidir) |
| $B_{\xi_{ij}}$ | Okumanın bant (aralık) biçimi |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bir faz geçişinin hangi koşulda **izinli** olduğunu tanımlar |
| **Neden yapıyor?** | Skaler bir eşik, $X$'in skaler olmayan doğasıyla çelişirdi; geçiş koşulu çözücünün tamamına ve bağlama bağlı olmalıdır |
| **Nasıl yapıyor?** | Genel durumda $X$ ve bağlamın kabul edilebilir alanda olmasını ister; model düzeyinde bu, bir okumanın kritik aralığa düşmesi ya da bandının aralıkla kesişmesi olarak somutlaşır |
| **Ne sonuç bekleniyor?** | Her kenar için ölçeğe ve kütle miktarına bağlı somut kritik aralıklar |
| **Ne sonuç elde ediliyor?** | Tür-güvenli tanım kanondur; nokta ve bant okumaları **özel durumlardır**, $X$'in ontolojik tanımı değildir. Vurgu **"izinli"** üzerindedir: izinlilik geçişi **zorunlu kılmaz** |

**Yazar hükmü:** Faz geçiş eşikleri ölçeğe ve kütle miktarına göre değerlendirilir; Çekim Kuvveti'nin izdüşümleri de aynı değişkenlere bağlıdır (1.2).

## 13.3 Kenar sınıflandırması

| Kenar | Damga taşıyıcı mı | Cₘ'de gözlenebilir mi |
|---|---|---|
| $\Delta_{0m}$ | Evet | Evet |
| $\Delta_{+m}$ | Evet | Dolaylı |
| $\Delta_{0+}$ | Hayır | Hayır |

$\Delta_{0+}$ damga üretmez, çünkü Cₘ'ye değmez — kayıt Cₘ'ye temas eden kenarlarda açılır.

### Kenar taşıyıcılığı ≠ yönlü üretim

$$\boxed{\;\text{Bir kenarın DAMGA TAŞIYICI olması, HER İKİ YÖNDE damga ürettiği anlamına GELMEZ.}\;}$$

```latex
\boxed{\;\text{Bir kenarın DAMGA TAŞIYICI olması, HER İKİ YÖNDE damga ürettiği anlamına GELMEZ.}\;}
```

Yön anlamı ayrı bir konudur. Biçimsel pakette `stampOf(c⁺ → Cₘ) = κ₊ₘ` biçimindeki damga taşıma kaydı ile ontolojik arşive yazma yönünün Cₘ → c⁺ olarak okunması aynı anlam katmanı olmak zorunda değildir. Bu sürümdeki koruma cümlesi şudur:

$$\boxed{\;\kappa_{+m}\text{'in taşındığı yön bilinçli olarak açıktır; damga taşıyıcılığı yön anlamını tek başına belirlemez.}\;}$$

```latex
\boxed{\;\kappa_{+m}\text{'in taşındığı yön bilinçli olarak açıktır; damga taşıyıcılığı yön anlamını tek başına belirlemez.}\;}
```

Yazar hükmü (7.1), ontolojik kayıt kanalının yönünü **Cₘ → c⁺** olarak sabitler. Biçimsel paketteki $\kappa_{+m}$ taşıma yönünün bu hükümle hizalanması açık borçtur. Kod bu borcu kapatmak için sessizce ters çevrilmez; ontoloji de yalnız mevcut kodun yönünden türetilmez.

## 13.4 Üç farklı "yokluk" — ve doğru biçimselleştirme

| Kavram | Anlamı |
|---|---|
| **Geçiş yok** | Kenar mevcut değil |
| **Damgasız geçiş** | Kenar var, geçiş var, damga üretilmedi |
| **Cebirsel birim** | Damga cebirinde nötr eleman |

### Doğru ayrım

Anlam düzeyinde "damga yok" ile cebirsel düzeyde "birim" **farklı** şeylerdir; bu yüzden iki ayrı haritayla ifade edilmeleri gerekir:

$$\boxed{\;\text{emittedStamp}(T_{0+}) = \texttt{None} \qquad\qquad \Sigma(T_{0+}) = e\;}$$

```latex
\boxed{\;\text{emittedStamp}(T_{0+}) = \texttt{None} \qquad\qquad \Sigma(T_{0+}) = e\;}
```

$$\boxed{\;e = \texttt{NoStamp} \text{ biçiminde bir TİP DÜZEYİ ÖZDEŞLİK KURULMAZ.}\;}$$

```latex
\boxed{\;e = \texttt{NoStamp} \text{ biçiminde bir TİP DÜZEYİ ÖZDEŞLİK KURULMAZ.}\;}
```

| Sembol | Anlamı |
|---|---|
| $T_{0+}$ | c₀ ↔ c⁺ kenarındaki geçiş |
| $\text{emittedStamp}$ | Geçişin ürettiği damgayı veren harita; sonuç türü `Option Stamp` |
| `None` | "Damga üretilmedi" değeri |
| $\Sigma$ | Geçişten damga monoidine giden cebirsel görüntü haritası |
| $e$ | Damga monoidinin birim (nötr) elemanı |
| $M$ | Damga monoidi |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | "Damga üretilmedi" ile "cebirsel birim" kavramlarını iki ayrı haritaya ayırır |
| **Neden yapıyor?** | $\Sigma : \text{Geçiş}\to M$ bir monoide gider ve monoid `None` içermez; iki kavramı tek haritada birleştirmek tür hatası olurdu |
| **Nasıl yapıyor?** | Damga **üretimini** `Option Stamp` döndüren ayrı bir haritayla, damganın **cebirsel görüntüsünü** monoid haritasıyla yazar |
| **Ne sonuç bekleniyor?** | Damgasız kenarın, damga cebirini bozmadan tutarlı biçimde ifade edilmesi |
| **Ne sonuç elde ediliyor?** | Doğru biçimselleştirme budur; $e$ ile `NoStamp` arasında tip düzeyinde özdeşlik kurulmaz |

## 13.5 Δ₀₊ için güvenli aday

Bu kenar için en güvenli biçimsel aday şudur:

$$\text{ArşivEtkisi} = \text{Değişiklik yok}, \qquad\qquad \text{KoordinasyonEtkisi} = X\text{-koordinasyonu}$$

```latex
\text{ArşivEtkisi} = \text{Değişiklik yok}, \qquad\qquad \text{KoordinasyonEtkisi} = X\text{-koordinasyonu}
```

$$\boxed{\;c_0 \leftrightarrow c^+ \text{ için doğrudan HAM ARŞİV yazma / okuma İTHAL EDİLMEZ.}\;}$$

```latex
\boxed{\;c_0 \leftrightarrow c^+ \text{ için doğrudan HAM ARŞİV yazma / okuma İTHAL EDİLMEZ.}\;}
```

Doğrudan arşiv erişimi c₀'ı tarihe duyarlı hâle getirirdi; bu, zaman-öncesi niteliğiyle çelişir. Bu koordinasyon yapısı **$U_0$ ile özdeşleştirilmez**.

Biçimsel adayın en zayıf ve güvenli arayüzü bir uyumluluk ilişkisidir:

$$\boxed{\;\mathcal R^X_{0+}\subseteq \mathcal X_0\times\mathcal X_+\;}$$

```latex
\boxed{\;\mathcal R^X_{0+}\subseteq \mathcal X_0\times\mathcal X_+\;}
```

Buradaki $\mathcal X_0$ ve $\mathcal X_+$ iki ayrı temel $X$ değildir; tek $X$ üst çözücüsünün faza göre dizinlenmiş kabul edilebilir sunum uzaylarıdır. İç gerçekleşme için bir açıklık / lif (span / fiber) adayı kullanılabilir:

$$\boxed{\;\mathcal X_0 \xleftarrow{p_0}\mathfrak F^X_{0+}\xrightarrow{p_+}\mathcal X_+\;}$$

```latex
\boxed{\;\mathcal X_0 \xleftarrow{p_0}\mathfrak F^X_{0+}\xrightarrow{p_+}\mathcal X_+\;}
```

İlişkide kaynak başına tek hedef kanıtlanırsa kısmi bir fonksiyon elde edilebilir. Ama çift yönlü kapı tek başına

$$F^X_{+0}=(F^X_{0+})^{-1}$$

```latex
F^X_{+0}=(F^X_{0+})^{-1}
```

sonucunu vermez; tam ters ya da birebir-örten eşleme ayrıca kanıt gerektirir.

| Sembol | Anlamı |
|---|---|
| $\mathcal R^X_{0+}$ | c₀ ile c⁺ sunumları arasındaki $X$-uyumluluk ilişkisi |
| $\mathcal X_0$, $\mathcal X_+$ | Tek $X$'in c₀ ve c⁺ için kabul edilebilir sunum uzayları |
| $\mathfrak F^X_{0+}$ | Geçiş tanığı / eşleşme yapısı (lif) |
| $p_0$, $p_+$ | Liften iki sunum uzayına izdüşümler |
| $F^X_{0+}$, $F^X_{+0}$ | Varsa iki yönlü kısmi fonksiyonlar |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Damgasız c₀ ↔ c⁺ kenarına, arşiv ya da madde taşımadan, yalnız $X$ düzeyinde bir uyumluluk anlamı verir |
| **Neden yapıyor?** | Kenar vardır (tam K3) ama Cₘ'ye değmez; ona bir anlam vermek gerekir ve bu anlam c₀'ı tarihe duyarlı yapmamalıdır |
| **Nasıl yapıyor?** | İlişkiyi iki sunum uzayının kartezyen çarpımının bir alt kümesi olarak yazar; iç gerçekleşmeyi bir lif ve iki izdüşümle kurar |
| **Ne sonuç bekleniyor?** | Kaynak başına tek hedef kanıtlanırsa kısmi fonksiyon; ayrıca kanıtlanırsa tam ters |
| **Ne sonuç elde ediliyor?** | **Biçimsel adaydır.** $\mathfrak F^X_{0+}$ yeni bir faz değildir, $U_0$ değildir ve fiziksel zaman taşımaz. Çift yönlü kapı tam tersi otomatik olarak vermez |

---

## 13.6 c₀ ↔ c⁺ için X-koordinasyon biçimsel adayı

*Statü:* Bu bölüm, c₀ ile c⁺ arasındaki belirli ilişki ve lif gerçeklemesi için bir **biçimsel adaydır**. $X$'in genel üst koordinasyonu (4.6) kesindir.

Doğrudan kenarın güncel güvenli anlamı ham arşiv taşıması ya da madde taşıması değil, **$X$ düzeyinde uyumluluk / koordinasyondur** (13.5'teki ilişki ve lif). Bu yapıda:

- $\mathfrak F^X_{0+}$ **yeni bir faz değildir**;
- $U_0$ değildir;
- fiziksel zaman ya da oran parametresi taşımaz;
- her kaynak durum için tek hedef kanıtlanırsa kısmi fonksiyona yükseltilebilir;
- çift yönlü kapı, $F_{+0}=F_{0+}^{-1}$ tam eşlemesini otomatik olarak vermez.

Tamamen belirlenmiş aynı durum altında $X$'in belirlenimci çözüm kuralı, **çözücü çıktısının işlevselliğini** destekler; ama faz geçişinin tersinirliğini kanıtlamaz.

### Model katmanı notu — doğrudan c₀ ⇄ c⁺ kenar kilidi

Yazar, bir düşünce deneyi oran modelinde doğrudan c₀ ⇄ c⁺ kenarı için şu kuralı onaylamıştır (2026-10-14): kenarın potansiyeli genişleme oranının kütleçekim oranına bölümüyle yazılır; damgasız kenar kuantum yerelleşme oranını içermez.

$$\Psi_{0+}(\ell,M)=\ln\frac{\Xi_\Lambda}{\Xi_g}=\ln\frac{\Lambda c^4\ell^4}{6G^2M^2},\qquad \Xi_g=\frac{2GM}{c^2\ell},\quad \Xi_\Lambda=\frac{\Lambda c^2\ell^3}{3GM},\quad \Xi_q=\frac{\hbar}{Mc\ell}$$

```latex
\Psi_{0+}(\ell,M)=\ln\frac{\Xi_\Lambda}{\Xi_g}=\ln\frac{\Lambda c^4\ell^4}{6G^2M^2},\qquad \Xi_g=\frac{2GM}{c^2\ell},\quad \Xi_\Lambda=\frac{\Lambda c^2\ell^3}{3GM},\quad \Xi_q=\frac{\hbar}{Mc\ell}
```

| Sembol | Anlamı |
|---|---|
| $\Psi_{0+}$ | Doğrudan c₀ ⇄ c⁺ kenar potansiyeli (model) |
| $\ell$, $M$ | Bakılan ölçek ve içindeki kütle — Cₘ okuma büyüklükleri |
| $\Xi_g$ | Kütleçekim izdüşüm oranı (ölçeğin Schwarzschild yarıçapına oranının tersi) |
| $\Xi_\Lambda$ | Genişleme / çekim oranı |
| $\Xi_q$ | Kuantum yerelleşme (Compton) oranı; damgasız kenar bunu içermez |
| $\Lambda$ | Kozmolojik sabit |
| $G$, $c$, $\hbar$ | Kütleçekim sabiti, ışık hızı, indirgenmiş Planck sabiti |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Damgasız c₀ ⇄ c⁺ kenarının hangi ölçek ve kütlede etkin olduğunu tek bir potansiyelle parametrize eder |
| **Neden yapıyor?** | Kenarın iki kutbu — çekim (c₀ yönü) ve genişleme (c⁺ yönü) — arasındaki göreli ağırlığı Cₘ'de okunabilir büyüklüklerle ifade etmek için |
| **Nasıl yapıyor?** | Genişleme oranını kütleçekim oranına böler ve logaritmasını alır; kuantum oranını bilinçli olarak dışarıda bırakır, çünkü kenar Cₘ'ye değmez ve damga üretmez |
| **Ne sonuç bekleniyor?** | $\Psi_{0+}=0$ çizgisinin, iki model göstergesinin ($\Xi_\Lambda$ ve $\Xi_g$) eşitlendiği eşiği vermesi; döngü afinitesinin kütleye bağımlılığı. Bu eşik, ivmelerin dengelendiği ölçek değildir (aşağıdaki not) |
| **Ne sonuç elde ediliyor?** | Bir **model kuralıdır**, ontolojik tanım değildir; 13.4–13.6'daki ontolojik anlamı değiştirmez: kenar damgasızdır ($\Sigma(T_{0+})=e$), ham arşiv yazma / okuma ithal etmez ve fiziksel zaman taşımaz. Modeldeki oran (hız) dili yalnız modelin Cₘ okuma muhasebesine aittir. Buradaki $\Xi$ oranları 8.8 ve 17'deki $\Xi=\ln\chi_S$ ile ilgisizdir |

**Eşik ile ivme dengesi ayrımı.** $\Xi_\Lambda$, Newton tipi okumada genişleme ivmesinin kütleçekim ivmesine oranıdır. İvme dengesi $\Xi_\Lambda=1$ koşuludur; $\Psi_{0+}=0$ ise $\Xi_\Lambda=\Xi_g$ koşuludur ve genel olarak farklı bir ölçek verir:

$$a_g=\frac{GM}{\ell^2},\quad a_\Lambda=\frac{\Lambda c^2\ell}{3},\quad \frac{a_\Lambda}{a_g}=\Xi_\Lambda;\qquad \ell_{\rm denge}=\left(\frac{3GM}{\Lambda c^2}\right)^{1/3},\qquad \ell_{\Psi=0}=\left(\frac{6G^2M^2}{\Lambda c^4}\right)^{1/4}$$

```latex
a_g=\frac{GM}{\ell^2},\quad a_\Lambda=\frac{\Lambda c^2\ell}{3},\quad \frac{a_\Lambda}{a_g}=\Xi_\Lambda;\qquad \ell_{\rm denge}=\left(\frac{3GM}{\Lambda c^2}\right)^{1/3},\qquad \ell_{\Psi=0}=\left(\frac{6G^2M^2}{\Lambda c^4}\right)^{1/4}
```

| Sembol | Anlamı |
|---|---|
| $a_g$, $a_\Lambda$ | Kütleçekim ve genişleme ivmesi okumaları |
| $\ell_{\rm denge}$ | İvmelerin eşitlendiği ölçek ($\Xi_\Lambda=1$) |
| $\ell_{\Psi=0}$ | Kenar potansiyelinin sıfır olduğu ölçek ($\Xi_\Lambda=\Xi_g$) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Model eşiğini fiziksel ivme dengesinden ayırır |
| **Neden yapıyor?** | Önceki açıklama $\Psi_{0+}=0$'ı "çekim ile genişlemenin dengelendiği ölçek" diye tanımlıyordu; denklem bunu vermez |
| **Nasıl yapıyor?** | İki koşulu ayrı ayrı çözer ve iki farklı ölçek bulur |
| **Ne sonuç bekleniyor?** | Kenar kilidinin fiziksel yorumunda doğru ölçeğin kullanılması |
| **Ne sonuç elde ediliyor?** | Yazarın onayladığı model kuralı **aynen korunur**; yalnız açıklaması düzeltilir. Güneş kütlesi için $\ell_{\rm denge}\approx3.4\times10^{18}$ m ($\approx111$ pc), $\ell_{\Psi=0}\approx5.9\times10^{14}$ m |

Kural altında modelin döngü afinitesi yalnız kütleye bağlı kalır ve $M\gg m_P$ için sıfıra **yaklaşır**. Parametre alanı $w>0$, $M>0$'dır ($w=0$'da tanımsız, $w<0$'da işaret değişir); bu alanda afinite her sonlu kütlede pozitiftir:

$$\mathcal A=\frac{1}{w}\ln\!\left(1+\frac{m_P^2}{2M^2}\right)$$

```latex
\mathcal A=\frac{1}{w}\ln\!\left(1+\frac{m_P^2}{2M^2}\right)
```

| Sembol | Anlamı |
|---|---|
| $\mathcal A$ | Döngü afinitesi; sıfırsa model ayrıntılı dengededir |
| $w$ | Eşik yumuşaklığı (model bandı, $w>0$; 11'deki durum denklemi $w$'si ile karıştırılmaz) |
| $m_P$ | Planck kütlesi |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Modelde üç faz arasında net bir döngü akısı olup olmadığını ölçer |
| **Neden yapıyor?** | Ayrıntılı dengeden sapmanın hangi kütle ölçeğinde önemli olduğunu görmek için |
| **Nasıl yapıyor?** | Kenar kuralı altında döngü boyunca potansiyel farklarını toplar; sonuç yalnız $M/m_P$ oranına bağlı kalır |
| **Ne sonuç bekleniyor?** | Makroskopik kütlelerde dengenin, küçük kütlelerde net akının görülmesi |
| **Ne sonuç elde ediliyor?** | $\mathcal A$ her sonlu kütlede pozitiftir ve $M\gg m_P$'de $\mathcal A\simeq m_P^2/(2wM^2)$ ile sıfıra yaklaşır; tam sıfırlanma yoktur. Afinite akının büyüklüğünü tek başına belirlemez: modelin geçiş hızlarıyla birlikte (V24 §732), net akımın $10^{-3}$ eşiğini aştığı bölge yalnız $\log_{10}(M/\mathrm{kg})\in[-42,-27]$, yani **atom altı kütlelerdir** (incelenen model ve parametre bandında model sonucu). Atom altı döngü hızı için entropi üretimi kaynaklı bir üst sınır açık borçtur (EK K). Sayısal bantlar ve türetim V24 yürüyen ana kaydındadır (§732) |




# BÖLÜM 14 — DAMGA CEBİRİ VE ARŞİV

## 14.1 Mühürleme

$$\boxed{\;\text{MÜHÜRLEME} = \text{bir kaydın GERİ ALINAMAZ biçimde yazılmasıdır.}\;}$$

```latex
\boxed{\;\text{MÜHÜRLEME} = \text{bir kaydın GERİ ALINAMAZ biçimde yazılmasıdır.}\;}
```

Mühürleme Cₘ'nin içinde değil, **Cₘ'ye temas eden eşik arayüzlerinde** gerçekleşir. Kayıt kanalı tek yönlüdür (Cₘ → c⁺); mühürleme gerçekleştiğinde kayıt sabittir (yazar hükmü, 7.1). Bu bölüm, bu sabitliğin cebirsel dilini kurar: bir şey yazılabiliyor ama silinemiyorsa, o yapının matematiği bir grup değil, bir **monoiddir**.

## 14.2 Damga monoidi

$$M = \big\langle s,\; s',\; \kappa_{0m},\; \kappa_{+m} \;\big|\; \kappa_{0m}^2 = \kappa_{0m},\;\; \kappa_{+m}^2 = \kappa_{+m} \big\rangle$$

```latex
M = \big\langle s,\; s',\; \kappa_{0m},\; \kappa_{+m} \;\big|\; \kappa_{0m}^2 = \kappa_{0m},\;\; \kappa_{+m}^2 = \kappa_{+m} \big\rangle
```

| Sembol | Anlamı |
|---|---|
| $M$ | Damga monoidi |
| $s$, $s'$ | Serbest geçiş üreteçleri (serbest damgalar) |
| $\kappa_{0m}$ | Δ₀ₘ kenarının kilit damgası |
| $\kappa_{+m}$ | Δ₊ₘ kenarının kilit damgası |
| $\langle\ \cdot\ \mid\ \cdot\ \rangle$ | Sunum: solda üreteçler, sağda bağıntılar |
| $\kappa^2=\kappa$ | İdempotentlik: kilidin ikinci kez basılması cebirsel görüntüyü değiştirmez |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Fazlar arası geçişlerin arşivdeki cebirsel izini, dört üreteçli ve iki bağıntılı bir monoid olarak tanımlar |
| **Neden yapıyor?** | Kayıt sırasını, kaynağını ve silinemezliğini aynı anda koruyan en küçük cebirsel yapıya ihtiyaç vardır |
| **Nasıl yapıyor?** | Serbest damgaları serbest bırakır; yalnız iki kilidi idempotent yapar. İki ayrı kilit üreteci, hangi kenardan gelindiği bilgisini korur |
| **Ne sonuç bekleniyor?** | İdempotentlerin tam sınıflandırması, normal formların tekliği, grup tamamlamasının yapısı |
| **Ne sonuç elde ediliyor?** | **Çekirdek arşiv cebiri olarak kanıtlanmıştır** (aşağıdaki alt başlıklar) |

### Neden monoid, neden grup değil

$$\boxed{\;s^{-1} \text{ YOKTUR — çünkü SİLME TEMEL İŞLEMİ yoktur. Tersinirlik yasağı, } M\text{'nin grup olmamasının KENDİSİDİR.}\;}$$

```latex
\boxed{\;s^{-1} \text{ YOKTUR — çünkü SİLME TEMEL İŞLEMİ yoktur. Tersinirlik yasağı, } M\text{'nin grup olmamasının KENDİSİDİR.}\;}
```

Bir grupta her elemanın tersi vardır; tersi olan bir kayıt silinebilir bir kayıttır. Evertophy'de mühür silinemediği için arşivin cebiri grup olamaz. Bu bir eksiklik değil, ontolojinin kendisidir.

### İdempotentler

$$\mathrm{Idem}(M) = \{e,\; \kappa_{0m},\; \kappa_{+m}\}$$

```latex
\mathrm{Idem}(M) = \{e,\; \kappa_{0m},\; \kappa_{+m}\}
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Monoidde kendisiyle çarpıldığında değişmeyen bütün elemanları listeler |
| **Neden yapıyor?** | Hangi damgaların "bir kez basılmakla tamamlanan" kilit davranışı gösterdiğini kesin olarak bilmek için |
| **Nasıl yapıyor?** | Serbest sektörde bir kelimenin karesi kelimenin kendisinden uzundur; dolayısıyla $ww=w$ olamaz. Geriye birim ve iki kilit kalır |
| **Ne sonuç bekleniyor?** | Kilitlerin dışında hiçbir damganın kendiliğinden idempotent olmaması |
| **Ne sonuç elde ediliyor?** | **Biçimsel olarak kanıtlanmıştır:** $w\cdot w = w$ ancak ve ancak $w \in \{e,\ \kappa_{0m},\ \kappa_{+m}\}$ |

### Yasaklı bağıntılar

| Bağıntı | Neden yasak |
|---|---|
| $ss' = s's$ | Kelime sırası olay sırasıdır; sıra silinemez |
| $\kappa s = \kappa$ | Kilitten sonra kayıt eklenemez hâle gelirdi |
| $s^N = \kappa$ | Serbest damga kendiliğinden kilide dönüşemez |

### Grup tamamlaması — ve yorumu

Grupta tersinirlik olduğundan kilitler tamamlamada birime gider; geriye serbest grup kalır.

$$\boxed{\;\text{BU, FİZİKSEL TERSİNİRLİK ANLAMINA GELMEZ. Grup tamamlaması bir CEBİRSEL ARAÇTIR.}\;}$$

```latex
\boxed{\;\text{BU, FİZİKSEL TERSİNİRLİK ANLAMINA GELMEZ. Grup tamamlaması bir CEBİRSEL ARAÇTIR.}\;}
```

Kilitlerin cebirsel tamamlamada sıfırlanması, arşivde bir kaydın silinebileceğini **ima etmez**. Ayrıca kilitleri tek bir soğurucu sıfıra çökertmek **reddedilir**; bu, kaynak ve sıra bilgisini siler.

Sunumun yalnız yukarıdaki idempotent bağıntılarla kapalı kaldığı varsayımında, evrensel grup tamamlamasında idempotentler birime gider ve şu sonuçlar çıkar:

$$\boxed{\;G_{\rm univ}(M)\cong F_2\;}\qquad\qquad \boxed{\;K(M)\cong \mathbb Z^2\;}$$

```latex
\boxed{\;G_{\rm univ}(M)\cong F_2\;}\qquad\qquad \boxed{\;K(M)\cong \mathbb Z^2\;}
```

| Sembol | Anlamı |
|---|---|
| $G_{\rm univ}(M)$ | $M$'nin evrensel grup tamamlaması |
| $F_2$ | İki üreteçli ($s$, $s'$) serbest grup |
| $K(M)$ | Değişmeli (abelyen) evrensel grup tamamlaması |
| $\mathbb Z^2$ | İki boyutlu tam sayı örgüsü |
| $\cong$ | İzomorfizma |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Damga monoidine yapay olarak ters elemanlar eklendiğinde geriye ne kaldığını hesaplar |
| **Neden yapıyor?** | Tamamlama, sayma ve muhasebe işlemleri için güçlü bir cebirsel araçtır; ama fiziksel anlamının sınırı açıkça çizilmelidir |
| **Nasıl yapıyor?** | Ters elemanlar eklenince $\kappa^2=\kappa$ bağıntısı $\kappa=e$'ye çöker; geriye $s$ ve $s'$ üzerinde serbest grup, değişmeli hâlde ise iki tam sayı sayacı kalır |
| **Ne sonuç bekleniyor?** | Serbest damgaların net sayımının iki tam sayıyla tutulabilmesi |
| **Ne sonuç elde ediliyor?** | Sonuçlar **sunum kapalı kaldığı sürece koşulludur**; ileride yeni bağıntı eklenirse yeniden denetlenir. Tamamlama fiziksel tersinirlik değildir |

### Karşı-damga yoktur

Bir damganın "negatifi" fiziksel bir nesne olarak **yoktur**. Cebirsel tamamlamada türetilebilir; bu bir **muhasebe aracıdır**.

### Damga cebirinin kanıt durumu

Damga cebirinin temel özellikleri sonlu örneklemenin ötesinde, genel olarak kanıtlanmıştır: birleşme özelliği, yeniden yazma sürecinin her zaman sonlandığı, her kelimenin tek bir normal forma ulaştığı ve farklı indirgeme yollarının aynı sonuca vardığı (konfluans).

Bir inceliğe dikkat etmek gerekir: konfluans, **olayların yer değiştirebileceği** anlamına gelmez. Olay sırası sabit tutulduğunda farklı gruplamalar ve indirgeme yolları aynı normal forma ulaşır; ama genel olarak $ab \neq ba$'dır ve olayların sırası sonucu değiştirir. Arşiv, tarihin sırasını korur.

### Denklem seti — damga monoidi ve arşiv cebiri

$$u\,\kappa\,\kappa\,v \;\to\; u\,\kappa\,v \qquad (\kappa \in \{\kappa_{0m}, \kappa_{+m}\})$$

```latex
u\,\kappa\,\kappa\,v \;\to\; u\,\kappa\,v \qquad (\kappa \in \{\kappa_{0m}, \kappa_{+m}\})
```

$$w \cdot w = w \iff w \in \{e,\ \kappa_{0m},\ \kappa_{+m}\}$$

```latex
w \cdot w = w \iff w \in \{e,\ \kappa_{0m},\ \kappa_{+m}\}
```

| Sembol | Anlamı |
|---|---|
| $u$, $v$ | Kelimenin öncesi ve sonrası (herhangi üreteç dizileri) |
| $w$ | Kelime (üreteç dizisi) |
| $\cdot$ / `mulW` | Normal forma indirgenmiş birleştirme |
| $\to$, $\to^*$ | Tek adım / çok adım yeniden yazma |
| $e$ | Boş kelime (birim) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Ardışık iki aynı kilidi teke indiren yeniden yazma kuralını ve idempotent sınıflandırmasını verir |
| **Neden yapıyor?** | Aynı tarihçenin arşiv karşılığının belirsiz kalmaması için: olay sırası sabitken farklı parantezlemeler ve indirgeme sıraları aynı normal forma ulaşmalıdır |
| **Nasıl yapıyor?** | Yalnız yan yana duran aynı kilitleri birleştirir; serbest damgalara ve sıraya dokunmaz |
| **Ne sonuç bekleniyor?** | Sonlanma, tek normal form ve konfluans |
| **Ne sonuç elde ediliyor?** | **Kanıtlanmıştır** (★ çekirdek arşiv cebiri). Grup tamamlaması $G(M)\cong F_2$, $K_{ab}(M)\cong\mathbb Z^2$ belirtilen kapalı sunum için geçerlidir. Ayrıca `None ≠ Some(e)`: **damga üretilmemesi** ile **birim damga** farklıdır. Bu, olayların yer değiştirmesinden bağımsızlık değildir |

## 14.3 Ağırlık fonksiyonu

Bir damganın ne kadar daralttığı, aralık oranıyla ölçülebilir. Ardışık damgalarda oranlar çarpılır, logaritmada toplanır — yani bir homomorfizma elde edilir.

### Kilit için sonuç

Durumdan bağımsız toplamsal bir karakter $\omega$ için $\kappa^2=\kappa$ bağıntısı $\omega(\kappa)=0$ sonucunu verir; bu elle atanmaz, **türetilir**. Ama bu sonuç, bağımsız aralık uçlarından kurulan kapsama aralığının $[0,0]$ olmasını ya da fiziksel bir kilidin ilk uygulamada hiçbir maliyet üretmemesini gerektirmez. Üç nesne ayrıdır:

| Nesne | Özelliği |
|---|---|
| **Kesin karakter** | Durumdan bağımsız ve toplamsal; $\omega(\kappa)=0$ |
| **Kapsama aralığı** | Bağımsız uçlardan kurulur; kesin değeri geçerli biçimde kapsıyorsa $0\in\Omega_{\rm enc}(\kappa)$, ama $[0,0]$ olması gerekmez |
| **Duruma bağlı fiziksel daralma maliyeti** | İlk uygulamada sıfırdan farklı olabilir |

Örneğin $P(W)=\min(W,1)$ idempotenttir; ama $W=2$ durumunda ilk uygulama $\ln 2$ maliyet üretir, ikincisi üretmez. Bir matematiksel maliyet modeli şöyle yazılabilir — mühürlemenin fiziksel yasası olarak atanmış değildir:

$$C(T_2\circ T_1,s)=C(T_1,s)+C(T_2,T_1(s)),\qquad C(T,s)=\ln W(s)-\ln W(T(s)),\quad W>0$$

```latex
C(T_2\circ T_1,s)=C(T_1,s)+C(T_2,T_1(s)),\qquad C(T,s)=\ln W(s)-\ln W(T(s)),\quad W>0
```

| Sembol | Anlamı |
|---|---|
| $T$, $T_1$, $T_2$ | Durum dönüşümleri (damga uygulamaları) |
| $s$ | Durum |
| $W(s)$ | Durumun genişliği (izinli aralığın büyüklüğü), kesin pozitif |
| $C(T,s)$ | $T$'nin $s$ durumunda ürettiği daralma maliyeti |
| $\circ$ | Bileşke (önce $T_1$, sonra $T_2$) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bir dönüşümün durumu ne kadar daralttığını logaritmik bir maliyet olarak ölçer ve bileşkede maliyetlerin toplandığını gösterir |
| **Neden yapıyor?** | Kilidin cebirsel karakteri sıfır olsa bile ilk uygulamasının fiziksel bir bedeli olabileceğini açık kılmak için |
| **Nasıl yapıyor?** | Maliyeti önceki ve sonraki genişliğin logaritma farkı olarak tanımlar; bileşkede ara durumu ($T_1(s)$) hesaba katar |
| **Ne sonuç bekleniyor?** | İdempotent bir dönüşümün ikinci uygulamasında sıfır, ilk uygulamasında sıfırdan farklı olabilen maliyet |
| **Ne sonuç elde ediliyor?** | Matematiksel bir **maliyet modelidir**; mühürlemenin fiziksel yasası olarak atanmamıştır |

### Karakter ≠ fiziksel kilit

$$\boxed{\;\text{Ağırlığın sıfır olması, kilidin FİZİKSEL OLARAK ETKİSİZ olduğu anlamına GELMEZ.}\;}$$

```latex
\boxed{\;\text{Ağırlığın sıfır olması, kilidin FİZİKSEL OLARAK ETKİSİZ olduğu anlamına GELMEZ.}\;}
```

Bu yalnız, kilidin toplamsal karakterin çekirdeğinde olduğunu söyler. Kilit hâlâ sonraki bileşimleri değiştirebilir ve durum uzayını kabalaştırabilir.

**Oran yönü korunmalıdır:** ağırlık "önceki genişlik / sonraki genişlik" yönünde tanımlanır; ters çevrilirse işaret bozulur. Pozitif genişlikler için temel gösterim şudur:

$$\boxed{\;\Omega(m)=\log\frac{W_{\rm önce}}{W_{\rm sonra}}\;}$$

```latex
\boxed{\;\Omega(m)=\log\frac{W_{\rm önce}}{W_{\rm sonra}}\;}
```

Ortak bir durum $s$'de **kesin karakter** bağımlılığı korur ve tam olarak toplamsaldır:

$$\boxed{\;\omega_{AB}(s)=\ln W_A(s)-\ln W_B(s)\;}\qquad \omega_{AB}(s)+\omega_{BC}(s)=\omega_{AC}(s)$$

```latex
\boxed{\;\omega_{AB}(s)=\ln W_A(s)-\ln W_B(s)\;}\qquad \omega_{AB}(s)+\omega_{BC}(s)=\omega_{AC}(s)
```

Bağımsız uç değerlerden kurulan aralık ise kesin karakter değil, bir **kapsama aralığıdır** ($W_A$ "önce", $W_B$ "sonra"):

$$\boxed{\;\Omega_{\rm enc}(m)=\left[\log\frac{W_A^-}{W_B^+},\ \log\frac{W_A^+}{W_B^-}\right]\;}\qquad \Omega_{\rm enc}(uv)\subseteq\Omega_{\rm enc}(u)\oplus\Omega_{\rm enc}(v)$$

```latex
\boxed{\;\Omega_{\rm enc}(m)=\left[\log\frac{W_A^-}{W_B^+},\ \log\frac{W_A^+}{W_B^-}\right]\;}\qquad \Omega_{\rm enc}(uv)\subseteq\Omega_{\rm enc}(u)\oplus\Omega_{\rm enc}(v)
```

| Sembol | Anlamı |
|---|---|
| $m$ | Bir damga ya da geçiş |
| $W_{\rm önce}$, $W_{\rm sonra}$ | Damgadan önceki ve sonraki genişlik |
| $\Omega(m)$ | Damganın ağırlığı (daralma ölçüsü) |
| $\omega_{AB}(s)$ | Ortak durum $s$'de A'dan B'ye kesin karakter |
| $W_A^{\pm}$, $W_B^{\pm}$ | Genişliklerin aralık uçları (alt / üst) |
| $\Omega_{\rm enc}$ | Kapsama aralığı |
| $\oplus$ | Bağımsız aralık toplamı (Minkowski toplamı) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Damganın ağırlığını hem kesin bir sayı (ortak durumda) hem de bir aralık (bağımsız uçlarda) olarak tanımlar |
| **Neden yapıyor?** | Range biçimciliğinde uçlar bağımsız alındığında bağımlılık bilgisi kaybolur; kesin değer ile kapsama aralığını karıştırmak yanlış sonuçlara götürür |
| **Nasıl yapıyor?** | Kesin karakteri aynı durumda logaritma farkı olarak; kapsama aralığını en kötü uç kombinasyonlarıyla kurar |
| **Ne sonuç bekleniyor?** | Kesin karakterde tam toplamsallık; kapsama aralığında yalnız içerme ilişkisi |
| **Ne sonuç elde ediliyor?** | Örneğin $W_A(s)=W_B(s)=s$, $s\in[1,2]$ için ortak durumda $\log(W_A/W_B)=0$ iken kapsama aralığı $[-\log2,\ \log2]$'dir. Tam toplamsallık ve idempotentte sıfırlanma **yalnız kesin karakter için** geçerlidir; bu kapsama sonucu duruma bağlı fiziksel maliyet aralığına otomatik taşınmaz. Logaritma için genişliklerin kesin pozitifliği gerekir |

Kilit etkisi ayrı bir idempotent temsil ya da izdüşümcüyle taşınabilir:

$$\Pi_\kappa:\mathcal B\to\mathcal B,\qquad \Pi_\kappa^2=\Pi_\kappa$$

```latex
\Pi_\kappa:\mathcal B\to\mathcal B,\qquad \Pi_\kappa^2=\Pi_\kappa
```

| Sembol | Anlamı |
|---|---|
| $\Pi_\kappa$ | Kilidin izdüşümcü (projektör) temsili |
| $\mathcal B$ | Durumların uzayı |

Böylece kesin karakterin idempotentte sıfırlanması ($\omega(\kappa)=0$), kilidin fiziksel etkisini ortadan kaldırmaz: etkiyi karakter değil, izdüşümcü taşır.

### Hesaplama notu

Aralık aritmetiği **kesin sayılarla** yapılmalıdır. Kayan nokta aritmetiğinde birleşme özelliği yuvarlamadan bozulur.

### Mühürleme maliyeti — tarihsel köprü, aday okuma

Mühürleme maliyeti $C_s$ için iki anlatım arşivde birlikte durur; ikisi de burada **aday okuma** kipindedir. Tarihsel modelde kaynak sembolü $\Gamma$ olan niceliği, güncel zaman iskelesindeki $\Gamma$ ile karıştırmamak için $\Gamma_{\rm hist}$ ile yazalım:

$$\Gamma_{\rm hist}=\Gamma_0(1+\lambda D_+)^{-1},\qquad C_s\propto\frac{1}{\Gamma_{\rm hist}}\propto(1+\lambda D_+),\qquad \nabla C_s=\Lambda\nabla\ln\chi_S \quad (\Lambda \text{ sabit})$$

```latex
\Gamma_{\rm hist}=\Gamma_0(1+\lambda D_+)^{-1},\qquad C_s\propto\frac{1}{\Gamma_{\rm hist}}\propto(1+\lambda D_+),\qquad \nabla C_s=\Lambda\nabla\ln\chi_S \quad (\Lambda \text{ sabit})
```

Tarihsel nedensellik zinciri şöyledir:

$$D_+\;\to\;\Gamma_{\rm hist}\downarrow\;\to\;C_s\uparrow\;\to\;\chi_S\neq1\;\to\;\mathbf g_\chi$$

```latex
D_+\;\to\;\Gamma_{\rm hist}\downarrow\;\to\;C_s\uparrow\;\to\;\chi_S\neq1\;\to\;\mathbf g_\chi
```

| Sembol | Anlamı |
|---|---|
| $\Gamma_{\rm hist}$ | Tarihsel modeldeki kayıt / çözünme hızı (7.2'deki $\Gamma$ ile karıştırılmaz) |
| $\Gamma_0$ | Referans değer |
| $D_+$ | c⁺ yönündeki yoğunluk / doluluk ölçüsü (tarihsel model niceliği) |
| $\lambda$ | Bağlaşım katsayısı |
| $C_s$ | Mühürleme maliyeti (aday okuma) |
| $\Lambda$ | Kanal ölçek katsayısı (kozmolojik sabit değil) |
| $\chi_S$ | Kanal asimetri oranı (17.1) |
| $\mathbf g_\chi$ | Kanal kaynaklı aday ivme alanı (8.8) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Mühürleme maliyetini c⁺ yoğunluğuna bağlayan ve oradan kanal asimetrisine giden bir zincir önerir |
| **Neden yapıyor?** | Mühürlemenin fiziksel bir bedeli varsa, bunun Cₘ'de ölçülebilir bir izi olup olmadığını aramak için |
| **Nasıl yapıyor?** | Yoğunluk arttıkça kayıt hızının düştüğünü, maliyetin arttığını ve bunun karşılıklı olmayan bir kanal asimetrisi olarak okunabileceğini varsayar |
| **Ne sonuç bekleniyor?** | Laboratuvarda ölçülebilir bir $\chi_S\neq1$ imzası |
| **Ne sonuç elde ediliyor?** | **Aday okumadır**; 7.2'deki zaman iskelesini ya da bu bölümdeki damga cebirini tanımlamaz. $D_+$ ve $C_s$ güncel çekirdeğin temel nicelikleri değildir. Kaynak gösterimdeki $\Gamma$ ile 7.2'deki $\Gamma$'nın aynı fiziksel rolün iki adı mı, yoksa bağımsız nicelikler mi olduğu açıktır. 24.2'deki çift sayım borcu bu blokla **çözülmüş sayılmaz**. Emekli "karanlık madde için $\nabla\ln\chi_S\neq0$" ölçütü bu zincire geri getirilmez |

## 14.4 İki katmanlı arşiv

| Katman | Yapı | Özellik |
|---|---|---|
| **Ham arşiv** | Kayıtlar üzerinde serbest monoid | **Salt ekleme**; tam sadakat |
| **Damga izdüşümü** | $M$'ye kaba izdüşüm | İdempotent kilitler burada |

$$\boxed{\;\text{Ham arşiv} \;\neq\; M\;}$$

```latex
\boxed{\;\text{Ham arşiv} \;\neq\; M\;}
```

Kritik fark şudur:

$$\kappa^2 = \kappa \quad\text{(damga monoidinde)} \qquad\qquad A + [r_1] + [r_2] \;\neq\; A + [r_1] \quad\text{(ham arşivde; } \mathrm{damga}(r_1)=\mathrm{damga}(r_2)=\kappa,\ \mathrm{rid}(r_1)\neq\mathrm{rid}(r_2))$$

```latex
\kappa^2 = \kappa \quad\text{(damga monoidinde)} \qquad\qquad A + [r_1] + [r_2] \;\neq\; A + [r_1] \quad\text{(ham arşivde; } \mathrm{damga}(r_1)=\mathrm{damga}(r_2)=\kappa,\ \mathrm{rid}(r_1)\neq\mathrm{rid}(r_2))
```

| Sembol | Anlamı |
|---|---|
| $A$ | Ham arşiv (kayıt dizisi) |
| $[r_1]$, $[r_2]$ | Aynı damgayı taşıyan, kimlikleri farklı iki tek kayıtlık dizi |
| $+$ | Ekleme (dizilerin art arda bağlanması) |

**Olay kaynağı çökertilmez.** Aynı damga iki kez basılsa bile iki ayrı kayıt oluşur — iki ayrı kimlikle ($r_1$, $r_2$): cebirsel görüntüde kilit bir kez sayılır, ama ham arşivde iki olay iki olay olarak kalır.

**Üst yapı ile geçerli arşiv ayrımı.** Serbest monoid bütün sonlu kayıt dizilerini içerir, aynı kimliğin tekrarlandığı dizileri de. Geçerli arşivler bunun kimlikleri tekrarsız alt kümesidir ve bu alt küme sınırsız birleştirme altında kapalı değildir; bu yüzden ekleme bir koşulla korunur:

$$\mathcal A_{\rm geçerli}=\{A\in\mathrm{FreeMonoid}(\mathrm{Record}):\ \mathrm{NoDup}(A.\mathrm{map}\;\mathrm{rid})\},\qquad \mathrm{append}(A,r)\ \text{yalnız}\ \mathrm{rid}(r)\notin\mathrm{IDs}(A)$$

```latex
\mathcal A_{\rm geçerli}=\{A\in\mathrm{FreeMonoid}(\mathrm{Record}):\ \mathrm{NoDup}(A.\mathrm{map}\;\mathrm{rid})\},\qquad \mathrm{append}(A,r)\ \text{yalnız}\ \mathrm{rid}(r)\notin\mathrm{IDs}(A)
```

| Sembol | Anlamı |
|---|---|
| $\mathcal A_{\rm geçerli}$ | Kimlikleri tekrarsız (geçerli) ham arşivler |
| $\mathrm{IDs}(A)$ | $A$'daki kayıt kimlikleri kümesi |
| $\mathrm{append}$ | Korumalı ekleme işlemi |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Serbest monoidi üst yapı, kimlik-tekrarsız dizileri geçerli arşiv olarak ayırır |
| **Neden yapıyor?** | $\mathrm{NoDup}$ değişmezi ile serbest monoidin aynı kapalı yapı sanılması, $[r]+[r]$ gibi geçersiz örnekler üretiyordu |
| **Nasıl yapıyor?** | Eklemeyi yeni kimlik koşuluna bağlar |
| **Ne sonuç bekleniyor?** | `rid` tekliğinin ve `WellFormedArchive`'ın biçimsel kanıtı (23.10) |
| **Ne sonuç elde ediliyor?** | **Tip ayrımı kuruludur**; damga monoidinin cebirsel sonuçları değişmez |

### Kayıt yapısı

$$r = \big(\mathrm{rid},\; \text{kenar},\; \text{damga},\; \text{içerik aralığı}\big)$$

```latex
r = \big(\mathrm{rid},\; \text{kenar},\; \text{damga},\; \text{içerik aralığı}\big)
```

- $\mathrm{rid}$ **tekildir** ve fiziksel bir parametre **değildir**
- Silme işlemleri işlem kümesinde **yoktur**
- Arşiv sırası bir **kaynak sırasıdır**; fiziksel zaman değildir
- Cₘ okumasındaki zaman etiketi arşive **geriye sokulmaz**

Zaman etiketi bir **Cₘ kaynak bilgisidir**; c⁺'ın kendi zaman koordinatı yoktur ($dt_{c^+}=0$ öğretici okuma; $\bot_+$ ontolojik durum).

İyi biçimli ham arşiv için iki temel biçimsel değişmez adayı şunlardır:

$$\boxed{\;\mathrm{NoDup}(A.\mathrm{map}\;\mathrm{rid})\;}\qquad\qquad \boxed{\;A\preceq A'\;}$$

```latex
\boxed{\;\mathrm{NoDup}(A.\mathrm{map}\;\mathrm{rid})\;}\qquad\qquad \boxed{\;A\preceq A'\;}
```

| Sembol | Anlamı |
|---|---|
| $\mathrm{NoDup}$ | Listede tekrar eden eleman olmaması |
| $A.\mathrm{map}\;\mathrm{rid}$ | Arşivdeki bütün kayıtların kimlik listesi |
| $A\preceq A'$ | $A$, $A'$'nün önekidir (salt ekleme düzeni) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | İyi biçimli bir ham arşivin iki temel değişmezini yazar |
| **Neden yapıyor?** | Kayıt kimliklerinin tekilliği ve kaynak bilgisinin yalnız büyüyebilmesi, mührün silinemezliğinin biçimsel karşılığıdır |
| **Nasıl yapıyor?** | Birinci değişmez kimliklerin tekrarsızlığını, ikincisi her yeni arşivin eskisini önek olarak içermesini ister |
| **Ne sonuç bekleniyor?** | Silme ya da geri alma temel işlemi olmadan kaynak bilgisinin tekdüze genişlemesi |
| **Ne sonuç elde ediliyor?** | **Biçimsel değişmez adaylarıdır**; ontolojik hükümle (kayıt sabit) tam uyumludur |

### Ham arşivin serbest monoid gerçeklemesi

Ham kaynak bilgisi için uygun en küçük yapı şudur:

$$\mathcal A_{\rm raw}=\mathrm{FreeMonoid}(\mathrm{Record}),\qquad \pi_{\rm stamp}:\mathcal A_{\rm raw}\to M$$

```latex
\mathcal A_{\rm raw}=\mathrm{FreeMonoid}(\mathrm{Record}),\qquad \pi_{\rm stamp}:\mathcal A_{\rm raw}\to M
```

| Sembol | Anlamı |
|---|---|
| $\mathcal A_{\rm raw}$ | Ham arşiv |
| $\mathrm{FreeMonoid}(\mathrm{Record})$ | Kayıtlar üzerinde serbest monoid (sonlu kayıt dizileri) |
| $\pi_{\rm stamp}$ | Damga izdüşümü: kayıt dizisini damga kelimesine kaba olarak indirger |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Ham arşivi kayıtların serbest monoidi olarak kurar ve damga monoidine bir izdüşümle bağlar |
| **Neden yapıyor?** | Tam sadakatli kayıt ile kaba cebirsel özet arasındaki ilişkiyi kesin kılmak için |
| **Nasıl yapıyor?** | İzdüşüm her kaydı damgasına indirger; `rid`, içerik aralığı ve olay çokluğu bu indirgemede korunmak zorunda değildir |
| **Ne sonuç bekleniyor?** | Cebirsel sonuçların ham arşiv anlamıyla karıştırılmaması |
| **Ne sonuç elde ediliyor?** | İzdüşüm **bilgi kaybettirir**; bu yüzden ham arşiv ≠ $M$ |

Silme işlemleri dışarıda tutulur:

```text
erase, pop, undo ∉ Ops(Archive)
```

### İdeal / Rees çökertmesi uyarısı

Kilit içeren kelimeler cebirde ideale benzer bir sınıf oluşturabilir; ama bütün kilit içeriğini tek bir soğurucu sıfıra çökertmek kaynak bilgisini yok eder. Dolayısıyla "kilitli her şeyi tek bir sıfır sınıfına indir" yaklaşımı güncel biçimsel programda kullanılmaz. Bu ayrım, grup tamamlaması ya da bölüm sonucunun fiziksel arşiv anlamı sanılmasını engeller.

### Arşiv sayısı ve tekdüzelik

Ham arşiv yalnız eklemeyle büyür. Buradan kesin bir sonuç çıkar: arşive bir kayıt eklendiğinde kayıt sayısı tam olarak bir artar.

$$N_{\rm arşiv}(n+1) \;\geq\; N_{\rm arşiv}(n)$$

```latex
N_{\rm arşiv}(n+1) \;\geq\; N_{\rm arşiv}(n)
```

| Sembol | Anlamı |
|---|---|
| $N_{\rm arşiv}(n)$ | $n$. ekleme adımından sonraki kayıt sayısı |
| $n$ | Kaynak sırası (ekleme sırası) indeksi — fiziksel zaman değil |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Arşivdeki kayıt sayısının ekleme sırasında azalmadığını söyler |
| **Neden yapıyor?** | Silme temel işlemi olmayan bir arşivin sayımsal sonucunu kesinleştirmek için |
| **Nasıl yapıyor?** | Her ekleme işleminin sayıyı tam olarak bir artırdığını gösterir |
| **Ne sonuç bekleniyor?** | Kaynak sırasında kesin tekdüzelik |
| **Ne sonuç elde ediliyor?** | **Biçimsel olarak kanıtlanmıştır**, ama kaynak sırasında geçerlidir; fiziksel zamana göre bir türev değildir ve sürekli bir "arşiv büyüme hızı" kendiliğinden çıkmaz. Entropi modellerindeki kayıt sayısı ayrı bir model niceliğidir; bir modelde doluluğun azalması arşivin silindiği anlamına gelmez |

Faz hafızasının kaynak sırasında tekdüze olduğu ilkesi ($R_\varphi(r_{n+1}) \geq R_\varphi(r_n)$) ise farklı bir statüdedir: fiziksel zaman yerine kaynak sırasının kullanılması kesindir, ama tekdüzeliğin kendisi biçimsel olarak kanıtlanmış bir teorem değil, bir **mimari kuraldır**. Statüsü yazarın kararına bağlıdır.

## 14.5 "Bütün geçmiş mevcuttur"un doğru hâli

"Bütün geçmiş c⁺'ta mevcuttur" sezgisinin doğru hâli, kayıt kümesi üzerinde **statik bir uygunluk ilişkisidir** — bir akış değil. Bu, zamansızlık ilkesini bozmadan arşiv sezgisini korur: arşivde "önce" ve "sonra" yoktur; yalnız kaynak sırası ve kayıtlar arasındaki ilişkiler vardır.

## 14.6 q/Σ iki katmanlı okuma

İki ayrı harita farklı bilgileri taşır:

$$q:\mathcal C_{\rm full}\to G_{\rm bare},\qquad\qquad \Sigma:\mathcal C_{\rm full}\to M$$

```latex
q:\mathcal C_{\rm full}\to G_{\rm bare},\qquad\qquad \Sigma:\mathcal C_{\rm full}\to M
```

Çıplak katmanda ters yön temsil edilebilir; damga monoidinde genel olarak edilemez:

$$\boxed{\;q(T_{ji})=q(T_{ij})^{-1}\;}\qquad\qquad \Sigma(T_{ji})=\Sigma(T_{ij})^{-1}\ \ \text{(genel olarak YAZILAMAZ)}$$

```latex
\boxed{\;q(T_{ji})=q(T_{ij})^{-1}\;}\qquad\qquad \Sigma(T_{ji})=\Sigma(T_{ij})^{-1}\ \ \text{(genel olarak YAZILAMAZ)}
```

Damgasız doğrudan kenarda anlam katmanı ile cebirsel katman ayrı tutulur:

$$\boxed{\;\mathrm{emittedStamp}(T_{0+})=\texttt{None},\qquad \Sigma(T_{0+})=e\;}\qquad \boxed{\;\text{NoStamp}\neq \text{NoTransition},\qquad \texttt{None}\neq\texttt{Some}(e)\;}$$

```latex
\boxed{\;\mathrm{emittedStamp}(T_{0+})=\texttt{None},\qquad \Sigma(T_{0+})=e\;}\qquad \boxed{\;\text{NoStamp}\neq \text{NoTransition},\qquad \texttt{None}\neq\texttt{Some}(e)\;}
```

| Sembol | Anlamı |
|---|---|
| $\mathcal C_{\rm full}$ | Bütün bilgileriyle (damga, kaynak, yön) geçişler kategorisi |
| $G_{\rm bare}$ | Damga ve kaynak bilgisi unutulmuş çıplak faz geçiş grupoidi |
| $q$ | Unutkan harita: çıplak faz geçişini verir |
| $\Sigma$ | Damga haritası: geçişin damga monoidindeki görüntüsü |
| $T_{ij}$, $T_{ji}$ | $i$'den $j$'ye ve ters yöndeki geçiş |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bir geçişin "hangi fazdan hangisine" bilgisini ve "arşive ne yazdı" bilgisini iki ayrı haritaya ayırır |
| **Neden yapıyor?** | Kapı çift yönlü, damga tek yönlüdür (13.1); tek bir harita ikisini birden doğru taşıyamaz |
| **Nasıl yapıyor?** | Çıplak katmanda ters geçişi grup tersi olarak temsil eder; damga katmanında monoid olduğu için ters yazmaz |
| **Ne sonuç bekleniyor?** | Kapının çift yönlülüğü ile mührün tek yönlülüğünün çelişkisiz bir arada yazılması |
| **Ne sonuç elde ediliyor?** | Koruma kuralları geçerlidir: **damgasız geçiş ≠ geçiş yok**, **`None` ≠ `Some(e)`** |

## 14.7 C katmanı — geçiş anlamının ayrıştırılması

Biçimsel modelde aşağıdaki alanların tek bir sembole sıkıştırılmaması gerekir:

$$\boxed{\;\mathfrak C(T)=(Gate,\,EdgeClass,\,Direction,\,StampClass,\,StampEmission,\,SealEffect,\,ArchiveEffect,\,CoordinationEffect,\,ProjectionEffect)\;}$$

```latex
\boxed{\;\mathfrak C(T)=(Gate,\,EdgeClass,\,Direction,\,StampClass,\,StampEmission,\,SealEffect,\,ArchiveEffect,\,CoordinationEffect,\,ProjectionEffect)\;}
```

| Alan | Anlamı |
|---|---|
| $Gate$ | Kapı (yapısal izin) |
| $EdgeClass$ | Kenar sınıfı (Δ₀ₘ, Δ₊ₘ, Δ₀₊) |
| $Direction$ | Geçiş yönü |
| $StampClass$ | Damga sınıfı (serbest / kilit) |
| $StampEmission$ | Damga üretimi (`Option Stamp`) |
| $SealEffect$ | Mühürleme etkisi |
| $ArchiveEffect$ | Arşive etkisi (ekleme / değişiklik yok) |
| $CoordinationEffect$ | $X$ koordinasyon etkisi |
| $ProjectionEffect$ | Cₘ'deki okuma / izdüşüm etkisi |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bir geçişin anlamını dokuz bağımsız alana ayırır |
| **Neden yapıyor?** | Bu alanları tek sembolde birleştirmek, ontolojide birbirinden ayrı tutulan kavramları sessizce özdeşleştirirdi |
| **Nasıl yapıyor?** | Her alanı ayrı bir bileşen olarak tutar; böylece şu özdeşlikler engellenir |
| **Ne sonuç bekleniyor?** | Biçimsel kodun ontolojik ayrımları birebir koruması |
| **Ne sonuç elde ediliyor?** | Cₘ → c⁺ yönünde arşive ekleme ve c⁺ → Cₘ yönünde okuma / izdüşüm ayrımı, ontolojiyle uyumlu bir **biçimsel adaydır**; yön anlamı doğrudan kanon olarak ayrıca kilitlenmediği yerde teorem gibi yazılmaz |

```text
faz ilişkisi ≠ yön
yön ≠ damga sınıfı
damga sınıfı ≠ damga üretimi
damga üretimi ≠ mühürleme
mühürleme ≠ arşiv değişikliği
arşiv değişikliği ≠ koordinasyon / okuma
```

---

## 14.8 Yol ilişkileri ve çevrim karakteri

Unutkan harita $q$ ve $q(T_{ji})=q(T_{ij})^{-1}$ aksiyomu altında, ters yönlü yollar için şu ilişki **türetilmiş bir sonuç** olabilir; bağımsız bir fizik aksiyomu olarak çoğaltılmamalıdır:

$$q(\gamma_-)=q(\gamma_+)^{-1}$$

```latex
q(\gamma_-)=q(\gamma_+)^{-1}
```

Damga haritası için aynı ters yazılamaz; $\Sigma(\gamma_-)=\Sigma(\gamma_+)^{-1}$ genel olarak anlamsızdır, çünkü $M$ grup değildir.

Bir çevrimde sıraya duyarsız toplamsal bilgi $\Omega$ karakteriyle özetlenebilir. Sıraya duyarlı içerik ise bir temsil ister:

$$\rho:M\to\operatorname{End}(V)$$

```latex
\rho:M\to\operatorname{End}(V)
```

Bir Cₘ izdüşüm modeli Schnakenberg benzeri bir çevrim afinitesi tanımlarsa:

$$\mathcal A_{\rm cyc}\neq0$$

```latex
\mathcal A_{\rm cyc}\neq0
```

| Sembol | Anlamı |
|---|---|
| $\gamma_+$, $\gamma_-$ | Bir yol ve onun ters yönlüsü |
| $\rho$ | Damga monoidinin bir vektör uzayı üzerindeki temsili |
| $\operatorname{End}(V)$ | $V$ vektör uzayının doğrusal dönüşümleri |
| $\mathcal A_{\rm cyc}$ | Çevrim afinitesi (Cₘ izdüşüm modelinde) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kapalı faz çevrimlerinde hangi bilginin sıraya duyarsız, hangisinin sıraya duyarlı olduğunu ayırır |
| **Neden yapıyor?** | Döngüsel bir faz yolunun arşivde bıraktığı izin, yalnız net bir sayıyla özetlenemeyecek kadar zengin olabileceğini göstermek için |
| **Nasıl yapıyor?** | Sıraya duyarsız kısmı karakterle, sıraya duyarlı kısmı doğrusal bir temsille taşır |
| **Ne sonuç bekleniyor?** | Mühürleme asimetrisinin ya da şiddetinin ölçülebilir bir okuma adayı |
| **Ne sonuç elde ediliyor?** | $\rho$'nun ilgili alt sektörü tersinirse "holonomi" dili kullanılabilir; genel monoid için **sıralı taşıma** daha güvenlidir. $\mathcal A_{\rm cyc}\neq0$, mühürleme asimetrisi için bir **okuma adayıdır**; zamansız temel katmanda bir hız yasası değildir |

## 14.9 Kayıt ile mühürleme ayrımı

Arşivde iki kavram ayrıştırılmıştır:

| Kavram | Anlamı |
|---|---|
| **Cₘ izi (recording)** | Cₘ içi sürecin tarih taşıyan, Cₘ'den geri okunabilir kalıcı bir iz üretmesi — korunabilirlik meselesi |
| **Mühürleme (sealing)** | c⁺ arşivine bir kaydın geri alınamaz biçimde yazılması — tersinmezlik meselesi |

$$\boxed{\;\text{"Geri kazanılabilir geçmiş izi" ancak Cₘ izi düzeyinde tanımlanabilir; mühürleme tek başına geçmişi geri getirmez.}\;}$$

```latex
\boxed{\;\text{"Geri kazanılabilir geçmiş izi" ancak Cₘ izi düzeyinde tanımlanabilir; mühürleme tek başına geçmişi geri getirmez.}\;}
```

Kritik hüküm: mühürleme, c⁺ arşivine bir kaydın yazılmasıdır (14.1) ve bu anlamda kaydı gerektirir; ama Cₘ içinde geri okunabilir bir iz bırakmayı, fiziksel durumun eksiksiz kaydını ya da kaydın Cₘ'den geri kazanılabilirliğini **garanti etmez**. Cₘ izleri çoğu durumda kısmi ve seçicidir; iz yoğunluğu ≠ zaman üretim hızı. (Önceki sürümdeki "mühürleme kaydı zorunlu kılmaz" yazımı, "kayıt" sözcüğünün hem c⁺ arşiv kaydı hem Cₘ izi için kullanılmasından doğan bir çelişkiydi; düzeltilmiştir.)

## 14.10 Durumsuz evren — geri kazanılabilir ve kodlanmış tarih

Arşivdeki "durumsuz evren" kaydı şunu söyler: evrenin hâli geçmişi depolayan bir durum değildir; tarih çoklu kayıtlarda (izlerde) korunur.

$$\boxed{\;\mathrm{durum}(t) \neq \text{depolanmış tarih}\quad \text{ve}\quad R_\varphi(t+\Delta t)\in[R_\varphi(t),\; R_\varphi(t)+\Delta R_{\max}]\;}$$

```latex
\boxed{\;\mathrm{durum}(t) \neq \text{depolanmış tarih}\quad \text{ve}\quad R_\varphi(t+\Delta t)\in[R_\varphi(t),\; R_\varphi(t)+\Delta R_{\max}]\;}
```

| Sembol | Anlamı |
|---|---|
| $\mathrm{durum}(t)$ | Cₘ'de $t$ anındaki durum |
| $R_\varphi$ | Faz hafızası (14.4) |
| $\Delta R_{\max}$ | Bir adımda faz hafızasının en fazla artışı |
| $t$, $\Delta t$ | Cₘ okuma zamanı ve adımı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Evrenin anlık durumunu, depolanmış tarihten ayırır ve faz hafızasının sınırlı tekdüze artışını yazar |
| **Neden yapıyor?** | "Gözlem kaydı otomatik olarak korur" varsayımının yanlış olduğunu ve tarihin izlerde yaşadığını açık kılmak için |
| **Nasıl yapıyor?** | Faz hafızasının her adımda azalmadığını ama sınırlı bir miktardan fazla artmadığını aralık biçiminde yazar |
| **Ne sonuç bekleniyor?** | **Kodlanmış tarih** (kayıt yalnız saklanıyor) ile **geri kazanılabilir tarih** (yapısal kalıntı etkin olarak okunabiliyor) arasında sınanabilir bir ayrım |
| **Ne sonuç elde ediliyor?** | "Kayıt hipotezi" (gözlemin kaydı otomatik olarak koruduğu) **reddedilmiştir**. Evertophy'nin ileri iddiası geri kazanılabilir tarihtir ve **kanıtlanmamıştır** |

---

### Denklem seti — Ω faz geçiş karakteri

Fazlar arası geçişin bileşim yasası: A → B ve B → C geçişleri A → C'yi vermelidir.

$$\omega_{AB} + \omega_{BC} = \omega_{AC}\ \text{(kesin)} \qquad \Omega_{AB} \boxplus_B \Omega_{BC} = \Omega_{AC}\ \text{(bağımlı)} \qquad \Omega_{AC} \subseteq \Omega_{AB} \oplus \Omega_{BC}\ \text{(bağımsız kapsama)}$$

```latex
\omega_{AB} + \omega_{BC} = \omega_{AC}\ \text{(kesin)} \qquad \Omega_{AB} \boxplus_B \Omega_{BC} = \Omega_{AC}\ \text{(bağımlı)} \qquad \Omega_{AC} \subseteq \Omega_{AB} \oplus \Omega_{BC}\ \text{(bağımsız kapsama)}
```

| Sembol | Anlamı |
|---|---|
| $\omega_{AB}(s)$ | Ortak durum $s$'de kesin skaler karakter: $\ln W_A(s) - \ln W_B(s)$ |
| $\Omega_{AB}$ | Aralık değerli karakter |
| $\boxplus_B$ | Ara faz B üzerinden bağımlılığı koruyan birleşim |
| $\oplus$ | Bağımsız (Minkowski) toplam |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Ardışık iki geçişin karakterlerinin nasıl birleştiğini üç farklı düzeyde yazar |
| **Neden yapıyor?** | Naif aralık eşitliği $\Omega_{AB}+\Omega_{BC}=\Omega_{AC}$, bağımlılık bilgisi kaybolduğunda yanlıştır |
| **Nasıl yapıyor?** | Kesin düzeyde tam toplamsallık; bağımlılık korunduğunda eşitlik; bağımsız uçlarda yalnız içerme |
| **Ne sonuç bekleniyor?** | Range biçimciliğinde tutarlı bir bileşim kuralı |
| **Ne sonuç elde ediliyor?** | Naif aralık eşitliği **yanlıştır**; üç katmanlı yapı (kesin / bağımlı / kapsama) **doğrudur** |




# BÖLÜM 15 — ÖLÇÜM VE OKUMA

## 15.1 Ölçüm Cₘ'ye aittir

$$\boxed{\;\text{DOĞRUDAN FİZİKSEL ÖLÇÜM YALNIZ Cₘ'DE MÜMKÜNDÜR.}\;}$$

```latex
\boxed{\;\text{DOĞRUDAN FİZİKSEL ÖLÇÜM YALNIZ Cₘ'DE MÜMKÜNDÜR.}\;}
```

Ölçüm; bir kaydın oluşması, bir saatin işlemesi, bir dedektörün tıklaması demektir. Bunların hepsi farklılaşmış madde, kurulmuş zaman ve metrik ister. c₀'da bunlar henüz kurulmamış, c⁺'ta çözünmüştür. Bu yüzden dış fazlar hakkında bildiğimiz her şey, onların Cₘ'deki **okumalarından** gelir.

## 15.1a Faz rolleri: içsel, kaynak ve gözlem fazı

Bir niceliğin fazlarla ilişkisini konuşurken üç farklı rol birbirine karıştırılmamalıdır:

| Rol | Anlamı |
|---|---|
| **İçsel faz** | Niceliğin kendi dilinde tanımlı olduğu faz |
| **Kaynak faz** | Bir etkinin geldiği faz |
| **Gözlem fazı** | Etkinin ölçüldüğü faz — ölçüm her zaman Cₘ'dedir |

Bu ayrım bir karışıklığı giderir: c⁺ kaynaklı bir etki Cₘ'de gözlendiğinde, gözlenen değer Cₘ'de bir değerdir; c⁺'ta çözünmüş olan hâlâ çözünmüş kalır. Bu ayrım tipli bir okuma yapısıyla biçimsel olarak kodlanmıştır. Okumanın **tipi** kuruludur; okumanın **yasası** — hangi c⁺ kaynağının Cₘ'de hangi değeri verdiği — aşağıda söylendiği gibi açık borçtur.

## 15.2 Okuma haritası — açık borç

Cₘ durumundan ölçülen niceliklere giden harita **tanımsızdır**.

$$\boxed{\;\text{Soru "okuma haritası nedir" DEĞİL, "onu TEKİL kılan ek ilke nedir"dir.}\;}$$

```latex
\boxed{\;\text{Soru "okuma haritası nedir" DEĞİL, "onu TEKİL kılan ek ilke nedir"dir.}\;}
```

Çünkü böyle bir harita gözlemden tekil olarak çıkarılamaz: aynı gözlemsel sonucu farklı yapılar verebilir. Bu, çerçevenin üçüncü ilkesiyle de uyumludur: bir temsil, ölçümü yeniden ürettiği kapsamda geçerlidir ve temsiller arasında ontolojik öncelik yoktur.

### Kuantum açık sistem araçları

Kraus, Lindblad ve Stinespring gibi araçlar bu harita için kullanılabilir.

$$\boxed{\;\text{Bunlar OLASI Cₘ MODEL / İSKELELERİDİR — ÇEKİRDEK ONTOLOJİ TEMEL ÖĞESİ DEĞİLDİR.}\;}$$

```latex
\boxed{\;\text{Bunlar OLASI Cₘ MODEL / İSKELELERİDİR — ÇEKİRDEK ONTOLOJİ TEMEL ÖĞESİ DEĞİLDİR.}\;}
```

Mühürleme tanımı bu araçlara **indirgenemez**; mühürleme ontolojiktir, bu araçlar Cₘ içi hesap dilidir. Arşivdeki tamamen pozitif ve iz koruyan (CPTP) Kraus modeli bu sınır içinde bir köprü adayıdır:

$$\mathcal E(\rho)=\sum_i K_i\rho K_i^\dagger,\qquad \sum_iK_i^\dagger K_i=I$$

```latex
\mathcal E(\rho)=\sum_i K_i\rho K_i^\dagger,\qquad \sum_iK_i^\dagger K_i=I
```

| Sembol | Anlamı |
|---|---|
| $\rho$ | Sistemin yoğunluk matrisi (Cₘ kuantum durumu) |
| $\mathcal E$ | Kuantum kanalı (durum dönüşümü) |
| $K_i$ | Kraus işlemcileri |
| $K_i^\dagger$ | $K_i$'nin eşlenik devriği |
| $I$ | Birim işlemci |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bir kuantum durumunun çevreyle etkileşim sonrası nasıl dönüştüğünü yazar |
| **Neden yapıyor?** | Ölçüm ve kayıt süreçlerinin Cₘ'deki hesaplanabilir dilini sağlamak için |
| **Nasıl yapıyor?** | Durumu Kraus işlemcilerinin toplamıyla dönüştürür; tamlık koşulu toplam olasılığı korur |
| **Ne sonuç bekleniyor?** | Mühürleme olayının Cₘ izdüşümünün hesaplanabilir bir modeli |
| **Ne sonuç elde ediliyor?** | **Köprü adayıdır.** "Mühürleme = dolanıklık aktarımı" ve Cₘ izdüşümündeki kısmi iz kaybının tek yönlü geçmiş olarak yorumlanması, **hesaplanabilir model hipotezidir**; mühürlemenin tanımı ya da c⁺'ın temel öğesi değildir. Hamilton / Lindblad dili de yalnız Cₘ içi etkin dinamik için adaydır; c₀'a üç artı bir boyutlu Lagrange / Hamilton yapısı ithal etmez |

## 15.3 Ölçüm ve çöküş — model sınırı

Evertophy, ölçümü faz, okuma ve mühürleme diliyle yeniden yorumlamayı araştırabilir; ama kuantum ölçüm probleminin çözüldüğü iddia edilmez. "Liminal rejim → Cₘ izdüşümü → mühürleme" zinciri bir **model / yorum adayıdır**.

Kuantum belirsizliğini doğrudan "Cₘ ekranının sonlu çözünürlüğü"ne eşitlemek güncel çekirdek değildir; böyle bir yorum ancak standart kuantum olasılıklarını ve Born kuralı davranışını türetirse fiziksel köprü statüsü kazanabilir.

Gecikmeli seçimli kuantum silici gibi deneyler bu çerçevede **uyumlu okuma** kipinde ele alınır: deneyin ölçülmüş sonuçları koşulsuz kabul edilir; Evertophy okuması bu sonuçlarla çelişmeyen bir yorum sunar, ama onları tescil ettiği ya da yalnız kendisinin açıkladığı iddiasında bulunmaz.

## 15.4 Mühürleme maliyeti

Mühürleme maliyeti, yenileme süresi ve çözünürlük gürültüsü arşivde kullanılan **kavramsal model değişkenleridir**; güncel ontolojinin temel öğeleri değildir ve nicel tanımları henüz kapanmamıştır. Mühürleme maliyeti $C_s$, 14.3'teki gibi **aday okuma** kipindedir.

---

## 15.5 Beş adımlı mühendislik ölçüm protokolü

*Not:* Tek port ya da tek bir faz farkı karşılıksızlığı kanıtlamaz; $S_{21}$ ve $S_{12}$ aynı normalizasyon ve koşullarda karşılaştırılmalıdır (17.1).

Deneysel köprüler için arşivde olgunlaştırılmış mühendislik protokolü şudur:

| # | Adım | İçerik |
|---|---|---|
| 1 | Giriş fazı | $(\Phi,\Xi,X)$ → empedans / faz parametreleri; port ve normalizasyon netleştirilir |
| 2 | Bağlaşım | Giriş–çıkış geçiş matrisi (CMT) |
| 3 | Asimetri | $S_{21}/S_{12}\to\chi_S$; karşılıklılık denetimi şarttır (17.1) |
| 4 | Güvenlik | Akromatiklik $\partial X/\partial E_{\rm probe} = 0$ (LHAASO kısıtlarıyla uyum); ayrık modellemede S-parametreleriyle doğrulama |
| 5 | Çıkış fazı | İvme eşlemesi (taslak köprü), aşağıdaki denklem |

$$\mathbf g_{\rm eff} = +c^2\nabla\ln Z_g \quad\text{ya da}\quad \mathbf g_{\rm eff}=-\Lambda\nabla\ln\chi_S - (\ln\chi_S)\nabla\Lambda$$

```latex
\mathbf g_{\rm eff} = +c^2\nabla\ln Z_g \quad\text{ya da}\quad \mathbf g_{\rm eff}=-\Lambda\nabla\ln\chi_S - (\ln\chi_S)\nabla\Lambda
```

Aktif eşik modülasyonu için aday mekanizma:

$$\Delta\Phi(t) = \Phi_0\sin(\omega_m t)$$

```latex
\Delta\Phi(t) = \Phi_0\sin(\omega_m t)
```

| Sembol | Anlamı |
|---|---|
| $\mathbf g_{\rm eff}$ | Etkin ivme okuması |
| $Z_g$ | Kütleçekimsel empedans (8.7) |
| $\chi_S$, $\Lambda$ | Kanal asimetri oranı ve ölçek katsayısı (17.1) |
| $E_{\rm probe}$ | Sınama sinyalinin enerjisi |
| $\Delta\Phi(t)$ | Tek porttan uygulanan eşik modülasyonu |
| $\Phi_0$, $\omega_m$ | Modülasyon genliği ve açısal frekansı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kanal köprüsünü sınamak için girişten çıkışa beş adımlı bir laboratuvar protokolü tanımlar |
| **Neden yapıyor?** | Köprü iddialarının ölçülebilir, tekrarlanabilir ve önceden kayıt edilebilir bir sınama düzenine bağlanması için |
| **Nasıl yapıyor?** | Port normalizasyonunu sabitler, iki yönlü saçılmayı ölçer, karşılıklılığı denetler, akromatiklik kısıtını uygular ve sonucu bir ivme eşlemesine bağlar; zamanla modülasyonu karşılıklılık kırıcı aday olarak kullanır (bant durduran aralıklar kaçak modları azalttığı için tercih edilir) |
| **Ne sonuç bekleniyor?** | Karşılıklılık kırıldığında ölçülebilir ve önceden kayıtlı bir bant üretilmesi |
| **Ne sonuç elde ediliyor?** | **Test tasarımıdır**, öngörü değildir |

## 15.6 Gözlemci ilkesinin fiziksel yeniden tanımı

Arşivdeki kilitli cümle şudur:

$$\boxed{\;\text{Gözlemci bilinç değil, madde fazıdır (} C_m \text{).}\;}$$

```latex
\boxed{\;\text{Gözlemci bilinç değil, madde fazıdır (} C_m \text{).}\;}
```

Bu, 1.4'teki çekirdek hükmün arşiv genişletmesidir: bütün Cₘ süreçleri gözlemci etkisi yaratır; gözlem, Cₘ'de fiziksel kayıt ve okuma üreten sistemlerin rolüdür. Bilinç kavramı bu hükme hiçbir biçimde gerekli değildir (24.8). Liminal rejim okumasıyla birlikte: ölçüm, liminal taşınımın Cₘ fazına zorunlu izdüşümüdür — bu bir model adayıdır, çekirdek değildir.

---

# BÖLÜM 16 — BİLGİ, ENTROPİ, KAYIT

## 16.1 Entropi özellik ailesi ve faz anlamı

Entropi $S(x)$ Faz-Parametre Matrisinde bir özellik ailesi olarak tutulabilir; ama standart termodinamik entropi dili üç faza aynen taşınmaz.

| Faz | Güvenli yorum |
|---|---|
| **c₀** | Standart $dS/dt$ dili kabul edilebilir değildir; zaman-öncesi yapısal düzen / potansiyel ayrıca tanımlanmalıdır |
| **Cₘ** | Termodinamik / istatistiksel entropi ve entropi üretimi fiziksel anlam taşır |
| **c⁺** | Zamansız arşiv / kaynak yapısı, termodinamik entropi evrimiyle özdeş değildir |

Eski "potansiyel / akış / koherent-kilitli" tablosu yalnız öğretici / model sezgisi olarak kullanılabilir.

## 16.2 Bilgi ve faz biçimi

Bilgi "kaybolmaz" — faz biçimi değişir. c₀'da bilgi, imha edilmeden tümleşik tek-yapıda potansiyel olarak korunur; c⁺'ta ise mühürlü kayıt olarak durur.

$$\boxed{\;\text{Bu bir TEOREM DEĞİL, bir YENİDEN YORUMDUR.}\;}$$

```latex
\boxed{\;\text{Bu bir TEOREM DEĞİL, bir YENİDEN YORUMDUR.}\;}
```

Mikrodurum sayımı yapılmamış, standart kara delik entropisiyle nicel ilişki kurulmamıştır.

## 16.3 Entropi türleri ayrıdır

| Tür | Ne |
|---|---|
| Kayıt entropisi | Kaynak / kayıt defteri modelinde tanımlanan aday sayım ölçüsü; ontolojik kök olduğu kanıtlanmış değildir |
| Termodinamik entropi | Cₘ içi izdüşüm |
| Bilgi kuramsal entropi | Cₘ içi izdüşüm |

$$\boxed{\;\text{Bu üçü arasında HAM EŞİTLİK KURULMAMIŞTIR; biri diğerinin TANIMI değildir.}\;}$$

```latex
\boxed{\;\text{Bu üçü arasında HAM EŞİTLİK KURULMAMIŞTIR; biri diğerinin TANIMI değildir.}\;}
```

### Yönsel entropi zinciri — aday köprü

Arşivde şu yönsel okuma bulunur:

$$S_{C_m}\uparrow\;\Rightarrow\;\text{kümelenme / çekim okuması},\qquad S_{c^+}\uparrow\;\Rightarrow\;\text{genişleme / karanlık enerji okuması}$$

```latex
S_{C_m}\uparrow\;\Rightarrow\;\text{kümelenme / çekim okuması},\qquad S_{c^+}\uparrow\;\Rightarrow\;\text{genişleme / karanlık enerji okuması}
```

| Sembol | Anlamı |
|---|---|
| $S_{C_m}$ | Cₘ'deki entropi ölçüsü |
| $S_{c^+}$ | c⁺ yönündeki entropi / çözünme ölçüsü (model etiketi) |
| $\uparrow$ | Artış yönelimi — c⁺ içinde zaman türevi anlamına gelmez |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | İki entropi yöneliminin Cₘ'de iki farklı kozmolojik okumaya karşılık geldiğini önerir |
| **Neden yapıyor?** | Kümelenme ile genişlemenin, aynı kayıt sürecinin iki yönü olarak okunup okunamayacağını sınamak için |
| **Nasıl yapıyor?** | Cₘ'deki entropi artışını kümelenme / çekim okumasına, c⁺ yönündeki artışı genişleme okumasına eşler |
| **Ne sonuç bekleniyor?** | İki yönelimin nicel olarak ayrıştırılması |
| **Ne sonuç elde ediliyor?** | **Aday köprüdür**; 16.3'ün tanım ayrımını bozmaz. $S_{c^+}$ standart termodinamik entropi üretimi değişkeni olarak kilitlenmemiştir ve $\uparrow$ c⁺ içinde akan fiziksel zaman türevi anlamına gelmez. Çekim Kuvveti'nin (Postüla-0) tanımı değildir |

### Denklem seti — K6 entropi modeli ve N ayrımı

Kayıt sayısı $N$ ile bir doluluk oranı $F$'den entropi türeten bir **modeldir**:

$$S = k_B\,N\,\frac{F}{F_{\max} - F}, \qquad \frac{dS}{d\tau} = k_B\left[\frac{N' F}{F_{\max}-F} + \frac{N F_{\max} F'}{(F_{\max}-F)^2} - \frac{N F F_{\max}'}{(F_{\max}-F)^2}\right]$$

```latex
S = k_B\,N\,\frac{F}{F_{\max} - F}, \qquad \frac{dS}{d\tau} = k_B\left[\frac{N' F}{F_{\max}-F} + \frac{N F_{\max} F'}{(F_{\max}-F)^2} - \frac{N F F_{\max}'}{(F_{\max}-F)^2}\right]
```

$$N_{\rm arşiv}(n+1) \geq N_{\rm arşiv}(n) \quad \text{(kaynak sırasında — fiziksel zaman türevi DEĞİL)}$$

```latex
N_{\rm arşiv}(n+1) \geq N_{\rm arşiv}(n) \quad \text{(kaynak sırasında — fiziksel zaman türevi DEĞİL)}
```

| Sembol | Anlamı |
|---|---|
| $S$ | Model entropisi |
| $k_B$ | Boltzmann sabiti |
| $N$ ($N_{\rm entropi}$) | K6 modelinin kayıt sayısı niceliği |
| $F$, $F_{\max}$ | Doluluk ve üst sınırı |
| $N'$, $F'$, $F_{\max}'$ | $\tau$'ya göre türevler |
| $\tau$ | Model parametresi (7.2'deki iskele değişkeni) |
| $N_{\rm arşiv}(n)$ | Salt ekleme ham arşivin $n$. önek uzunluğu |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kayıt sayısı ve doluluktan bir entropi ve onun değişim hızını hesaplar |
| **Neden yapıyor?** | Arşiv birikimi ile termodinamik entropi arasında sınanabilir bir model köprüsü aramak için |
| **Nasıl yapıyor?** | Entropiyi doluluğun üst sınıra yaklaştıkça ıraksayan bir oranla yazar; türevi zincir kuralıyla açar |
| **Ne sonuç bekleniyor?** | Doluluk üst sınıra yaklaştıkça hızla artan bir entropi eğrisi |
| **Ne sonuç elde ediliyor?** | **K6 modelidir.** Arşiv sayısının ayrık tekdüzeliği **kanıtlanmıştır**; ama $N_{\rm arşiv}$ ile $N_{\rm entropi}$ otomatik olarak özdeş değildir. "$F'<0 \Rightarrow$ silme" çıkarımı **yanlıştır**: modelde doluluğun azalması arşivin silindiği anlamına gelmez |

## 16.4 Varlık ≠ kayıt

$$\boxed{\;\text{"Yalnız mühürlenmiş olan vardır" ONTOLOJİSİ ÇEKİRDEĞE GİRMEZ.}\;}$$

```latex
\boxed{\;\text{"Yalnız mühürlenmiş olan vardır" ONTOLOJİSİ ÇEKİRDEĞE GİRMEZ.}\;}
```

Kayıt ve mühürleme bir **kaynak / biçimsel katmandır**. Bunlar varoluşun kendisiyle özdeşleştirilemez. Özellikle c₀ zaman-öncesi **potansiyel** olduğu için, "mühürlenmemiş potansiyel gerçek değildir" ifadesi çerçeveyle çelişir: c₀'da bilgi henüz mühürlenmemiştir, ama vardır.

## 16.5 Nesnel kayıt eşiği

Bir olayın gerçekleşmesi ile fiziksel kaydının oluşması aynı şey değildir. Nesnel kayıt için bilginin yeterli sayıda bağımsız erişilebilirlik kazanması gerekir.

---

## 16.6 Kayıt defteri entropisi — çift katmanlı yapı

Arşivde kayıt defteri ve bilgi için iki katmanlı bir yapı önerilmiştir:

| Katman | Yapı | Koruma |
|---|---|---|
| **Global** | Üniter evrim + kayıt defterinin tekdüzeliği | Bilgi korunur |
| **Yerel** | Kraus / CPTP: $\rho' = \sum_i K_i\rho K_i^\dagger$, $\sum K_i^\dagger K_i = I$ | Cₘ içi okuma modeli |

GKSL / Lindblad şablonu (Markov yaklaşımı altında genel biçim):

$$\frac{d\rho}{d\tau} = -\frac{i}{\hbar}[H(\Phi,\Xi),\rho] + \sum_k \gamma_k(\Phi)\left(L_k\rho L_k^\dagger - \tfrac12\{L_k^\dagger L_k,\rho\}\right)$$

```latex
\frac{d\rho}{d\tau} = -\frac{i}{\hbar}[H(\Phi,\Xi),\rho] + \sum_k \gamma_k(\Phi)\left(L_k\rho L_k^\dagger - \tfrac12\{L_k^\dagger L_k,\rho\}\right)
```

| Sembol | Anlamı |
|---|---|
| $\rho$ | Yoğunluk matrisi |
| $H(\Phi,\Xi)$ | Etkin Hamiltoniyen (eşik ve asimetri parametrelerine bağlı aday) |
| $[\cdot,\cdot]$ | Komütatör |
| $\{\cdot,\cdot\}$ | Antikomütatör |
| $L_k$ | Lindblad (sıçrama) işlemcileri |
| $\gamma_k(\Phi)$ | Sönüm oranları |
| $\hbar$ | İndirgenmiş Planck sabiti |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Açık bir kuantum sisteminin çevreyle etkileşim altındaki zaman evrimini yazar |
| **Neden yapıyor?** | "Global olarak bilgi korunur, yerel olarak kaybolmuş görünür" ikiliğinin Cₘ'deki hesap dilini kurmak için |
| **Nasıl yapıyor?** | Üniter kısmı komütatörle, çevre etkisini Lindblad terimleriyle yazar |
| **Ne sonuç bekleniyor?** | $\{H, L_k, \gamma_k\}$ seçildiğinde ölçülebilir bir eşevresizlik (decoherence) modeli |
| **Ne sonuç elde ediliyor?** | **Hesap şablonudur**; $\{H, L_k, \gamma_k\}$ seçimi açık borçtur, ontolojinin temel öğesi değildir. "Global üniterlik + yerel Kraus" ikilisi, bilgi kaybının gözlemsel olduğunu söyler; kara delik bilgi paradoksuna bir yol açar ama çözüm değildir (0.3) |

## 16.7 Entropi okunun türetimi — üç katman özeti

Zaman oku ile entropi arasındaki ilişki için arşivde üç katmanlı çalışma modeli korunur:

1. **Çekirdek katman:** zaman iskelesi — fiziksel zaman Cₘ'de üretilir:

$$dt = \Gamma\cdot\mathcal G_{C_m}\cdot d\tau$$

```latex
dt = \Gamma\cdot\mathcal G_{C_m}\cdot d\tau
```

2. **Kayıt katmanı:** arşiv tekdüzeliği, kaynak sırasında (14.4 ile aynı hüküm):

$$R_\varphi(r_{n+1}) \ge R_\varphi(r_n)$$

```latex
R_\varphi(r_{n+1}) \ge R_\varphi(r_n)
```

3. **Entropi katmanı:** yalnız Cₘ içi termodinamik izdüşüm olarak; ikinci yasa sistem sınırı ve entropi alışverişi belirtilerek yazılır:

$$\frac{dS_{\rm sis}}{dt}=\Phi_S+\sigma,\qquad \sigma\ge0;\qquad \text{yalıtılmış sistem }(\Phi_S=0):\ \frac{dS}{dt}\ge0;\qquad \frac{dS_{\rm sis}}{dt}+\frac{dS_{\rm çevre}}{dt}\ge0$$

```latex
\frac{dS_{\rm sis}}{dt}=\Phi_S+\sigma,\qquad \sigma\ge0;\qquad \text{yalıtılmış sistem }(\Phi_S=0):\ \frac{dS}{dt}\ge0;\qquad \frac{dS_{\rm sis}}{dt}+\frac{dS_{\rm çevre}}{dt}\ge0
```

| Sembol | Anlamı |
|---|---|
| $dt$ | Cₘ'de üretilen fiziksel zaman aralığı |
| $\Gamma$ | Cₘ okuma / raporlama-düzenleme ailesinin katsayısı (7.2) |
| $\mathcal G_{C_m}$ | Cₘ içinde ölçülebilir değişim ve ayrışma yapısı (7.2; henüz kapanmamış nesne) |
| $d\tau$ | İskele parametresinin aralığı |
| $R_\varphi(r_n)$ | $n$. kayıttan sonraki faz hafızası |
| $S$, $S_{\rm sis}$, $S_{\rm çevre}$ | Termodinamik entropi; sistemin ve çevrenin entropisi |
| $\Phi_S$ | Sisteme net entropi akışı (açık sistemde negatif olabilir) |
| $\sigma$ | İç entropi üretimi (negatif olamaz) |

$$\boxed{\;\text{Çekirdek oku, kayıt birikimi ve termodinamik entropi üretimi AYNI yasa değildir.}\;}$$

```latex
\boxed{\;\text{Çekirdek oku, kayıt birikimi ve termodinamik entropi üretimi AYNI yasa değildir.}\;}
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Zamanın yönünü üç ayrı katmana — üretim, kayıt, entropi — ayırır |
| **Neden yapıyor?** | "Zaman oku = entropi artışı" özdeşliği, Evertophy'nin zaman ≠ entropi ≠ arşiv sırası ayrımıyla (7.8) çelişirdi |
| **Nasıl yapıyor?** | Her katmana kendi yasasını ve kendi geçerlilik alanını verir |
| **Ne sonuç bekleniyor?** | Aday modelde zaman okunun kayıt protokolünden doğduğunun, termodinamik okun ise bu kaydın istatistiksel Cₘ izdüşümünde göründüğünün gösterilmesi |
| **Ne sonuç elde ediliyor?** | Üç katman birbiriyle ilişkilendirilir, ama bu ilişki **henüz gösterilmemiştir**; katmanlar birbirinin tanımı değildir |

---

## 16.7a Entropi ve enerji: Uₓ düzeyinde korunum

**Yazar hükmü:** Entropi, Cₘ'deki yapının c⁺'a çözünmüş hâlidir. Enerji yok olmaz; çözünen yapının hem kaydı hem enerji payı c⁺'ta mühürlenir.

$$\boxed{\;\text{Toplam enerji } U_x \text{ düzeyinde korunur; enerjinin bir kısmı Cₘ'de ölçülemez — bu pay c⁺'ta mühürlüdür.}\;}$$

```latex
\boxed{\;\text{Toplam enerji } U_x \text{ düzeyinde korunur; enerjinin bir kısmı Cₘ'de ölçülemez — bu pay c⁺'ta mühürlüdür.}\;}
```

Bu hüküm üç ayrı enerji türünü ayırır:

$$E_{U_x}^{\rm muhasebe}\;\supseteq\;\big\{E_{C_m},\;E_+^{\rm mühürlü}\big\}\qquad(\text{tür ayrımı; nicel toplama yasası açık})$$

```latex
E_{U_x}^{\rm muhasebe}\;\supseteq\;\big\{E_{C_m},\;E_+^{\rm mühürlü}\big\}\qquad(\text{tür ayrımı; nicel toplama yasası açık})
```

| Sembol | Anlamı |
|---|---|
| $E_{C_m}$ | Cₘ'de ölçülen enerji |
| $E_{U_x}^{\rm muhasebe}$ | $U_x$ düzeyindeki toplam enerji muhasebesi |
| $E_+^{\rm mühürlü}$ | c⁺'ta mühürlü enerji payı (Cₘ tipi enerji değil, c⁺'a özgü mühürlü biçim) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Enerjinin kaybolmadığını, bir kısmının c⁺'ta mühürlenerek Cₘ ölçümünün dışına çıktığını söyler |
| **Neden yapıyor?** | Entropi artışı ile enerji korunumunu, c⁺'ın arşiv rolüyle tek bir resimde birleştirmek için |
| **Nasıl yapıyor?** | Korunumu Cₘ'nin zaman simetrisine değil, $U_x$ düzeyinde global bir muhasebe ilkesine bağlar |
| **Ne sonuç bekleniyor?** | Ölçülemeyen payın kozmolojik ölçekte belirginleşmesi; üç tür arasında nicel bir harita |
| **Ne sonuç elde ediliyor?** | Yazar hükmüdür. Kapalı Cₘ sistemlerinde ölçülmüş enerji korunumu **zorunlu dış koşuldur** ve karşılanır. Türler arasındaki nicel harita, ortak değer uzayı ve aktarım yasası **henüz kurulmamıştır** |

Bu hükmün dört inceliği vardır:

- **Bir Noether korunumu değil, global bir muhasebe ilkesidir.** Cₘ'deki enerji korunumu Cₘ zamanındaki simetriden gelir; $U_x$ düzeyinde global bir zaman yoktur. Bu yüzden $U_x$ düzeyindeki korunum Cₘ fiziğinden türetilmiş değil, ontolojik bir postüladır ve "zaman yalnız Cₘ'de geçerlidir" hükmüyle çelişmez.
- **Üç ayrı tür.** Yukarıdaki üç enerji farklı tanım ve kullanım katmanlarına aittir; bu, değerlerinin her durumda farklı olduğu anlamına gelmez.
- **Ölçümlerle uyum.** Kapalı sistemlerdeki ölçülmüş enerji korunumu, ölçüm hassasiyeti içinde zorunlu bir dış koşuldur. Ölçülemeyen payın kozmolojik ölçekte belirginleşmesi ise henüz hesaplanmamış bir beklentidir; genel görelilikte de enerji korunumu kozmolojik ölçekte global olarak tanımlı değildir. Bu hüküm ne her Cₘ ölçümünde enerjinin korunduğunu, ne de herhangi bir kapalı sistemde korunumun ihlal edildiğini iddia eder; yerel korunum, açık sistem alışverişi ve kozmolojik global enerji ayrı kapsamlardır.
- **Kapı yapısı.** Bir niceliğin Cₘ'ye özgü nicelikler listesinde yer almaması, onun başka fazlardaki içsel tanımını ya da belirli bir faz çifti için taşıma iznini belirlemez (13.1a). Enerjinin c⁺'taki içsel statüsü ve taşıma izni açıktır.

Biçimsel ayrım da korunur: arşiv sayısının ayrık tekdüzeliği, faz hafızasının tekdüzeliği ve termodinamik entropi artışı aynı teoremden çıkmaz (14, 7.8). Ham kayıt sayısının artması fiziksel entropi üretimi değildir. Yazar hükmü bunlar arasında ontolojik bir bağ kurar; hangi entropi ölçüsünün hangi mühürleme sürecine karşılık geldiğini gösteren nicel harita açıktır.

---

# BÖLÜM 17 — KANAL ASİMETRİSİ (ADAY KÖPRÜ)

## 17.1 Temel fikir

Bir ortamın iki yön arasında asimetrik davranması, saçılma parametreleri üzerinden ölçülebilir:

$$\chi_S \;\equiv\; \frac{|S_{21}|}{|S_{12}|}$$

```latex
\chi_S \;\equiv\; \frac{|S_{21}|}{|S_{12}|}
```

Logaritmik ölçü ve türetilen alan şunlardır:

$$\Xi = \ln\chi_S, \qquad \Phi_\chi = \Lambda\ln\chi_S, \qquad \mathbf{g}_\chi = -\Lambda\nabla\ln\chi_S-(\ln\chi_S)\nabla\Lambda \quad (\text{kısa biçim yalnız } \nabla\Lambda=0)$$

```latex
\Xi = \ln\chi_S, \qquad \Phi_\chi = \Lambda\ln\chi_S, \qquad \mathbf{g}_\chi = -\Lambda\nabla\ln\chi_S-(\ln\chi_S)\nabla\Lambda \quad (\text{kısa biçim yalnız } \nabla\Lambda=0)
```

| Sembol | Anlamı |
|---|---|
| $S_{21}$, $S_{12}$ | Saçılma matrisinin ileri (1 → 2) ve geri (2 → 1) iletim genlikleri |
| $\chi_S$ | İleri / geri iletim genlik oranı |
| $\Xi$ | Logaritmik asimetri ölçüsü |
| $\Lambda$ | Kanal ölçek katsayısı (kozmolojik sabit değil) |
| $\Phi_\chi$ | Kanal potansiyeli (4.2'deki tarihsel $\Phi(x)$ ile özdeşleştirilmez) |
| $\mathbf g_\chi$ | Kanal kaynaklı aday ivme alanı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bir ortamın iki yönlü iletimindeki asimetriyi ölçer ve ondan bir potansiyel ve ivme alanı türetir |
| **Neden yapıyor?** | Fazlar arası yönlü bir yapının laboratuvarda ölçülebilir bir izi olup olmadığını aramak için |
| **Nasıl yapıyor?** | İleri ve geri genliklerin oranını alır; logaritmasını bir ölçek katsayısıyla çarparak potansiyel kurar; gradyanından ivmeyi çıkarır. Simetri koşulu otomatiktir: $\chi_S = 1 \Rightarrow \Phi_\chi = 0$ |
| **Ne sonuç bekleniyor?** | Karşılıklılığı bozan bir sistemde ölçülebilir ve kütleçekim okumasıyla bağımsız olarak karşılaştırılabilir bir sinyal |
| **Ne sonuç elde ediliyor?** | **Aday köprüdür.** Karşılıklı her sistemde ölçüt özdeş olarak 1'dir (aşağıdaki not); köprünün akıbeti yazarın kararına bırakılmıştır. Emekli "karanlık madde için $\nabla\ln\chi_S\neq0$" ölçütü kullanılmaz |

### Karşılıklılık notu

Bu ölçütün önemli bir sınırı vardır. Aynı port normalizasyonunda **karşılıklı** her sistemde ($S_{21} = S_{12} \neq 0$) oran özdeş olarak 1'dir; bunun için kayıpsızlık gerekmez, Onsager karşılıklılığı yeterlidir. Faz farkı $\arg S_{21} - \arg S_{12}$ de aynı koşulda özdeş olarak sıfırdır, yani otomatik bir yedek ölçüt değildir.

$$\boxed{\;\text{Karşılıklı sistem:}\quad \chi_S \equiv 1,\qquad \Delta\varphi \equiv 0\;}$$

```latex
\boxed{\;\text{Karşılıklı sistem:}\quad \chi_S \equiv 1,\qquad \Delta\varphi \equiv 0\;}
```

| Sembol | Anlamı |
|---|---|
| $\Delta\varphi$ | $\arg S_{21} - \arg S_{12}$, iki yönlü iletimin faz farkı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kanal asimetrisi ölçütünün karşılıklı sistemlerde neden boş kaldığını gösterir |
| **Neden yapıyor?** | Önceki kanon $\chi_S$'yi genel bir ölçüt gibi kullanıyordu; Onsager karşılıklılığı bunu geçersiz kılar |
| **Nasıl yapıyor?** | Karşılıklılık altında $S_{21}=S_{12}$ olduğundan hem genlik oranının hem faz farkının özdeş olarak sabit olduğunu çıkarır |
| **Ne sonuç bekleniyor?** | Ölçütün yalnız **karşılıklılığı bozan** bir fiziksel sınıf, port yapılandırması ve referans düzlemi açıkça tanımlandığında kullanılması |
| **Ne sonuç elde ediliyor?** | Genel ölçüt olarak $\chi_S$ **yanlıştır**; $\Delta\varphi$ otomatik yedek olarak **yanlıştır**; karşılıklılığı bozan sınıfın seçimi **Daha Sonra Ele Alınacak** (yazar kararı) |

### 17.1a Empedans ve potansiyel köprü ailesi

Kanal asimetrisi hattı yalnız $\chi_S$ tanımından ibaret değildir. Model düzeyinde şu zincir araştırılmıştır:

$$\boxed{\;\chi_S\to Z_{\rm eff}\to\Phi_\chi\to \mathbf g_\chi\;}$$

```latex
\boxed{\;\chi_S\to Z_{\rm eff}\to\Phi_\chi\to \mathbf g_\chi\;}
```

Bazı CMT / empedans gerçeklemelerinde $Z_{\rm eff}$ ya da benzeri bir etkin kanal büyüklüğü ile $\chi_S$ arasında bağ kurulabilir. Ama bu zincir **aday köprüdür**, ontolojik bir kütleçekim yasası değildir. $\Lambda$ birden fazla faktörün çarpımıyla tanımlanıyorsa, yalnız çarpımın ölçülmesi faktörleri ayrı ayrı öngörmez; bu durum parametre ve köprü bütçesi (ParamBudget / BridgeBudget) altında fiyatlandırılır.

### Denklem seti — Z_eff, kanonik yönlü etkin empedans

KAP-03, K5v2 ve K12v2'nin hepsi $Z_{\rm eff}$ kullanır; bu niceliğin **kanonik tanımı** burada verilir:

$$Z_{{\rm eff},i}(\omega) \equiv Z_{0,i}\,\frac{1 + S_{ii}(\omega)}{1 - S_{ii}(\omega)}, \qquad \Phi_{\rm ch}^{(\pm)}(\mathbf{x},\omega) \equiv \lambda\ln\frac{Z_{\rm eff}^{(\pm)}(\mathbf{x},\omega)}{Z_{\rm ref}}$$

```latex
Z_{{\rm eff},i}(\omega) \equiv Z_{0,i}\,\frac{1 + S_{ii}(\omega)}{1 - S_{ii}(\omega)}, \qquad \Phi_{\rm ch}^{(\pm)}(\mathbf{x},\omega) \equiv \lambda\ln\frac{Z_{\rm eff}^{(\pm)}(\mathbf{x},\omega)}{Z_{\rm ref}}
```

| Sembol | Anlamı |
|---|---|
| $S_{ii}(\omega)$ | $i$ portunun yansıma katsayısı |
| $Z_{0,i}$ | Port referans empedansı |
| $Z_{{\rm eff},i}$ | $i$ portundan görülen etkin empedans |
| $\Phi_{\rm ch}^{(\pm)}$ | İki yön için kanal potansiyeli |
| $\lambda$, $Z_{\rm ref}$ | Ölçek ve referans empedans |
| $\omega$ | Açısal frekans |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Yansıma katsayısından etkin empedansı ve ondan yönlü kanal potansiyelini tanımlar |
| **Neden yapıyor?** | Farklı modellerin aynı niceliği farklı biçimlerde kullanmasını önlemek için tek bir kanonik tanım gerekir |
| **Nasıl yapıyor?** | İletim hattı kuramının standart yansıma–empedans ilişkisini kullanır; potansiyeli referansa göre logaritmik oran olarak yazar |
| **Ne sonuç bekleniyor?** | 8.7'deki $\Phi_g\leftrightarrow\Phi_{\rm ch}$ eşlemesinin bu tanım üzerinden kalibre edilmesi |
| **Ne sonuç elde ediliyor?** | **Kayıtlı referans tanımdır** (tanımlılık koşulları aşağıda); fiziksel köprü **Daha Sonra Ele Alınacak** |

**Karmaşık değer ve tanım alanı notu.** Yansıma katsayısı genel olarak karmaşıktır; bu yüzden $Z_{\rm eff}$ ve onun logaritması da karmaşık olabilir ve logaritma çok değerlidir. Gerçel bir kütleçekim potansiyeliyle karşılaştırılacak nicelik **genlik potansiyelidir**; faz ayrı bir gözlenebilir olarak taşınır:

$$\Phi_{\rm ch}^{\rm gen}=\lambda\ln\left|\frac{Z_{\rm eff}}{Z_{\rm ref}}\right|,\qquad \phi_{\rm ch}=\arg\frac{Z_{\rm eff}}{Z_{\rm ref}}\ (\text{dal seçimi belirtilerek}),\qquad S_{ii}\neq1,\ \ Z_{\rm eff}\neq0$$

```latex
\Phi_{\rm ch}^{\rm gen}=\lambda\ln\left|\frac{Z_{\rm eff}}{Z_{\rm ref}}\right|,\qquad \phi_{\rm ch}=\arg\frac{Z_{\rm eff}}{Z_{\rm ref}}\ (\text{dal seçimi belirtilerek}),\qquad S_{ii}\neq1,\ \ Z_{\rm eff}\neq0
```

| Sembol | Anlamı |
|---|---|
| $\Phi_{\rm ch}^{\rm gen}$ | Gerçel genlik potansiyeli |
| $\phi_{\rm ch}$ | Empedans oranının fazı |
| $\arg$ | Karmaşık sayının açısı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Karmaşık empedanstan gerçel bir potansiyel çıkarmanın iyi tanımlı yolunu verir |
| **Neden yapıyor?** | $S_{ii}=0.2+0.3i$ için $\ln Z_{\rm eff}\approx0.370+0.604i$; $S_{ii}=i/2$ için $Z_{\rm eff}=0.6+0.8i$ ve $\ln Z_{\rm eff}\approx0.927i$ çıkar ($Z_0=Z_{\rm ref}=1$): doğrudan logaritma gerçel bir potansiyel vermez |
| **Nasıl yapıyor?** | Genliği ve fazı ayırır; $S_{ii}=1$ (sonsuz empedans) ve $Z_{\rm eff}=0$ noktalarını tanım alanından çıkarır |
| **Ne sonuç bekleniyor?** | Kütleçekim okumasıyla karşılaştırmada genlik potansiyelinin kullanılması; faz etkisinin ayrı bir gözlenebilir olarak sınanması |
| **Ne sonuç elde ediliyor?** | **Matematiksel iyi tanımlılık onarımıdır**, ontolojik değişiklik değildir. Kütleçekim potansiyeli olarak okunacaksa $[\lambda]=\mathrm{m^2\,s^{-2}}$ olmalıdır. Hangi biçimin (genlik, faz ya da ikisi) fiziksel olduğu ayrıca gerekçe ister; 8.7'deki $\Phi_{\rm ch}$ bu genlik biçimiyle okunur |

### 17.1b İşlemsel ölçüm protokolü — model testi

Kanal köprüsü sınanacaksa örnek bir vektör ağ çözümleyicisi (VNA) / CMT protokolü şudur:

1. İki yönlü saçılma ölçümüyle $S_{21}(\omega)$ ve $S_{12}(\omega)$ kaydedilir.
2. Aynı cihaz ve kalibrasyon koşullarında $\chi_S(\omega)$ üretilir.
3. Karşılıklı denetim rejiminde $\chi_S\simeq1$ doğrulanır.
4. Aktif ya da karşılıklı olmayan bir bileşen varsa, bunun kaynağı ayrıca ölçülür; "asimetri gördük = kütleçekim" çıkarımı yapılmaz.
5. $\Phi_\chi$ ya da $\mathbf g_\chi$ köprüsü önceden kaydedilmiş bir bant üretirse, bağımsız veriyle karşılaştırılır.

Yumuşak eleme: kanal asimetrisi fiziksel kütleçekim okumasına bağımsız biçimde bağlanamıyorsa **köprü hattı kapanır**, çekirdek ontoloji değil.

### 17.1c CMT model iskelesi

Kanal asimetrisinin hesaplanabilir model dili olarak standart bağlı mod biçimlerinden biri kullanılabilir. 7.2'deki $\Gamma$ ile karışmaması için sönüm / kayıp matrisi burada $\Gamma_{\rm CMT}$ ile gösterilir:

$$S(\omega)=C+D\,[\,i(\omega I-\Omega)+\Gamma_{\rm CMT}\,]^{-1}K^{\mathsf T}$$

```latex
S(\omega)=C+D\,[\,i(\omega I-\Omega)+\Gamma_{\rm CMT}\,]^{-1}K^{\mathsf T}
```

Bir rezonans çevresinde, seçilen port / mod normalizasyonuna bağlı yaklaşık asimetri okuması:

$$\chi\approx\frac{|d_2k_1|}{|d_1k_2|}$$

```latex
\chi\approx\frac{|d_2k_1|}{|d_1k_2|}
```

Burada $S=C+DRK^{\mathsf T}$, $D=(d_1,d_2)^{\mathsf T}$, $K=(k_1,k_2)^{\mathsf T}$ için $S_{21}=C_{21}+d_2Rk_1$ ve $S_{12}=C_{12}+d_1Rk_2$'dir; oran, doğrudan yol bileşenleri ihmal edilebildiğinde geçerlidir. Kanal potansiyelinde $\Lambda$ konuma bağlıysa $-\nabla\Phi_\chi=-\Lambda\nabla\ln\chi_S-(\ln\chi_S)\nabla\Lambda$ olur; son terim yalnız $\Lambda$ uzayda sabitse düşer. Karşılıklılık kırılması için işlemsel imza ve tek port etkin empedans okuması:

$$\boxed{\;S_{21}\neq S_{12}\;}\qquad\qquad Z_{{\rm eff},i}=Z_{0,i}\frac{1+S_{ii}}{1-S_{ii}}$$

```latex
\boxed{\;S_{21}\neq S_{12}\;}\qquad\qquad Z_{{\rm eff},i}=Z_{0,i}\frac{1+S_{ii}}{1-S_{ii}}
```

| Sembol | Anlamı |
|---|---|
| $C$ | Doğrudan (rezonanssız) yol saçılma matrisi |
| $D$, $K$ | Modlardan portlara ve portlardan modlara bağlaşım matrisleri |
| $d_1,d_2$, $k_1,k_2$ | Tek mod için bağlaşım bileşenleri |
| $\Omega$ | Mod frekansları matrisi |
| $\Gamma_{\rm CMT}$ | Sönüm / kayıp matrisi |
| $R$ | Rezonans yanıtı $[\,i(\omega-\Omega)+\Gamma_{\rm CMT}]^{-1}$ |
| $I$ | Birim matris |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Saçılma matrisini rezonans modlarının bağlaşımlarından hesaplar ve asimetri oranının rezonans yakınındaki yaklaşık biçimini verir |
| **Neden yapıyor?** | Kanal asimetrisini ölçülebilir donanım parametrelerine bağlamak için hesaplanabilir bir model gerekir |
| **Nasıl yapıyor?** | Standart bağlı mod kuramı biçimini kullanır; doğrudan yol küçükse oranı bağlaşım katsayılarının oranına indirger |
| **Ne sonuç bekleniyor?** | Karşılıklılığı bozan bir yapıda $S_{21}\neq S_{12}$'nin tasarlanabilir ve ölçülebilir olması |
| **Ne sonuç elde ediliyor?** | CMT, kanal asimetrisinin hesaplanabilir **model dilidir**; ontolojik köprü adayının kendisi değildir. Matris boyutları, port normalizasyonları ve $C,D,K,\Omega,\Gamma_{\rm CMT}$ gösterimleri seçilen gerçeklemeye bağlıdır. $S_{21}\neq S_{12}$ tek başına kütleçekim ya da Evertophy doğrulaması sayılmaz |

## 17.2 Açık borçlar

$$\boxed{\;\text{Bu hat ADAY KÖPRÜDÜR — kurulmuş bir türetim DEĞİLDİR.}\;}$$

```latex
\boxed{\;\text{Bu hat ADAY KÖPRÜDÜR — kurulmuş bir türetim DEĞİLDİR.}\;}
```

| Borç | İçerik |
|---|---|
| **Çarpan belirsizliği** | $\Lambda$ ifadesi yalnız **çarpımı** sabitler; çarpanlar serbest kalır |
| **Kaynak dışsallığı** | Ölçek katsayısı dış bir kaynaktan alınmıştır |
| **Asimetrinin kaynağı** | Karşılıklılık koşullarını sağlayan ortamlarda $S_{21}=S_{12}$'dir; pasiflik ve zamanla değişmezlik bunu tek başına garanti etmez (statik manyetik öngerilim altındaki ferrit sistemler pasif ama karşılıklı değildir). Asimetrinin kütleçekimle bağı **kurulmamıştır** |

$$\boxed{\;\text{ÇARPIMI SABİTLEYİP ÇARPANLARI SERBEST BIRAKMA deseni: bilinmeyen KAPANMAZ, YER DEĞİŞTİRİR.}\;}$$

```latex
\boxed{\;\text{ÇARPIMI SABİTLEYİP ÇARPANLARI SERBEST BIRAKMA deseni: bilinmeyen KAPANMAZ, YER DEĞİŞTİRİR.}\;}
```

## 17.3 Yapısal benzerlik uyarısı

$$\boxed{\;\text{YAPISAL BENZERLİK, DOĞRULAMA DEĞİLDİR. Gösterim ödünç almak, SONUÇ İTHAL ETMEZ.}\;}$$

```latex
\boxed{\;\text{YAPISAL BENZERLİK, DOĞRULAMA DEĞİLDİR. Gösterim ödünç almak, SONUÇ İTHAL ETMEZ.}\;}
```

---

## 17.4 χ_S tanım seti (model adayı)

*Tek tanım yetkesi 17.1c'dir; karşılıklılık sınırı için 17.1'e bakılır.* 17.1'deki tanımın arşivdeki tamamlanmış hâli:

$$\chi_S \equiv \frac{|S_{21}|}{|S_{12}|}, \qquad \Xi = \ln\chi_S, \qquad Z_{{\rm eff},i} = Z_{0,i}\frac{1+S_{ii}}{1-S_{ii}}$$

```latex
\chi_S \equiv \frac{|S_{21}|}{|S_{12}|}, \qquad \Xi = \ln\chi_S, \qquad Z_{{\rm eff},i} = Z_{0,i}\frac{1+S_{ii}}{1-S_{ii}}
```

Rezonans çevresinde tek mod yaklaşık okuması $\chi \approx |d_2k_1|/|d_1k_2|$'dir (doğrudan yol bileşenleri ihmal edilebildiğinde; port / mod normalizasyonuna bağlı).

## 17.5 Üç faktörlü ayrışım ve aralık değeri biçimi

*Statü:* Mekanik × bağlaşım × direnç ayrışımı bir model atamasıdır; bağımsız ölçüm ve faktör tanımı olmadan türetilmiş bir yasa değildir.

$$\chi_S = \chi_{\rm mek}\cdot\chi_{\rm bağ}\cdot\chi_{\rm dir},\qquad \chi_S \in [\chi_S^-, \chi_S^+]$$

```latex
\chi_S = \chi_{\rm mek}\cdot\chi_{\rm bağ}\cdot\chi_{\rm dir},\qquad \chi_S \in [\chi_S^-, \chi_S^+]
```

| Sembol | Anlamı |
|---|---|
| $\chi_{\rm mek}$ | Mekanik asimetri katkısı |
| $\chi_{\rm bağ}$ | Bağlaşım asimetrisi katkısı |
| $\chi_{\rm dir}$ | Direnç / yükleme etkisi |
| $[\chi_S^-,\chi_S^+]$ | Asimetri oranının aralık değeri |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Asimetri oranını üç fiziksel kaynağın çarpımına ayırır ve aralık değeriyle yazar |
| **Neden yapıyor?** | Ölçülen bir asimetrinin hangi kaynaktan geldiğini ayırt edebilmek için |
| **Nasıl yapıyor?** | Her kaynağı ayrı bir çarpan olarak tanımlar; belirsizliği Range biçimciliğiyle taşır |
| **Ne sonuç bekleniyor?** | Faktörlerin bağımsız ölçümlerle ayrı ayrı sabitlenmesi |
| **Ne sonuç elde ediliyor?** | **Model atamasıdır.** $\Lambda$ çarpımı sabitlenirken çarpanları serbest bırakmak yasaktır (17.2). 21.6'nın düzeltilmiş hükmü burada da geçerlidir: aralık üzerinden türetim iddiası ancak köprü dondurulmuşsa anlamlıdır |

## 17.6 Kanal potansiyeli

$\Phi_\chi = \Lambda\ln\chi_S$ tanımının potansiyel dilindeki okumasıdır. Karşılıklılık bozulmadığında $\Phi_\chi \equiv 0$'dır; potansiyel ancak asimetri kaynağı fiziksel olarak tanımlandığında anlamlıdır (17.1 koruması). $\Phi_\chi$ ile 4.2'deki tarihsel $\Phi(x)$ sembolü özdeşleştirilmez.

## 17.7 Karşılıklılık kırılması için zorunlu koşullar

8.8'deki mekanizma sınıflarının bu hattaki yerel ifadesi şudur: karşılıklılık koşullarını sağlayan (manyetik öngerilim ya da zamanla modülasyon içermeyen) doğrusal ortamda $S_{21} = S_{12}$ olur; pasiflik tek başına bunu garanti etmez. $\chi_S \neq 1$ aktif bir eleman gerektirmez; karşılıklılığı bozan somut bir fiziksel sınıf (örneğin statik manyetik öngerilim) yeterlidir. "Asimetri gördük = kütleçekim" çıkarımı yasaktır (17.1b).

## 17.8 Nedenselliğin tersine çevrilmesi ilkesi

Arşivdeki aday ilke şudur: bir kanalda gözlenen yönsel asimetrinin kaynağı "nedenselliğin zayıflaması" değil, kanalın yapısal önceliklerinin izdüşümüdür. Yön okuması kaynağa değil, taşıyıcıya atıfta bulunur. Bu ilke model düzeyindedir; ontolojik bir nedensellik yorumu eklemez.

## 17.9 χ_S ≈ 137 hipotezi — statü ve kırmızı bayrak kaydı

Arşivde $\chi_S$'nin ince yapı sabitiyle ilişkilendirilmesi denenmiştir. Kayıtlı statü:

$$\boxed{\;\chi_S \approx 137 \text{ hipotezi, uydurma–türetim ayrımı çözülmeden kanona alınmaz.}\;}$$

```latex
\boxed{\;\chi_S \approx 137 \text{ hipotezi, uydurma–türetim ayrımı çözülmeden kanona alınmaz.}\;}
```

| Kırmızı bayrak | Neden |
|---|---|
| Kaynak dışsallığı | $\Lambda$ ölçek katsayısı dışarıdan alınmıştır |
| Çarpan belirsizliği | Çarpım sabit, çarpanlar serbest |
| Asimetri yokluğu | Karşılıklı sistemde $\chi_S \equiv 1$ — hipotezin sınanabilir örneği tanımsız |

Bu hipotez sayaç üretmez; önceden kayıtlı bir köprü testine dönüşmedikçe **açık borç** olarak kalır.

---




# BÖLÜM 18 — KUANTUM OLGULARI

## 18.0 Kuantum davranışı ve faz rejimi – eşik sınırı

Atom altı düzey, c⁺ ile Cₘ arasındaki **faz rejimi – eşik sınırında** bulunur — tıpkı $v=c$ sınırındaki ışık gibi. Yazar hükmüyle: c eşik rejiminin sınırında bulunan bir yapı, aynı zamanda c⁺ rejiminin de sınırındadır. Bu bir çelişki değildir; iki rejimin **ortak sınırında** bulunmak, ikisinin birden üyesi olmak demek değildir (sınır ≠ üyelik).

$$\boxed{\;v=c\;\text{: Cₘ ile } c^+ \text{'ın liminal ortak sınırı}\qquad \text{sınırda bulunmak}\neq\text{iki fazın üyesi olmak}\;}$$

```latex
\boxed{\;v=c\;\text{: Cₘ ile } c^+ \text{'ın liminal ortak sınırı}\qquad \text{sınırda bulunmak}\neq\text{iki fazın üyesi olmak}\;}
```

c⁺'ta zaman ve zamana bağlı kısıt yoktur. Bu yüzden sınırdaki bir yapı için zaman kavramı belirsizleşir: Cₘ tarafından bakıldığında zaman işler, c⁺ tarafında kurulu değildir. Dalga–parçacık ikiliği, ölçüm problemi ve kuantum davranışının zamanla tutarsız görünmesi bu sınırın davranışları olarak okunur; ölçüm ise her zaman Cₘ'de gerçekleşir.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kuantum davranışının tuhaflıklarını, c⁺ ile Cₘ'nin ortak sınırında bulunmanın sonuçları olarak okur |
| **Neden yapıyor?** | Zamanla tutarsız görünen kuantum davranışlarını (gecikmeli seçim, dolanıklık), zamanın yalnız Cₘ'de kurulu olduğu ontolojiyle bağlamak için |
| **Nasıl yapıyor?** | Atom altı düzeyi faz rejimi – eşik sınırına (25.1) yerleştirir; ışıkla benzerliği, ikisinin de sınır olgusu olmasıdır — aynı sınır parametresi değildir (aşağıdaki iki eksen); sınırın iki tarafındaki zaman durumunu (Cₘ'de kurulu, c⁺'ta yok) ayrı tutar |
| **Ne sonuç bekleniyor?** | Born olasılıkları, girişim, Bell korelasyonları, bağlamsallık ve sinyalsizliğin aynı modelde geri kazanılması |
| **Ne sonuç elde ediliyor?** | Bir **okumadır**; kuantum mekaniğinin ölçülmüş öngörülerine dokunmaz. Fiziksel bir açıklamaya dönüşmesi için yukarıdaki geri kazanımlar gereklidir ve **açıktır** |

**İki eksen: kinematik üyelik ve faz sınırı.** Elektron, proton ve nötrino gibi kütleli atom altı parçacıklar kinematik olarak $0<v<c$ bandındadır ve **Cₘ üyesidir**. Bunların "faz rejimi – eşik sınırında" bulunması, $v=c$ kinematik sınırında bulunmaları anlamına gelmez; ayrı bir eksende — faz eşevreliği / kuantum okuma ekseninde — tanımlanan sınırdır. $v=c$ kinematik sınırı yalnız ışık (kütlesiz parçacıklar) için tutulur:

$$\beta=\frac{v_{\rm üyelik}}{c}\in(0,1)\ \ (\text{kinematik üyelik ekseni}),\qquad q_\partial\ \ (\text{faz sınırı / kuantum okuma ekseni}),\qquad \text{ışık: }\beta=1$$

```latex
\beta=\frac{v_{\rm üyelik}}{c}\in(0,1)\ \ (\text{kinematik üyelik ekseni}),\qquad q_\partial\ \ (\text{faz sınırı / kuantum okuma ekseni}),\qquad \text{ışık: }\beta=1
```

| Sembol | Anlamı |
|---|---|
| $\beta$ | Boyutsuz kinematik üyelik okuması |
| $v_{\rm üyelik}$ | Üyelik okuması (laboratuvar koordinat hızı değil; 3.3) |
| $q_\partial$ | Faz rejimi – eşik sınırına yakınlık okuması (tipi ve ölçüsü açık) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kütleli atom altı parçacıkların Cₘ üyeliği ile kuantum sınır davranışını iki ayrı eksende yazar |
| **Neden yapıyor?** | "Atom altı düzey ışıkla aynı sınırda" ifadesi harfiyen okunursa kütleli parçacıkların $0<v<c$ üyeliğiyle çelişirdi |
| **Nasıl yapıyor?** | Kinematik sınırı $\beta$ ekseninde, faz rejimi – eşik sınırını $q_\partial$ ekseninde tanımlar; bir parçacık $\beta<1$ ile Cₘ üyesiyken $q_\partial$ bakımından sınır davranışı gösterebilir |
| **Ne sonuç bekleniyor?** | $q_\partial$'ın tipinin ve ölçüsünün tanımlanması |
| **Ne sonuç elde ediliyor?** | Yazar hükmü (sınırda bulunma, sınır ≠ üyelik) **aynen korunur**; yalnız hangi sınırın kastedildiği açık kılınır. $q_\partial$ açıktır (EK K.1) |

Örnek olarak **nötrino salınımı** — nötrinoların yolculuk sırasında tür değiştirmesi — sağlam biçimde ölçülmüş bir olgudur ve faz eşiği sınırında bulunma okumasına adaydır. Nötrinoların ışıktan hızlı gittiğini öne süren 2011 ölçümü bir ölçüm hatası olarak geri çekilmiştir; Evertophy bu sonuca dayanmaz.

## 18.1 Dolanıklık

$$\boxed{\;c^+ \text{ BİR İLETİŞİM KANALI DEĞİLDİR.}\;}$$

```latex
\boxed{\;c^+ \text{ BİR İLETİŞİM KANALI DEĞİLDİR.}\;}
```

Bu, sinyal gönderme yasağını koruyan kritik kısıttır. Dolanık iki parçacığın korelasyonu c⁺'ın Cₘ'deki bir okuması olarak yorumlanabilir; ama bu korelasyon üzerinden kontrol edilebilir bir bilgi gönderilemez.

**Kuantum ışınlama okuması.** Kuantum ışınlama deneylerinde bir durumun aktarılması, ölçüm sonuçlarının **klasik bir kanal** üzerinden (ışık hızını aşmadan) iletilmesini zorunlu olarak gerektirir. Evertophy okumasında c⁺, aktarımın **korelasyon kaynağıdır**; bilgiyi taşıyan kanal değildir. Bilgi Cₘ'nin klasik kanalıyla, en fazla ışık hızıyla gider. Bu okuma deneylerin ölçülmüş sonuçlarıyla **uyumlu okumadır** ve sinyal yasağını aşmaz.

$$\boxed{\;\text{Işınlama} = \underbrace{c^+\text{ korelasyon kaynağı}}_{\text{okuma}} + \underbrace{\text{klasik kanal}}_{C_m,\ \le c}\;}$$

```latex
\boxed{\;\text{Işınlama} = \underbrace{c^+\text{ korelasyon kaynağı}}_{\text{okuma}} + \underbrace{\text{klasik kanal}}_{C_m,\ \le c}\;}
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Dolanıklık ve ışınlamada c⁺'ın rolünü korelasyon kaynağıyla sınırlar |
| **Neden yapıyor?** | c⁺'a sinyal kanalı rolü vermek, göreliliğin ve kuantum mekaniğinin ölçülmüş sinyal yasağıyla çelişirdi |
| **Nasıl yapıyor?** | Aktarımı iki bileşene ayırır: c⁺'tan okunan korelasyon ve Cₘ'deki klasik bilgi kanalı |
| **Ne sonuç bekleniyor?** | Bell korelasyonlarının ve sinyalsizliğin aynı modelde nicel olarak geri kazanılması |
| **Ne sonuç elde ediliyor?** | **Uyumlu okumadır.** Dürüst kayıt: Evertophy dolanıklığı **açıklamaz**; bir okuma çerçevesi önerir |

## 18.2 Faz sözlüğü

Aşağıdaki eşlemeler **tarihsel / kavramsal benzetmeler ya da model adaylarıdır** — çekirdek ontoloji değildir ve türetim değildir:

| Olgu | Faz okuması |
|---|---|
| Spin | Yapı düğümünün Cₘ üzerindeki durum etiketi |
| Pauli dışlama | Kayıt protokolünde adres çakışması engeli |
| Kuantum Zeno | Sürekli ölçüm mühürleme ritmini dondurur |
| Tünelleme | Kaydın gevşemesi, bariyerin aşılması, yeniden mühürlenme |
| Gecikmeli seçim | Mühürleme kararının zaman indeksinden bağımsız tutarlılığı |
| Belirsizlik | Cₘ okumasının sonlu çözünürlüğü |

$$\boxed{\;\text{Hiçbiri standart kuantum mekaniğinden FARKLI bir ÖNGÖRÜ üretmez.}\;}$$

```latex
\boxed{\;\text{Hiçbiri standart kuantum mekaniğinden FARKLI bir ÖNGÖRÜ üretmez.}\;}
```

## 18.3 Kuantum alan kuramının statüsü

$$\boxed{\;\text{Kuantum alan kuramı Evertophy'nin ALTERNATİFİ DEĞİL, Cₘ fazındaki ETKİN HESAP LİMİTİDİR.}\;}$$

```latex
\boxed{\;\text{Kuantum alan kuramı Evertophy'nin ALTERNATİFİ DEĞİL, Cₘ fazındaki ETKİN HESAP LİMİTİDİR.}\;}
```

Bu, çerçevenin üçüncü ilkesinin doğrudan uygulamasıdır: ölçümü doğru yeniden üreten matematiksel temsil, o ölçüm kapsamında koşulsuz kabul edilir; temsiller arasında ontolojik öncelik yoktur. Kuantum alan kuramının vakum durumu da c⁺ ≡ vakum kimliğinin Cₘ içindeki hesap dilidir (Bölüm 3).

### Yapısal ayrım kuralı

$$\boxed{\;\text{Ana metin SAF FAZ ONTOLOJİSİDİR. Kuantum alan kuramı araçları, Cₘ hesaplarını ÇEVİREN bir EK KATMANDIR.}\;}$$

```latex
\boxed{\;\text{Ana metin SAF FAZ ONTOLOJİSİDİR. Kuantum alan kuramı araçları, Cₘ hesaplarını ÇEVİREN bir EK KATMANDIR.}\;}
```

Kuantum alan kuramı parametrelerinin ilke olarak faza bağlı olabileceği önerilir; bu bağımlılıkların biçimi bilinmemektedir.

## 18.4 Vakumdan madde üretimi

Değişen bir arka planda parçacık üretimi hesapları **verili bir metrik** varsayar; Evertophy'de geometri Cₘ'nin çıktısıdır.

$$\boxed{\;\text{Bu araçlar Cₘ İÇİNDE kullanılabilir; } c_0 \to C_m \text{ geçişine UYGULANAMAZ.}\;}$$

```latex
\boxed{\;\text{Bu araçlar Cₘ İÇİNDE kullanılabilir; } c_0 \to C_m \text{ geçişine UYGULANAMAZ.}\;}
```

c⁺ ≡ vakum kimliği altında, güçlü bir alanla vakumdan parçacık üretimi (Schwinger mekanizması) ya da yüksek enerjili fotonlardan çift oluşumu, **c⁺ → Cₘ kenarında dış enerjiyle tetiklenen yerel bir faz geçişi** olarak okunur (aday okuma). Ölçülmüş ve hesaplanmış bütün sonuçlar kuantum alan kuramının Cₘ hesap dili olarak aynen geçerlidir.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Vakumdan madde üretimini, c⁺ ≡ vakum kimliği altında bir faz geçişi olarak okur |
| **Neden yapıyor?** | Vakum c⁺'ın laboratuvar okumasıysa, vakumdan madde doğması c⁺'tan Cₘ'ye bir geçişin Cₘ'deki görünümüdür |
| **Nasıl yapıyor?** | Hesabı kuantum alan kuramına bırakır; yalnız ontolojik etiketi (Δ₊ₘ kenarı, dış enerjiyle tetikleme) ekler |
| **Ne sonuç bekleniyor?** | Eşik alanları ve üretim oranları için standart sonuçlarla birebir uyum |
| **Ne sonuç elde ediliyor?** | **Aday okumadır**; yeni bir sayısal öngörü üretmez. Aynı araçlar c₀ → Cₘ geçişine uygulanmaz, çünkü c₀'da metrik henüz kurulmamıştır |

## 18.5 Laboratuvar benzerleri

Bose–Einstein yoğuşması (BEC) ve süperakışkanlık, **toplu ve eşevreli (koherent) davranışın** laboratuvar örnekleridir.

**Yazar hükmü:** BEC c₀ değildir; **madde fazında c₀ ortamına en yakın ortamdır.** Atomların tek bir kuantum durumunda toplanması, c₀'ın tümleşik tek-yapı sezgisine Cₘ içinden bakmanın en iyi yoludur; ama BEC hâlâ Cₘ'dedir: zamanı, metriği ve ölçülebilir parçacık yapısı vardır.

$$\boxed{\;\text{BEC}\neq c_0;\qquad \text{BEC = madde fazında } c_0 \text{ ortamına en yakın ortam}\;}$$

```latex
\boxed{\;\text{BEC}\neq c_0;\qquad \text{BEC = madde fazında } c_0 \text{ ortamına en yakın ortam}\;}
```

$$\boxed{\;\text{Süperakışkan} \to c^+ \text{ eşlemesi KULLANILMAZ.}\;}$$

```latex
\boxed{\;\text{Süperakışkan} \to c^+ \text{ eşlemesi KULLANILMAZ.}\;}
```

Bunun nedeni şudur: c⁺'ın ayırt edici özelliği eşevrelilik değil, **Cₘ madde desteğinin çözülmesidir**.

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Laboratuvar yoğuşmalarını faz mimarisinde doğru yere koyar |
| **Neden yapıyor?** | BEC'i c₀ ile özdeşleştirmek kategori hatası olurdu; ama onu c₀ sezgisinden tümüyle koparmak da öğretici bir köprüyü kaybettirirdi |
| **Nasıl yapıyor?** | BEC'i Cₘ üyeliğinde tutar; c₀'a "en yakın Cₘ ortamı" olarak konumlar; süperakışkanı c⁺ ile eşlemeyi yasaklar |
| **Ne sonuç bekleniyor?** | BEC deneylerinin c₀ tek-yapı sezgisi için nitel bir sınama ortamı sağlaması |
| **Ne sonuç elde ediliyor?** | Yazar hükmüdür; BEC'in c₀'a "yakınlığı" nicel olarak tanımlanmamıştır |

---

## 18.6 Dolanıklıkta yazma koruması

Arşivdeki aday okuma: dolanıklık, c⁺'ta etkin "yazmaya karşı korumalı korelasyon deposu" olarak modellenir.

| Kavram | Evertophy okuması |
|---|---|
| Mühürleme | Yazma |
| Geri çağırma | Okuma |
| Dolanıklık | c⁺'ta etkin, yazmaya karşı korumalı korelasyon deposu |
| Sinyal gönderme | Geri çağırma aileleri nedeniyle engelli |

"Uzak korelasyonlar geri çağrılabilir ama değiştirilemez" cümlesi bir model adayıdır; sinyal yasağıyla uyumludur ama ondan türetilmiş değildir.

## 18.7 Titreşim (jitter) = bilgi taşıyıcısı adayı

Planck ölçeğindeki zaman titreşiminin bilgi taşıyıcısı olabileceği önerisi arşivde korunur:

$$\Delta t \sim \sqrt{\frac{G\hbar}{c^5}} \approx 5.39\times10^{-44}\ \mathrm{s}$$

```latex
\Delta t \sim \sqrt{\frac{G\hbar}{c^5}} \approx 5.39\times10^{-44}\ \mathrm{s}
```

| Sembol | Anlamı |
|---|---|
| $\Delta t$ | Planck zamanı mertebesindeki titreşim ölçeği |
| $G$, $\hbar$, $c$ | Kütleçekim sabiti, indirgenmiş Planck sabiti, ışık hızı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Cₘ zamanının en küçük anlamlı ölçeğini Planck zamanı olarak verir ve bunu bir bilgi taşıyıcısı adayı sayar |
| **Neden yapıyor?** | Zamanın Cₘ'de kurulan bir okuma olduğu görüşünde, bu okumanın bir çözünürlük sınırı olup olmadığını sormak için |
| **Nasıl yapıyor?** | Temel sabitlerden boyut çözümlemesiyle zaman ölçeğini kurar |
| **Ne sonuç bekleniyor?** | Titreşim bütçesinin bilgi kapasitesiyle ilişkilendirilmesi |
| **Ne sonuç elde ediliyor?** | Arşiv notları (titreşim bütçesi üst sınırı ~$10^{-44}$ s; karşılık gelen frekans ~$10^{44}\ \mathrm{s^{-1}}$) **bilgi kapasitesi kaydı** olarak tutulur. Titreşimin gerçekten bu nitelikte olduğu gösterilmemiştir ve CMT doğrusallaştırması altında kendiliğinden ortadan kalkar |

## 18.8 Onaylama / geri alma ontolojisi

Kuantum üst üste binme (süperpozisyon) için onaylama / geri alma (commit / rollback) dili: üst üste binme "onaylanmamış taslak alanı", ölçüm "onaylama" işlemidir.

$$\boxed{\;\text{Üst üste binme = onaylanmamış taslak alanı; ölçüm = onaylama. Geri alma, onaydan sonra Cₘ'de gerçekleşmez.}\;}$$

```latex
\boxed{\;\text{Üst üste binme = onaylanmamış taslak alanı; ölçüm = onaylama. Geri alma, onaydan sonra Cₘ'de gerçekleşmez.}\;}
```

Bu bir model adayıdır — hesaplama dilinden bir ithaldir, ontolojik ilan değildir.

## 18.9 Dolanıklık takası — zincirleme dolanıklık

Dolanıklık takasının arşiv okuması bir "onay zinciridir". Bell ölçümü aracı olmadan korelasyon aktarılamaz; bu okuma sinyal yasağıyla uyumludur, onu aşmaz. "c⁺ = ağ, EPR = kısa devre, dolanıklık = yazmaya karşı korumalı korelasyon" olarak işlenen benzetme ailesinin tamamı model düzeyindedir.

## 18.10 Üç aşamalı iç içe çift yarık — fiziksel model

Ara katmanlı çift yarık düzeneği için arşivdeki fiziksel model: $\varphi_b$ düzeyi c⁺'a bağlanır; girişim deseni $d\Phi(x)$ korelasyonundan doğar. Zamansızlık çözümünün aday ifadesi şudur: "c⁺ kalıcıdır; Cₘ zamanı türetilmiştir; üst üste binme faz içi kalıcılıktır." Bu, ertelenmiş seçim deneylerinin çerçeve içi **uyumlu okumasıdır** — türetim değil, yorum adayıdır ve Born kuralını türetmez.

## 18.11 Kuantum belirsizliği = görüntüleme gürültüsü okuması

Belirsizlik ilkesinin "Cₘ okumasının sonlu çözünürlük gürültüsü" olarak okunması adayı, 15.3'teki kısıtla aynı statüdedir: standart olasılıkları ve Born kuralını türetmedikçe fiziksel köprü sayılmaz. Belirsizlik bağıntıları ifade edilmiş hâlleriyle korunur:

$$\Delta x\,\Delta p \;\ge\; \frac{\hbar}{2},\qquad \sigma_x\,\sigma_p \;\ge\; \frac{\hbar}{2}$$

```latex
\Delta x\,\Delta p \;\ge\; \frac{\hbar}{2},\qquad \sigma_x\,\sigma_p \;\ge\; \frac{\hbar}{2}
```

| Sembol | Anlamı |
|---|---|
| $\Delta x$, $\Delta p$ | Konum ve momentum belirsizlikleri |
| $\sigma_x$, $\sigma_p$ | Konum ve momentumun standart sapmaları |
| $\hbar$ | İndirgenmiş Planck sabiti |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kuantum belirsizliğini Cₘ ekranının sonlu çözünürlüğü olarak okumayı önerir |
| **Neden yapıyor?** | Belirsizliği, ölçümün Cₘ'ye ait olmasıyla doğal biçimde ilişkilendirmek için |
| **Nasıl yapıyor?** | Standart bağıntıları olduğu gibi korur; yalnız yorum katmanında bir okuma ekler |
| **Ne sonuç bekleniyor?** | Okumanın Born kuralını ve standart olasılıkları türetmesi |
| **Ne sonuç elde ediliyor?** | Bağıntılar ölçülmüş fiziktir ve koşulsuz kabul edilir; okuma **model adayıdır**, güncel çekirdek değildir |

## 18.12 Kuantum yorumlarıyla karşılaştırma notu

| Yorum | Evertophy ile ilişki |
|---|---|
| **Kopenhag** | Ölçüm vurgusu paralel; "gözlemci" ontolojik bir sınıf değil (15.6) |
| **Çoklu dünyalar** | Arşiv / dal dili c⁺ ile karıştırılmaz; c⁺ çoklu dünya değildir |
| **Pilot dalga (Bohm)** | Gizli değişken programı çekirdeğe ithal edilmez |
| **QBism** | Yetersiz kaynak desteği nedeniyle ayrı başlık açılmamıştır; not düzeyinde korunur |
| **İlişkisel kuantum mekaniği (RQM)** | Etkileşim merkezli ölçüm dili paralel (7.11d) |

$$\boxed{\;\text{Evertophy hiçbir yorumu seçmez; ölçümü faz / okuma / mühürleme diliyle yeniden konumlandırır (15.3).}\;}$$

```latex
\boxed{\;\text{Evertophy hiçbir yorumu seçmez; ölçümü faz / okuma / mühürleme diliyle yeniden konumlandırır (15.3).}\;}
```

---

# BÖLÜM 19 — TOPOLOJİ

## 19.1 Güncel topoloji

$$\boxed{\;\text{Tam çift yönlü üçgen: } c_0 \leftrightarrow C_m,\; C_m \leftrightarrow c^+,\; c_0 \leftrightarrow c^+\;}$$

```latex
\boxed{\;\text{Tam çift yönlü üçgen: } c_0 \leftrightarrow C_m,\; C_m \leftrightarrow c^+,\; c_0 \leftrightarrow c^+\;}
```

Üç fazın her biri diğer ikisine doğrudan bağlıdır (K3). Kenarlardan ikisi Cₘ'ye değer ve damga taşır (Δ₀ₘ, Δ₊ₘ); üçüncüsü (Δ₀₊) Cₘ'ye değmez ve damgasızdır. Cₘ **epistemik merkezdir** — her şeyi oradan ölçeriz —, ama topolojik olarak zorunlu bir aracı değildir: c₀ ile c⁺ arasında Cₘ'den geçmeyen doğrudan bir kenar vardır.

## 19.1a Tam üçgen boyuttan bağımsızdır

Faz kapılarının tam üçgen oluşturması bir **tip** özelliğidir; belirli bir geometriye bağlı değildir. Bunu bir karşı örnek netleştirir: yalnız bir doğru üzerine yerleşen kuyular bir zincir oluşturur ve tam üçgen veremez; ama bir çember üzerinde, örneğin $V(\theta) = -A\cos 3\theta$ gibi bir potansiyel, tek boyutta tam üçgen verir. Dolayısıyla "tam üçgen için en az iki boyut gerekir" genellemesi yanlıştır ve geri çekilmiştir.

İki boyutlu gerçeklemeler **model** düzeyindedir. İdeal eşkenar Gauss peyzajında kuyu genişliği $\sigma$ arttıkça yapı üç rejimden geçer: tam üçgen, merkez-yıldız ve tek düğüm. Okuma uzayının Öklid yapısı bir Cₘ temsilidir; c₀ ya da c⁺'a Öklid yapı atfetmez. Disk gerçeklemesinin "kanonik" ya da "tek" olduğu iddiası da geri çekilmiştir.

### Denklem seti — faz topolojisi: Morse peyzajı ve tam üçgen

Üç fazın arasındaki geçişlerin **tam bir üçgen** (K3) oluşturduğu kanondur. Soru şudur: bu yapı bir potansiyel peyzajında nasıl gerçeklenir ve kaç boyut gerekir?

$$\chi = m - s + M \quad (\text{disk: } 3 - 3 + 1 = 1;\ \ S^1: 3 - 3 = 0)$$

```latex
\chi = m - s + M \quad (\text{disk: } 3 - 3 + 1 = 1;\ \ S^1: 3 - 3 = 0)
```

$$V(\theta) = -A\cos 3\theta,\quad \theta \in S^1 \quad \text{(karşı örnek)}$$

```latex
V(\theta) = -A\cos 3\theta,\quad \theta \in S^1 \quad \text{(karşı örnek)}
```

$$V(\mathbf{x}) = -A\sum_{i=1}^{3}\exp\!\Big(-\frac{|\mathbf{x}-\mathbf{v}_i|^2}{2\sigma^2}\Big),\qquad \mathbf{v}_1 = (0,1),\ \ \mathbf{v}_{2,3} = \big(\mp\tfrac{\sqrt3}{2}, -\tfrac12\big)$$

```latex
V(\mathbf{x}) = -A\sum_{i=1}^{3}\exp\!\Big(-\frac{|\mathbf{x}-\mathbf{v}_i|^2}{2\sigma^2}\Big),\qquad \mathbf{v}_1 = (0,1),\ \ \mathbf{v}_{2,3} = \big(\mp\tfrac{\sqrt3}{2}, -\tfrac12\big)
```

$$H(0) = \frac{3A(2\sigma^2 - 1)}{2\sigma^4}\,e^{-1/2\sigma^2}\,I \;\Rightarrow\; \sigma^* = \tfrac{1}{\sqrt2},\qquad \sigma_{\rm fold} \approx 0.7391346294$$

```latex
H(0) = \frac{3A(2\sigma^2 - 1)}{2\sigma^4}\,e^{-1/2\sigma^2}\,I \;\Rightarrow\; \sigma^* = \tfrac{1}{\sqrt2},\qquad \sigma_{\rm fold} \approx 0.7391346294
```

| $\sigma$ rejimi | $(m,s,M)$ | Komşuluk çizgesi |
|---|---|---|
| $0 < \sigma < 1/\sqrt2$ | (3, 3, 1) | $K_3$ |
| $1/\sqrt2 < \sigma < \sigma_{\rm fold}$ | (4, 3, 0) | $K_{1,3}$ |
| $\sigma > \sigma_{\rm fold}$ | (1, 0, 0) | Tek düğüm |

| Sembol | Anlamı |
|---|---|
| $V$ | Okuma uzayındaki potansiyel |
| $\theta$ | Çember üzerindeki açı koordinatı |
| $(m, s, M)$ | Minimum, eyer ve maksimum sayısı |
| $\chi$ | Euler karakteristiği |
| $K_3$, $K_{1,3}$ | Tam üçgen; bir merkez + üç kol (yıldız) |
| $\mathbf v_i$ | Eşkenar üçgenin köşeleri (birim çember üzerinde) |
| $\sigma$ | Gauss kuyularının genişliği |
| $A$ | Kuyu derinliği ($A > 0$) |
| $H(0)$ | Potansiyelin merkezdeki Hessian matrisi |
| $\sigma^*$ | Merkezin maksimumdan minimuma döndüğü eşik |
| $\sigma_{\rm fold}$ | Eyerlerin yok olduğu katlanma eşiği |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Tam üçgen faz topolojisinin bir potansiyel peyzajında nasıl gerçeklenebileceğini ve hangi parametre aralığında bozulduğunu hesaplar |
| **Neden yapıyor?** | "Tam üçgen için en az iki boyut gerekir" ve "disk tek kanonik gerçeklemedir" gibi genellemeleri sınamak için |
| **Nasıl yapıyor?** | Morse kuramıyla kritik nokta sayılarını Euler karakteristiğine bağlar; çember üzerinde tek boyutlu bir karşı örnek kurar; iki boyutta Gauss kuyularının merkezdeki Hessian'ını analitik olarak hesaplar |
| **Ne sonuç bekleniyor?** | Rejim eşiklerinin kesin değerleri ve tam üçgenin geometriden bağımsızlığı |
| **Ne sonuç elde ediliyor?** | Tipli kapı K3 **kanıtlanmıştır** (★). Çember, disk ve Gauss gerçeklemeleri **modeldir**; ideal Gauss rejimleri **doğrudur** (model). Tam aralık sertifikası **kısmidir**. "$d_{\min}=2$", disk kanonikliği ve "Morse-7" iddiaları **yanlıştır** ve geri çekilmiştir |

## 19.2 Ek topolojik yapılar ithal edilmez

$$\boxed{\;\text{Ek boyut, burulma yapıları, Chern–Simons terimleri, süpersimetri, çoklu evren — HİÇBİRİ çekirdeğe ithal EDİLMEZ.}\;}$$

```latex
\boxed{\;\text{Ek boyut, burulma yapıları, Chern–Simons terimleri, süpersimetri, çoklu evren — HİÇBİRİ çekirdeğe ithal EDİLMEZ.}\;}
```

Bunlar gerekiyorsa **ayrıca gerekçelendirilmeli** ve parametre bedeli açıkça sayılmalıdır. Bu, 9.2a'daki üç boyutlu düz Öklid uzay hükmüyle de tutarlıdır: Cₘ'nin temel uzayında ek boyut yoktur.

## 19.3 Bilinen yapısal kısıt

Tek bağımsız çevrimli bir yapıda temsillerin imgesi devirli — dolayısıyla değişmeli — olur. Bu, değişmesiz bir ayar grubunun bütününün çıplak çevrimden üretilemeyeceği anlamına gelir. Buna karşılık tek çevrime üniter bir holonomi **atanabilir**: her üniter $U$ için $\rho(n)=U^n$ bir temsildir. Örneğin:

$$U_{jk}=\frac{\omega^{jk}}{\sqrt3},\quad \omega=e^{2\pi i/3},\ \ j,k=0,1,2;\qquad J=\operatorname{Im}\!\big(U_{00}U_{11}U_{01}^*U_{10}^*\big)=\frac{\sqrt3}{18}\neq0$$

```latex
U_{jk}=\frac{\omega^{jk}}{\sqrt3},\quad \omega=e^{2\pi i/3},\ \ j,k=0,1,2;\qquad J=\operatorname{Im}\!\big(U_{00}U_{11}U_{01}^*U_{10}^*\big)=\frac{\sqrt3}{18}\neq0
```

| Sembol | Anlamı |
|---|---|
| $\rho(n)=U^n$ | Tek çevrimin $n$ kez dolaşılmasına karşılık gelen temsil |
| $U$ | Üniter matris (3×3 ayrık Fourier matrisi örneği) |
| $\omega$ | Birimin üçüncü kökü |
| $J$ | Jarlskog benzeri faz değişmezi (CP ihlali ölçüsü) |
| $^*$ | Karmaşık eşlenik |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Tek çevrimli faz topolojisinin ayar ve karışım yapıları üzerine koyduğu sınırı ve bıraktığı olanağı gösterir |
| **Neden yapıyor?** | Faz üçgeninden CKM / PMNS karışım matrislerinin "kendiliğinden" çıkacağı iddiasını sınamak için |
| **Nasıl yapıyor?** | Tek üreteçli temel grubun temsillerinin devirli olduğunu gösterir; yine de üniter bir holonomi atanabileceğini ve bunun sıfırdan farklı bir CP fazı verebileceğini somut bir örnekle hesaplar |
| **Ne sonuç bekleniyor?** | Belirli karışım değerlerini seçen ek fiziksel yapının bulunması |
| **Ne sonuç elde ediliyor?** | Doğru hüküm şudur: **çıplak faz topolojisi belirli CKM / PMNS karışım değerlerini tek başına seçmez; bu seçim için ek fiziksel yapı gerekir.** Tek çevrim holonomisi yaklaşımı bir alternatif olarak açıktır ve fiziksel türetim bekler |

$$\boxed{\;\text{Bu bir YAPISAL KISITTIR — ek yapı ithal edilirse PARAMETRE BEDELİ doğar.}\;}$$

```latex
\boxed{\;\text{Bu bir YAPISAL KISITTIR — ek yapı ithal edilirse PARAMETRE BEDELİ doğar.}\;}
```

## 19.4 Sıra duyarlılığı

Çevrim boyunca biriken etki iki farklı nesneyle ölçülebilir: sıraya duyarsız bir skaler karakter ve sıraya duyarlı bir sıralı taşıma. Değişmelileştirme (abelyenleştirme) sıra bilgisini **siler**. Damgalar tersinir olmadığından "holonomi" adı yalnız tersinir sektöre ayrılır; genel durum **sıralı taşımadır** (14.8).

## 19.5 Çıplak üçgenin homolojisi

Üç kenarlı yapı yalnız sınır çizgesi olarak alınırsa:

$$V=3,\qquad E=3,\qquad \beta_1=E-V+1=1,\qquad \boxed{\;H_1\cong\mathbb Z,\qquad \pi_1\simeq\mathbb Z\;}$$

```latex
V=3,\qquad E=3,\qquad \beta_1=E-V+1=1,\qquad \boxed{\;H_1\cong\mathbb Z,\qquad \pi_1\simeq\mathbb Z\;}
```

Üçgen bir 2-simpleks olarak **doldurulursa**:

$$\boxed{\;H_1=0\;}$$

```latex
\boxed{\;H_1=0\;}
```

| Sembol | Anlamı |
|---|---|
| $V$, $E$ | Köşe (faz) ve kenar sayısı (bu bağlamda potansiyel değil) |
| $\beta_1$ | Birinci Betti sayısı (bağımsız çevrim sayısı) |
| $H_1$ | Birinci homoloji grubu |
| $\pi_1$ | Temel grup |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Faz üçgeninin topolojik değişmezlerini iki farklı biçimselleştirme için hesaplar |
| **Neden yapıyor?** | Çevrim programının (holonomi, karışım) üçgenin içinin boş mu dolu mu sayıldığına bağlı olduğunu göstermek için |
| **Nasıl yapıyor?** | Sınır çizgesinde tek bağımsız çevrim bulur; doldurulmuş simplekste çevrimin büzülebildiğini ve homolojinin sıfırlandığını gösterir |
| **Ne sonuç bekleniyor?** | "Sınır mı, dolu simpleks mi?" sorusunun ayrı bir biçimsel kararla kapatılması |
| **Ne sonuç elde ediliyor?** | Tek üreteçli temel grubun her temsilinin imgesi devirlidir; çıplak tek çevrim değişmesiz bir ayar yapısını kendiliğinden üretmez ve belirli karışım değerlerini seçmez. Tek çevrime üniter holonomi atamak mümkündür (19.3). Seçim, üç kenarın ontolojik varlığını değiştirmez |

## 19.6 Burulma ve ek yapı maliyeti

Çıplak sınır üçgeninde $H_1\cong\mathbb Z$ burulmasızdır (torsiyonsuz). Dolayısıyla

$$W^k=I$$

```latex
W^k=I
```

gibi bir $\mathbb Z_k$ koşulu topolojiden bedelsiz çıkmaz; ek hücre, bağıntı ya da temsil yapısı ithal eder ve parametre / köprü bütçesi maliyeti doğurur. Burada $W$ çevrim holonomisi, $k$ bir tam sayı, $I$ birim matristir.

## 19.7 Karakter ve sıraya duyarlı temsil

Sıraya duyarsız toplamsal bilgi değişmelileştirilmiş karakterle tutulabilir. Sıraya duyarlı içerik için

$$\rho:M\to \operatorname{End}(V)$$

```latex
\rho:M\to \operatorname{End}(V)
```

gibi bir temsil gerekir. $\rho(M)$ tersinir bir alt sektördeyse holonomi dili kullanılabilir; genel monoid etkisi için "sıralı taşıma" daha doğru terimdir.

---

# BÖLÜM 20 — STANDART MODEL VE GENEL GÖRELİLİK

## 20.1 Hedef ve mevcut durum

Hedef, Standart Model sabitlerini keyfî girdiler olmaktan çıkarıp faz yapısının çözümleri hâline getirmektir.

$$\boxed{\;\text{Hiçbir Standart Model sabiti için TÜRETİLMİŞ bir sayı ya da dar aralık ÜRETİLMEMİŞTİR.}\;}$$

```latex
\boxed{\;\text{Hiçbir Standart Model sabiti için TÜRETİLMİŞ bir sayı ya da dar aralık ÜRETİLMEMİŞTİR.}\;}
```

## 20.2 Mekanizma ataması ≠ türetim

$$\boxed{\;\text{"Bu sabit şu faz olayına karşılık gelir" demek, o olayın sayıyı ÜRETTİĞİNİ göstermez.}\;}$$

```latex
\boxed{\;\text{"Bu sabit şu faz olayına karşılık gelir" demek, o olayın sayıyı ÜRETTİĞİNİ göstermez.}\;}
```

Bu ayrım korunmazsa çerçeve, hiçbir şey öngörmeden her şeyi "açıklamış" görünür.

## 20.3 İki farklı problem

| Problem | Soru |
|---|---|
| **A — Mutlak değer** | Neden tam olarak bu sayı? |
| **B — Dinamik** | Bu nicelik koşullarla nasıl değişir? |

$$\boxed{\;\text{Evertophy şu an YALNIZ B'de ilerlemiştir.}\;}$$

```latex
\boxed{\;\text{Evertophy şu an YALNIZ B'de ilerlemiştir.}\;}
```

## 20.4 Üç makine programı

Amaç: **az girdi → çok gözlenebilir**.

| Makine | Zincir | Hedef |
|---|---|---|
| **1 — Kinetik** | $X$, kenarlar → ayar kinetik katsayıları → bağlaşımlar | Ayar sektörü |
| **2 — Potansiyel** | $X$, kenarlar → etkin potansiyel → skaler sektör | Higgs benzeri nicelikler |
| **3 — Yukawa** | $X$, kenarlar → Yukawa yapıları → kütleler ve karışımlar | Fermiyon sektörü |

### Hedef değer ≠ öngörü

$$\boxed{\;\text{Bir HEDEF DEĞERİ yazmak, onu ÖNGÖRMEK DEĞİLDİR.}\;}$$

```latex
\boxed{\;\text{Bir HEDEF DEĞERİ yazmak, onu ÖNGÖRMEK DEĞİLDİR.}\;}
```

Gözlemsel bir değeri "ulaşılacak hedef" olarak listelemek meşrudur; onu "öngörü" diye sunmak **değildir**. Asıl soru her zaman şudur: *neden bu değer?*

### Eleme testleri

| Makine | Eleme koşulu |
|---|---|
| 1 | Elektrozayıf tutarlılık ilişkileri ağaç düzeyinde geri üretilemezse |
| 1 | Bağlaşım koşusunun bilinen katsayıları geri üretilemezse |
| 3 | Karışım matrisi serbestçe uydurulursa — gizlice parametre olarak geri girer |

### CKM ve tek çevrim holonomisi

$$\boxed{\;\text{Çıplak faz topolojisi belirli CKM / PMNS değerlerini seçmez; tek çevrim holonomisi bir alternatiftir ve fiziksel türetim bekler (19.3).}\;}$$

```latex
\boxed{\;\text{Çıplak faz topolojisi belirli CKM / PMNS değerlerini seçmez; tek çevrim holonomisi bir alternatiftir ve fiziksel türetim bekler (19.3).}\;}
```

Yaşayan hipotez göreli sektör yapısıdır; ama serbestçe uydurulursa parametre bütçesi ihlal edilir.

### Makine ayrıntıları — yalnız program hedefi

Kinetik makine için araştırma zinciri, skaler makine ve Yukawa makinesi şöyle yazılabilir:

$$X,\Delta \longrightarrow \{Z_B,Z_W,Z_G\}\longrightarrow\{\alpha_{\rm EM},\sin^2\theta_W,\alpha_s\}$$

```latex
X,\Delta \longrightarrow \{Z_B,Z_W,Z_G\}\longrightarrow\{\alpha_{\rm EM},\sin^2\theta_W,\alpha_s\}
```

$$X,\Delta \longrightarrow V_{\rm eff}\longrightarrow\{v,\ m_H/v,\ \Gamma_{\rm vac}\}$$

```latex
X,\Delta \longrightarrow V_{\rm eff}\longrightarrow\{v,\ m_H/v,\ \Gamma_{\rm vac}\}
```

$$X,\Delta\longrightarrow\{Y_u,Y_d,Y_e,Y_\nu\}\longrightarrow\{\text{kütleler, CKM, PMNS}\}$$

```latex
X,\Delta\longrightarrow\{Y_u,Y_d,Y_e,Y_\nu\}\longrightarrow\{\text{kütleler, CKM, PMNS}\}
```

| Sembol | Anlamı |
|---|---|
| $X$, $\Delta$ | Dinamik üst çözücü ve faz kenarları |
| $Z_B$, $Z_W$, $Z_G$ | Hiperyük, zayıf izospin ve renk ayar alanlarının kinetik katsayıları |
| $\alpha_{\rm EM}$ | İnce yapı sabiti |
| $\theta_W$ | Zayıf karışım (Weinberg) açısı |
| $\alpha_s$ | Güçlü bağlaşım sabiti |
| $V_{\rm eff}$ | Etkin skaler potansiyel |
| $v$ | Higgs vakum beklenen değeri |
| $m_H$ | Higgs kütlesi |
| $\Gamma_{\rm vac}$ | Vakum bozunma oranı |
| $Y_u, Y_d, Y_e, Y_\nu$ | Yukarı kuark, aşağı kuark, yüklü lepton ve nötrino Yukawa matrisleri |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Standart Model'in üç sektörü için faz yapısından gözlenebilirlere giden üç araştırma zincirini tanımlar |
| **Neden yapıyor?** | Az sayıda girdiyle çok sayıda ölçülmüş değeri üretme hedefini somut ve sınanabilir hâle getirmek için |
| **Nasıl yapıyor?** | Her zinciri ara nicelikler üzerinden yazar ve her biri için eleme testleri tanımlar |
| **Ne sonuç bekleniyor?** | Ölçülmüş bağlaşımların, kütlelerin ve karışımların serbest uydurma olmadan çıkması |
| **Ne sonuç elde ediliyor?** | **Program hedefleridir**; güncel sayısal öngörü listesine girmez. Hiçbir zincir henüz kapanmamıştır |

### Üç minimumlu etkin potansiyel kaydı — aday

Tarihsel geliştirme kayıtlarında üç faz değerini etkin minimumlar olarak temsil eden bir model adayı vardır:

$$V(C)=\beta(C-C_0)^2(C-C_m)^2(C-C_+)^2,\qquad \Box C+V'(C)=J_{\rm int}$$

```latex
V(C)=\beta(C-C_0)^2(C-C_m)^2(C-C_+)^2,\qquad \Box C+V'(C)=J_{\rm int}
```

| Sembol | Anlamı |
|---|---|
| $C$ | Etkin düzen parametresi alanı |
| $C_0$, $C_m$, $C_+$ | Üç fazın etkin minimum değerleri |
| $\beta$ | Potansiyel derinlik katsayısı |
| $\Box$ | d'Alembert işlemcisi (yalnız Cₘ etkin alan gerçeklemesinde) |
| $V'(C)$ | Potansiyelin $C$'ye göre türevi |
| $J_{\rm int}$ | İç kaynak terimi |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Üç fazı tek bir etkin alanın üç minimumu olarak temsil eder |
| **Neden yapıyor?** | Faz geçişlerini alan kuramının tanıdık diliyle (minimumlar arası geçişler) modellemeyi denemek için |
| **Nasıl yapıyor?** | Üç minimumlu altıncı dereceden bir potansiyel kurar ve alan denklemini kaynak terimiyle yazar |
| **Ne sonuç bekleniyor?** | $\beta$, $C_i$ ve $J_{\rm int}$ türetilirse sınanabilir geçiş dinamikleri |
| **Ne sonuç elde ediliyor?** | **Temel faz ontolojisi değildir.** $\Box$ kullanımı Cₘ etkin alan gerçeklemesine aittir ve c₀ / c⁺'a metrik ya da tetrad sokmaz. Eşlemeler türetilmeden bu biçim öngörü üretmez |

## 20.4a Üç makinenin daha keskin eleme testleri

### Makine 1 — kinetik / ayar sektörü

Örnek aday parametrizasyon şudur:

$$\sin^2\theta_W\stackrel{\rm aday}{=}\frac{Z_W}{Z_W+Z_B}$$

```latex
\sin^2\theta_W\stackrel{\rm aday}{=}\frac{Z_W}{Z_W+Z_B}
```

Bu biçimin değeri, ölçülmüş $\sin^2\theta_W$'yi yerine koymak değil, **neden belirli bir $Z_W/Z_B$ oranının zorunlu olarak çıktığını** gösterebilmesindedir. Arşivde Makine 1 için kullanılan karşılaştırma hedeflerinden biri şudur:

$$\sin^2\theta_W^{\rm eff}(M_Z)\approx0.23149(13)$$

```latex
\sin^2\theta_W^{\rm eff}(M_Z)\approx0.23149(13)
```

$$\boxed{\;\text{ölçülmüş karşılaştırma değeri}\neq\text{Evertophy öngörüsü}\;}$$

```latex
\boxed{\;\text{ölçülmüş karşılaştırma değeri}\neq\text{Evertophy öngörüsü}\;}
```

Yayın ya da sayısal karşılaştırma öncesinde kullanılan **şema, gösterim ve dış kaynak** ayrıca doğrulanmalıdır. Elektrozayıf en küçük tutarlılık hedeflerinden biri, ağaç düzeyi limitinin geri kazanılmasıdır:

$$\rho_{\rm EW}=\frac{m_W^2}{m_Z^2\cos^2\theta_W}\simeq1$$

```latex
\rho_{\rm EW}=\frac{m_W^2}{m_Z^2\cos^2\theta_W}\simeq1
```

Nötr kütle matrisi yapısı ve koruyucu (custodial) simetri tutarlılığı türetilemezse "elektrozayıf türetim tamamlandı" denmez. Güçlü sektörde yalnız "$\alpha_s$ enerjiyle azalır" demek yetersizdir; pertürbatif limitte bilinen bir-döngü yapı katsayısı doğru etkin limitten geri kazanılmalıdır:

$$b_0=11-\frac{2}{3}n_f$$

```latex
b_0=11-\frac{2}{3}n_f
```

| Sembol | Anlamı |
|---|---|
| $\sin^2\theta_W^{\rm eff}(M_Z)$ | Z kütlesi ölçeğinde etkin zayıf karışım açısı (ölçülmüş) |
| $M_Z$, $m_Z$ | Z bozonu kütlesi |
| $m_W$ | W bozonu kütlesi |
| $\rho_{\rm EW}$ | Elektrozayıf $\rho$ parametresi |
| $b_0$ | Güçlü bağlaşımın bir-döngü beta fonksiyonu katsayısı |
| $n_f$ | Etkin kuark çeşni sayısı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Ayar sektörü için sınanabilir hedefleri ve eleme ölçütlerini sayısal olarak kesinleştirir |
| **Neden yapıyor?** | "Elektrozayıf yapı açıklandı" iddiasının ancak bilinen tutarlılık ilişkileri geri kazanılırsa yapılabileceğini kural hâline getirmek için |
| **Nasıl yapıyor?** | Aday parametrizasyonu, ölçülmüş değeri, ağaç düzeyi $\rho$ ilişkisini ve bir-döngü koşu katsayısını yan yana koyar |
| **Ne sonuç bekleniyor?** | $Z_W/Z_B$ oranının faz yapısından zorunlu çıkması; $\rho_{\rm EW}\simeq1$ ve $b_0$'ın geri kazanılması |
| **Ne sonuç elde ediliyor?** | **Program hedefidir.** Sayılar ölçülmüş karşılaştırma değeridir, Evertophy öngörüsü değildir |

### Makine 2 — etkin potansiyel / skaler sektör

Ölçülmüş oranı ya da bağlaşımı hedef olarak listelemek meşrudur; **hedef değer öngörü değildir**. Serbest bir potansiyel fonksiyonu eklemek de sonsuz fonksiyonel serbestlik anlamına gelebileceği için köprü bütçesine yazılır.

### Makine 3 — Yukawa / çeşni sektörü

Tek faz üçgeni çevriminin CKM'yi değişmesiz bir holonomi olarak otomatik üretmesi dışlanır. Yaşayan biçimsel aday, iki sektörün göreli taşımasıdır:

$$V_{\rm mix}\stackrel{\rm aday}{=}H_u^\dagger H_d$$

```latex
V_{\rm mix}\stackrel{\rm aday}{=}H_u^\dagger H_d
```

| Sembol | Anlamı |
|---|---|
| $V_{\rm mix}$ | Karışım matrisi (CKM ya da PMNS) |
| $H_u$, $H_d$ | Yukarı ve aşağı sektörü köşegenleştiren üniter dönüşümler |
| $^\dagger$ | Eşlenik devrik |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Karışım matrisini iki sektörün köşegenleştirme dönüşümlerinin göreli konumu olarak yazar |
| **Neden yapıyor?** | Standart Model'de karışım tam olarak bu biçimde ortaya çıkar; Evertophy'nin bunu faz yapısından üretmesi gerekir |
| **Nasıl yapıyor?** | İki sektörün taşımasını ayrı ayrı yazar ve göreli dönüşümü karışım olarak tanımlar |
| **Ne sonuç bekleniyor?** | $H_u$ ve $H_d$'nin faz yapısından birbirine bağlı olarak çıkması; Jarlskog türü değişmezin geri kazanılması |
| **Ne sonuç elde ediliyor?** | **Aday biçimdir.** $H_u$ ve $H_d$ bağımsız olarak serbestçe uydurulursa karışım matrisi gizlice girdi olarak geri girer. CP ihlali için yalnız determinant fazı yeterli değildir |

### Güçlü-CP notu

Bir üstel bastırma parametresi ekleyerek $\theta_{\rm QCD}$'yi küçük yapmak, bastırma ölçeği serbestse ince ayarı başka bir sembole taşır. Güçlü çözüm, yeni ince ayar eklemek yerine yapısal / topolojik bir zorunluluk üretmelidir. Bu bir **program hedefidir**, mevcut bir çözüm değildir.

## 20.5 Genel görelilikle ilişki

Genel görelilik **yanlış değildir** — Cₘ'nin etkin dilidir. Ama:

$$\boxed{\;\text{Evertophy'nin kullandığı eylem TEMEL EYLEM DEĞİLDİR — Cₘ'nin ETKİN eylemidir.}\;}$$

```latex
\boxed{\;\text{Evertophy'nin kullandığı eylem TEMEL EYLEM DEĞİLDİR — Cₘ'nin ETKİN eylemidir.}\;}
```

## 20.6 Geri kazanılması gerekenler

| Hedef | Durum |
|---|---|
| Newton limiti, zayıf alan | Skaler-tensör dili üzerinden erişilebilir |
| FRW kozmolojisi | Erişilebilir |
| Kuantum biçimciliği | Köprü yok |
| Ayar yapısı | Köprü yok; yapısal kısıt var |
| İkinci yasa | Kısmen kurulmuş |

## 20.7 Etkin olmayan türetim hatları

Nötrino kütleleri, baryon asimetrisi, tam Yukawa matrisleri ve mutlak fermiyon kütleleri için bugün **etkin ve doğal bir türetim köprüsü kurulmuş değildir**. Bu yüzden bunlar güncel sayısal türetim programının merkezinde değildir. Bu ifade kalıcı bir ontolojik yasak değildir; yeni bir köprü ancak parametre / köprü bütçesi bedeli ve bağımsız eleme testleriyle açılabilir.

---

## 20.8 Elektron = plazma bulutu modeli (tarihsel)

Erken katmanda elektronun "plazma bulutu" olarak ele alınması denenmiştir. Güncel çekirdekte parçacıklar Cₘ okuma izdüşümleridir (10.3); bu model geri getirilmez. Kayıt, arşivin model çeşitliliğini göstermek için korunur.

## 20.9 Proton kütlesi (QCD) — literatür sınıflaması kaydı

Proton kütlesinin büyük kısmı kuantum renk dinamiğinden (QCD) gelir; Higgs mekanizmasının kuark kütleleri üzerinden doğrudan katkısı küçüktür. Kesin yüzdeler ayrıştırma yöntemine bağlıdır ve kaynak gösterilmeden kullanılmaz. Bu, çerçeve dışı bir literatür kaydıdır:

$$\boxed{\;\text{Kütle çoğunlukla dinamiktir; bu gerçek, Evertophy'nin kütle türetimini yapmış olduğu anlamına gelmez.}\;}$$

```latex
\boxed{\;\text{Kütle çoğunlukla dinamiktir; bu gerçek, Evertophy'nin kütle türetimini yapmış olduğu anlamına gelmez.}\;}
```

Proton kütlesi örgü QCD hesaplarından öngörülmüştür; bu, çerçevenin henüz yapamadığı işin ölçütüdür — yapılmış işin değil.

## 20.10 "Doku düğümü" ve SU(3) türetimi sorusu

Renk hapsinin faz-kısıt diliyle okunması (25.8) güçlü bir adaydır; ama SU(3) ayar yapısının kendisinin faz topolojisinden türetilip türetilemeyeceği açıktır. "Doku düğümü" terimi arşivde bu soruyu adlandırmak için kullanılmıştır; ontolojik bir terim değildir.

## 20.11 Üç nesil ve kütle hiyerarşisi sorusu

Üç nesil yapısının ve fermiyon kütle hiyerarşisinin faz yapısından türetilip türetilemeyeceği sorusu açıktır. Ölçülmüş hiyerarşi çok geniştir: üst kuarkın elektrona kütle oranı yaklaşık $3.4\times10^{5}$, en ağır nötrinoya oranı ise $10^{12}$ mertebesindedir; salınım verisi en ağır nötrino kütlesine bir **alt sınır** koyduğu için bu oranı **yukarıdan** sınırlar.

$$\frac{m_t}{m_e}\approx\frac{172.7\ \mathrm{GeV}}{0.511\ \mathrm{MeV}}\approx3.4\times10^{5},\qquad m_{\nu,\max}\gtrsim0.05\ \mathrm{eV}\ \Rightarrow\ \frac{m_t}{m_{\nu,\max}}\lesssim\frac{172.7\ \mathrm{GeV}}{0.05\ \mathrm{eV}}\approx3.5\times10^{12}$$

```latex
\frac{m_t}{m_e}\approx\frac{172.7\ \mathrm{GeV}}{0.511\ \mathrm{MeV}}\approx3.4\times10^{5},\qquad m_{\nu,\max}\gtrsim0.05\ \mathrm{eV}\ \Rightarrow\ \frac{m_t}{m_{\nu,\max}}\lesssim\frac{172.7\ \mathrm{GeV}}{0.05\ \mathrm{eV}}\approx3.5\times10^{12}
```

| Sembol | Anlamı |
|---|---|
| $m_t$ | Üst (top) kuark kütlesi |
| $m_e$ | Elektron kütlesi |
| $m_{\nu,\max}$ | En ağır nötrinonun kütlesi, $\max(m_{\nu_1},m_{\nu_2},m_{\nu_3})$ (bilinmiyor). Normal sıralamada $\nu_3$, ters sıralamada $\nu_2$'dir; sınır iki sıralamada da geçerlidir |
| $0.05\ \mathrm{eV}$ | Salınım verisinden (atmosferik kütle farkı) gelen alt sınır: $m_{\nu,\max}\gtrsim\sqrt{\vert\Delta m^2_{\rm atm}\vert}\approx0.05$ eV |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Açıklanması gereken kütle hiyerarşisinin büyüklüğünü sayısal olarak koyar |
| **Neden yapıyor?** | Bir türetim iddiasının hangi aralığı kapsaması gerektiğini açık kılmak için |
| **Nasıl yapıyor?** | Ölçülmüş kütlelerin oranlarını alır |
| **Ne sonuç bekleniyor?** | Faz yapısından üç nesil ve bu oranların çıkması |
| **Ne sonuç elde ediliyor?** | Sayılar ölçülmüş bağlamdır, öngörü değildir. Arşivdeki farklı yoğunluk düzeyleri için değişen faktör önerisi (1, 20, 1836; 1, ~200, 3500) tablo kaydı olarak korunur — sayısal eşleşme türetim değildir. Minor12'deki "~10⁵⁵–10¹⁷" mertebe yazımı ölçülmüş kütle oranlarıyla uyumsuz olduğu için editoryal olarak düzeltilmiştir |

## 20.12 QED süreç genliği uyum sorusu

Feynman çizgelerinin çerçeve içinde yeniden okunmasının, ölçülmüş süreç genlikleriyle uyum koşulu altında yapılıp yapılamayacağı sorusu açıktır. Bu soru, makine programının (20.4) kapanmamış uçlarından biridir.

---




# BÖLÜM 21 — AMPİRİK DURUM VE DENETİM

## 21.1 Kapatılmış hat

Çerçevenin bir dönem en güçlü ampirik iddiası, farklı fiziksel alanlardan gelen verilerin yüzdelik hizalama yoluyla karşılaştırılmasıydı. Çok yüksek korelasyon değerleri elde edilmişti.

**Bu hat, iç denetimle kalıcı olarak kapatılmıştır.**

### Üç kök hata

| # | Hata | Onarılabilir mi |
|---|---|---|
| 1 | Veri zamana göre değil değere göre sıralanmış | Evet |
| 2 | **Fiziksel ortak anahtar yok** | **Hayır — yapısal** |
| 3 | Permütasyon testi yanlış soruyu sınamış | Evet |

### Yapısal sonuç

Sıralama ve sözde eşleştirme işlemi, fiziksel bir ortak anahtar yokken bile güçlü görsel ve korelasyon yapısı üretebilir. Bu yüzden yüksek korelasyon **tek başına** ortak, gizli bir fiziksel koordinatın kanıtı değildir.

Denetimde düzeltilmiş sıfır / permütasyon koşusu ilgili iddiayı desteklememiştir. Arşiv aktarım kaydında düzeltilmiş koşu için $p\approx0.530$ (BAŞARISIZ) raporlanır; bu sayı **arşivde raporlanmış** statüsündedir ve ham koşu kaynağıyla bağımsız son teyit bekler. Yapısal sonuç değişmez: çok alanlı Xa / Xz / Xt hattı **ampirik kanıt statüsünden kalıcı olarak çıkarılmıştır**.

### Dil yasağı

$$\boxed{\;\text{Bu hat için "kanıtlandı", "kilitli", yüksek-sigma ifadeleri KULLANILAMAZ. Emekli sabitler GERİ GETİRİLEMEZ.}\;}$$

```latex
\boxed{\;\text{Bu hat için "kanıtlandı", "kilitli", yüksek-sigma ifadeleri KULLANILAMAZ. Emekli sabitler GERİ GETİRİLEMEZ.}\;}
```

## 21.2 Yön değişikliği

$$\boxed{\;\text{"Veride korelasyon ARA" DEĞİL — "ARALIK TÜRET, sonra KARŞILAŞTIR".}\;}$$

```latex
\boxed{\;\text{"Veride korelasyon ARA" DEĞİL — "ARALIK TÜRET, sonra KARŞILAŞTIR".}\;}
```

Beş adımlı protokol şudur:

| # | Adım |
|---|---|
| 1 | Verisi olan, birimli, tek bir hedef nicelik seç |
| 2 | Zinciri yaz ve **serbest parametreleri say** |
| 3 | Aralığı türet — önselden dar |
| 4 | **ÖN KAYIT yap — veriye bakmadan** |
| 5 | Karşılaştır |

Kapanan hat tam da dördüncü adımda kaybetti.

### Şu anki birincil doğrulama alanı

$$\boxed{\;\text{Birincil etkin alan çoklu alan korelasyonu DEĞİL; "aralık türet, sonra karşılaştır" protokolleridir.}\;}$$

```latex
\boxed{\;\text{Birincil etkin alan çoklu alan korelasyonu DEĞİL; "aralık türet, sonra karşılaştır" protokolleridir.}\;}
```

Nükleer bağlanma enerjisi zarf modülasyonu, bu protokolün ilk somut uygulama adayıdır (Bölüm 22).

## 21.3 Veri kökeni mühürlenmelidir

$$\boxed{\;\text{"Önceden mühürledik" TEK BAŞINA YETERSİZDİR. VERİ SOYAĞACI da mühürlenmelidir.}\;}$$

```latex
\boxed{\;\text{"Önceden mühürledik" TEK BAŞINA YETERSİZDİR. VERİ SOYAĞACI da mühürlenmelidir.}\;}
```

Mühürlenecekler: öngörüyü üreten parametreleri belirleyen kayıtlar · hedef seçimi · veri sürümü · varsa ayrılmış test kümesi. Aksi hâlde "kör görünen" ama aslında kör olmayan bir test elde edilir.

## 21.4 Mevcut ampirik varlıklar

Elde olanlar Evertophy **üzerine konan kısıtlardır**: zayıf alan testleri, atomik saat karşılaştırmaları, kütleçekim sabiti değişim sınırları, kozmolojik spektroskopi.

$$\boxed{\;\text{Hiçbiri Evertophy'nin ÖNGÖRÜSÜ DEĞİLDİR.}\;}$$

```latex
\boxed{\;\text{Hiçbiri Evertophy'nin ÖNGÖRÜSÜ DEĞİLDİR.}\;}
```

## 21.5 Yanlışlama araçları

### Hızlı ret eşikleri

Bir **destek ya da öngörü iddiası** şu durumlarda **derhal reddedilir** (modelin ya da model ailesinin çürütülmesi ayrı bir hükümdür, 21.7):

- Türetilen aralık gözlem aralığıyla kesişmiyorsa
- Kör testte iddia edilen etkinin istatistiksel anlamlılığı sağlanamıyorsa (iddia reddedilir; bu, modelin çürütüldüğü anlamına gelmez)
- Bilinen yapıyı (ölçülmüş kabuk konumları gibi) silen ya da kaydıran bir sonuç veriyorsa
- Veri görüldükten sonra bir katsayı eklenmişse
- Etkin bir kısıt ihlal ediliyorsa

### Erken başarısızlık S1 — arşivden çıkarılmış aday protokol

Aşağıdaki eşikler ontoloji postülası ya da Evertophy öngörüsü değildir; ileride önceden kaydedilecek model koşuları için **yöntemsel aday** olarak korunur:

| Denetim | Aday karar kuralı |
|---|---|
| Arka plan uyumu | $\chi^2_{\rm red}\le1.2$ kabul bölgesi; $1.2$–$1.5$ uyarı; $>1.5$ sert ret |
| Yapı büyümesi | $\Delta\chi^2_{\rm growth}\le0$ beklenir |
| Kararlılık | Hayalet / gradyan / takyon patolojisi → anında ret |
| Etkin Planck kütlesi | $M_*^2\le0$ → ret |
| Saat / sabit çapraz denetimi | $\Delta\alpha$ ile uyumsuzluk → ret |
| Pencere kararlılığı | Pencereler arası $\Delta\chi^2\le3$; $>5$ sert fren |
| Serbestlik maliyeti | Yeni parametre başına iyileşme $<2$ ise şişme uyarısı |
| Etkin alan kuramı yorumu | $\alpha_M$ türetilmeyip serbest bırakılıyorsa genel görelilik sonrası eşik sinyali sayılır |
| Güçlü alan | EHT / kütleçekim dalgası sonucu "ufuk" değil, doğrulandığı kapsamda "ufuk yakını" diliyle raporlanır |

| Sembol | Anlamı |
|---|---|
| $\chi^2_{\rm red}$ | Serbestlik derecesine bölünmüş ki-kare (indirgenmiş uyum ölçüsü) |
| $\Delta\chi^2_{\rm growth}$ | Yapı büyümesi verisinde referans modele göre ki-kare farkı |
| $M_*^2$ | Etkin Planck kütlesinin karesi |
| $\Delta\alpha$ | İnce yapı sabitindeki bağıl değişim |
| $\alpha_M$ | Etkin Planck kütlesinin akış oranı (etkin alan kuramı parametresi) |

Bu sayılar önceden kaydedilmeden kanonik eşik değildir. Aynı nedenle arşivdeki $r_{\rm global}<0.5$ eşiği de **yöntemsel adaydır**; veri görüldükten sonra kurtarma sınırı olarak kullanılamaz.

Üç gözlem protokolü araştırma programında saklanır: çok sondalı eşzamanlılık (BAO / $f\sigma_8$ / merceklenme kalıntı kırılmalarının aynı $z$ çevresinde kümelenmesi), faz duvarı sigmoid biçiminin pürüzsüz CPL'den ayrılması ve maskelenmiş yerellik. Bunlar **öngörü değil, yanlışlama köprüsü tasarımlarıdır**; 0.4'teki altı koşul sağlanmadan 0/10 sayacını değiştirmez.

### Geniş kanon iyileştirme uyarısı — model notu

Çok modlu bir sonsal dağılım tek başına patoloji ya da modelin yanlışlığı değildir. Patoloji hükmü; tanımlanamazlık, dal seçimi, veri sonrası iyileştirme, kararsızlık ya da fiziksel olarak kabul edilemez modlar gibi ek ölçütler gerektirir. Bu not "en iyi modu seçip raporlama" yetkisi vermez; dal alışverişi yasağı ve en kötü durum raporlaması aynen geçerlidir.

### Kesişim ölçüsü

Öngörü ve gözlem aralıklarının örtüşme oranı bir ölçüt olarak kullanılabilir.

$$\boxed{\;\text{Bu ölçüt bir MODEL KURTARMA aracı DEĞİL, yanlışlamanın parçasıdır.}\;}$$

```latex
\boxed{\;\text{Bu ölçüt bir MODEL KURTARMA aracı DEĞİL, yanlışlamanın parçasıdır.}\;}
```

### En kötü durum raporlaması

$$\boxed{\;\text{Uyumu YALNIZ EN İYİ DURUMLA raporlamak YASAKTIR. Uyum EN KÖTÜ kabul edilebilir durumla birlikte raporlanır; aile reddinde en iyi üye (inf) kullanılır.}\;}$$

```latex
\boxed{\;\text{Uyumu YALNIZ EN İYİ DURUMLA raporlamak YASAKTIR. Uyum EN KÖTÜ kabul edilebilir durumla birlikte raporlanır; aile reddinde en iyi üye (inf) kullanılır.}\;}
```

Yeni parametre başına uyum iyileşmesi belirli bir eşiğin altındaysa, model **serbestlik satın alıyordur**.

### Eleme anahtarı aileleri

| Aile | Örnek |
|---|---|
| **Ontoloji** | $U_0$'ın dördüncü faz gibi kullanılması → ret |
| **Ontoloji** | c⁺'a doğrudan metrik atfedilmesi → sert çelişki |
| **Gösterim** | Tarihsel çekirdeğin güncel $X$ yerine kullanılması → ret |
| **Veri** | Veri sızıntısı → yayın eleme |
| **Öngörü** | Kesişim ölçüsü sürekli düşük → öngörü reddi |
| **Aşırı uyum** | Aralık şişirme → eleme |
| **Köprü** | Köprü hattı desteklenmezse → yumuşak eleme |
| **Araç** | Bir aracın kendi çıktısını kanon ilan etmesi → çıktı reddi |

---

## 21.6 Aralık kesişim ölçüsü ve kalibrasyon disiplini

İki aralığın örtüşmesini nicelleştirmek için IOM benzeri bir ölçü kullanılabilir:

$$\mathrm{IOM}(B_{\rm pred},B_{\rm obs})=\frac{\mu(B_{\rm pred}\cap B_{\rm obs})}{\mu(B_{\rm pred}\cup B_{\rm obs})},\qquad \mu(B_{\rm pred}\cup B_{\rm obs})>0$$

```latex
\mathrm{IOM}(B_{\rm pred},B_{\rm obs})=\frac{\mu(B_{\rm pred}\cap B_{\rm obs})}{\mu(B_{\rm pred}\cup B_{\rm obs})},\qquad \mu(B_{\rm pred}\cup B_{\rm obs})>0
```

$$\mathrm{Compat}(B_{\rm pred},B_{\rm obs})=\mathbf 1\big[B_{\rm pred}\cap B_{\rm obs}\neq\varnothing\big]\qquad(\text{her bant için; nokta aralıklar dahil})$$

```latex
\mathrm{Compat}(B_{\rm pred},B_{\rm obs})=\mathbf 1\big[B_{\rm pred}\cap B_{\rm obs}\neq\varnothing\big]\qquad(\text{her bant için; nokta aralıklar dahil})
```

Sert ret ölçütü ise şudur:

$$\text{Sert ret} \iff B_{\rm pred} \cap B_{\rm obs} = \varnothing$$

```latex
\text{Sert ret} \iff B_{\rm pred} \cap B_{\rm obs} = \varnothing
```

| Sembol | Anlamı |
|---|---|
| IOM | Aralık örtüşme ölçüsü (genişlik tabanlı Jaccard oranı); yalnız birleşimin genişliği pozitifken tanımlıdır |
| $\mu$ | Seçilen genişlik ölçüsü (aralık uzunluğu) |
| $\mathrm{Compat}$ | Uyumluluk göstergesi: kesişim boş değilse 1, boşsa 0 |
| $\mathbf 1[\cdot]$ | Gösterge fonksiyonu |
| $B_{\rm pred}$, $B_{\rm obs}$ | Öngörü ve gözlem bantları |
| $\vert\cdot\vert$ | Seçilen ölçüye göre bant genişliği |
| $\cap$, $\cup$ | Kesişim ve birleşim |
| $[P,P]$ | Sıfır genişlikli (nokta) aralık |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Öngörü ile gözlem bandının ne kadar örtüştüğünü ölçer ve sert ret koşulunu tanımlar |
| **Neden yapıyor?** | Bir modelin reddedilip reddedilmeyeceğine sayısal ve önceden belirlenmiş bir kuralla karar vermek için |
| **Nasıl yapıyor?** | Kesişim genişliğini birleşim genişliğine böler; reddi yalnız kesişimin boş olmasına bağlar |
| **Ne sonuç bekleniyor?** | Pozitif genişlikli bantlar için tanısal bir uyum skoru; ayrık bantlar için kesin ret |
| **Ne sonuç elde ediliyor?** | **Sert ret yalnız boş kesişimde** geçerlidir (★ kanıtlanmış). IOM ile sert ret **yanlıştır**: sıfır genişlikli bir öngörü $[P,P]$ gözlem bandının içindeyse IOM yine 0 çıkar, ama öngörü **dışlanmamıştır**. Önceki sürümdeki "IOM = 0 ise reddedilir" ifadesi bu yüzden düzeltilmiştir |

**Nokta aralıklar.** İki bant da $[P,P]$ biçiminde olduğunda pay ve payda sıfırdır ve IOM $0/0$ olarak tanımsızdır. Bu durumda yalnız uyumluluk göstergesi $\mathrm{Compat}$ kullanılır; $[P,P]$ tamamen geçerli bir Range değeri olarak kalır. Sert ret ölçütü ($\mathrm{Compat}=0$, yani boş kesişim) bütün bant türlerinde aynı biçimde yazılır.

**Bant türleri.** Boş kesişimin kesin ret anlamına gelmesi, bantların türüne bağlıdır. Garantili kapsama bantlarında ($B_{\rm kesin}$) boş kesişim mantıksal rettir; güven bölgelerinde ($B_{1-\alpha}$) ve Bayesçi inanç bölgelerinde ($B_{\rm inanç}$) boş kesişim, **belirtilen belirsizlik modeli ve test düzeyinde ret** olarak raporlanır. Örneğin %16–84 kantillerinden kurulmuş bir gözlem bandıyla boş kesişim, otomatik olarak kesin yanlışlama değildir. Bant türü ön kayıtta belirtilir.

Bu sayı **evrensel bir fizik yasası değildir**. Arşivde farklı koşularda 0.5 / 0.6 / 0.8 gibi pratik ya da taslak eşikler görülür; ayrıca tarihsel kozmolojik uyum standardında $\mathrm{IOM}\ge0.7$ ve $\chi^2_{\rm range}\le1.2$ **kilitli koşu eşiği** olarak kaydedilmiştir. 0.7 değeri evrensel bir ontoloji sabiti değildir; son eşik veri türüne, hata modeline ve önceden kaydedilmiş test protokolüne göre kalibre edilmelidir. Temel anlam değişmez:

- Yüksek IOM yalnız uyum gösterir; doğrulama değildir.
- Öngörü bandını sonradan genişleterek IOM'u artırmak **aşırı uyumdur**.

## 21.7 En kötü durum uyumu ve serbestlik maliyeti

Aralık değerli bir model yalnız "en iyi nokta" üzerinden raporlanmamalıdır. Uyum, önceden kaydedilmiş bandın **en kötü kabul edilebilir** davranışıyla da değerlendirilir. Bir $\chi^2$ ya da olabilirlik ölçütünde yeni parametre eklenmesi küçük bir iyileşme sağlıyorsa, iyileşme model serbestliğinin maliyetini aşmak zorundadır. Arşivde kullanılan "yeni parametre başına $\Delta\chi^2$" kuralları **yöntemsel adaydır**, evrensel eşik değildir.

### Denklem seti — KAP-09: aile reddi ve aralık χ²

$$\chi^2(\theta) = \sum_i\left[\frac{y_i - f_i(\theta)}{\sigma_i}\right]^2, \qquad \text{aile reddi} \iff \inf_{\theta\in\Theta}\chi^2(\theta) > T, \qquad d\big(y, [l,h]\big) = \max(l - y,\ 0,\ y - h)$$

```latex
\chi^2(\theta) = \sum_i\left[\frac{y_i - f_i(\theta)}{\sigma_i}\right]^2, \qquad \text{aile reddi} \iff \inf_{\theta\in\Theta}\chi^2(\theta) > T, \qquad d\big(y, [l,h]\big) = \max(l - y,\ 0,\ y - h)
```

| Sembol | Anlamı |
|---|---|
| $y_i$ | $i$. gözlem değeri |
| $f_i(\theta)$ | Modelin $\theta$ parametreleriyle $i$. gözlem için öngörüsü |
| $\sigma_i$ | $i$. gözlemin belirsizliği |
| $\theta$, $\Theta$ | Ortak parametre vektörü ve izinli kümesi |
| $\inf$ | En büyük alt sınır (ailenin en iyi uyumu) |
| $T$ | Ret eşiği |
| $d(y,[l,h])$ | Bir noktanın $[l,h]$ bandına en yakın uzaklığı (bandın içindeyse sıfır) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bir model ailesinin bütünüyle ne zaman reddedileceğini tanımlar ve noktanın banda uzaklığını verir |
| **Neden yapıyor?** | Tek bir üyenin başarısızlığının bütün aileyi reddettiren yanlış kuraldan kaçınmak için |
| **Nasıl yapıyor?** | Aileyi ancak en iyi üyesi bile eşiği aşıyorsa reddeder; bant uzaklığını aralığın dışında kalan miktar olarak ölçer |
| **Ne sonuç bekleniyor?** | Model ailelerinin adil ve sağlam bir kuralla değerlendirilmesi |
| **Ne sonuç elde ediliyor?** | Aile reddinde **inf kuralı doğrudur**; **sup kuralı yanlıştır** |

### Aile reddi ile en kötü uyum

Bir model ailesinde tek bir parametre seçiminin başarısızlığı, bütün ailenin başarısızlığı değildir. **En iyi uyum**, ailenin tümüyle reddedilip reddedilemeyeceği için; **en kötü uyum**, parametre belirsizliği karşısındaki sağlamlık için önemlidir. İkisi birlikte raporlanabilir, ama birbirinin yerine geçmez; 21.5'teki en kötü uyum disiplini aile reddi ölçütünü bozmaz. İstatistiksel olarak anlamlı sonuç bulunmaması otomatik çürütme değildir; veriyle uyum da "öngörü doğrudur" değil, **"belirtilen testte dışlanmadı"** olarak yazılır.

## 21.8 Eleme anahtarı sınıfları

| Sınıf | Neyi eler | Örnek |
|---|---|---|
| Ontoloji sert eleme | Çekirdek tip ihlali | $U_0$'ı dördüncü faz yapmak; c⁺'a metrik atamak |
| Köprü yumuşak eleme | Köprü hattı | $\chi_S$ kütleçekimle bağlanmazsa kanal köprüsü kapanır |
| Veri eleme | Testin geçerliliği | Veri sızıntısı / yanlış soyağacı |
| Yöntem eleme | İstatistik protokolü | Yanlış sıfır modeli, sözde eşleştirme |
| Aşırı uyum eleme | Öngörü iddiası | Veri sonrası bant şişirme / katsayı ekleme |
| Yayın eleme | İddia statüsü | Kör olmayan sonucu kör öngörü diye sunmak |
| Araç / yapay zekâ eleme | Kaynak | Aracın kendi üretimini "kanıt" ilan etmesi |

Eleme anahtarı, her başarısız köprüyle çekirdek ontolojiyi yok etmez; **hangi katmanın reddedildiğini** açıkça belirtir.

## 21.9 Hata sınıfları — F / C / R

Eleme sonuçları aynı epistemik ağırlıkta değildir:

| Sınıf | Anlamı | Sonuç |
|---|---|---|
| **F — Ölümcül** | Çekirdek programı durduran yapısal hata | İlgili temel yapı kapanmadan program ilerlemez |
| **C — Düzeltilebilir** | Katsayı, limit, ölçek ya da benzeri onarılabilir hata | Revizyon yapılır; program devam eder |
| **R — Geri çekilebilir** | Belirli bir gerçekleme / pencere / rota geri çekilir | Kuram otomatik olarak ölmez; rota bilgisi üretilir |

Tarihsel F sınıfı dört çekirdek örnekle kaydedilmiştir: aynı varsayımdan doğrudan çelişki; gerekçesiz nedensellik ihlali; temel kavramın matematiksel olarak tanımsız kalması; geri çekme / erken başarısızlık mekanizmasının kendisinin işlememesi. Bu liste **her başarısız deneyin F olduğu** anlamına gelmez.

$$\boxed{\;\text{ERKEN BAŞARISIZLIK}\neq\text{TOPTAN BAŞARISIZLIK}\;}$$

```latex
\boxed{\;\text{ERKEN BAŞARISIZLIK}\neq\text{TOPTAN BAŞARISIZLIK}\;}
```

Eski Xa / Xz / Xt ampirik hattının geri çekilmesi ve belirli köprü testlerinin başarısızlığı, aksi ayrıca gösterilmedikçe **R sınıfı** düzeyinde okunur. Bir R başarısızlığı, çekirdek ontolojinin deneysel olarak doğrulandığı anlamına da gelmez.

## 21.10 Zaman serisi kanıt protokolü v0.5

Zaman serisi çözümlemesinde kayıtlı protokol dört aşamalıdır: normalizasyon → kalıntı çıkarımı → çapraz korelasyon → beyaz gürültü testi. Bir kayıt-mühürleme imzasının bu protokolle nasıl sınanacağı açık bir araştırma sorusudur; protokolün sayısal eşikleri henüz kaynakta tanımlanmamıştır.

## 21.11 H(z) gerçek Pantheon+ çözümlemesi — Evertophy ve ΛCDM

Kaynakta kayıtlı tarihsel bir koşu, Evertophy okumasını ΛCDM ile $H(z)$ verisi üzerinden karşılaştırmıştır:

$$\chi^2_{\min}=204.7\quad(\gamma=+0.328,\ n=300),\qquad \chi^2/\text{dof}=0.685,\qquad \Delta\chi^2=+2.7$$

```latex
\chi^2_{\min}=204.7\quad(\gamma=+0.328,\ n=300),\qquad \chi^2/\text{dof}=0.685,\qquad \Delta\chi^2=+2.7
```

| Sembol | Anlamı |
|---|---|
| $\chi^2_{\min}$ | En iyi uyumdaki ki-kare |
| $\gamma$ | Koşudaki Evertophy okuma parametresi |
| $n$ | Veri noktası sayısı |
| dof | Serbestlik derecesi |
| $\Delta\chi^2$ | Evertophy ile ΛCDM arasındaki ki-kare farkı (pozitif: Evertophy lehine değil) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Evertophy okumasının genişleme geçmişi verisine ΛCDM'den daha iyi uyup uymadığını sınar |
| **Neden yapıyor?** | Kozmolojik bir okuma iddiasını standart modelle aynı veri üzerinde karşılaştırmak için |
| **Nasıl yapıyor?** | Her iki model için ki-kare uyumunu hesaplar ve farkını alır |
| **Ne sonuç bekleniyor?** | Ön kayıtlı bir koşuda ayırt edici bir fark |
| **Ne sonuç elde ediliyor?** | Bu koşuda **Evertophy lehine bir üstünlük yoktur.** Kayıt kendi vekil (proxy) uyarılarını taşır: Pantheon+ doğrudan bir $H(z)$ tablosu değil, Tip Ia süpernova uzaklık verisidir; doğrudan karşılaştırma için yeniden kurma adımı ve tam kovaryans gerekir. Ön kayıtlı yenileme açık bir görevdir. Sayaç 0/10 |

## 21.12 Üçlü CDF Q-Align ve φ-manifold PCA testi

Üçlü birikimli dağılım (X, z, t) Q-Align korelasyonu ve Φ-manifold temel bileşen çözümlemesi testinin koşuları arşivde korunur. Bütünüyle anonimleştirilmiş üst koşularda bile anlamlı sapmaların gözlendiği raporlanır; ama 21.1'in yapısal hatası (fiziksel ortak anahtar yokluğu) bu hatları da sınırlar. Bütün koşular denetim borcuna tabidir — kanıt statüsü yoktur.

## 21.13 Sıfır model testleri — C1–C5 ve genişletmeler

| Test | İçerik |
|---|---|
| C1 | Zamana bağlı ağırlık |
| C2 | Üç bileşenli rastgele doku |
| C3 | Sabit faz farkı |
| C4 | Düz evren ($a(t) = H_0t$) |
| C5 | Sabit ses hızı |

Hiçbir sıfır model Evertophy'yi reddetmez; ama hiçbiri onu desteklemez de. Sıfır kümesinin görevi "beklenen başarısızlıkları" önceden tanımlamaktır. Genişletme sıfır modelleri (karıştırılmış frekans, belirlenimci faz, yalnız gürültü, sabit tohum) arşivde tam listelenmiştir.

## 21.14 Yıkım testi kümesi D1–D5

| Test | Kırılganlık |
|---|---|
| D1 | Parametre kaldırma |
| D2 | Sabit değiştirme |
| D3 | Fiziği bozma |
| D4 | Gürültü ekleme |
| D5 | Şema değişimi |

D kümesinin amacı, başarının fizikten mi yoksa sayısal ayardan mı geldiğini ayırt etmektir. Bir bulgunun D testlerinden geçmemesi, onun öngörü değil uydurma olduğunu gösterir.

## 21.15 Histerezis ve yenileme hızı yanlışlama protokolü

Faz geçişinde beklenen histerezis / yenileme hızı imzaları için tasarlanmış testler arşivde korunur: ileri / geri rampa, bekleme süresi denemeleri, frekans taraması histerezisi. Bu testler öngörü değildir; köprü hattı desteklenirse uygulanacak protokollerdir.

## 21.16 Metrik dışılık histerezis testi

Weibel / bağlantı anizotropisi ($k_\parallel$ ve $k_\perp$) ve metrik dışılık (non-metricity) kaynaklı histerezis izlerinin aranması tasarımıdır. Kozmik manyetizma araştırmalarının bulguları (evrensel manyetik alanlar için ~100 kpc en küçük ölçek) bağlam olarak işlenmiştir.

## 21.17 Gözlemsel anomali kataloğu ve beş anomali stres testi

Kaynakta kayıtlı beş stres testi alanı şunlardır: $z>10$ erken galaksiler, Hubble gerilimi, "Kötülük Ekseni" (Axis of Evil), karanlık madde – MOND tartışması ve "Küçük Kırmızı Noktalar" (Little Red Dots). Bunlar Evertophy'nin sınanmak istediği alanlardır; hiçbiri için bir Evertophy açıklaması ya da öngörüsü kurulmuş değildir. Hubble gerilimi için çerçevenin önceki iddiası üç kez geri çekilmiştir.

## 21.18 Kozmik çift kırılma — yöntem notu

Kozmik çift kırılma için kayıtlı not yalnız yöntemseldir: faz belirsizliği ve morfoloji. Gözlemsel açı değerleri ve anlamlılık düzeyleri doğrudan makale atfıyla desteklenene kadar bu belgede kullanılmaz. Sinyalin Evertophy okumasıyla ilişkisi açık bir araştırma sorusudur.

## 21.19 Faz içi dalga imza test kartı (önceden kayıtlı)

Faz içi dalgalar (IPW) hattının önceden kayıtlı test kartı: $X_T$ spektral ayrışma imzası için parametre uzayı $(A, \omega, \varphi, \mathrm{FWHM}, \rho)$ tanımlıdır; koşul başarısız olursa hat kapanır. Ön kayıt, bu hattın kanıt statüsü kazanmasının tek yoludur.

## 21.20 BEC / süper-atom laboratuvar paketi — üç yanlışlanabilir öngörü

| Öngörü | Gözlem | Zaman penceresi | Statü |
|---|---|---|---|
| Gauss dışı ön donma imzası | İki boyutlu gazda | 1–5 yıl | Açık |
| Faz duvarı sigmoidi ile CPL'nin ayrışması | Kozmik | 5–10 yıl | Açık |
| Çok sondalı eşzamanlılık (BAO / $f\sigma_8$ / merceklenme) | Kozmik | 10–15 yıl | Açık |

Hiçbiri henüz 0/10 → 1/10 kapısının altı koşulunu sağlamamıştır (0.4). Paketin adındaki BEC, c₀'ın kendisi değil, **madde fazında c₀ ortamına en yakın ortamdır** (18.5); laboratuvar sonuçları c₀ hakkında doğrudan değil, bu yakınlık üzerinden okunur.

**Ek ön kayıt — Page köşesi (düşünce deneyi).** 2026-10-13 tarihli bir düşünce deneyinde, c₀ kapasitesinin kütleyle ölçeklendiği yazar tanımlarından ($N=M/m_P$, Bölüm 3) ve V24 §736'daki ek tanımlarla (Y1–Y3) — $N$ tek başına Hilbert uzayı boyutunu, entropiyi ya da korelasyon eğrisini belirlemez —, kara delikten kütle çıkışı sırasında dışarı ile çekirdek arasındaki ölçülebilir korelasyon için standart fizikten ayrışan bir eğri sınıfı türetilmiş ve veriden önce dondurulmuştur (V24 §736). Bugün test platformu yoktur; ön kayıt 0/10 → 1/10 kapısının altı koşulunu sağlamaz ve sayacı değiştirmez.

## 21.21 Laboratuvar protokol taslağı v0.1 ve faz seçici pencere

Mikrodalga / atom fiziği kesişim hatları için tasarım kayıtları: malzeme kayıpları, kalibrasyon, karşılıklılık denetimleri, faz seçici süzgeç pencereleri. Bütünü test tasarımıdır; deneysel sonuç değildir.

## 21.22 Optik saat kararsızlığı kanalı (Yb / Sr)

Al⁺ saatleriyle ~$10^{-18}$ mertebesinde kesirli frekans belirsizliği raporları bağlam olarak korunur; çerçevenin kendi saat karşılaştırma protokolü buradan doğrudan sayı almaz — bunları dış kısıt olarak kullanır.

## 21.23 Veri kümesi kilitleri — AME2020 / Pantheon+ / frekans oranları

Kullanılan dış veri kümeleri için arşiv kilit kayıtları: AME2020 (22.5'teki Katı Kör Soyağacı ile birlikte), Pantheon+ (21.11), optik frekans oranları (21.22).

$$\boxed{\;\text{Bir veri kümesinin aynı anda hem kalibrasyon hem kör doğrulama kaynağı olması yasaktır (22.5).}\;}$$

```latex
\boxed{\;\text{Bir veri kümesinin aynı anda hem kalibrasyon hem kör doğrulama kaynağı olması yasaktır (22.5).}\;}
```

---

## 21.24 Arşivdeki sayısal okumalar

Arşivde yirmiyi aşkın sayısal okuma bulunur — örneğin kararlılık adaları ve $10^{40}$, $10^{120}$ mertebesindeki büyük sayılar. Bunların hiçbiri önceden kayıtlı, ayırt edici bir öngörü değildir; envanteri ve her birinin statüsü V24 yürüyen ana kaydında (§686) tutulur. Bir sayısal okumanın öngörü sayılması için ayırt edici olması, eleme koşuluyla önceden kaydedilmesi ve kaynak türetiminin gösterilmesi gerekir. Sayaç 0/10.

# BÖLÜM 22 — NÜKLEER KÖPRÜ PROTOKOLÜ

Bu bölüm, "aralık türet, sonra karşılaştır" protokolünün ilk somut uygulama tasarımını anlatır.

## 22.1 Hedef

Hedef, nükleer bağlanma yapısındaki **kabuk gücü modülasyonudur**. Yani kabukların *nerede* olduğu değil, *ne kadar güçlü* oldukları ve bu gücün kütleyle nasıl değiştiği.

## 22.1a Nükleer köprü zinciri — koşullu yapısal aday

Nükleer programın hedef zinciri, ayrı bir temel $X_A$ varlığı gerektirmeden bir alan okumasıyla yazılabilir:

$$[X_A]\equiv[\Pi_A(X)],\qquad [X_A],[\Delta_{ij}]\longrightarrow[Z_G]\longrightarrow[\alpha_s(Q)]\longrightarrow\mathcal F_{\rm nuc}\longrightarrow[\Delta_{\rm kabuk}]_{\rm pred}$$

```latex
[X_A]\equiv[\Pi_A(X)],\qquad [X_A],[\Delta_{ij}]\longrightarrow[Z_G]\longrightarrow[\alpha_s(Q)]\longrightarrow\mathcal F_{\rm nuc}\longrightarrow[\Delta_{\rm kabuk}]_{\rm pred}
```

| Sembol | Anlamı |
|---|---|
| $[\cdot]$ | Aralık (Range) değeri |
| $\Pi_A$ | $X$'in atom / çekirdek bağlamındaki izdüşümü |
| $X_A$ | Nükleer bağlam okuması (ayrı bir temel $X$ değil) |
| $\Delta_{ij}$ | Faz kenarları |
| $Z_G$ | Renk ayar alanının kinetik katsayısı |
| $\alpha_s(Q)$ | $Q$ enerji ölçeğindeki güçlü bağlaşım |
| $\mathcal F_{\rm nuc}$ | Nükleer köprü fonksiyonu |
| $[\Delta_{\rm kabuk}]_{\rm pred}$ | Kabuk boşluğu için öngörü bandı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Faz yapısından nükleer kabuk boşluğunun öngörü bandına giden zinciri yazar |
| **Neden yapıyor?** | "Aralık türet, sonra karşılaştır" protokolünü ölçülmüş, birimli ve verisi bol bir nicelikte uygulamak için |
| **Nasıl yapıyor?** | $X$'in nükleer okumasından renk sektörü kinetik katsayısına, oradan güçlü bağlaşıma, köprü fonksiyonuna ve kabuk boşluğuna gider |
| **Ne sonuç bekleniyor?** | Önceden kaydedilmiş dar bir kabuk boşluğu bandı |
| **Ne sonuç elde ediliyor?** | Her ok **türetilmesi gereken bir köprüdür**; zincirin yazılmış olması öngörü değildir. $X_A$, denetimde başarısız olmuş eski $X_a$ korelasyon değişkeninin yeniden kanonlaştırılması değildir; yalnız güncel tek-$X$ ontolojisi içindeki bağlam izdüşümü gösterimidir. Protokol mimarisi koşullu olarak kurulabilirken temelden nükleere türetim **açıktır** |

## 22.2 İki katmanlı ansatz

$$[\Delta_{\rm kabuk}]_{\rm ET} \;=\; [\mu_A] \;\odot\; [\Delta_{\rm kabuk}]_{\rm yapı}$$

```latex
[\Delta_{\rm kabuk}]_{\rm ET} \;=\; [\mu_A] \;\odot\; [\Delta_{\rm kabuk}]_{\rm yapı}
```

| Sembol | Anlamı |
|---|---|
| $[\Delta_{\rm kabuk}]_{\rm ET}$ | Evertophy'nin kabuk boşluğu bandı |
| $[\mu_A]$ | Kütle numarasına ($A$) bağlı zarf modülasyon bandı (Evertophy) |
| $[\Delta_{\rm kabuk}]_{\rm yapı}$ | Kabuk modelinin verdiği yapısal boşluk (konumlar, sihirli sayılar) |
| $\odot$ | Aralık çarpımı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kabuk boşluğunu bir yapısal kısım ile bir modülasyon çarpanının aralık çarpımı olarak yazar |
| **Neden yapıyor?** | Evertophy'nin kabuk konumlarını icat etmeden yalnız güçlerini modüle ettiğini biçimsel olarak ayırmak için |
| **Nasıl yapıyor?** | Yapıyı kabuk modeline bırakır; Evertophy'ye yalnız $A$'ya bağlı zarf çarpanını verir |
| **Ne sonuç bekleniyor?** | $[\mu_A]$'nın faz yapısından türetilmesi ve ölçülmüş kabuk güçleriyle karşılaştırılması |
| **Ne sonuç elde ediliyor?** | **Ansatz'dır**; $[\mu_A]$ henüz türetilmemiştir |

$$\boxed{\;\text{Evertophy kabuk KONUMLARINI İCAT ETMEZ — ZARFI MODÜLE EDER.}\;}$$

```latex
\boxed{\;\text{Evertophy kabuk KONUMLARINI İCAT ETMEZ — ZARFI MODÜLE EDER.}\;}
```

## 22.3 Dört rota

| Rota | Yöntem | Öncelik |
|---|---|---|
| **α** | **Oranlar** — normalizasyon iptali + sıralama haritası + sıfır kalibrasyon + mühürlü ön kayıt | **Birincil** |
| β | Tek çapa | İkincil |
| γ | Mutlak normalizasyon + doğrudan köprü fonksiyonu | Üçüncül |
| δ | Kalıntı çözümlemesi | Yardımcı |

**α'nın seçilme gerekçesi:** oran testi normalizasyondan arınmıştır; en temiz kesişim testini verir ve köprü fonksiyonuna en az bağımlıdır.

## 22.4 Eleme koşulları

| Koşul | Sonuç |
|---|---|
| Öngörü–gözlem kesişimi boş | Yanlışlandı |
| Bilinen kabukları siliyor ya da kaydırıyor | **Yapı koruma elemesi** |
| Veriden sonra kütleye bağlı katsayı eklenmiş | **Parametre bütçesi elemesi** |
| Etkin bir kısıt ihlal ediliyor | Eleme |
| Ayar aralığı nükleer veriye yeniden uydurulmuş | **Kör izdüşüm elemesi** |

## 22.5 Veri soyağacı kilidi — Katı Kör Soyağacı

Mühürlenmesi gerekenler: köprü girdileri · parametre üretim kayıtları · hedef seçimi · veri sürümü · eğitim / kalibrasyon varsa kullanılan alt küme · kör ayrılmış küme · dondurma zamanı.

$$\boxed{\;\text{"Önceden mühürledik" TEK BAŞINA YETMEZ.}\;}$$

```latex
\boxed{\;\text{"Önceden mühürledik" TEK BAŞINA YETMEZ.}\;}
```

Temel bağımsızlık kısıtı ve dondurma kuralı şunlardır:

$$\boxed{\;D_{\rm türetim}\cap D_{\rm kör}=\varnothing\;}\qquad\qquad \boxed{\;\theta_{\rm köprü}\ \text{kör veri açılmadan ÖNCE dondurulur}\;}$$

```latex
\boxed{\;D_{\rm türetim}\cap D_{\rm kör}=\varnothing\;}\qquad\qquad \boxed{\;\theta_{\rm köprü}\ \text{kör veri açılmadan ÖNCE dondurulur}\;}
```

| Sembol | Anlamı |
|---|---|
| $D_{\rm türetim}$ | Öngörünün türetilmesinde ya da kalibrasyonda kullanılan veri |
| $D_{\rm kör}$ | Kör doğrulama için ayrılmış veri |
| $\theta_{\rm köprü}$ | Köprü kalibrasyon parametreleri |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Türetim verisi ile doğrulama verisinin kesişmemesini ve köprü parametrelerinin önceden dondurulmasını şart koşar |
| **Neden yapıyor?** | Aynı veriyle hem ayar yapıp hem başarı raporlamak, öngörüyü uydurmaya dönüştürür |
| **Nasıl yapıyor?** | Veri kümelerini ayrık tutar; parametreleri kör veri açılmadan önce kilitler; soyağacını mühürler |
| **Ne sonuç bekleniyor?** | Gerçekten kör bir test |
| **Ne sonuç elde ediliyor?** | **Yöntem kuralıdır**; AME2020 ya da başka bir veri kümesinin aynı anda hem kalibrasyon hem kör doğrulama kaynağı olmasını engeller |

Üç yöntemsel düzey ayrılır:

1. **En güçlü:** öngörü bandı hedef dışı / temel girdilerden türetilir; nükleer hedef verisi kalibrasyona girmez.
2. **Kabul edilebilir:** yalnız önceden kaydedilmiş bir eğitim alt kümesi kullanılır; köprü dondurulur; katı ayrılmış kümeyle sınanır.
3. **Öngörü değildir:** bütün hedef veri kümesine uydurma yapılıp aynı küme üzerinde başarı raporlanır.

## 22.6 Statü

Bu hat, nükleer köprü programında **koşullu yapısal aday** olarak izlenir.

$$\boxed{\;\text{PROTOKOL MİMARİSİ KAPALI} \;/\; \text{TEMELDEN NÜKLEERE TÜRETİM AÇIK}\;}$$

```latex
\boxed{\;\text{PROTOKOL MİMARİSİ KAPALI} \;/\; \text{TEMELDEN NÜKLEERE TÜRETİM AÇIK}\;}
```

Bu nükleer köprü hattı **kanonik sayısal öngörü değildir**; sayaç 0/10 olarak kalır. Yani *nasıl sınanacağı* belirlidir; *ne öngörüleceği* henüz türetilmemiştir.

## 22.7 Uzak hedeflerin kullanımı

Henüz sentezlenmemiş ağır çekirdek bölgeleri **ilk kör koşuda ana hedef yapılmaz**. Önce ölçülmüş kapanma bölgelerinde sınanır.

---

## 22.8 Genişletilmiş yarı ampirik kütle formülü ve kabuk terimi düzeltmeleri

Arşivdeki yarı ampirik biçim ($E_{B0}$ taban + FM çift katmanlı kabuk düzeltmesi + $\beta X$ / $\rho\Omega$ ilişkileri), Bölüm 22'nin yapısal aday katmanıdır. Kritik korumalar 12.4'ten değişmez:

$$\boxed{\;\text{Evertophy zarfı modüle eder; kabuk konumlarını icat etmez; FM düzeltmesi dış fizik kalibrasyonudur.}\;}$$

```latex
\boxed{\;\text{Evertophy zarfı modüle eder; kabuk konumlarını icat etmez; FM düzeltmesi dış fizik kalibrasyonudur.}\;}
```

Bu blokta [mod 33] doluluk-öğe katkısı, [mod 5] düzeltmesi, ilgili terim ve $\delta_{\rm yüzey}$ katmanları arşiv kaydı olarak korunur; hiçbiri öngörü sayılmaz.

## 22.9 κ_i(Φ, s) genişletilmiş biçimi (∇²Φ dahil)

Kabuk modülasyonu parametrizasyonunun arşiv biçimi şudur:

$$\kappa_i(\Phi, s) = \kappa_i^{(0)} + \kappa_i^{(1)}\,\frac{\Phi}{\Phi_{\rm ref}} + \kappa_i^{(2)}\,\frac{\nabla^2\Phi}{\Phi_{\rm ref}/L_{\rm ref}^2} + \kappa_i^{(3)}\,s$$

```latex
\kappa_i(\Phi, s) = \kappa_i^{(0)} + \kappa_i^{(1)}\,\frac{\Phi}{\Phi_{\rm ref}} + \kappa_i^{(2)}\,\frac{\nabla^2\Phi}{\Phi_{\rm ref}/L_{\rm ref}^2} + \kappa_i^{(3)}\,s
```

| Sembol | Anlamı |
|---|---|
| $\kappa_i$ | $i$. kabuk modülasyon katsayısı |
| $\kappa_i^{(0)}\ldots\kappa_i^{(3)}$ | Açılımın sabit katsayıları (serbest parametreler) |
| $\Phi$ | Faz skaleri (tarihsel gösterim; $X$'in bir okuması) |
| $\Phi_{\rm ref}$ | Referans değer |
| $\nabla^2\Phi$ | $\Phi$'nin Laplasyeni (yerel kütleçekimsel ortamın eğrilik etkisi) |
| $L_{\rm ref}$ | Referans uzunluk |
| $s$ | Yapı parametresi |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kabuk modülasyon katsayılarını yerel faz okumasına, onun ikinci türevine ve bir yapı parametresine bağlar |
| **Neden yapıyor?** | Yerel kütleçekimsel ortamın kabuk güçleri üzerindeki olası etkisini parametrelendirmek için |
| **Nasıl yapıyor?** | Birinci dereceden bir açılım yazar; her terimi referans ölçeklerle boyutsuzlaştırır |
| **Ne sonuç bekleniyor?** | Katsayıların faz yapısından türetilip dondurulması |
| **Ne sonuç elde ediliyor?** | Bütün $\kappa_i$ katsayıları **serbest parametredir**; dondurulmadıkça türetim iddiası yoktur |

## 22.10 Υ(Z, N; Φ) tam biçimi ve E_B kaydı

Modüle edilmiş bağlanma enerjisinin arşiv biçimi şudur:

$$E_B(Z, N; \Phi) = E_B^{(0)}(Z, N)\cdot\left[1 + \Upsilon(Z, N; \Phi)\right], \qquad \Upsilon = \sum_i \kappa_i(\Phi, s)\,f_i(Z, N)$$

```latex
E_B(Z, N; \Phi) = E_B^{(0)}(Z, N)\cdot\left[1 + \Upsilon(Z, N; \Phi)\right], \qquad \Upsilon = \sum_i \kappa_i(\Phi, s)\,f_i(Z, N)
```

| Sembol | Anlamı |
|---|---|
| $E_B$ | Bağlanma enerjisi |
| $Z$, $N$ | Proton ve nötron sayısı |
| $E_B^{(0)}$ | Taban (standart yarı ampirik) bağlanma enerjisi |
| $\Upsilon$ | Evertophy modülasyon terimi |
| $f_i(Z,N)$ | Kabuk yapısına bağlı taban fonksiyonları |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Standart bağlanma enerjisini faz okumasına bağlı küçük bir modülasyon çarpanıyla düzeltir |
| **Neden yapıyor?** | 22.2'deki iki katmanlı ansatz'ı somut ve hesaplanabilir bir biçime getirmek için |
| **Nasıl yapıyor?** | Modülasyonu kabuk taban fonksiyonlarının katsayılı toplamı olarak yazar |
| **Ne sonuç bekleniyor?** | Katsayılar dondurulduktan sonra ölçülmüş bağlanma enerjileriyle kör karşılaştırma |
| **Ne sonuç elde ediliyor?** | Katsayılar dondurulmadan **öngörü statüsü taşımaz**; 22.6'daki "protokol mimarisi kapalı / temelden nükleere türetim açık" hükmünün arşivdeki somut parametrizasyonudur |

$$\boxed{\;E_B\ \text{kaydı, katsayılar dondurulmadan öngörü statüsü taşımaz.}\;}$$

```latex
\boxed{\;E_B\ \text{kaydı, katsayılar dondurulmadan öngörü statüsü taşımaz.}\;}
```

---




# BÖLÜM 23 — YÖNTEM ONTOLOJİSİ

## 23.1 Bağlam ve risk

Çerçeve, tek bir araştırmacı tarafından, çok sayıda yapay zekâ sistemi araç olarak kullanılarak geliştirilmiştir. Bu ortamın en büyük riski **kendi kendini onaylayan bir döngüye** girmektir: araçlar araştırmacının dilini öğrenir, araştırmacı araçların ürettiği cümleleri benimser ve sonunda kimse neyin gerçekten türetildiğini, neyin yalnızca tekrar edildiğini ayırt edemez hâle gelir. Bu bölüm, bu döngüyü kırmak için kurulan kuralları toplar.

## 23.2 Çelişkili çoklu sistem mimarisi

Birden fazla sistem eşzamanlı çalıştırılır ve bilgi **kasıtlı olarak bölümlendirilir**. Hiçbir sistem resmin tamamını görmez. *(Bu, maraton öncesi Değnek Ambarı yöntemidir. 23–26 Eylül maratonunda ise her turun bütün çıktıları tek bir metinde bütün katılımcılara verildi; ortak çıktıları gören sistemlerin mutabakatı bütünüyle bağımsız doğrulama sayılmaz.)* Araştırmacı tek bütünleştirici olarak kalır; bir çıktının kanona girip girmeyeceğine yalnız o karar verir.

### Kaynak ayrıştırma kuralı

$$\boxed{\;\text{Bütün üretim, MİMAR KAYNAĞI ve ARAÇ ÜRETİMİ blokları hâlinde AYRIŞTIRILIR.}\;}$$

```latex
\boxed{\;\text{Bütün üretim, MİMAR KAYNAĞI ve ARAÇ ÜRETİMİ blokları hâlinde AYRIŞTIRILIR.}\;}
```

Bu bir biçim tercihi değil, **epistemik / kaynak güvenlik duvarıdır**. Bir araç kendi üretimini kanıt olarak sunamaz.

### Bilinen sınır

$$\boxed{\;\text{Çoklu sistem MUTABAKATI, BAĞIMSIZ KANIT DEĞİLDİR.}\;}$$

```latex
\boxed{\;\text{Çoklu sistem MUTABAKATI, BAĞIMSIZ KANIT DEĞİLDİR.}\;}
```

Sistemler benzer eğitim dağılımlarından geldiği için aynı yanlışa aynı anda kayabilir. Kapatılan ampirik hat (21.1) bunun somut örneğidir. Çerçevenin genel ilkesi burada da geçerlidir: **konsensüs ⇏ kanon**.

## 23.3 Doğrulama standardı

Geçerli bir doğrulama şunları içerir: açık türetim adımları · sembolik / hesaplamalı çıktı · yeniden üretilebilir hesap · denetlenmiş denklem izi. İki fiziksel denetim de zorunludur:

**Ölçek denetimi.** Çıkan sayı fiziksel olarak erişilebilir bir aralıkta mı?

**Gösterim denetimi.** Sonuç, keyfî bir tanım seçiminin fonksiyonu mu?

$$\boxed{\;\text{ARİTMETİK DOĞRULAMA, FİZİKSEL DOĞRULAMA DEĞİLDİR.}\;}$$

```latex
\boxed{\;\text{ARİTMETİK DOĞRULAMA, FİZİKSEL DOĞRULAMA DEĞİLDİR.}\;}
```

**Yazar hükmü — bağlayıcı modeller.** Gözlem ya da deneyden türetilmemiş kuramsal matematiksel modellere bağlı kalmak zorunlu değildir; gözlem ve deneyden türetilen modeller bağlayıcıdır. Örneğin kara delik ufkunun alanının azalmadığını söyleyen alan teoremi gözlemle sınanmış bir kısıttır; entropinin alanla orantılı olduğunu söyleyen Bekenstein–Hawking alan yasası ise henüz gözlemle sınanmamış kuramsal bir sonuçtur. Bu hüküm kuramsal modellerin kullanımını yasaklamaz.

$$\text{alan teoremi: }\ \frac{dA}{dt}\ge0\qquad\qquad \text{alan yasası: }\ S_{BH}=\frac{A}{4\ell_P^2}$$

```latex
\text{alan teoremi: }\ \frac{dA}{dt}\ge0\qquad\qquad \text{alan yasası: }\ S_{BH}=\frac{A}{4\ell_P^2}
```

| Sembol | Anlamı |
|---|---|
| $A$ | Ufuk yüzey alanı |
| $dA/dt$ | Alanın değişimi; teorem azalmadığını söyler (gözlemle sınanmış) |
| $S_{BH}$ | Bekenstein–Hawking entropisi (kuramsal; doğrudan ölçülmedi), $k_B$ biriminde |
| $\ell_P$ | Planck uzunluğu |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Çerçevenin hangi dış modellere bağlı olduğunu ve hangilerine bağlı olmadığını ayırır |
| **Neden yapıyor?** | c₀'ın kapasite ölçeklemesi (Bölüm 3) gibi yazar hükümlerinin, sınanmamış kuramsal sonuçlarla çelişmesi durumunda neyin bağlayıcı olduğunu açık kılmak için |
| **Nasıl yapıyor?** | Gözlemle sınanmış alan teoremini bağlayıcı kısıt olarak, henüz sınanmamış alan yasasını kullanılabilir ama bağlayıcı olmayan kuramsal sonuç olarak sınıflar |
| **Ne sonuç bekleniyor?** | Çerçevenin ölçülmüş fiziğe sıkı sıkıya bağlı, kuramsal sonuçlara karşı ise serbest kalması |
| **Ne sonuç elde ediliyor?** | Yazar hükmüdür. Kuramsal modellerin kullanımı yasaklanmaz; bağlayıcılığı gözleme bağlanır |

## 23.4 Sayı sınıflandırması

| Sınıf | Ne |
|---|---|
| **Postüle** | Dış kaynağı da türetimi de yok |
| **Dış ölçüm** | Veriden alınmış |
| **Uyum / uydurma** | Veriye uydurulmuş |
| **Dal içi türetim** | Bir model dalı içinde çıkarılmış |
| **Çerçeve çıktısı** | Ontolojiden türetilmiş |

Postülden türeyen bir sayı, dış ölçümden türeyene göre **epistemik olarak zayıftır**.

## 23.5 Parametre bütçesi

$$\boxed{\;\text{SERBEST GİRDİ SAYISI} \;<\; \text{ÖNGÖRÜLEN GÖZLENEBİLİR SAYISI}\;}$$

```latex
\boxed{\;\text{SERBEST GİRDİ SAYISI} \;<\; \text{ÖNGÖRÜLEN GÖZLENEBİLİR SAYISI}\;}
```

Bu kural, tekrar eden bir hata desenine karşıdır: bir **çarpımın** sabitlenip **çarpanların** serbest bırakılması.

### Fonksiyonel serbestlik

$$D_{\rm model} = N_{\rm skaler} + N_{\rm fonksiyonel} + N_{\rm hiper}$$

```latex
D_{\rm model} = N_{\rm skaler} + N_{\rm fonksiyonel} + N_{\rm hiper}
```

| Sembol | Anlamı |
|---|---|
| $D_{\rm model}$ | Modelin toplam serbestlik derecesi |
| $N_{\rm skaler}$ | Serbest skaler parametre sayısı |
| $N_{\rm fonksiyonel}$ | Serbest fonksiyonların sonlu bir bazdaki parametre sayısı |
| $N_{\rm hiper}$ | Üst parametre (hiperparametre) sayısı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bir modelin gerçek serbestliğini üç kaynağın toplamı olarak sayar |
| **Neden yapıyor?** | Serbest fonksiyonlar sonsuz serbestlik taşır; yalnız skaler parametreleri saymak modelin ne kadar "satın aldığını" gizler |
| **Nasıl yapıyor?** | Fonksiyonları sonlu bir bazda parametrelendirerek sayılabilir kılar ve skaler ve üst parametrelerle toplar |
| **Ne sonuç bekleniyor?** | $D_{\rm model}$'in öngörülen gözlenebilir sayısından küçük kalması |
| **Ne sonuç elde ediliyor?** | **Gerekli bir filtredir**; tanımlanabilirlik ve dejenerelik ayrıca ele alınmalıdır |

### Gerekli ama yeterli değil

$$\boxed{\;ab = 6 \text{ bilmek, } a \text{ ve } b \text{'yi ÖNGÖRMEK DEĞİLDİR.}\;}$$

```latex
\boxed{\;ab = 6 \text{ bilmek, } a \text{ ve } b \text{'yi ÖNGÖRMEK DEĞİLDİR.}\;}
```

### Köprü bütçesi

Çekirdek ontolojiden gözlenebilir niceliğe giden köprüler de ayrı fiyatlandırılır:

| Serbestlik türü | Örnek |
|---|---|
| **Sürekli** | Yeni ayarlanabilir katsayı |
| **Fonksiyonel** | Serbest harita / fonksiyon biçimi |
| **Yapısal** | Yeni eşleme, sıra, seçim ya da topoloji varsayımı |

Bir modelde $N_{\rm serbest}<N_{\rm gözlenen}$ sağlansa bile, serbest bir köprü fonksiyonu ya da yapısal seçim öngörüyü fiilen geri alabilir.

$$\boxed{\;\text{Parametre bütçesini geçmek} \;\nRightarrow\; \text{öngörüsel kapanış}\;}$$

```latex
\boxed{\;\text{Parametre bütçesini geçmek} \;\nRightarrow\; \text{öngörüsel kapanış}\;}
```

## 23.6 Sayı falcılığı ve yön hatası

| Risk | Ne |
|---|---|
| **Sayı falcılığı (numeroloji)** | Sayının kaynağı belirsiz |
| **Yön hatası** | Kaynağı belli, ama **girdi** olarak girip **çıktı** diye sunuluyor |

İkincisi daha sinsidir. Bir uyarı işareti de şudur: fizikte çok yaygın bir sayıya rastlamanın önsel olasılığı yüksektir; eşleşmenin bilgi içeriği düşüktür.

## 23.7 Eleme testi kültürü

$$\boxed{\;\text{YANLIŞ VARLIK} \;\neq\; \text{AÇIK BORÇ}\;}$$

```latex
\boxed{\;\text{YANLIŞ VARLIK} \;\neq\; \text{AÇIK BORÇ}\;}
```

Bir kuramın en tehlikeli hâli açık deliği değil, **kapalı sandığı yanlış hükmüdür**. Açık borç dürüstçe yazılmış bir eksikliktir; yanlış varlık ise eksikliği kapatmış gibi görünen bir hatadır.

## 23.8 Dal alışverişi yasağı

Alternatif modeller **önceden** listelenir ve mühürlenir. Veriye bakıp en uyumlu dalı seçmek yasaktır.

## 23.9 Dil disiplini

Yasak: *"kanıtlandı"* (biçimsel kanıt dışında), *"fiziksel yasa"*, *"tamamlanmış kuram"*, *"çözüldü"*. Yerine: *"kuruludur"*, *"adaydır"*, *"açıktır"*, *"yapısal olarak dışlanır"*, deneyler için *"uyumlu okumadır"*.

$$\boxed{\;\text{Dil gevşerse muhasebe gevşer.}\;}$$

```latex
\boxed{\;\text{Dil gevşerse muhasebe gevşer.}\;}
```

## 23.10 Biçimsel doğrulama katmanı

Çerçevenin ontolojik kısıtları Lean tabanlı biçimsel paketlerde tip düzeyinde kodlanmıştır. Maraton öncesi proje envanterinde şu sayım bulunur:

$$\boxed{\;66\ \text{eski} + 53\ \text{V03} = 119\ \text{teorem bildirimi}\;}$$

```latex
\boxed{\;66\ \text{eski} + 53\ \text{V03} = 119\ \text{teorem bildirimi}\;}
```

Kaynak arşivde bir koşuda temiz `lake build`, başka bir bağımsız araç koşusunda ise **119 teorem bildirimi ve eksik bırakılmış kanıt bulunmadığı** raporlanmıştır. Aynı atıf disiplini `stamp.py` sayımları ile $G_{\rm univ}(M)\simeq F_2$ ve $K(M)\simeq\mathbb Z^2$ araç teyitleri için de geçerlidir: bunlar kaynak koşularında raporlanmıştır; bu çalışma içinde ikinci kez yürütülmüş sayılmaz. İlgili ZIP / Lean / Python kaynakları burada yeniden çalıştırılmadığı için rapor "yerel bağımsız yeniden doğrulama" diye yükseltilmez. Bu sayı **fiziksel doğrulama sayısı değildir**.

23–26 Eylül 2026 maratonunun sonundaki envanter şudur:

$$\boxed{\;46\ \text{üretim} + 223\ \text{arşiv} = 269\ \text{teorem / önerme bildirimi}\;}$$

```latex
\boxed{\;46\ \text{üretim} + 223\ \text{arşiv} = 269\ \text{teorem / önerme bildirimi}\;}
```

Arşiv kısmı 66 eski, 53 V03 ve 104 V24 bildirimini içerir ($66+53+104=223$); üretim kısmı ise eski arayüzlerden yalıtılmış, tek kanonik çekirdektir. Hiçbir bildirimde eksik bırakılmış kanıt yoktur ("0 aksiyom" projenin kendi bildirimleri için bir sayımdır; Lean'in mantıksal temelinde hiç varsayım bulunmadığı anlamına gelmez) ve üretim çekirdeğinin eski arayüzlerden yalıtılmışlığı düşmanca test durumlarıyla ayrıca sınanmıştır. Bu sayı bir **biçimsel envanterdir**, fiziksel doğrulama sayısı değildir. Ayrıca iki aracın ya da iki yapay zekânın aynı sonuca varması, bağımsız yürütme kaydı yoksa bir yeniden üretim değil, yalnız görüş uyumudur.

Biçimsel kayıtlar beş sınıfta ayrılmalıdır:

| Sınıf | Anlamı |
|---|---|
| **SPEC** | Tanım / aksiyomdan doğrudan gelen belirtim sonucu |
| **DERIVED** | Genel tanımlardan türetilmiş teorem |
| **FINITE-CHECK** | Sonlu, eksiksiz tarama / sağlık denetimi |
| **PHYS-BRIDGE** | Biçimsel yapı ile fizik arasında ek köprü isteyen sonuç |
| **POLICY** | Muhasebe / yöntem değişmezi |

$$\boxed{\;\text{Bir BİÇİMSEL TEOREM, bir FİZİK TEOREMİ DEĞİLDİR.}\;}$$

```latex
\boxed{\;\text{Bir BİÇİMSEL TEOREM, bir FİZİK TEOREMİ DEĞİLDİR.}\;}
```

### Açık biçimsel borçlar

- Yeniden yazma / normal forma indirgeyici için genel birleşme ve küresel konfluans zinciri — **kapandı** (biçimsel olarak kanıtlandı; 14.2).
- Arşiv–Σ bütünleştirmesi ve yön anlamının bu bütünleştirmeye girmesi.
- `rid` tekliği ve `WellFormedArchive` (iyi biçimli arşiv).
- Tam sayı vekilinden $I(\mathbb Q)$ / gerçel aralık yapısına geçiş.
- Kesin karakter $\omega$ ile kapsama aralığı $\Omega_{\rm enc}$'nin biçimsel tip olarak ayrılması.
- c₀ ↔ c⁺ $X$-lifi yapısının parametre / köprü bütçesi muhasebesi.
- Metrik yeniden inşa arayüzü.
- `U0_bidirectional := false` rezervinin ontolojik üst katmanla uyumlu biçimde korunması.
- Bağımsız dış derleme / yeniden üretim.

Biçimsel paket güncel ontolojinin tip tutarlılığını sınar; genel görelilik / kuantum alan kuramının geri kazanımını, alan denklemlerini ve doğanın doğru kuramı olma iddiasını kanıtlamaz.

### 23.10a Çift mühürleme — arşiv bütünlüğü protokolü

Yapay zekâ ve biçim geçişlerinde denklemlerin yalnız görüntülenmiş hâlini saklamak yeterli değildir. Arşiv yönteminde bir denklem kaydı, mümkün olduğunda iki temsille korunur:

$$S(E)=\{\mathrm{Skeleton}(E)\in R_{\rm ham},\;\mathrm{Rendered}(E)\in R_{\rm görünür}\}$$

```latex
S(E)=\{\mathrm{Skeleton}(E)\in R_{\rm ham},\;\mathrm{Rendered}(E)\in R_{\rm görünür}\}
```

| Sembol | Anlamı |
|---|---|
| $E$ | Bir denklem |
| $S(E)$ | Denklemin saklanan çift kaydı |
| $\mathrm{Skeleton}(E)$ | Ham (LaTeX) iskelet |
| $\mathrm{Rendered}(E)$ | Görüntülenmiş temsil |
| $R_{\rm ham}$, $R_{\rm görünür}$ | Ham ve görünür kayıt depoları |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Her denklemi hem ham iskelet hem görüntülenmiş biçimde saklar |
| **Neden yapıyor?** | Kodlama onarımlarında ve araç geçişlerinde denklemlerin sessizce bozulmasını önlemek için |
| **Nasıl yapıyor?** | İki temsili ayrı depolarda tutar ve toplu karakter değişikliğinden önce birbirleriyle çapraz denetler |
| **Ne sonuç bekleniyor?** | Denklem kaynağının biçim geçişlerinden zarar görmeden korunması |
| **Ne sonuç elde ediliyor?** | **Fizik postülası değil, arşiv protokolüdür.** Bu belgede her denklemin ardından gelen LaTeX kod bloğu bu protokolün doğrudan uygulamasıdır |

### 23.10b V24 teknik sonuçlarının ontolojik statüsü

- **Cₘ sıfır-vakum yerel kütle önermesi (§509.4):** koşullu bir skaler-tensör / etkin alan kuramı teknik sonucudur; model katmanında tutulur, çekirdek ontolojiye otomatik olarak yükseltilmez. "Sıfır-vakum" adı teknik bir model adıdır; c⁺ ≡ vakum kimliğiyle çelişmez ve onu sınırlamaz.
- **Z işlemcisi $Z:\Phi\to T$:** tarihsel kinematik ikilik ailesinde tanımlanmıştır; eski $d(x)/Z(x)$ gösterimiyle eşlemesi açık olduğundan güncel $X$ tanımına temel öğe olarak eklenmez.
- **$X_{\rm durum}\to X_{\rm alan}\to X_{\rm okuma}$ katman şeması:** güncel 4.5 "okuma yüzleri" ile doğrudan özdeşleştirilmez; aralarındaki eşleme açık bir düzenleme borcudur.
- **$\Pi_{+\to m}$ ve "c₀ üzerinden zorunlu" tarihsel hükmü:** tam çift yönlü üçgen kanonuyla uyumlaştırılmadan güncel geçiş yasası sayılmaz; mimar kararı bekler.

## 23.11 Tarihsel hatlar ve neden bırakıldıkları

| Hat | Neden |
|---|---|
| Lojistik skaler çekirdek | Bir modeldi; ontolojik $X$ değildi |
| Sayısal $U_0$ okumaları | $U_0$'ı bir Cₘ niceliğine indirgiyordu |
| Çok alanlı korelasyon hattı | Yapısal yapay sonuç |
| Çıplak faz topolojisinden belirli CKM / PMNS değerlerinin seçimi | Ek fiziksel seçim yapısı olmadan değerler belirlenmez; tek çevrim holonomisi açık bir alternatiftir (19.3) |
| Zincir topolojisi | Tam üçgenle değiştirildi |
| Nokta fiziği yasağı dili | $[P,P]$ meşrudur |
| Sıfır Enerji / Düz Evren hattı | Raf kararı; güncel çekirdeğin çözülmüş sonucu değildir |
| Lagrange MHTML kaydı | Kurtarma / kaynak notu; dış fazlara eylem yazma yetkisi vermez |
| Karanlık madde için $\nabla\ln\chi_S\neq0$ ölçütü | Emekli; karşılıklı sistemlerde $\chi_S\equiv1$ (17.1) |
| "c⁺ ≠ vakum" kısıtı | Yazar hükmüyle kaldırıldı; güncel kanon c⁺ ≡ vakum |

Bu kayıtlar silinmez; **neden bırakıldıklarıyla** birlikte saklanır.

## 23.12 Eşsesli kavramlar için belge sınırı

Başka çalışmalarda geçen "çıplak iskelet" benzeri terimler, buradaki c₀ "iskelet" benzetmesiyle aynı kavram değildir. Ortak sözcük, farklı belge ailelerine ait kavramları anlam bakımından birleştirme yetkisi vermez.

---

## 23.18 Atma grubu — kayıt ve gerekçe disiplini

Dışlanan öneriler silinmez; reddedilme gerekçeleriyle korunur ("eksi kayıt disiplini"). Eleme gerekçeleri bir sınıflandırmayla tutulur: kapsam dışı, yetersiz kaynak, tekilleştirme, çelişki.

## 23.19 Araç kaynaklı epistemik riskler (yapay zekâ yanılgıları dahil)

| Risk | Önlem |
|---|---|
| Uydurma (halüsinasyon) kaynaklı içerik | Kaynak etiketi zorunlu; doğrulanamayan içerik belgeye girmez |
| Aynı yanlışa ortak kayma | Görünürlük defteri; çapraz denetim |
| Araç çıktısını kanıt ilan etme | Kaynak ayrıştırma kuralı (23.2) |
| Sayısal uydurma | EK H kaynak kaydı; dış karşılaştırma yeniden doğrulanmadan kullanılmaz |

## 23.20 En küçük güvenli iddia / son hüküm çıktı protokolü

Her çalışma koşusunun çıktısı için asgari güvenli iddia biçimi: kanonik olmayan içerik "STATÜ + KAYNAK + KORUMA" üçlüsüyle taşınır; koruma cümlesi olmayan içerik belgeye girmez. Bu protokol monografinin hazırlık sürümlerinde kanonik olmayan bölümlere uygulanmıştı; yayın metninde güven düzeyi doğrudan cümlede belirtilir. Bu sürümdeki "Ne sonuç elde ediliyor?" satırları, aynı protokolün okura dönük biçimidir.

## 23.21 Çift görüntüleme ve LODO doğrulama protokolü

Çift mühürlemenin (23.10a) çalışma katmanı uzantısıdır: her denklem ham iskelet + görünür görüntüleme olarak saklanır; LODO (bir veri kümesini dışarıda bırak) doğrulaması, veri kümeleri arası sızıntı denetimi için tanımlıdır.

# BÖLÜM 24 — SINIRLAR VE AÇIK SORULAR

## 24.1 Altı kritik soru

| # | Soru |
|---|---|
| **1** | Faz sektörlerinin durum uzayı ayrışımı nedir? |
| **2** | Fazların alan uzayındaki konumları nerededir? |
| **3** | Kütleçekim bağlaşımının karakteristik ölçeği nedir? |
| **4** | Okuma haritasını **tekil kılan ek ilke** nedir? |
| **5** | Faz sayısının ve dağılımın gerekçesi nedir? |
| **6** | Cₘ neden zayıf bağlaşımlı sabit noktadır? |

**Ve merkezî boşluk:**

$$\boxed{\;X \;\longrightarrow\; \{\text{fiziksel fonksiyonlar}\} \quad \text{ZİNCİRİ YAZILMAMIŞTIR.}\;}$$

```latex
\boxed{\;X \;\longrightarrow\; \{\text{fiziksel fonksiyonlar}\} \quad \text{ZİNCİRİ YAZILMAMIŞTIR.}\;}
```

### Dördüncü sorunun biçimsel yeri

Dördüncü sorunun neden zor olduğu kesin olarak gösterilmiştir. Tip kuralları, aralık güvenliği, sabit uç noktalar, tekdüzelik ve iyi tanımlılık — bunların hepsi birlikte bile $X$'ten fiziksel niceliğe giden köprüyü **tekil olarak seçmez**; iki farklı köprü bu koşulların tamamını sağlayabilir. Sonlu bir oyuncak modelde bu Lean'de, sürekli durumda ise analitik karşı örneklerle gösterilmiştir.

$$\boxed{\;\text{Tip} + \text{aralık} + \text{iyi tanımlılık} \;\nRightarrow\; \text{tekil köprü}\;}$$

```latex
\boxed{\;\text{Tip} + \text{aralık} + \text{iyi tanımlılık} \;\nRightarrow\; \text{tekil köprü}\;}
```

Sonuç açıktır: okuma haritasını tekil kılacak olan bir **fiziksel seçim ilkesi** ve gözlemdir. Zayıf alanda, sabit katsayılı bir yanıt işlemcisi için doğrusal yanıt koşullu olarak türetilebilir; ama $X$'ten kaynak, katsayı ve sınır verisine giden kurucu harita açıktır. Merkezî boşluk artık yalnız "yazılmamış" değil, **nerede durduğu belirlenmiş** bir boşluktur. Genel fiziksel seçici dondurulmuş açık borçtur (EK K.1).

### Denklem seti — köprünün tekil olmayışı ve ayırt edici ilkeler

$X$'ten Cₘ'deki fiziksel niceliklere giden **köprü** ($J_X$ / $\mathcal{E}_\phi$), Evertophy'nin gözlemle temas noktasıdır. Soru şudur: tip ve iyi tanımlılık kuralları bu köprüyü **tek başına seçebilir mi?**

$$B_1(x) = x, \qquad B_2(x) = x + \tfrac{x(1-x)}{2} \quad (B_2' = \tfrac32 - x > 0) \qquad B_1(\tfrac12) = \tfrac12 \neq \tfrac58 = B_2(\tfrac12)$$

```latex
B_1(x) = x, \qquad B_2(x) = x + \tfrac{x(1-x)}{2} \quad (B_2' = \tfrac32 - x > 0) \qquad B_1(\tfrac12) = \tfrac12 \neq \tfrac58 = B_2(\tfrac12)
```

$$\operatorname{diam} B(I_x) \leq \frac{L_x}{1-q}\operatorname{diam} I_x \ \text{(büzülme)}, \qquad \operatorname{diam} B(I_x) \leq \frac{L_x}{\mu}\operatorname{diam} I_x \ \text{(varyasyonel)}$$

```latex
\operatorname{diam} B(I_x) \leq \frac{L_x}{1-q}\operatorname{diam} I_x \ \text{(büzülme)}, \qquad \operatorname{diam} B(I_x) \leq \frac{L_x}{\mu}\operatorname{diam} I_x \ \text{(varyasyonel)}
```

| Ayırt edici ilke | $B_1$ | $B_2$ | Hüküm |
|---|---|---|---|
| Toplamsal üst üste binme $B(x{+}y) = B(x) + B(y)$ | ✓ | ✗ | **Tekil seçer** (Cauchy + tekdüzelik) — doğru |
| Çarpımsal bileşim | ✓ | ✗ | $x^p$ ailesine indirger — kısmi |
| Yansıma simetrisi | ✓ | ✗ | Tekil değil — kısmi |
| "Varyasyon ilkesi tek başına seçer" çıkarımı | — | — | **Başarısız:** $J_1=\int_0^1 \tfrac12 B'^2\,dx \to B_1=x$ ve $J_2=\int_0^1 (\tfrac12 B'^2-B)\,dx \to B_2=\tfrac32x-\tfrac12x^2$; ikisi de kesin dışbükey ve tek çözümlüdür. Varyasyonel yöntem matematiksel olarak başarılı bir alternatiftir; hangi eylemin fiziksel olduğu açıktır |
| Sonlu kalibrasyon | — | — | **Başarısız:** $B_\varepsilon$ karşı örneği |
| Korunum tek başına | — | — | **Başarısız:** toz ve ışınım aynı süreklilik denklemini sağlar |

| Sembol | Anlamı |
|---|---|
| $A_{\min}$ | Dondurulmuş en küçük aksiyomlar: A1 tip · A2 Range güvenliği · A3 sabit uç noktalar · A4 tekdüzelik · A5 tek çıktı |
| $B_1, B_2, B_\varepsilon$ | Aday köprüler ($[0,1]$ üzerinde, uç noktaları sabit) |
| $I_x$ | Girdi aralığı |
| $\operatorname{diam}$ | Aralığın genişliği |
| $q$ | Büzülme sabiti ($0\le q<1$) |
| $L_x$ | Lipschitz sabiti |
| $\mu$ | Güçlü dışbükeylik sabiti |
| $J_1$, $J_2$ | İki farklı eylem fonksiyoneli |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Bütün biçimsel koşulları sağlayan iki farklı köprü gösterir ve hangi ek ilkelerin seçimi daralttığını tablolar |
| **Neden yapıyor?** | Köprünün yalnız tip ve iyi tanımlılık kurallarından çıkarılabileceği beklentisini sınamak için |
| **Nasıl yapıyor?** | Uç noktaları ve tekdüzeliği koruyan iki fonksiyon kurar; ayırt edici ilkeleri tek tek bu iki fonksiyona uygular; aralık genişliği için büzülme ve varyasyonel sınırlar verir |
| **Ne sonuç bekleniyor?** | Hangi fiziksel ilkenin köprüyü tekil olarak seçtiğinin belirlenmesi |
| **Ne sonuç elde ediliyor?** | **Olmazlık (no-go) sonucu kanıtlanmıştır:** biçimsel kurallar tek başına köprüyü seçmez. Toplamsal üst üste binme tekil seçer; varyasyon ilkesi tek başına seçmez. Sonlu seçici **oyuncak modeldir**; genel fiziksel seçici **Daha Sonra Ele Alınacak** |

### Denklem seti — fiziksel köprü adayları A / B / C ve seçim zinciri

Köprünün tip kurallarıyla seçilemediği gösterildiğine göre, bu küme **hangi fiziksel ilkelerin** serbestliği ne kadar daralttığını ve ampirik kalibrasyonun nerede kaçınılmaz olduğunu kurar.

$$\textbf{A:}\ G_{\mu\nu} + \Lambda g_{\mu\nu} = \frac{8\pi G}{c^4}\,T_{\mu\nu}[J_X] \qquad \textbf{B:}\ S = \int\!\sqrt{-g}\Big[\tfrac{M^2}{2}F(\chi)R - \tfrac12 K(\chi)(\nabla\chi)^2 - V(\chi)\Big] + S_m[A^2 g]$$

```latex
\textbf{A:}\ G_{\mu\nu} + \Lambda g_{\mu\nu} = \frac{8\pi G}{c^4}\,T_{\mu\nu}[J_X] \qquad \textbf{B:}\ S = \int\!\sqrt{-g}\Big[\tfrac{M^2}{2}F(\chi)R - \tfrac12 K(\chi)(\nabla\chi)^2 - V(\chi)\Big] + S_m[A^2 g]
```

$$\textbf{C (DD ADAY-01):}\ -\nabla\!\cdot\!(Z\nabla\phi) + \mu^2\phi + 4\pi G\rho = 0,\qquad \phi_{\rm dış} = -C\,\frac{e^{-m r}}{r},\ \ m = \frac{\mu}{\sqrt{Z}}\ \ (\text{sabit } Z > 0)$$

```latex
\textbf{C (DD ADAY-01):}\ -\nabla\!\cdot\!(Z\nabla\phi) + \mu^2\phi + 4\pi G\rho = 0,\qquad \phi_{\rm dış} = -C\,\frac{e^{-m r}}{r},\ \ m = \frac{\mu}{\sqrt{Z}}\ \ (\text{sabit } Z > 0)
```

Kaynaksız bölgede sabit $Z$ için denklem $\nabla^2\phi = (\mu^2/Z)\phi$ olur; sönüm $m = \mu/\sqrt{Z}$'dir. Önceki $e^{-\mu r}$ yazımı yalnız $Z = 1$'de doğrudur. Einstein denkleminde fiziksel birimlerle katsayı $8\pi G/c^4$'tür ($c = 1$ biriminde $8\pi G$). Alan oranı ve onun terslenmesi:

$$Q(m) = e^{-m(r_2 - r_1)}\,\frac{1 + m r_2}{1 + m r_1},\quad 0 < r_1 < r_2,\ m > 0 \;\Rightarrow\; m \in \big[Q^{-1}(Q^+),\ Q^{-1}(Q^-)\big],\quad 0 < Q^- \leq Q^+ < 1$$

```latex
Q(m) = e^{-m(r_2 - r_1)}\,\frac{1 + m r_2}{1 + m r_1},\quad 0 < r_1 < r_2,\ m > 0 \;\Rightarrow\; m \in \big[Q^{-1}(Q^+),\ Q^{-1}(Q^-)\big],\quad 0 < Q^- \leq Q^+ < 1
```

$Q$ kesin azalandır, $Q(0) = 1$, $Q(\infty) = 0$; bu yüzden ölçülmüş bir $Q$ aralığı tek bir $m$ aralığına terslenir. $Q$ terslemesi **$m$'yi** verir; $Z$ bilinmiyorsa oran $\mu$ ile $Z$'yi ayrı ayrı belirlemez.

| Sembol | Anlamı |
|---|---|
| $G_{\mu\nu}$, $\Lambda$ | Einstein tensörü, kozmolojik sabit |
| $T_{\mu\nu}[J_X]$ | $X$'ten gelen kaynağın enerji-momentum tensörü |
| $\chi = \pi_\chi(X)$ | Skaler izdüşüm (17'deki $\chi_S$ ile karıştırılmaz) |
| $M$ | Kütle ölçeği (Planck kütlesi mertebesi) |
| $R$ | Ricci skaleri |
| $F, K, V, A$ | Skaler-tensör kuramının serbest fonksiyonları |
| $S_m[A^2g]$ | $A^2g$ metriğine bağlaşan madde eylemi |
| $\phi$ | Ekranlanmış Poisson potansiyeli |
| $Z$, $\mu$ | Ekranlanmış Poisson katsayı alanı ve ekranlama kütlesi |
| $\rho$ | Madde yoğunluğu |
| $C$ | Dış çözümün genlik sabiti |
| $m$ | Sönüm parametresi |
| $r_1$, $r_2$ | İki ölçüm yarıçapı |
| $Q(m)$ | İki yarıçaptaki ($r^2$ ile ölçeklenmiş) alan şiddeti oranı |
| $Q^\pm$ | Ölçülmüş oran aralığının uçları |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Köprü için üç somut aday — standart Einstein tabanı, skaler-tensör eylemi ve ekranlanmış Poisson test yatağı — kurar ve ölçülebilir bir oranın sönüm parametresine nasıl terslendiğini gösterir |
| **Neden yapıyor?** | Hangi fiziksel ilkenin köprünün serbestliğini ne kadar daralttığını adım adım görmek için |
| **Nasıl yapıyor?** | Lovelock teoreminden başlayarak her ek ilkenin sabitlediğini ve geriye bıraktığını tablolar (aşağıda); test yatağında dış çözümü Yukawa biçiminde yazar ve iki yarıçaptaki oranı kesin azalan olduğu için terslenebilir kılar |
| **Ne sonuç bekleniyor?** | Zayıf alanda koşullu bir türetim; güçlü alanda ve kurucu haritada açık uçların açıkça işaretlenmesi |
| **Ne sonuç elde ediliyor?** | A **köprüdür** (standart taban); B **modeldir** (küresel P3 alt sınıfı); C **modeldir** (test yatağı). Zayıf alan yanıtı **koşullu türetilmiştir**; genel $J_X$ **Daha Sonra Ele Alınacak** |

**Seçim zinciri:**

| İlke | Sabitlediği | Kalan serbestlik |
|---|---|---|
| Lovelock teoremi | Geometri tarafı — **varsayımlarla**: dört boyut, yalnız metrikten, yerel / doğal, simetrik, ıraksamasız ve metrik türevlerinde ikinci mertebe ⇒ $aG_{\mu\nu} + bg_{\mu\nu}$ | Tümü $J_X$'te |
| P1 — eşdeğişkenlik + korunum | $T$'nin keyfî olmaması | Korunumlu her tensör |
| P2 — varyasyonel köken (Hilbert tensörü) | Korunumu kabukta otomatik kılar | $F, K, V, A$ |
| P3 — **küresel kısıtlı alt sınıf**: $F \equiv 1$, $K \equiv 1$, $A \equiv 1$ | $G_{\rm eff}$ sabitliği; madde bağlaşımı | **Yalnız $V(\chi)$** — yalnız bu küresel kabulle |
| P3′ — **yerel donmuş genel görelilik eşleşmesi**: $F(\chi_0) = 1$, $F'(\chi_0) = 0$, $A(\chi_0) = 1$, $A'(\chi_0) = 0$, $V'(\chi_0) = 0$, $V(\chi_0) \propto \Lambda M_{\rm Pl}^2$ (normalizasyona bağlı) | Yalnız $\chi_0$ çevresindeki eşleşme | $F, K, A$'nın **küresel fonksiyon serbestliği kapanmaz**; $A'(\chi_0) = 0$ tek başına "yalnız $V$" sonucunu vermez |

| $J_X$ bileşeni | Statü |
|---|---|
| Sabit katsayılı zayıf alan **yanıt işlemcisi** | Koşullu türetilmiş (DERIVED-CONDITIONAL) |
| $X \to (\rho, Z, \mu,$ sınır verisi$)$ kurucu haritası | Açık |
| Güçlü alan | Açık |
| $V(\chi)$ (kısıtlı P3 modelinde) | Ampirik kalibrasyon ($\dot G/G$, PPN $\gamma$, $w(z)$) |

## 24.2 Diğer açık sorular

Dondurulmuş açık borç listesi EK K.1'dedir; aşağıdaki sorular onunla birlikte okunur.

Metrik doğuş haritaları · potansiyel yapısının faz sayısıyla uyumu · ayrıcalıklı çerçeve riski · iki saat sorunu · küresel korunum yasaları · pertürbasyon ve kararlılık ölçütleri · $X$'in argüman ailesi · ayar gruplarının kökeni · c₀ tek-yapısının iç profili ve olay ufkuyla nicel ilişkisi · **$\Gamma/\mathcal G_{C_m}$ çift sayım borcu:**

$$\Gamma\sim\frac{1}{C_s}\ \ \text{ve}\ \ \mathcal G_{C_m}\sim\frac{1}{C_s}\quad\Longrightarrow\quad \frac{dt}{d\lambda}\sim\frac{1}{C_s^2}$$

```latex
\Gamma\sim\frac{1}{C_s}\ \ \text{ve}\ \ \mathcal G_{C_m}\sim\frac{1}{C_s}\quad\Longrightarrow\quad \frac{dt}{d\lambda}\sim\frac{1}{C_s^2}
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Eski $C_s$ köprülerinde mühürleme maliyetinin zaman iskelesine iki kez girebileceğini gösterir |
| **Neden yapıyor?** | Aynı fiziksel etkinin iki farklı çarpanda sayılması, zaman okumasını yapay olarak karesel bastırırdı |
| **Nasıl yapıyor?** | Her iki çarpanı $1/C_s$ ile ölçeklendiğinde çarpımlarının $1/C_s^2$ verdiğini yazar |
| **Ne sonuç bekleniyor?** | İki faktörün bağımsız fiziksel roller mi yoksa aynı rolün iki temsili mi olduğunun belirlenmesi |
| **Ne sonuç elde ediliyor?** | **Açık borçtur**; $C_s$ aday okuma kipindedir (14.3) |

**Ayrılmış başlıkların anlamı:** SYNTAX ↔ $U_x$ ↔ $X$ ilişkisinin tipi · faz rejimi – eşik sınırının genişliği ve $X$ ile bağı · Faz Çöküşü ile Faz Yırtılmasının tam tanımları (Bölüm 25).

**Küresel düzey açık soruları:** küresel okların matematiksel tipi (faz kapısı olmadıkları bilinir) · $U_x$'in ontolojik tipi (kapsama mı, üyelik mi) · $U_+$ için işlev cümlesi ve genelleştirilmiş doğuş kuralı · $\mathrm{CycleSeed} \dashrightarrow \mathrm{Genesis}$ bağı · devre indeksinin zaman dışı tanımı.

## 24.3 Bilinçli olarak açık bırakılanlar

$$\boxed{\;X\text{'in tam matematiksel gerçeklemesi BİLİNÇLİ OLARAK AÇIKTIR.}\;}$$

```latex
\boxed{\;X\text{'in tam matematiksel gerçeklemesi BİLİNÇLİ OLARAK AÇIKTIR.}\;}
```

$U_0$'ın ön katman iç yapısının tam nitelendirmesi ve $X$'in **nihai matematiksel tipi / kapanış yasası / özellik ailelerinin ortak değişim yasası** aynı kategoridedir. Buna karşılık $X$'in kavramsal rolü güncel çekirdekte açıktır: tek, dinamik, faza / aralığa / bağlama duyarlı üst çözücüdür. Açık bırakılan şey kavramsal anlamı değil, matematiksel gerçeklemesidir.

## 24.4 Yasak yorumlar — toplu liste

### Küresel düzey
$U_0$, $U_x$, $U_+$ faz **değildir** ve faz üçgenine yerleştirilmez · $U_+$ beşinci düğüm, $c^+$, $X$ ya da gelecek **değildir** · $U_+$ "son durak / ölüm" **değildir** · küresel kutuplar **eşik değildir** · küresel oklar **faz kapısı değildir**, faza değil **bütüne** bağlanır · küresel çift yönlülük matematiksel tersinirlik **değildir** · küresel devre bir **zaman akışı ya da zorunlu periyodik çevrim değildir** · $U_0 : c_0 :: U_+ : c^+$ eşlemesi **kurulmaz** · Büyük Yırtılma (Mutlak Yırtılma ≡ Mutlak Çözünme), standart kozmolojinin terminal Big Rip senaryosuyla **özdeşleştirilmez** · $U_0 \leftrightarrow U_+$ doğrudan ilişkisi hakkında **hüküm verilmez** · küresel düzeyde metrik, tetrad, hız ya da süre **yazılmaz**.

### U₀
Faz değildir · kapı uç noktası değildir · c₀ alt türü değildir · topolojik delik değildir · lif değildir · metafizik bir varlık değildir · sayısal bir kütle değeriyle özdeşleştirilemez · $u(0)$ ile karıştırılamaz.

### c₀
Zamansal bir başlangıç anı değildir · zaman "durmuş" değil, **henüz kurulmamıştır** · c₀ tek-yapısı Planck boyutunda bir nokta değildir; metrik boşluksuz, bitişik, sonlu tek bir formdur ve kütleyle büyür · BEC c₀ değildir (madde fazında c₀ ortamına en yakın ortamdır) · tarihsel aşırı somut tanımlar (tam Planck doygunluğu, durağanlık kilidi, sıfır diferansiyel motor) güncel çekirdek değildir.

### c⁺
Gelecek **değildir** · iletişim kanalı **değildir** · Cₘ madde desteği çözülür · Cₘ metrik uzunluğu / süresi / hızı aynen taşınmaz · Cₘ tipi maddesel / durgun kütle taşıyıcı madde varsayılmaz · tarihsel K2 `Dim.mass` kaydı güncel c⁺-yerel kütle gözlenebiliri sayılmaz · ışık-üstü madde **değildir** · olay ufkuyla sert özdeşliği **kurulmamıştır**. *(Önceki sürümlerdeki "c⁺ vakum değildir" maddesi yazar hükmüyle kaldırılmıştır: güncel kanon **c⁺ ≡ vakumdur**; kuantum alan kuramının vakum durumu bu kimliğin Cₘ hesap dilidir.)*

### X
Çekim Kuvveti değildir · kütleçekim değildir · metrik değildir · tek bir skaler değildir · lojistik fonksiyon değildir · matris satırı değildir · özelliklerin ortalaması değildir · $[0,1]$ ile sınırlı değildir · bölünmez · yalnız izinlilik süzgeci değildir · yalnız çözüm sonrası okuma katmanı değildir · faz üstü statüsü yalnız boyutsuzluktan türemez.

### Aralık biçimciliği
"Noktasal fizik yasaktır" dili **kullanılmaz** · $[P,P]$ meşrudur ve özel bir mekanizma gerektirmez · aralık değerli olmak zamanla değişken olmak değildir.

### Topoloji ve cebir
Zincir topolojisi güncel değildir · karışım-simpleks modeli zorunlu değildir · $U_0$ topolojik merkez yapılmaz · ek topolojik yapılar ithal edilmez · birim ile "damga yok" tip düzeyinde özdeşleştirilmez · grup tamamlaması fiziksel tersinirlik anlamına gelmez.

### Genel
**Harita konumu ≠ faz üyeliği** · **sınır ≠ üyelik** · $U_x$ dördüncü faz ya da $X$'in başka adı değildir · boyutsuzluk geçiş için yeterli değildir · yapısal benzerlik doğrulama değildir · mekanizma ataması türetim değildir · aritmetik doğrulama fiziksel doğrulama değildir · biçimsel teorem fizik teoremi değildir · varlık kayda indirgenmez · konsensüs kanon değildir.

## 24.5 Çerçevenin kendi hakkındaki hükmü

$$\boxed{\;\text{Evertophy şu anda TAMAMLANMIŞ BİR KURAM DEĞİL, KURAM OLMAYA HAZIRLANMIŞ BİR YAPIDIR.}\;}$$

```latex
\boxed{\;\text{Evertophy şu anda TAMAMLANMIŞ BİR KURAM DEĞİL, KURAM OLMAYA HAZIRLANMIŞ BİR YAPIDIR.}\;}
```

---

## 24.6 X(x)'in rejimler arası geçiş sürekliliği sorusu

$X$'in farklı faz / rejimler arasında geçişte sürekli davranıp davranmadığı sorusu açıktır. Arşivdeki süreksiz limit riski kaydı korunur: aday bir $X$ tipi seçilirken geçişlerde süreksizlik üretip üretmediği ayrıca sınanmalıdır. Bu, $X$'in "tam matematiksel gerçeklemesi açık" kararının (24.3) somut uçlarından biridir.

## 24.7 m_Ξ etkin kütlesinin sayısal değeri sorusu

Faza bağlı yayıcı kütlesi $m_\Xi$ için sayısal değer önerisi arşivde bulunur; ama değer dondurulmamıştır. EK H disiplini gereği dondurulmamış sayı bu belgeye girmez.

## 24.8 Bilinç — temkinli işaret (ayrılmış çerçeve kaydı)

Arşivdeki kayıt tek cümleyle korunur: bilinç kavramı çerçevede yer almaz; "uzak hedef" olarak işaretlenmiştir.

$$\boxed{\;\text{Bilinç Evertophy'nin konusu değildir; gözlemci Cₘ içi fiziksel sistemdir (15.6).}\;}$$

```latex
\boxed{\;\text{Bilinç Evertophy'nin konusu değildir; gözlemci Cₘ içi fiziksel sistemdir (15.6).}\;}
```

## 24.9 Hamilton biçimciliğinin c₀'da reddedilme gerekçesi

c₀'da Hamilton biçimciliği reddedilir; gerekçe, Cₘ'deki yapının c₀'a ithal edilmesi yasağıdır (15.2). c₀'da zaman durmuş değil, **henüz kurulmamıştır**; "$dt = 0$" dili yalnız pedagojik bir kısaltma olarak kalır (3.2). Hamiltoniyenin kendisi c₀'daki durumun tanımı değildir.

---




# BÖLÜM 25 — AYRILMIŞ ONTOLOJİK BAŞLIKLAR VE MEKANİZMA ADAYLARI

Bu bölüm, çerçevede **açılmış ama kapatılmamış** başlıkları taşır. Hepsi kayıtlıdır; bazılarında **ad, ayrım kuralı ya da ontolojide yer alma kararı** mimar düzeyinde sabitlenmiş olabilir. Buna karşılık burada açık olarak işaretlenen başlıkların **tam ontolojik anlamı ve / veya mekanizması henüz kapanmamıştır**. Ayrılmış ontolojik başlık, mekanizma adayı ve tamamlanmış kanon aynı statüde değildir:

$$\boxed{\;\text{AYRILMIŞ ONTOLOJİK BAŞLIK} \;\neq\; \text{MEKANİZMA / DÜŞÜNCE DENEYİ ADAYI}\;}$$

```latex
\boxed{\;\text{AYRILMIŞ ONTOLOJİK BAŞLIK} \;\neq\; \text{MEKANİZMA / DÜŞÜNCE DENEYİ ADAYI}\;}
```

| Sınıf | Ne | Kim açar |
|---|---|---|
| **Ayrılmış ontolojik başlık** | Çerçeveye ekleneceği kararlaştırılmış, ama tam anlamı yazılmamış yapı | Yalnız mimar |
| **Mekanizma adayı** | Bir olguyu çerçeve diliyle okuma denemesi | Çalışma katmanı; ayrı türetim ve ön kayıt gerektirir |

İkisi aynı statüde değildir ve karıştırılmamalıdır.

---

## 25.1 Faz rejimi – eşik sınırı — ayrılmış ontolojik başlık

$$\boxed{\;\textbf{KANONİK AD: FAZ REJİMİ – EŞİK SINIRI}\;}$$

```latex
\boxed{\;\textbf{KANONİK AD: FAZ REJİMİ – EŞİK SINIRI}\;}
```

Üçgenin her kenarı için bir **faz rejimi – eşik sınırı** ontolojik başlığı ayrılmıştır. Ad çift bileşenlidir, çünkü ayrılan yapı rejim sınırı ile geçiş eşiği arasındaki ilişkiyi birlikte ifade etmek üzere kurulmuştur. Bu kayıt, sınırın nihai matematiksel tipini ya da fiziksel kalınlığını önceden belirlemez.

Bu başlık, yazarın "sınırda bulunma" hükmüyle doğrudan ilişkilidir (18.0): c eşik rejiminin sınırındaki bir yapı, aynı zamanda c⁺ rejiminin de sınırındadır. Faz rejimi – eşik sınırı, böyle yapıların ontolojideki yeridir; sınırda bulunmak iki fazın üyesi olmak demek değildir.

### Temsil ile fiziksel genişlik ayrımı

$$\boxed{\;\text{Faz rejimi – eşik sınırı, ontoloji gösteriminde keskin bir çizgi yerine SINIR BANDI olarak TEMSİL EDİLİR.}\;}$$

```latex
\boxed{\;\text{Faz rejimi – eşik sınırı, ontoloji gösteriminde keskin bir çizgi yerine SINIR BANDI olarak TEMSİL EDİLİR.}\;}
```

Bu bir **gösterim kararıdır**, fiziksel bir hüküm değil:

$$\text{"bant gösterimi kullanılır"} \;\neq\; \text{"fiziksel geçiş sonlu genişlikli bir banttır"}$$

```latex
\text{"bant gösterimi kullanılır"} \;\neq\; \text{"fiziksel geçiş sonlu genişlikli bir banttır"}
```

$$\boxed{\;\text{Bandın fiziksel genişliğinin sıfırdan farklı olup olmadığı ve matematiksel profili HENÜZ TÜRETİLMEMİŞTİR.}\;}$$

```latex
\boxed{\;\text{Bandın fiziksel genişliğinin sıfırdan farklı olup olmadığı ve matematiksel profili HENÜZ TÜRETİLMEMİŞTİR.}\;}
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Faz kenarlarındaki geçiş bölgesine ontolojide bir yer ayırır ve onu bant olarak gösterir |
| **Neden yapıyor?** | Işık, atom altı yapılar ve liminal rejim gibi sınır olgularının yerleştirileceği açık bir başlık olmadan, bunlar ya yeni bir faz ya da yanlış bir üyelik gibi okunurdu |
| **Nasıl yapıyor?** | Sınırı keskin bir çizgi yerine bant olarak gösterir; ama bunun fiziksel bir genişlik iddiası olmadığını açıkça ayırır |
| **Ne sonuç bekleniyor?** | Sınırın matematiksel tipinin, fiziksel genişliğinin ve mikrofiziksel profilinin türetilmesi |
| **Ne sonuç elde ediliyor?** | **Kanonik olan:** başlığın ontolojide ayrılması ve sınır / bant gösteriminin kullanılması. **Açık olan:** sınırın nihai matematiksel tipi, fiziksel genişliği ve mikrofiziksel profili |

**Karıştırılmamalı:** 12.1'deki eşik kanallarının geçişli karakteri, o kanallar için yazılmış **ayrı bir model ifadesidir**; buradaki gösterim kararının fiziksel kanıtı sayılmaz.

**Ne olmadığı — dört koruma:**

| Değildir | Neden |
|---|---|
| **Yeni bir faz değildir** | Faz sayısı üçtür |
| **Yeni bir kapı değildir** | Üç kenar zaten tanımlıdır |
| **Üçgen topolojisini değiştirmez** | Tam çift yönlü üçgen korunur |
| **Yeni bir düğüm değildir** | Çizgeye nokta eklemez |

**Amacı:** insan tarafından okunabilirlik, ontolojik sağlamlaştırma ve **sınır olgularının yerleştirilmesi**. Eşik geçişlerinin sigmoid karakteri (12.1) ve liminal rejim (15.3) bu bandın içinde konumlanır.

### Terim kuralı — kilitli

Çalışma sırasında bu yapıya, kolay hatırlanması için gündelik bir anahtar kelime kullanılmıştır. O kelime **yalnız bir hatırlatıcıdır**; ontolojik bir terim değildir ve çağrışımları çerçeveye ait değildir.

$$\boxed{\;\text{Gündelik anahtar kelime AKADEMİK METNE ve BU BELGEYE GİRMEZ. Tek geçerli ad: FAZ REJİMİ – EŞİK SINIRI.}\;}$$

```latex
\boxed{\;\text{Gündelik anahtar kelime AKADEMİK METNE ve BU BELGEYE GİRMEZ. Tek geçerli ad: FAZ REJİMİ – EŞİK SINIRI.}\;}
```

Bu bir üslup tercihi değildir: gündelik kelimenin taşıdığı ara durum / bekleme çağrışımları, bandın ontolojik içeriğiyle (rejim sınırı + geçiş eşiği) örtüşmez ve yanlış okumaya açıktır.

**Birleşik açık borç kaydı:** sınırın nihai matematiksel tipi; fiziksel genişliğinin sıfırdan farklı olup olmadığı ve neye bağlı olduğu; mikrofiziksel profili; $X$ ile ilişkisi; üç kenarda aynı mı yoksa farklı mı davrandığı.

---

## 25.2 SYNTAX — ayrılmış ontolojik başlık

SYNTAX, hangi yapılanmaların **fiziksel olarak geçerli** olduğunu belirleyen kural sistemi olarak düşünülmüştür.

$$\text{GEÇERLİ / GEÇERSİZ durum} \qquad \text{izinli / izinsiz faz geçişi yapılanması}$$

```latex
\text{GEÇERLİ / GEÇERSİZ durum} \qquad \text{izinli / izinsiz faz geçişi yapılanması}
```

**Ne olmadığı:** yeni bir faz değildir · yeni bir fiziksel nesne değildir · bir kuvvet ya da alan değildir.

### En kritik açık nokta

$$\boxed{\;\text{SYNTAX} \;\leftrightarrow\; U_x \;\leftrightarrow\; X(x) \quad \text{ilişkisinin TAM TİPİ AÇIKTIR.}\;}$$

```latex
\boxed{\;\text{SYNTAX} \;\leftrightarrow\; U_x \;\leftrightarrow\; X(x) \quad \text{ilişkisinin TAM TİPİ AÇIKTIR.}\;}
```

Üç olasılık kayıtlıdır ve hiçbiri seçilmemiştir:

| Olasılık | İçerik |
|---|---|
| (a) | SYNTAX, $U_x$'in **yerine** geçer |
| (b) | SYNTAX, $U_x$'in **içinde** bir katmandır |
| (c) | SYNTAX, $U_x$'in **üstünde** ayrı bir rol alır |

### Seçeneklerin mimari maliyeti — bağımlılık çözümlemesi

Üç seçenek **tarihsel karar uzayını** kaydeder; hiçbiri elenmemiştir. Ama iki düzeyli mimari kurulduktan sonra maliyetleri eşit değildir:

$$\boxed{\;\text{(a) seçeneği, } U_x\text{'in Dinamik Evren rolünün YENİDEN TANIMLANMASINI gerektirir — en yüksek yeniden yazım maliyeti.}\;}$$

```latex
\boxed{\;\text{(a) seçeneği, } U_x\text{'in Dinamik Evren rolünün YENİDEN TANIMLANMASINI gerektirir — en yüksek yeniden yazım maliyeti.}\;}
```

Nedeni kategoriktir: $U_x$ küresel ontolojide bir **evren yapısıdır**; SYNTAX ise bir **kural sistemidir**. Programlama diliyle söylersek: *bir programın çalışan durumu* ile *o dilin dilbilgisi* aynı nesne değildir. Bu bir karar değil, **bağımlılık çözümlemesidir**.

### Aday ayrım — kanon değil

| Nesne | Aday tanım |
|---|---|
| **SYNTAX** | Hangi yapı ya da yapılanmaların geçerlilik koşullarını taşıyabileceğini sınırlayan **kabul edilebilirlik / tutarlılık kural yapısı** |
| **$X$** | Verilmiş tam faz / rejim / bağlam durumunda hangi rejim ve değerin çözüldüğünü belirleyen **verili durum çözücüsü** |

Bu aday ayrımda **SYNTAX'ın zorunlu olarak durumdan bağımsız, bağlamdan bağımsız ya da değişmez bir dilbilgisi olduğu varsayılmaz**. Uygulanabilir kısıtların faz / rejim bağlamına göre farklılaşması açık tutulur.

Satranç benzetmesiyle: SYNTAX geçerlilik kurallarıdır; $X$ ise mevcut tahtayı ve geçerli bağlamı okuyup o durumda hangi hamlelerin fiilen izinli olduğunu çözen motordur. Rok, şah durumu ya da geçerken alma gibi kuralların uygulanmasının mevcut duruma bağlı olabilmesi, **kural yapısı** ile **durum çözücüsünün** aynı nesne olmasını gerektirmez. **Bu ayrım kanon değildir**; kararı kolaylaştıran bir adaydır.

Bu sınır netleşmelidir — $X$ zaten "hangi değerlerin izinli olduğunu çözen" nesnedir (4.1); dolayısıyla iki kavramın çakışma riski vardır.

**Açık karar borcu:** SYNTAX'ın nihai ontolojik / biçimsel kategorisi — ayrı bir varlık mı, kural yapısı mı, yoksa $X$'in uymak zorunda olduğu üst kısıt ailesi mi olduğu — mimar kararı ve sonraki biçimselleştirmeyle kapanacaktır.

$$\boxed{\;\text{V24 yazımında bu ilişki ÇÖZÜLMÜŞ KABUL EDİLMEZ.}\;}$$

```latex
\boxed{\;\text{V24 yazımında bu ilişki ÇÖZÜLMÜŞ KABUL EDİLMEZ.}\;}
```

---

## 25.3 Faz Çöküşü — ayrılmış ontolojik başlık

Ayrı bir ontolojik olgu olarak ayrılmıştır.

$$\boxed{\;\text{Faz Çöküşü} \;\neq\; \text{sıradan faz geçişi}\;}$$

```latex
\boxed{\;\text{Faz Çöküşü} \;\neq\; \text{sıradan faz geçişi}\;}
```

Sıradan geçiş, kapı üzerinden gerçekleşen ve damga üretebilen bir olaydır (Bölüm 13). Faz Çöküşü bununla **eş anlamlı kabul edilmez**. **Ayrıntıları mimarda ayrılmıştır.** Bu belge mekanizma uydurmaz; başlığı ve ayrım kuralını kaydeder.

---

## 25.4 Faz Yırtılması — ayrılmış ontolojik başlık

Faz Çöküşü'nden ayrı ve bağımsız bir başlıktır.

$$\boxed{\;\text{Faz Yırtılması} \;\neq\; \text{Faz Çöküşü} \qquad\qquad \text{Faz Yırtılması} \;\neq\; \text{yeni faz ya da kapı}\;}$$

```latex
\boxed{\;\text{Faz Yırtılması} \;\neq\; \text{Faz Çöküşü} \qquad\qquad \text{Faz Yırtılması} \;\neq\; \text{yeni faz ya da kapı}\;}
```

**Eşsesli terim uyarısı:** Bu başlık, küresel düzeydeki **Big Yırtılma** ile (2.8) **aynı şey değildir**. Big Yırtılma, bütün $U_x$ yapısının $U_+$ formuna eriştiği küresel olaydır; orada **Mutlak Yırtılma ile Mutlak Çözünme aynı şeyi ifade eder** (yazar hükmü). Faz Yırtılması ise faz düzeyinde bir olgudur. Ortak sözcük anlam birleştirme yetkisi vermez.

**Olası olgusal köprü:** renk hapsi altında akı tüpünün kopması (25.8). Ama:

$$\boxed{\;\text{Renk akı tüpünün kopması} \;\neq\; \text{Faz Yırtılması}\;}$$

```latex
\boxed{\;\text{Renk akı tüpünün kopması} \;\neq\; \text{Faz Yırtılması}\;}
```

Bu yalnız bir köprü adayıdır; kimlik değildir.

---

## 25.5 Büyük Boşluk (Massive Void) — ayrılmış ontolojik türetim

Büyük kozmik boşlukların farklı dalga boylarıyla gözlenmesi ve bu bölgelerde yeni yıldız oluşumu. c⁺ ≡ vakum kimliği altında kozmik boşluklar c⁺'ın en saf Cₘ okumalarından biridir (Bölüm 3); bu başlık, böyle bölgelerde Cₘ yapısının nasıl ortaya çıkabildiğini sorar.

### Kaynak ayrımı zorunlu

Arşivde bu konuda **daha eski bir anlatım** bulunur. Yeni türetim onun tekrarı değildir.

$$\boxed{\;\text{Eski Büyük Boşluk anlatımı} \;\neq\; \text{yeni ontolojik türetim}\;}$$

```latex
\boxed{\;\text{Eski Büyük Boşluk anlatımı} \;\neq\; \text{yeni ontolojik türetim}\;}
```

İki kayıt birbirine karıştırılmaz; yeni türetim kendi gerekçesiyle kurulur. **Ayrıntıları mimarda ayrılmıştır.**

---

## 25.6 Pauli dışlama ↔ faz rejimi – eşik sınırı davranışı — yüksek öncelikli mekanizma adayı

Pauli dışlama ilkesinin, faz sınırındaki olgu davranışıyla ilişkilendirilmesi. Olası araştırma zinciri:

$$\text{faz rejimi – eşik sınırı} \;\rightarrow\; \text{erişilebilir durum uzayının kısıtlanması} \;\rightarrow\; \text{çift işgal yasağı} \;\rightarrow\; \text{Pauli olgubilimi}$$

```latex
\text{faz rejimi – eşik sınırı} \;\rightarrow\; \text{erişilebilir durum uzayının kısıtlanması} \;\rightarrow\; \text{çift işgal yasağı} \;\rightarrow\; \text{Pauli olgubilimi}
```

### Üç bilimsel eşik

Bu hattın benzetme olmaktan çıkıp mekanizma sayılabilmesi için:

| # | Eşik |
|---|---|
| **1** | Pauli sonucu **baştan varsayılmadan** çıkmalı |
| **2** | Antisimetri, spin-$\tfrac{1}{2}$ ve özdeş fermiyon yapısıyla **uyuşmalı** |
| **3** | Yeni ya da önceden belirlenmiş bir **gözlemsel davranış** üretmeli |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Pauli dışlamayı, atom altı yapıların bulunduğu faz sınırının durum uzayını kısıtlaması olarak okumayı önerir |
| **Neden yapıyor?** | Atom altı düzeyin c⁺ ile Cₘ'nin ortak sınırında bulunması (18.0) doğruysa, bu sınırın kuantum istatistiğinde bir izi olması beklenir |
| **Nasıl yapıyor?** | Sınırdan durum uzayı kısıtına, oradan çift işgal yasağına giden bir zincir yazar ve mekanizma statüsü için üç eşik koyar |
| **Ne sonuç bekleniyor?** | Pauli sonucunun varsayılmadan türetilmesi ve yeni bir gözlemsel davranış |
| **Ne sonuç elde ediliyor?** | Üç eşik sağlanmadan bu hat **benzetme düzeyindedir** |

**Model notu (2026-10-13 düşünce deneyi).** Ölçek–kütle faz haritasını kullanan bir düşünce deneyinde nötron yıldızları, kütleçekim eşik çizgisinin (Schwarzschild yarıçapı çizgisi) geçiş bandının içine düşmüş; dejenere fermiyon desteğinin bu eşiğin hemen önünde bittiği nicel bir aday bant elde edilmiştir (V24 §732). Not üç eşikten hiçbirini sağlamaz; hat mekanizma adayı statüsünde kalır. "Pauli kararlılığı garanti eder" okuması reddedilmiştir: destek Chandrasekhar ve TOV sınırlarının üstünde çöker ve madde kararlılığı için Pauli tek başına yetmez.

---

## 25.7 Kara delik çevresindeki vakumda c⁺ → Cₘ — düşünce deneyi

Bir kara deliğin, kütleçekim etkisiyle bulunduğu ortamdaki c⁺ yapısını madde fazına indirip indirmediği sorusudur. c⁺ ≡ vakum kimliği altında bu soru, "kara delik çevresindeki vakumdan madde doğuyor mu?" sorusuyla aynıdır.

$$c^+_{\rm yerel} \;\xrightarrow[\text{güçlü çekim / faz eşiği}]{} \; C_m$$

```latex
c^+_{\rm yerel} \;\xrightarrow[\text{güçlü çekim / faz eşiği}]{} \; C_m
```

$$\boxed{\;\text{Kara delik maddeyi YOKTAN ÜRETMEZ; } c^+ \text{ içeriğinin } C_m \text{'ye geçişini HIZLANDIRIYOR (KATALİZLİYOR) olabilir.}\;}$$

```latex
\boxed{\;\text{Kara delik maddeyi YOKTAN ÜRETMEZ; } c^+ \text{ içeriğinin } C_m \text{'ye geçişini HIZLANDIRIYOR (KATALİZLİYOR) olabilir.}\;}
```

Olası gözlemsel imza bir **kalıntıdır**:

$$L_{\rm gözlenen} \;>\; L_{\rm toplanma,max} + L_{\rm spin,max} + L_{\rm depo,max}$$

```latex
L_{\rm gözlenen} \;>\; L_{\rm toplanma,max} + L_{\rm spin,max} + L_{\rm depo,max}
```

| Sembol | Anlamı |
|---|---|
| $c^+_{\rm yerel}$ | Kara delik çevresindeki c⁺ (vakum) içeriği |
| $L_{\rm gözlenen}$ | Gözlenen toplam ışıma gücü |
| $L_{\rm toplanma,max}$ | Madde toplanmasından (akresyon) gelebilecek en büyük güç |
| $L_{\rm spin,max}$ | Dönme enerjisinin çekilmesinden gelebilecek en büyük güç |
| $L_{\rm depo,max}$ | Depolanmış enerjiden gelebilecek en büyük güç |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kara deliğin çevresindeki vakumdan Cₘ maddesi ortaya çıkışını hızlandırıp hızlandırmadığını sorar ve bunun ışıma bütçesindeki izini tanımlar |
| **Neden yapıyor?** | c⁺ ≡ vakum ve c⁺ → Cₘ kenarı varsa, en güçlü çekim ortamında bu kenarın gözlenebilir bir etkisi olup olmadığını sınamak için |
| **Nasıl yapıyor?** | Bilinen bütün enerji kaynaklarının en büyük katkılarını toplar; gözlenen güç bunu aşarsa bir kalıntı arar. Daha güçlü imza, çevrede yeterli baryonik kaynak yokken yeni Cₘ maddesinin ortaya çıkması olurdu |
| **Ne sonuç bekleniyor?** | Standart kaynaklarla açıklanamayan bir ışıma ya da madde fazlası |
| **Ne sonuç elde ediliyor?** | **Düşünce deneyidir**, kanon değildir. Bu imzalar **öngörü değildir**: öngörü olabilmesi için 0/10 → 1/10 kapısının altı koşulunu (0.4) sağlaması gerekir |

---

## 25.8 Renk hapsi ↔ faz limiti / SYNTAX — güçlü türetim adayı

Kuark hapsi, akı tüpünün gerilmesi, kopması ve çift üretimi zinciri.

**İki olası çerçeve rolü:**

| Faz | Rol |
|---|---|
| c₀ | Cₘ yapılanmasının **sürdürülebilirlik limiti** |
| c⁺ | Yeni Cₘ durumuna erişim — **çift üretimi** tarafı (c⁺ ≡ vakum) |

**SYNTAX okuması (aday):**

$$\text{serbest renk durumu} = \text{GEÇERSİZ} \qquad\qquad \text{renk-nötr hadron} = \text{GEÇERLİ}$$

```latex
\text{serbest renk durumu} = \text{GEÇERSİZ} \qquad\qquad \text{renk-nötr hadron} = \text{GEÇERLİ}
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Renk hapsini, SYNTAX'ın bir geçerlilik kuralı ve faz limitlerinin bir sonucu olarak okur |
| **Neden yapıyor?** | Hapsin ölçülmüş olgubilimi (serbest kuark yok, akı tüpü kopunca çift üretimi), geçerli / geçersiz yapılanma diline doğal olarak uyar |
| **Nasıl yapıyor?** | Serbest renk durumunu geçersiz, renk-nötr hadronu geçerli sayar; akı tüpü kopmasını c⁺ (vakum) tarafından yeni Cₘ çiftlerinin doğuşu olarak okur |
| **Ne sonuç bekleniyor?** | SU(3) yapısının ve hapsin faz yapısından türetilmesi (20.10) |
| **Ne sonuç elde ediliyor?** | **Güçlü türetim adayıdır.** 18.4'teki kısıtla birlikte okunur: vakumdan çift üretimi hesapları **verili bir metrik** varsayar ve c₀'a uygulanamaz. Zincirin Cₘ içinde kalan kısmı meşrudur |

---

## 25.9 Görsel yardımcı katmanlar — düşünce deneyi

| Katman | İçerik | Koruma |
|---|---|---|
| **Dalga boyu çarpanı** | Faz rejimlerinin $\lambda$, $\nu$, $E$ ile farklı gözlem bantlarında nasıl göründüğü | Resmî denklem değil; görsel / yorum katmanı |
| **Kara delik eşik çarpanı** | *"Her yoğun yapı kara delik değildir"* ayrımının eşik mantığıyla gösterimi | **Evrensel bir sabit değildir**; ayrıntıları mimarda ayrılmış |

**Hız bandı notu:** Kanonik görselde Cₘ altında bir hız bandı gösterimi düşünülmektedir: $0<v<c$ üyelik bandı ve $v=c$ liminal ortak sınır. Buradaki hız **yerel laboratuvar hızı değildir**; çerçevenin kozmolojik referansına göre değerlendirilen parametredir. Laboratuvar hızının sıfır olması bir c₀ üyeliği **sayılmaz** (3.7).

---

## 25.10 Faz sızması ve eski zaman sınırı kayıtları — hizalama borcu

Arşivde faz sızması, sınır rejiminde $\Delta t \approx 0$ görünümü ve faz uyumsuz ölçüm üzerine eski kayıtlar bulunur (18.6).

$$\boxed{\;\text{Eski arşiv girdisi} \;\neq\; \text{yeni faz rejimi – eşik sınırı çalışması}\;}$$

```latex
\boxed{\;\text{Eski arşiv girdisi} \;\neq\; \text{yeni faz rejimi – eşik sınırı çalışması}\;}
```

Bu kayıtların 25.1'deki sınır diliyle yeniden hizalanması gerekir; ama iki katman **ayrı tutulmalıdır** — eski anlatımın terimleri yeni bandın tanımı sayılmaz.

---

## 25.11 Bu bölümün statü özeti

| Başlık | Sınıf | Statü |
|---|---|---|
| **Faz rejimi – eşik sınırı** | Ayrılmış ontolojik | Başlığın ayrılması + sınır / bant gösterim kararı sabit; nihai tip, fiziksel genişlik ve mikrofiziksel profil açık |
| SYNTAX | Ayrılmış ontolojik | $U_x$ / $X$ ilişkisi **açık** |
| Faz Çöküşü | Ayrılmış ontolojik | Ayrıntı mimarda |
| Faz Yırtılması | Ayrılmış ontolojik | Ayrıntı mimarda |
| Büyük Boşluk | Ayrılmış ontolojik türetim | Kaynak ayrımı zorunlu |
| Pauli ↔ faz rejimi – eşik sınırı | Mekanizma adayı | **Yüksek öncelikli**; üç eşik |
| Kara delik çevresinde c⁺ → Cₘ | Düşünce deneyi | Kanon değil |
| Renk hapsi ↔ SYNTAX | Türetim adayı | Güçlü |
| Görsel katmanlar | Düşünce deneyi | Denklem değil |
| Faz sızması hizalaması | Hizalama borcu | Katman ayrımı zorunlu |

$$\boxed{\;\text{Bu bölümdeki HİÇBİR madde, ayrı türetim ve ön kayıt olmadan ÖNGÖRÜ sayılmaz. Sayaç } \mathbf{0/10}.\;}$$

```latex
\boxed{\;\text{Bu bölümdeki HİÇBİR madde, ayrı türetim ve ön kayıt olmadan ÖNGÖRÜ sayılmaz. Sayaç } \mathbf{0/10}.\;}
```

**Eşleme koruması:** V24 bütün dosya denetiminden taşınan yöntem / kaynak kayıtları, Bölüm 25'teki ayrılmış başlıkların statüsünü yükseltmez; SYNTAX, faz sınırı ve $\Pi_{+\to m}$ uyumu mimar kararı beklemeye devam eder.

---

## 25.12 Kalıntı alan biçimciliği (v0.1 aksiyom kümesi → v0.4 parametrik model)

Faz izinin (7.9) alan kuramı gerçeklemesi olarak geliştirilmiş parametrik model ailesidir. Arşivdeki gelişim hattı: v0.1 genel kurallar → v0.2 Lorentz koruması ve klasik limit → v0.3 süreklilik sınırı → v0.4 $F(\rho)\,Z(\Phi,\rho)$ parametrik model.

$$\boxed{\;\text{Bu blok } X \text{'i skalerleştirmez; zaman dışı fazlara Cₘ zamanı taşımaz; çekirdek yasa değildir.}\;}$$

```latex
\boxed{\;\text{Bu blok } X \text{'i skalerleştirmez; zaman dışı fazlara Cₘ zamanı taşımaz; çekirdek yasa değildir.}\;}
```

## 25.13 Faz içi dalgalar (IPW) modeli

Tek bir faz içindeki dalga benzeri modların çerçeve içi modelidir; önceden kayıtlı test kartı 21.19'dadır. "Bir sonraki heyecan verici pencere" dili arşiv notudur; statü taşımaz.

### IPW oyuncak modeli — X_T spektral ayrışma

Tek cisimli oyuncak modelde $X_T$ için spektral ayrışma imzasının taramasıdır; koşul kümesi 21.19'dadır.

## 25.14 Kinematik ikilik postülası — tam biçim ve Z işlemcisi köprüsü

Arşivdeki tarihsel ikilik (4.2 kaydıyla aynı kaynak) burada tam biçimiyle korunur:

$$\Phi(c^+, C_m, c_0) = \mathrm{T}(z^+, z_m, z_0),\qquad \Phi\,e^{+i\pi} = \mathrm{T}\,e^{-i\pi}$$

```latex
\Phi(c^+, C_m, c_0) = \mathrm{T}(z^+, z_m, z_0),\qquad \Phi\,e^{+i\pi} = \mathrm{T}\,e^{-i\pi}
```

| Sembol | Anlamı |
|---|---|
| $\Phi$ | Tarihsel "faz" tarafı (17'deki $\Phi_\chi$ ile özdeş değil) |
| $\mathrm{T}$ | Tarihsel "zaman–geometri" tarafı; tipi tamamlanmamış |
| $z^+$, $z_m$, $z_0$ | Üç faza karşılık gelen tarihsel koordinatlar |
| $e^{\pm i\pi}$ | Karşı faz çarpanları (ikisi de $-1$) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Faz tarafı ile zaman–geometri tarafı arasında tarihsel bir ikilik önerir |
| **Neden yapıyor?** | Erken katmanda fazları kinematik bir ikilikle birleştirme denemesiydi |
| **Nasıl yapıyor?** | İki tarafı eşitler ve karşı faz biçimiyle zıt yönlü iki fazı yazar |
| **Ne sonuç bekleniyor?** | Z işlemcisi ($Z:\Phi\to\mathrm{T}$) üzerinden bir dinamik yasa |
| **Ne sonuç elde ediliyor?** | **Tarihsel kayıttır.** Karşı faz biçimi, $e^{+i\pi}=e^{-i\pi}=-1$ olduğundan cebirsel olarak yalnız $\Phi=\mathrm{T}$'ye indirgenir. Z işlemcisi güncel $X$ tanımına temel öğe olarak eklenmez (23.10b) |

## 25.15 Üç metrik rejim ayrışması — g(0) / g(m) / g(+)

Üç faz için üç metrik okumasının ayrıştırılması önerisidir: $g^{(0)}$ c₀ okuması (kabul edilebilir değil — 9.3), $g^{(m)}$ Cₘ metriği (tek meşru alan), $g^{(+)}$ c⁺ okuması (kabul edilebilir değil). Ayrışma önerisi bir gösterim tasarımıdır; dış fazlara metrik geri getirmez.

## 25.16 X(x) ≈ ln(a) kozmoloji köprüsü

Hubble genişlemesi ile $X$ arasında bir aday köprü:

$$\xi_{\rm koz}(x)=\pi_{\rm koz}[X](x)\approx\ln a$$

```latex
\xi_{\rm koz}(x)=\pi_{\rm koz}[X](x)\approx\ln a
```

| Sembol | Anlamı |
|---|---|
| $\pi_{\rm koz}$ | $X$'in kozmolojik okuma izdüşümü |
| $\xi_{\rm koz}$ | Kozmolojik okuma |
| $a$ | Kozmik ölçek çarpanı |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | $X$'in kozmolojik okumasını ölçek çarpanının logaritmasına bağlar |
| **Neden yapıyor?** | Genişleme geçmişi ile çözücü arasında basit, sınanabilir bir köprü aramak için |
| **Nasıl yapıyor?** | Okumayı $\ln a$'ya eşitler; genelleştirilmiş biçimleri de arşivde tutar |
| **Ne sonuç bekleniyor?** | Kozmolojik veriyle temas |
| **Ne sonuç elde ediliyor?** | **Aday köprüdür**, kanon değildir. Arşivdeki "$X(x)\approx\ln a$" yazımı, $X$'in kendisi skaler olmadığından burada okuma $\xi=\pi(X)$ üzerinden yazılmıştır. Temas noktası 21.11'deki uyum düzeyi denetimidir |

## 25.17 Krylov doygunluğu ↔ ξ_sat → ξ_sat^max eşlemesi

Kuantum evriminin Krylov alt uzayı doygunluğunun, $X$'in doygunluk okumasının uç rejimiyle eşlenmesi önerisidir. Arşivdeki "$X\to1$" yazımı güncel gösterimde doygunluk okumasıyla ifade edilir:

$$\xi_{\rm sat}=\pi_{\rm sat}(X)\;\to\;\xi_{\rm sat}^{\max}$$

```latex
\xi_{\rm sat}=\pi_{\rm sat}(X)\;\to\;\xi_{\rm sat}^{\max}
```

Aday köprüdür; sayısal doğrulama açıktır.

## 25.18 Küresel üniterlik + yerel Kraus aksiyom kümesi

16.6'daki çift katmanlı yapının aksiyom ifadesidir. Model katmanıdır; ontolojinin temel öğesi değildir.

## 25.19 Işık = tutarlılık kısıtı okuması

$c$'nin Cₘ tutarlılık kısıtı olarak okunmasının (3.3) arşiv genişletmesidir: ışık hızı sınırı bir madde hızı yasağı olarak değil, bilgi işleme / kayıt / çözünürlük limiti olarak işlenir. $v=c$, Cₘ ile c⁺'ın liminal ortak sınırıdır. Bu okuma çekirdek hükümle uyumludur; ek mekanizma eklemez.

## 25.20 Yapısal çözülme — sabit kayma senaryosu

Çerçevenin yapılarının (gök cisimleri, çekirdekler) uzun vadede çözülme senaryosu: yörünge sönümü → kararsızlık → ayrışma zinciri. Senaryo tasarımıdır; gözlemsel taahhüt değildir.

## 25.21 Evrenin sonu — iki senaryo kaydı

Arşivdeki dört aşamalı anlatı (düzenli son → kademeli çözülme → durağanlaşma → sonsuz seyrelme), güncel iki kutuplu dille (2.8) hizalanmıştır: iki senaryo küresel kutuplara bağlanır. $U_+$ yönündeki son, Mutlak Yırtılma ≡ Mutlak Çözünme olarak adlandırılır ve aynı zamanda yeni bir doğuştur. Kıyamet bilimsel (eskatolojik) okuma yasaktır (2.6).

## 25.22 Kozmik süper atom iddiası

Evrenin "süper atom" olarak okunması iddiasıdır; BEC / süper atom benzetme ailesinin kozmik uç örneğidir. Benzetme düzeyindedir; gerçek bir kimlik kurulmamıştır. BEC c₀ değildir (18.5).

## 25.23 Çeviri matrisi — Cₘ ↔ dış faz okuma dönüşümü

Dış faz kavramlarının Cₘ okumasına çevrildiği çalışma matrisidir: kayıt / ölçüm / vakum / faz sınırı terimlerinin iki katman arasında taşınma kuralları. 13.1a'daki "taşıma ≠ okuma" hükmünün çalışma aracıdır.

## 25.24 Faz iletkenliği

Fazlar arası etki aktarımının "iletkenlik" diliyle modellenmesi önerisidir. Elektrik iletkenliği gösterimi ödünç alınır; yapısal benzerlik doğrulama değildir (17.3).

## 25.25 Faz eşzamanlama mekanizması

c₀ ↔ c⁺ $X$-koordinasyonunun (13.6) bir eşzamanlama mekanizması olarak gerçeklenmesi adayıdır. Mekanizma yazılmamıştır; başlık program kaydıdır. Eşzamanlama burada zaman dışı bir uyum ilişkisidir; fiziksel bir zaman akışı varsaymaz.

## 25.26 Evren çekirdeği — üç senaryo hesabı

Evrensel çekirdek ölçeği için arşivdeki üç hesap senaryosu (CMB'ye kilitli, CMB+MPC, CMB+SN) ve iç tutarlılık penceresi (~$10^{47}$ ışık yılı). Senaryolar 2.10'un hesap gövdesidir; sayısal sonuçlar EK H disiplinindedir.

## 25.27 Dinamik çekim şablonu

Göreli yıldız modellerinde dinamik çekim için kullanılan şablon kayıtlarıdır (özel görelilikte Mestel yıldızı; genel görelilikte yıldız modelleri; dönme, çerçeve sürüklenmesi). Bağlam kaydıdır; Evertophy türetimi değildir.

## 25.28 Kara delik içi tek-yapı okumaları

Kara delik içi için arşiv öngörü kayıtları (gölge imzaları, evrensel Boyer–Lindquist ölçekleri) korunur; bunlar öngörü statüsü taşımaz. Güncel sürümde iki unsurun statüsü değişmiştir: **metrik boşluksuz tek-yapı** ve **yoğunluğun kütleyle artmaması** (daha kütleli kara delik daha yoğun değildir; hacim kütleyle büyür) artık tarihsel proje iddiası değil, **yazar hükmüdür** (Bölüm 3). Hacmin kütleyle **tam doğru orantısı** ise ortalama yoğunluğun kütleden bağımsız olduğu sabit yoğunluk gerçeklemesinde ($\rho_{c_0}=\rho_*$) geçerlidir:

$$N_{c_0}=\frac{M}{m_P},\qquad \rho_{c_0}\le\rho_P,\qquad V_{c_0}\ge N_{c_0}\,\ell_P^3\;\propto\;M,\qquad R_{c_0}\propto M^{1/3}\ \ (\rho_{c_0}=\rho_*\ \text{sabit})$$

```latex
N_{c_0}=\frac{M}{m_P},\qquad \rho_{c_0}\le\rho_P,\qquad V_{c_0}\ge N_{c_0}\,\ell_P^3\;\propto\;M,\qquad R_{c_0}\propto M^{1/3}\ \ (\rho_{c_0}=\rho_*\ \text{sabit})
```

| Sembol | Anlamı |
|---|---|
| $N_{c_0}$ | Çekirdek kapasitesinin Planck kütlesi biriminde sayımı |
| $M$ | Kara deliğin kütlesi |
| $m_P$ | Planck kütlesi |
| $\rho_{c_0}$ | Tek-yapının yoğunluğu |
| $\rho_P$ | Planck yoğunluğu ($\approx5.16\times10^{96}\ \mathrm{kg/m^3}$) |
| $V_{c_0}$ | Tek-yapının hacmi |
| $\ell_P$ | Planck uzunluğu |
| $R_{c_0}$ | Tek-yapının yarıçap ölçeği |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kara delik içi tek-yapının kütle, yoğunluk ve hacim ilişkilerini yazar hükmüne göre sabitler |
| **Neden yapıyor?** | Eski kayıtta "tarihsel proje iddiası" olarak duran bu ilişkiler, 2026-10-14 yazar onaylarıyla çekirdeğe alınmıştır |
| **Nasıl yapıyor?** | Kapasiteyi Planck kütlesiyle sayar; yoğunluğu Planck yoğunluğuyla sınırlar; sabit yoğunluk gerçeklemesinde hacmin kütleyle doğru orantılı büyüdüğünü ve yarıçapın kütlenin küp köküyle ölçeklendiğini yazar |
| **Ne sonuç bekleniyor?** | İç profilin ve olay ufkuyla nicel ilişkinin türetilmesi; gölge ve ölçek imzalarının bu yapıdan öngörülmesi |
| **Ne sonuç elde ediliyor?** | Tek-yapı ve yoğunluğun kütleyle artmaması **yazar hükmüdür**; tam doğru orantı sabit yoğunluk gerçeklemesinin sonucudur; tek-yapının iç profili, ufukla ilişkisi ve gözlemsel imzaları **açık borçtur** (EK K.1). Gölge ve Boyer–Lindquist kayıtları öngörü değildir |

## 25.29 Kırmızıya kaymanın konumlandırılması

Kozmik kırmızıya kaymanın faz haritasındaki konumlandırılması kaydıdır. 11.7'deki kırmızıya kayma köprü satırıyla aynı statüdedir.

## 25.31 Evertophy periyodik cetveli / Mendeleyev tarzı alan çizelgesi

Faz-parametre matrisinin (Bölüm 5) alan çizelgesi düzeyindeki sunum önerisidir. Gösterim aracıdır; ontolojik içerik eklemez.

## 25.32 Frekans dönüşümü düşünce deneyi

Frekans / enerji ölçeklerinin faz okumaları arasında dönüştürülmesi düşünce deneyidir; 25.9'daki dalga boyu çarpanı katmanıyla aynı ailededir.

---




# BÖLÜM 26 — OLGULAR, AÇIK PROBLEMLER VE EVERTOPHY'NİN ADAY OKUMALARI

Bu bölüm, yerleşik fiziksel olguları, kuramsal açık problemleri ve Evertophy'nin bunlara ilişkin aday okumalarını bir başlık haritasında birlikte sunar. Bir başlığın burada yer alması, modern bilimin o olguyu açıklayamadığı ya da Evertophy'nin onu çözdüğü anlamına gelmez; her satır kendi kaynak ve türetim statüsüyle değerlendirilir.

$$\boxed{\;\text{Her okuma "adaydır"; hiçbiri "çözdü" değildir. Bu bölümün tamamı 0.3 ve 23.9 dil disiplinine tabidir.}\;}$$

```latex
\boxed{\;\text{Her okuma "adaydır"; hiçbiri "çözdü" değildir. Bu bölümün tamamı 0.3 ve 23.9 dil disiplinine tabidir.}\;}
```

Bu bölümdeki her satır bir **okumadır, açıklama değildir.** Modern bilimin ölçtüğü olgu olduğu gibi kabul edilir; Evertophy'nin önerdiği okuma o ölçümün üzerine ayrı bir katman olarak konur ve sınanmaya adaydır (Yazardan Okuyucuya). Bir okumanın bu listede yer alması, onun nicel olarak türetildiği ya da doğrulandığı anlamına gelmez. Bölüm, yerleşik olguları (ölçülmüş ama açıklaması tartışmalı) ve kuramsal açık problemleri birlikte listeler; her satırın statüsü ayrıdır. Bu bölüm sayaca hiçbir katkı yapmaz:

$$\boxed{\;\text{Kanonik sayısal öngörü sayacı: } 0/10\;}$$

```latex
\boxed{\;\text{Kanonik sayısal öngörü sayacı: } 0/10\;}
```

## 26.1 Kozmolojik olgular

| Olgu | Aday okuma | Statü |
|---|---|---|
| Karanlık madde / dönme eğrileri | c⁺'ın kümelenmiş Cₘ görünümü (11.1a, 11.2) | Aday — nicel türetim yok |
| Karanlık enerji / fantom sınırı | c⁺'ın genişlemeyi sürdüren Cₘ görünümü | Aday (11.9) |
| Hubble gerilimi | Ölçeğe bağlı etkin kütleçekim okuması adayı | Aday — yalnız köprü yanlışlama programı (11.7). Çerçevenin önceki Hubble iddiası **üç kez geri çekilmiştir** (V24 §538.3) |
| S8 / σ8 gerilimi | Köprü yanlışlama programı satırı | Aday |
| Çekirdek-hale / küçük ölçek krizleri | c⁺ kümelenme rejiminin Cₘ okuması | Aday |
| MOND ve değiştirilmiş kütleçekim | Paradigmalar arası köprü bağlamı | Bağlam |
| Kozmolojik sabit problemi | c⁺ ≡ vakum kimliği altında vakum enerjisinin c⁺ payının Cₘ okumasıyla ilişki adayı | Aday |
| Karanlık akış (dark flow) | c⁺ yöneliminin Cₘ izdüşümü olarak okunabilir | Bağlam |
| Kozmik çift kırılma | Kalibrasyon açıklanana dek bağlam | Bağlam (21.18) |
| Big Yırtılma senaryosu | Küresel düzeyde doğuş olayı (2.8); Mutlak Yırtılma ≡ Mutlak Çözünme — eşsesli terim uyarısı geçerli | Kanonik çerçeve, fiziksel senaryo değil |

## 26.2 Erken evren ve başlangıç olguları

| Olgu | Aday okuma |
|---|---|
| Big Bang tekilliği / şişme öncesi | $U_0$ sınırındaki kritik eşik + üç fazın birlikte doğuşu (2.4) |
| Ufuk problemi | Birlikte doğuşun doğal sonucu olarak okunmaya aday |
| Düzlük problemi | Başlangıç koşullarının $U_0$ kaynaklı okuması — aday; temel uzayın düz Öklid olması (9.2a) ile ilişkisi açık |
| Tek kutup (monopol) problemi | Faz yapısının ayar alanı doğuşu kısıtı olarak okunmaya aday |
| Baryon oluşumu | Açık borç (20.7) |

## 26.3 Kuantum olguları

| Olgu | Aday okuma |
|---|---|
| Ölçüm problemi | Liminal rejim → Cₘ izdüşümü → mühürleme (15.3) |
| Dolanıklık | c⁺'ta yazmaya karşı korumalı korelasyon (18.6) — sinyal kanalı değil |
| Kuantum ışınlama | c⁺ korelasyon kaynağı + Cₘ klasik kanalı (18.1) — uyumlu okuma |
| Hartman etkisi | Faz eşiği bölgesinde saf geçiş süresi dilinin yetersizliği (EK D) |
| Ertelenmiş seçim / kuantum silici | Mühürleme kararının zaman indeksinden bağımsız tutarlılığı (18.10) — uyumlu okuma |
| Zaman kristalleri | Cₘ içi periyodik yapı — faz dilinde yeniden okunabilir; aday |

## 26.4 Standart Model olguları

| Olgu | Aday okuma / statü |
|---|---|
| İnce ayar | Aralık biçimciliğinin motivasyonu; açıklama değil |
| Hiyerarşi problemi | Açık borç |
| Güçlü-CP | Program hedefi (20.4a) |
| Nötrino kütlesi / salınımı | Açık borç (20.7); salınım, faz eşiği sınırında bulunma okumasına aday (18.0) |
| Renk hapsi | Güçlü türetim adayı (25.8) |
| Kütle kökeni / Higgs | Makine 2 hedefi; türetim yok |

## 26.5 Kütleçekim–kuantum kesişimi

| Olgu | Aday okuma / statü |
|---|---|
| Kuantum kütleçekim | Çerçevenin merkezî boşluğu; çözüm iddiası yok |
| Planck ölçeği | c₀ tek-yapısının yoğunluk üst sınırı ($\rho\le\rho_P$) ve kapasite sayım birimi ($m_P$) olarak yazar hükmüne girmiştir (Bölüm 3); kuantum kütleçekimle nicel köprü yok |
| Kara delik bilgi paradoksu | Çözülmedi (0.3); bilginin c₀ tek-yapısında imha edilmeden potansiyel olarak korunması ve kayıt / arşiv dili yeniden okuma sunar |
| Hawking / Unruh | Bağlam; ısıl izdüşüm literatürü; $T_H$ ufkun Cₘ okuma sıcaklığı (aday okuma, 3.2) |
| Wheeler–DeWitt zamansızlığı | Faz ayrımıyla okuma (7.11e) |

## 26.6 Zaman olguları

| Olgu | Aday okuma |
|---|---|
| Zamanın oku | Aday okuma: Cₘ → c⁺ kayıt kanalının tek yönlülüğü ve damga birikimiyle ilişkilendirilir (7.1, 16.7) |
| Ortaya çıkan zaman literatürü | Karşılaştırma haritası (7.11) |

## 26.7 Yoğun madde ve laboratuvar olguları

| Olgu | Aday okuma |
|---|---|
| Yüksek sıcaklık süperiletkenliği | Toplu davranış benzetme ailesi; gerçek kimlik değil |
| Casimir etkisi | c⁺ ≡ vakum kimliği altında c⁺'ın Cₘ üzerindeki okuması; kuvvetin standart kuantum alan kuramı hesabı Cₘ hesap dili olarak aynen geçerlidir (Bölüm 3) |
| Schwinger etkisi / çift oluşumu | c⁺ → Cₘ kenarında dış enerjiyle tetiklenen yerel faz geçişi (aday okuma, 18.4) |
| BEC / süperakışkan | BEC c₀ değildir; **madde fazında c₀ ortamına en yakın ortamdır** (18.5). Süperakışkan → c⁺ eşlemesi kullanılmaz |

## 26.8 Gözlem kanalları ve veri pencereleri

CMB anizotropileri · BAO · 21 cm kozmolojisi · Pantheon+ · optik saat kararsızlık verileri (Yb / Sr) · AME2020 kütle tabloları — tamamı Bölüm 21'deki denetim disiplinine tabi dış veri kanallarıdır; hiçbiri Evertophy öngörüsü değildir.

## 26.9 Nadir / tekil anomali kayıtları

**Anomali kayıtları:** yakın geçiş (flyby) anomalileri · Pioneer anomalisi (büyük ölçüde ısıl geri tepmeyle açıklanmıştır; tarihsel kayıt) · metrik dışılık imzaları (21.16; test tasarımı). Bunlar "açıklanamayan ya da tartışmalı olgu envanteri" kaydıdır; çerçeve bunlara bir bakış açısı önerir, hüküm vermez.

**Geri kazanılması gereken standart sonuçlar (anomali değildir):** Shapiro gecikmesi ölçümleri (8.9) genel görelilikle açıklanmış ölçülmüş olgulardır; Evertophy'nin etkin geometriden geri kazanması gereken sonuçlar arasındadır (9.2a, 20.6).

---

# BÖLÜM 27 — TEMEL DENKLEMLER VE KÖPRÜ BİÇİMCİLİĞİ (ADAY ENVANTERİ)

Bu bölüm, arşivdeki köprü denklemi ailesini ad düzeyinde envantere alır. EK C çekirdek koruma kayıtlarının genişletmesidir; yeni sayısal sonuç içermez. Her denklemin ayrıntılı sembol açıklaması ve soru–cevap çizelgesi, parantez içinde gösterilen bölümdedir; burada denklemler toplu olarak, güven düzeylerine göre iki katmanda bir araya getirilir.

Bir denklemin bu bölümde yer alması, onun aynı güvenle söylendiği anlamına gelmez. Bu yüzden bölüm iki katmana ayrılır: doğrulanmış yapısal denklemler (27.A) ve kapsamı ve varsayımları açıkça yazılmış model ve köprü denklemleri (27.B). Arşivden gelen tarihsel ve aday envanter ile model aileleri V24 yürüyen ana kaydında tutulur.

## 27.A Doğrulanmış yapısal denklemler

Bu denklemler çerçevenin **yapısal tutarlılığını** kurar; fizik öngörüsü değildir.

| Denklem | Ne söyler | Kanıt türü |
|---|---|---|
| $g = E^{\mathsf T}\eta E,\quad \det g = -(\det E)^2$ | Cebirsel dejenere olmama koşulu; metriğin yalnız Cₘ'de izinli olması **ayrı bir faz postülasıdır** (Bölüm 9) | Sembolik — iki bağımsız hesap motoru |
| $w\cdot w = w \iff w \in \{e,\ \kappa_{0m},\ \kappa_{+m}\}$ | Damga cebirinin idempotentleri; birleşme, sonlanma, tek normal form ve konfluans da kanıtlı (Bölüm 14) | Biçimsel (Lean) |
| $x\in[a,b],\ y\in[c,d] \Rightarrow xy \in [\min(ac,ad,bc,bd),\ \max(ac,ad,bc,bd)]$ | Aralık hesabının güvenilirliği; toplama, eksi alma, kesişim ve sıfırı dışlama da kanıtlı (6.4a) | Biçimsel (Lean) |
| $q \text{ kapı-kilitli} \iff q \text{ en fazla bir fazda içsel olarak tanımlı}$ | Cₘ'ye özgü niceliklerin hiçbir kapıdan taşınamaması (13.1a) | Biçimsel (Lean) |
| $\text{Tip}+\text{aralık}+\text{iyi tanımlılık} \nRightarrow \text{tekil köprü}$ | $B_1(x)=x$ ile $B_2(x)=x+\tfrac{x(1-x)}{2}$ aynı koşulları sağlar (24.1) | Biçimsel (sonlu) + analitik (sürekli) |
| $N_{\rm arşiv}(n+1) = N_{\rm arşiv}(n) + 1$ | Arşiv sayısının ayrık tekdüzeliği; fiziksel zaman türevi değildir (Bölüm 14) | Biçimsel (Lean) |
| $\text{Sert ret} \iff B_{\rm pred}\cap B_{\rm obs}=\varnothing$ | Yanlışlama ölçütü; uyum ölçüsü tek başına ret nedeni değildir (21.6) | Biçimsel (Lean) |

Denklemlerin LaTeX kaydı:

```latex
g = E^{\mathsf T}\eta E,\quad \det g = -(\det E)^2
w\cdot w = w \iff w \in \{e,\ \kappa_{0m},\ \kappa_{+m}\}
x\in[a,b],\ y\in[c,d] \Rightarrow xy \in [\min(ac,ad,bc,bd),\ \max(ac,ad,bc,bd)]
q \text{ kapı-kilitli} \iff q \text{ en fazla bir fazda içsel olarak tanımlı}
\text{Tip}+\text{aralık}+\text{iyi tanımlılık} \nRightarrow \text{tekil köprü}
N_{\rm arşiv}(n+1) = N_{\rm arşiv}(n) + 1
\text{Sert ret} \iff B_{\rm pred}\cap B_{\rm obs}=\varnothing
```

| Sembol | Anlamı |
|---|---|
| $g$, $E$, $\eta$ | Metrik, tetrad, Minkowski metriği (9.2) |
| $w$, $e$, $\kappa_{0m}$, $\kappa_{+m}$ | Damga kelimesi, birim, iki kilit damgası (14.2) |
| $[a,b]$, $[c,d]$ | Kapalı aralıklar (Range) |
| $q$ | Bir nicelik türü |
| $B_1$, $B_2$ | Aynı biçimsel koşulları sağlayan iki aday köprü |
| $N_{\rm arşiv}(n)$ | $n$. eklemeden sonraki kayıt sayısı |
| $B_{\rm pred}$, $B_{\rm obs}$ | Öngörü ve gözlem bantları |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Çerçevenin biçimsel olarak kanıtlanmış yapısal sonuçlarını tek bir çizelgede toplar |
| **Neden yapıyor?** | Okurun, hangi sonuçların gerçekten kanıtlandığını ve hangilerinin model olduğunu bir bakışta ayırabilmesi için |
| **Nasıl yapıyor?** | Her denklemi söylediği şeyle ve kanıt türüyle (sembolik, Lean, analitik) birlikte listeler |
| **Ne sonuç bekleniyor?** | Bu yapısal çekirdeğin üzerine kurulacak fiziksel köprülerin tutarlı bir zemine oturması |
| **Ne sonuç elde ediliyor?** | Hepsi **kanıtlanmış yapısal sonuçlardır**; hiçbiri fizik öngörüsü değildir ve sayaca katkı yapmaz |

## 27.B Kapsamı yazılmış model ve köprü denklemleri

Bu denklemler kendi varsayımları içinde doğrudur; çekirdeğe terfi ettirilmez.

| Denklem | Kapsam ve varsayım | Statü |
|---|---|---|
| $\int \mathcal G_{\rm FS}\,d\lambda \ge \theta_{\min},\quad \Delta t\ge\hbar\theta_{\min}/\overline{\Delta E}$ | Yalnız kuantum-Cₘ; saf durum, üniter evrim, $\overline{\Delta E}>0$; bir alt sınırdır (7.4) | Köprü |
| $\tau_0\tilde\Gamma\,\mathcal G_{C_m}=\eta_{\rm clock}\,d\tau_{\rm GR}/d\lambda$ | Aday saat eşlemesi; durağan gözlemcide $d\tau_{\rm GR}=\sqrt{-g_{00}}\,dt_{\rm koor}$ (7.4) | Köprü |
| $G_{\mu\nu}+\Lambda g_{\mu\nu} = \frac{8\pi G}{c^4}\,T_{\mu\nu}[J_X]$ | Standart Cₘ karşılaştırma tabanı; $J_X$ açık borçtur (24.1) | Köprü |
| $-\nabla\cdot(Z\nabla\phi)+\mu^2\phi+4\pi G\rho=0,\quad m=\mu/\sqrt{Z}$ | Sabit $Z>0$ ve uygun sınır / zorlayıcılık koşulları; $\mu=0$ saf Neumann durumunda ek ortalama koşulu gerekir | Model — zayıf alan test yatağı |
| $Q(m) = e^{-m(r_2-r_1)}\,\frac{1+mr_2}{1+mr_1}$ | $0<r_1<r_2$, $m>0$; kesin azalan; ters problem $m$'yi verir ($\mu=m\sqrt Z$ yalnız $Z$ biliniyorsa) | Model |
| $\sigma^* = 1/\sqrt2,\quad \sigma_{\rm fold}\approx 0.7391346294$ | İdeal eşkenar Gauss peyzajının rejim eşikleri (19.1a) | Model |
| Matematiksel $z\to\pm\infty$ uçlarında $w\to-1 \iff (X_{\min}>0 \lor p=0)\wedge(X_{\max}<1 \lor q=0)$ | Lojistik okuma modeli; $s>0$, $p,q$ sonlu; kaynak türetimi açık. Fiziksel alan $z>-1$, fiziksel gelecek $z\to-1^+$ (11.9) | Model |
| $\chi_S \equiv 1,\quad \Delta\varphi \equiv 0$ (karşılıklı sistem) | Aynı port normalizasyonu, $S_{21}=S_{12}\neq0$ (17.1) | Sınır sonucu |
| $\vert A_{\rm loop}\vert = \dfrac{\pi\vert k\vert\delta^2\omega}{\lambda^2+\omega^2}$ | Gevşemeli doğrusal yanıt modeli, kalıcı periyodik rejim; $1/\omega$ biçimi yalnız $\omega\gg\lambda$ | Model |
| $\Delta_{0m}\,\Delta_{+m} = \dfrac{d\ln F}{d\tau}$ | Zincir kuralından gelen özdeşlik; fiziksel iddia olan kazanç ilişkisi $\Delta_{0+} = G\,\Delta_{+m}$ ayrıdır | Özdeşlik doğru / kazanç model |
| $\ln\dfrac{Z(\tau)}{Z(\tau_0)} = -\displaystyle\int_{\tau_0}^{\tau}\eta(u)\,[F(u)-F^*(u)]\,du$ | Sürüklenme empedansı modeli; $\alpha^{-1}\propto Z_{\rm drift}$ ($\xi=1$) tanımsaldır | Model |
| $N_{c_0}=M/m_P,\ \ \rho_{c_0}\le\rho_P,\ \ R_{c_0}\propto M^{1/3}$ | c₀ tek-yapı kapasite ilişkileri; yarıçap ölçeklemesi yalnız sabit yoğunluk ($\rho_*\le\rho_P$) gerçeklemesinde; $R,V,\rho$ Cₘ etkin okumalarıdır (Bölüm 3) | Yazar hükmü (ilişkiler) / iç profil açık |
| $\Psi_{0+}=\ln\dfrac{\Lambda c^4\ell^4}{6G^2M^2},\ \ \mathcal A=\dfrac1w\ln\!\Big(1+\dfrac{m_P^2}{2M^2}\Big)$ | Doğrudan c₀ ⇄ c⁺ kenar kilidi düşünce deneyi oran modeli (13.6) | Model |

Denklemlerin LaTeX kaydı:

```latex
\int \mathcal G_{\rm FS}\,d\lambda \ge \theta_{\min},\quad \Delta t\ge\hbar\theta_{\min}/\overline{\Delta E}
\tau_0\tilde\Gamma\,\mathcal G_{C_m}=\eta_{\rm clock}\,d\tau_{\rm GR}/d\lambda
G_{\mu\nu}+\Lambda g_{\mu\nu} = \frac{8\pi G}{c^4}\,T_{\mu\nu}[J_X]
-\nabla\cdot(Z\nabla\phi)+\mu^2\phi+4\pi G\rho=0,\quad m=\mu/\sqrt{Z}
Q(m) = e^{-m(r_2-r_1)}\,\frac{1+mr_2}{1+mr_1}
\sigma^* = 1/\sqrt2,\quad \sigma_{\rm fold}\approx 0.7391346294
w\to-1 \iff (X_{\min}>0 \lor p=0)\wedge(X_{\max}<1 \lor q=0)
\chi_S \equiv 1,\quad \Delta\varphi \equiv 0
|A_{\rm loop}| = \dfrac{\pi|k|\delta^2\omega}{\lambda^2+\omega^2}
\Delta_{0m}\,\Delta_{+m} = \dfrac{d\ln F}{d\tau}
\ln\dfrac{Z(\tau)}{Z(\tau_0)} = -\displaystyle\int_{\tau_0}^{\tau}\eta(u)\,[F(u)-F^*(u)]\,du
N_{c_0}=M/m_P,\ \ \rho_{c_0}\le\rho_P,\ \ R_{c_0}\propto M^{1/3}
\Psi_{0+}=\ln\dfrac{\Lambda c^4\ell^4}{6G^2M^2},\ \ \mathcal A=\dfrac1w\ln\!\Big(1+\dfrac{m_P^2}{2M^2}\Big)
```

| Sembol | Anlamı |
|---|---|
| $\mathcal G_{\rm FS}$ | Fubini–Study değişim hızı (kuantum durum uzayında hız) |
| $\theta_{\min}$ | Ayırt edilebilirlik için gereken en küçük açı |
| $\Delta t_{\min}$, $\Delta E$ | En küçük geçiş süresi ve enerji yayılımı |
| $J_X$ | $X$'ten Cₘ kaynağına giden köprü (açık) |
| $Z$, $\mu$, $m$ | Ekranlama katsayısı, ekranlama kütlesi, sönüm parametresi |
| $r_1$, $r_2$ | Ölçüm yarıçapları |
| $\sigma^*$, $\sigma_{\rm fold}$ | Gauss peyzajı rejim eşikleri |
| $w$ | Karanlık enerji durum denklemi parametresi (lojistik modelde); 13.6'da eşik yumuşaklığı |
| $A_{\rm loop}$ | Döngü genliği; $k$ bağlaşım, $\delta$ genlik, $\omega$ sürme frekansı, $\lambda$ gevşeme oranı |
| $F$, $F^*$, $\eta$ | Doluluk, denge doluluğu, sürüklenme katsayısı |
| $Z_{\rm drift}$ | Sürüklenme empedansı |
| $N_{c_0}$, $\rho_P$, $R_{c_0}$ | c₀ kapasite sayımı, Planck yoğunluğu, tek-yapı yarıçapı |
| $\Psi_{0+}$, $\mathcal A$ | c₀ ⇄ c⁺ kenar potansiyeli ve döngü afinitesi |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kendi varsayımları içinde doğru olan model ve köprü denklemlerini kapsamlarıyla birlikte toplar |
| **Neden yapıyor?** | Model sonuçlarının sessizce çekirdeğe terfi etmesini önlemek ve her birinin geçerlilik koşulunu görünür kılmak için |
| **Nasıl yapıyor?** | Her denklemin yanına kapsamını, varsayımlarını ve statüsünü (köprü, model, sınır sonucu, özdeşlik, yazar hükmü) yazar |
| **Ne sonuç bekleniyor?** | Köprülerin ileride türetilerek ya da önceden kayıtlı testlerle sınanarak statü kazanması |
| **Ne sonuç elde ediliyor?** | Hepsi **kapsamı yazılmış** sonuçlardır; çekirdeğe terfi ettirilmez. c₀ kapasite ilişkileri yazar hükmüdür, ama iç profil açıktır. Hiçbiri sayaca katkı yapmaz |




# EK A — KAVRAM SÖZLÜĞÜ

| Kavram | Tanım |
|---|---|
| **Çekim Kuvveti (Force of Attraction)** | Temel ontolojik postüla; fazdan bağımsız kısıt koheransı. Bilinen dört kuvvet onun ölçeğe, kütle miktarına ve faza göre izdüşümleridir. "Kütleçekim" ile karıştırılmaz |
| **Kütleçekim (Gravitation)** | Çekim Kuvveti'nin Cₘ'deki metrik izdüşümü; genel göreliliğin konusu |
| **Kısıt koheransı** | Üç fazın izinli yapılanmalarının birbiriyle uyumlu olma zorunluluğu; metrik gerektirmez |
| **Kümelenmiş / genişlemeyi sürdüren c⁺** | c⁺'ın maddeyle kümelenmiş (karanlık madde) ve madde baskısından uzak, genişlemeyi sürdüren (karanlık enerji) görünümleri; arşivdeki "tutuklu / serbest" adları bunlara karşılık gelir |
| **Vakum** | c⁺'ın laboratuvar ve atom içi ölçekteki Cₘ okuması; **c⁺ ≡ vakum** (yazar hükmü). Kuantum alan kuramının vakum durumu bu kimliğin Cₘ hesap dilidir |
| **Atom içi boşluk** | Atomu oluşturan parçacıklar arasındaki boşluk; c⁺'ın Cₘ okumasıdır (yazar hükmü) |
| **Liminal** | $v=c$ sınırında bulunma; ışığın durumu. Cₘ ile c⁺'ın ortak sınırıdır; ne $0<v<c$ bandının ne de c⁺'ın üyeliğidir (sınır ≠ üyelik) |
| **Kinematik üyelik bandı** | Cₘ'nin madde üyelik bandı $0<v<c$; $v=c$ liminal ortak sınırdır |
| **$U_0$ (Mutlak Çekirdek)** | Üç fazı aynı kuruluşta birlikte oluşturan ön katman / mutlak üretici kaynak; Dinamik Evren'in bütün yapılarının metrik boşluksuz duruma yakınsayan derecede bitişik tek bir formda bulunduğu katman; faz değildir |
| **$U_x$ (Dinamik Evren)** | Üç fazın birlikte gerçekleştiği küresel yapı; dördüncü faz ya da $X$ değildir |
| **$U_+$ (Mutlak Çözünme ≡ Mutlak Yırtılma)** | Küresel çözünme kutbu; bütün $U_x$ yapısı bu forma eriştiğinde Mutlak Yırtılma ile Mutlak Çözünme aynı şeyi ifade eder. Faz değildir, $c^+$ değildir |
| **Küresel evren düzeyi** | $U_0$, $U_x$, $U_+$ katmanı; faz düzeyinden ayrıdır |
| **Sessizlik ilkesi** | Temsili olmayan yerde Evertophy hüküm vermez |
| **Faz rejimi – eşik sınırı** | Kenarlardaki geçiş bandı; yeni faz, kapı ya da düğüm değildir |
| **SYNTAX** | Geçerli yapılanmaları belirleyen kural sistemi adayı; $U_x$ / $X$ ilişkisi açık |
| **Ayrılmış ontolojik başlık** | Eklenmesi kararlaştırılmış, anlamı henüz yazılmamış yapı |
| **Big Yırtılma** | Küresel $U_x$'in $U_+$ sınırındaki kritik eşiği aşmasıyla gerçekleşen, hem son hem yeni doğuş olan olay; standart kozmolojinin terminal Big Rip senaryosu değildir |
| **c₀ (Potansiyel / Kara Delik Fazı)** | Zaman-öncesi potansiyel ve çekirdek fazı; kara delik ≡ c₀ (yazar hükmü). Madde Planck ölçeğinde metrik boşluksuz duruma yakınsayan derecede bitişik, sonlu, tek bir yapı formundadır. Zaman durmuş değil, **henüz kurulmamıştır** |
| **Metrik boşluksuz tek-yapı** | c₀'daki maddenin, parçacıklar arasında metrik boşluğun neredeyse kalmadığı bütünleşik tek formu; Planck boyutunda bir nokta değildir, kütleyle büyür ($\rho\le\rho_P$) |
| **Cₘ (Madde Fazı)** | Farklılaşmış madde fazı; ölçümün ve fiziksel zamanın tek evi; temel uzayı düz, üç boyutlu Öklid uzayıdır |
| **c⁺ (Karanlık Madde / Karanlık Enerji / Vakum Fazı)** | Zaman dışı üst / arşiv / koordinasyon fazı; Cₘ madde desteği çözülür; c⁺ ≡ DM ≡ DE ≡ Vakum |
| **BEC** | Bose–Einstein yoğuşması; c₀ değildir, **madde fazında c₀ ortamına en yakın ortamdır** |
| **$X(x)$** | Dinamik üst çözücü; faz rejimini ve izinli değerleri çözer; skaler değildir, okumaları $\xi_k=\pi_k(X)$ |
| **Postüla-0** | Çekim Kuvveti'nin temel ontolojik postüla olması |
| **Aralık biçimciliği** | Fiziksel niceliklerin aralık değerli yazılması; $[P,P]$ geçerlidir |
| **Kapı** | Faz geçiş olanağı; çift yönlü |
| **Taşıma izni** | Bir niceliğin bir kapıdan geçebilmesi; niceliğin iki uçta da içsel tanımlı olmasını gerektirir |
| **Okuma** | c⁺ ya da c₀ kaynaklı bir etkinin Cₘ'de, Cₘ'nin kendi dilinde gözlenmesi; taşıma değildir |
| **Damga** | Geçişte basılan kayıt; tek yönlü |
| **Mühürleme** | Kaydın geri alınamaz biçimde yazılması |
| **Kayıt kanalı** | Cₘ → c⁺ tek yönlü kanal; mühürlendiğinde kayıt sabittir (yazar hükmü) |
| **Faz hafızası** | Eşik istatistiğinin kaynak sırasında tekdüze birikimi |
| **Faz-parametre matrisi** | ÖzellikAilesi × Faz → Aralık ya da ⊥ |
| **⊥₀ / ⊥₊** | c₀'daki "henüz kurulmamış" ve c⁺'taki "çözünmüş" tanımsızlıklar; ikisi farklıdır ve hiçbiri sayısal sıfır değildir |
| **Eşik (liminal) rejim** | Cₘ'ye tam olarak izdüşmemiş ara durum |
| **Parametre bütçesi** | Serbest girdi < öngörülen çıktı kuralı |
| **Kesişim ölçüsü** | Öngörü ve gözlem aralıklarının örtüşme oranı |
| **Uyumlu okuma** | Bir deneyin ölçülmüş sonuçlarıyla çelişmeyen Evertophy yorumu; tescil ya da tek açıklama iddiası değildir |
| **Sayaç** | Kanonik sayısal öngörü sayacı; güncel değer 0/10 |
| **Konsensüs ⇏ kanon** | Çoklu sistem mutabakatı kanon belirlemez; kanonu yalnız yazar belirler |

# EK B — SEMBOL LİSTESİ

| Sembol | Anlamı |
|---|---|
| $U_0$ | Mutlak Çekirdek — küresel doygunluk kutbu / ön katman |
| $U_x$ | Dinamik Evren — küresel düzey nesnesi ve üçlü faz sisteminin bütünsel gösterimi ($\neq X(x)$) |
| $U_+$ | Mutlak Çözünme ≡ Mutlak Yırtılma — küresel çözünme kutbu |
| $\mathcal{L}_{\rm çöküş},\ \mathcal{L}_{\rm seyrelme}$ | İki küresel limit |
| $c_0,\, C_m,\, c^+$ | Üç faz |
| $\Delta_{0m},\ \Delta_{+m},\ \Delta_{0+}$ | Tam üçgenin (K3) üç kenarı; ilk ikisi damga taşır, üçüncüsü damgasızdır |
| $X(x)$ | Dinamik üst çözücü (skaler değil) |
| $\xi_k=\pi_k(X)$ | $X$'in $k$. okuması (izdüşümü) |
| $\xi_{\rm sat}=\pi_{\rm sat}(X)$ | Doygunluk okuması; c₀'da $\xi_{\rm sat}\to\xi_{\rm sat}^{\max}$ (normalize okumada $\approx1$) |
| $\Theta_{\rm alan}$, $\Theta_{ij}$ | Alana özgü parametreler; geçişe özgü bağlam ailesi |
| $\rho_{C_m}$ | Cₘ durum tanımlayıcısı |
| $\mathcal{G}_{C_m}$ | Cₘ içinde ölçülebilir değişim ve ayrışma yapısı (değişim normu) |
| $\Gamma$ | Cₘ okuma / raporlama-düzenleme ailesinin katsayısı (7.2) |
| $\tau_0,\, \tilde\Gamma$ | Zaman üretim ölçeği ve boyutsuz katsayı |
| $\tau$ | Sıralama parametresi |
| $\lambda$ | Boyutsuz parametrizasyon değişkeni (7.3) |
| $\tau_{\rm GR}$ | Cₘ öz zamanı — genel görelilik okuması (8.7) |
| $Z_g$ | Kütleçekimsel empedans — yalnız Cₘ'de tanımlı (8.7) |
| $\bot_0$, $\bot_+$ | c₀'da "henüz kurulmamış", c⁺'ta "çözünmüş" tanımsızlık; $\bot_0\neq\bot_+\neq0$ |
| $T(c^+)=\bot_+$ | c⁺'ın zaman durumu; $dt_{c^+}=0$ yalnız pedagojik kısaltma |
| $0<v<c$ | Cₘ kinematik üyelik bandı; buradaki $v$ üyelik okumasıdır ($v_{\rm üyelik}$) |
| $v_{\rm üyelik}$, $\beta=v_{\rm üyelik}/c$ | Ontolojik üyelik okuması ve boyutsuz biçimi; işlemsel tanımı $\mathcal R_v$ açık (3.3) |
| $v_{\rm lab}$ | Laboratuvar koordinat hızı; $v_{\rm lab}=0\not\Rightarrow c_0$ |
| $q_\partial$ | Faz rejimi – eşik sınırı / kuantum okuma ekseni (18.0) |
| $v_\partial$, $\rho_\partial$ | c₀'dan ayrılışın Cₘ sınır okumaları (3.2) |
| $v=c$ | Cₘ ile c⁺'ın liminal ortak sınırı |
| $m_P$ | Planck kütlesi; c₀ kapasitesinin sayım birimi (3.2) |
| $\ell_P$ | Planck uzunluğu |
| $\rho_P$ | Planck yoğunluğu, $c^5/(\hbar G^2)\approx5.16\times10^{96}\ \mathrm{kg/m^3}$; c₀ yoğunluk üst sınırı |
| $N_{c_0}=M/m_P$ | c₀ kapasite sayımı |
| $V_{c_0}$, $R_{c_0}$ | c₀ tek-yapısının Cₘ etkin hacmi ($\ge N_{c_0}\ell_P^3$) ve yarıçapı ($\ge R_{c_0}^{\min}$; sabit yoğunlukta $\propto M^{1/3}$) |
| $R_s$, $A$ | Schwarzschild yarıçapı ($\propto M$) ve ufuk alanı ($\propto M^2$) |
| $T_H$ | Hawking sıcaklığı — ufkun Cₘ okuma sıcaklığı (aday okuma, 3.2) |
| $\Psi_{0+}$ | Doğrudan c₀ ⇄ c⁺ kenar potansiyeli — model (13.6) |
| $\Xi_g,\ \Xi_\Lambda,\ \Xi_q$ | Kütleçekim, genişleme ve kuantum izdüşüm oranları — model (13.6) |
| $\Xi=\ln\chi_S$ | Kanal logaritmik asimetri ölçüsü (8.8, 17.1) |
| $\Xi_{\rm iz}$ | Faz izi bağlamındaki alternatif işlevsel mühür adayı (7.9) |
| *Not* | Üç $\Xi$ ailesi birbiriyle ilgisizdir; ortak harf yalnız tarihsel gösterimdir |
| $\mathcal O^{C_m}_{c_0}$ | c₀ yapısından Cₘ etkin parametrelerine okuma haritası (3.2) |
| $\rho_*$ | Sabit yoğunluk gerçeklemesinde tek-yapı yoğunluğu ($\le\rho_P$) |
| $\eta_{\rm clock}$ | Evertophy zamanı ile öz zaman arasındaki boyutsuz saat oranı (7.4) |
| $\Phi_{\rm ch}^{\rm gen}$, $\phi_{\rm ch}$ | Kanal genlik potansiyeli ve fazı (17.1a) |
| $\mathcal A$ | Döngü afinitesi — model (13.6) |
| $g_{\mu\nu}$ | Metrik (yalnız Cₘ) |
| $E^A{}_\mu$ | Tetrad (yalnız Cₘ) |
| $\mathcal{E}_m^{(0)},\, \mathcal{E}_m^{(+)}$ | Metrik doğuş haritaları |
| $G_{\rm eff}$ | Etkin kütleçekim bağlaşımı (model) |
| $S_c$ | Duyarlılık katsayısı |
| $\Delta X_{\rm acc/pred/obs}$ | Kabul / öngörü / gözlem aralıkları |
| $M$ | Damga monoidi (bağlama göre kütle de olabilir; ayrıca belirtilir) |
| $s,\, s'$ | Serbest damga üreteçleri |
| $\kappa_{0m},\, \kappa_{+m}$ | Kilit damgaları |
| $\mathrm{rid}$ | Kayıt kimliği |
| $\chi_S$ | Kanal asimetrisi (aday köprü) |
| $C_s$ | Mühürleme maliyeti (aday okuma) |
| $R_\varphi$ | Faz hafızası kaydı |
| $\bot$ | O fazda kabul edilemez (genel gösterim) |
| $\texttt{None}$ | Damga üretilmedi ($\text{NoStamp} \neq \text{NoTransition}$) |
| $[P,P]$ | Sıfır genişlikli geçerli aralık |




# EK C — TEMEL DENKLEM VE KORUMA KAYITLARI

Bu ek, aynı denklem sembolünün farklı katmanlarda farklı anlamlara kaymasını önlemek için hazırlanmıştır. Denklemler konu gruplarına ayrılmıştır; her grubun ardından kısa bir sembol çizelgesi ve soru–cevap çizelgesi gelir. Ayrıntılı açıklamalar parantez içinde gösterilen bölümlerdedir; bütün semboller ayrıca EK B'de toplanmıştır. **Çekirdek**, **biçimsel aday** ve **model** ayrımı her grupta açıkça belirtilir.

## C.1 Köken, küresel düzey ve faz topolojisi

**Köken / ön katman:**

$$U_0 \rightsquigarrow \{c_0,\, C_m,\, c^+\}_{\text{eş zamanlı — aynı kuruluşta birlikte}}, \qquad U_0 \notin \mathrm{Obj}(\mathcal{C}_{\rm faz})$$

```latex
U_0 \rightsquigarrow \{c_0,\, C_m,\, c^+\}_{\text{eş zamanlı — aynı kuruluşta birlikte}}, \qquad U_0 \notin \mathrm{Obj}(\mathcal{C}_{\rm faz})
```

**Sistem bütünü — kaynaklı kanon, anlamı kısmen açık:**

$$U_0\leftrightarrow[c_0\rightleftarrows C_m\rightleftarrows c^+]\equiv U_x,\qquad U_x\equiv\{c_0,C_m,c^+\}_{\rm sistem\ bütünü}$$

```latex
U_0\leftrightarrow[c_0\rightleftarrows C_m\rightleftarrows c^+]\equiv U_x,\qquad U_x\equiv\{c_0,C_m,c^+\}_{\rm sistem\ bütünü}
```

Buradaki zincir yazımı tarihsel kaynak ifadesini korur; güncel kapı topolojisi aşağıdaki tam çift yönlü üçgendir. $U_0\leftrightarrow U_x$ ilişkisinin tam anlamı açık borçtur.

**Faz topolojisi (K3):**

$$c_0 \overset{\Delta_{0m}}{\longleftrightarrow} C_m, \qquad C_m \overset{\Delta_{+m}}{\longleftrightarrow} c^+, \qquad c_0 \overset{\Delta_{0+}}{\longleftrightarrow} c^+$$

```latex
c_0 \overset{\Delta_{0m}}{\longleftrightarrow} C_m, \qquad C_m \overset{\Delta_{+m}}{\longleftrightarrow} c^+, \qquad c_0 \overset{\Delta_{0+}}{\longleftrightarrow} c^+
```

**Küresel evren devresi, iki doğuş olayı ve korumalar:**

$$U_0 \;\leftrightarrow\; U_x \;\leftrightarrow\; U_+, \qquad U_0,\,U_x,\,U_+ \notin \{c_0,\,C_m,\,c^+\}$$

```latex
U_0 \;\leftrightarrow\; U_x \;\leftrightarrow\; U_+, \qquad U_0,\,U_x,\,U_+ \notin \{c_0,\,C_m,\,c^+\}
```

$$U_x\text{, } U_0 \text{ sınırındaki kritik eşiği aşar} \Rightarrow \text{Big Bang}, \qquad U_x\text{, } U_+ \text{ sınırındaki kritik eşiği aşar} \Rightarrow \text{Big Yırtılma}, \qquad \text{her iki durumda } \Rightarrow U_x$$

```latex
U_x\text{, } U_0 \text{ sınırındaki kritik eşiği aşar} \Rightarrow \text{Big Bang}, \qquad U_x\text{, } U_+ \text{ sınırındaki kritik eşiği aşar} \Rightarrow \text{Big Yırtılma}, \qquad \text{her iki durumda } \Rightarrow U_x
```

$$U_+\;=\;\text{Mutlak Çözünme}\;\equiv\;\text{Mutlak Yırtılma}\qquad(\text{bütün } U_x \text{ yapısı } U_+ \text{ formuna eriştiğinde})$$

```latex
U_+\;=\;\text{Mutlak Çözünme}\;\equiv\;\text{Mutlak Yırtılma}\qquad(\text{bütün } U_x \text{ yapısı } U_+ \text{ formuna eriştiğinde})
```

$$\mathrm{Genesis} = U_0 \rightsquigarrow \{c_0,C_m,c^+\}_{\text{eş zamanlı}}, \qquad \mathrm{CycleSeed} = \{\mathcal{L}_{\rm çöküş}, \mathcal{L}_{\rm seyrelme}\},\qquad \text{Devre indeksi} \neq t, \qquad U_0 : c_0 \;\not::\; U_+ : c^+$$

```latex
\mathrm{Genesis} = U_0 \rightsquigarrow \{c_0,C_m,c^+\}_{\text{eş zamanlı}}, \qquad \mathrm{CycleSeed} = \{\mathcal{L}_{\rm çöküş}, \mathcal{L}_{\rm seyrelme}\},\qquad \text{Devre indeksi} \neq t, \qquad U_0 : c_0 \;\not::\; U_+ : c^+
```

**Çift-limit çekirdek tohumu — mekanizma V24'e ayrılmış:**

$$\mathrm{DoubleLimit}_{\rm çekirdek}=\{\text{çöküş / doygunluk limiti},\ \text{seyrelme / kapalı devre limiti}\},\qquad \mathrm{DoubleLimit}_{\rm çekirdek}\nRightarrow(c_0\to U_0)\ \text{sıradan faz geçişi}$$

```latex
\mathrm{DoubleLimit}_{\rm çekirdek}=\{\text{çöküş / doygunluk limiti},\ \text{seyrelme / kapalı devre limiti}\},\qquad \mathrm{DoubleLimit}_{\rm çekirdek}\nRightarrow(c_0\to U_0)\ \text{sıradan faz geçişi}
```

| Sembol | Anlamı |
|---|---|
| $\rightsquigarrow$ | "Doğurur" (üretici ilişki; fiziksel geçiş değil) |
| $\mathrm{Obj}(\mathcal C_{\rm faz})$ | Faz kategorisinin nesneleri (üç faz) |
| $\Delta_{0m},\Delta_{+m},\Delta_{0+}$ | Üçgenin kenarları |
| $\mathcal L_{\rm çöküş}$, $\mathcal L_{\rm seyrelme}$ | İki küresel limit |
| $::$ / $\not::$ | Oran benzetmesi kurulur / kurulmaz |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Kökeni, iki düzeyli mimariyi (faz düzeyi ve küresel düzey) ve faz topolojisini tek yerde kaydeder |
| **Neden yapıyor?** | $U_0$, $U_x$, $U_+$'nın fazlarla karışmasını ve tarihsel zincir yazımının güncel üçgenle çakışmasını önlemek için |
| **Nasıl yapıyor?** | Küresel nesneleri faz kümesinin dışına koyar; üçgenin üç kenarını adlandırır; iki doğuş olayını ve korumaları yazar |
| **Ne sonuç bekleniyor?** | Bütün bölümlerde aynı mimari dilin kullanılması |
| **Ne sonuç elde ediliyor?** | **Çekirdek** (yazar kanonu); $U_0\leftrightarrow U_x$ ilişkisinin tam anlamı ve çift-limit mekanizması açıktır |

## C.2 Kinematik bant, çözücü ve matris

$$0<v<c \;\neq\; \text{laboratuvar koordinat hızı},\qquad v=c\ \text{liminal ortak sınır (sınır}\neq\text{üyelik)},\qquad v_{\rm lab}=0 \;\not\Rightarrow\; c_0$$

```latex
0<v<c \;\neq\; \text{laboratuvar koordinat hızı},\qquad v=c\ \text{liminal ortak sınır (sınır}\neq\text{üyelik)},\qquad v_{\rm lab}=0 \;\not\Rightarrow\; c_0
```

$$S_1=S_2 \Longrightarrow X(S_1)=X(S_2),\qquad X_\phi=X_\phi(x;\theta_1,\ldots,\theta_{n_\phi}),\qquad \xi_k=\pi_k(X)$$

```latex
S_1=S_2 \Longrightarrow X(S_1)=X(S_2),\qquad X_\phi=X_\phi(x;\theta_1,\ldots,\theta_{n_\phi}),\qquad \xi_k=\pi_k(X)
```

$$\mathrm{MetaCrossPermission}(X)=\text{true},\qquad \mathrm{MetaCrossPermission}\neq\mathrm{TransportPermission}$$

```latex
\mathrm{MetaCrossPermission}(X)=\text{true},\qquad \mathrm{MetaCrossPermission}\neq\mathrm{TransportPermission}
```

$$\mathrm{ÖzellikAilesi}\times\mathrm{Faz}\longrightarrow \mathrm{Aralık}\ \text{ya da}\ \bot,\qquad P\in[P^-,P^+],\qquad [P,P]\ \text{geçerlidir},\qquad \text{aralık değerli}\nRightarrow\text{zamanla değişken}$$

```latex
\mathrm{ÖzellikAilesi}\times\mathrm{Faz}\longrightarrow \mathrm{Aralık}\ \text{ya da}\ \bot,\qquad P\in[P^-,P^+],\qquad [P,P]\ \text{geçerlidir},\qquad \text{aralık değerli}\nRightarrow\text{zamanla değişken}
```

| Sembol | Anlamı |
|---|---|
| $S_1$, $S_2$ | Tamamen belirlenmiş iki durum |
| $X_\phi$ | $X$'in $\phi$ fazındaki sunumu; argüman sayısı $n_\phi$ faza göre değişebilir |
| $\theta_i$ | Bağlam parametreleri |
| $\pi_k$ | $X$'in $k$. okuma izdüşümü |
| $\mathrm{MetaCrossPermission}$ | $X$'in fazlar arası üst koordinasyon izni |
| $P^-$, $P^+$ | Aralığın alt ve üst ucu |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Cₘ üyelik bandını, çözücünün belirlenimciliğini ve faza bağlı argüman yapısını, matris mimarisini ve aralık biçimciliğini kaydeder |
| **Neden yapıyor?** | Hız, çözücü ve aralık kavramlarının yanlış okunmasını (laboratuvar hızıyla karıştırma, $X$'i skaler sanma, $[P,P]$'yi yasaklama) önlemek için |
| **Nasıl yapıyor?** | Her kavramı tek satırlık bir koruma denklemiyle sabitler |
| **Ne sonuç bekleniyor?** | Gövde bölümlerindeki bütün kullanımların bu korumalara uyması |
| **Ne sonuç elde ediliyor?** | **Çekirdek** (Bölüm 3, 4, 5, 6) |

## C.3 Zaman

$$dt=\Gamma\,\mathcal G_{C_m}\,d\tau,\qquad \tau\neq\text{temel fiziksel zaman}$$

```latex
dt=\Gamma\,\mathcal G_{C_m}\,d\tau,\qquad \tau\neq\text{temel fiziksel zaman}
```

$$dt=\tau_0\tilde\Gamma\,\mathcal G_{C_m}\,d\lambda,\qquad \mathcal G_{C_m}\stackrel{\rm model}{=}\left\|\frac{d\rho_{C_m}}{d\lambda}\right\|\qquad(\text{model gerçeklemesi örneği})$$

```latex
dt=\tau_0\tilde\Gamma\,\mathcal G_{C_m}\,d\lambda,\qquad \mathcal G_{C_m}\stackrel{\rm model}{=}\left\|\frac{d\rho_{C_m}}{d\lambda}\right\|\qquad(\text{model gerçeklemesi örneği})
```

$$\left.\frac{\partial X}{\partial E_{\rm probe}}\right|_{\mathcal S}=0,\qquad \left.\frac{\partial\Gamma}{\partial E_{\rm probe}}\right|_{\mathcal S}=0\qquad(\text{akromatiklik})$$

```latex
\left.\frac{\partial X}{\partial E_{\rm probe}}\right|_{\mathcal S}=0,\qquad \left.\frac{\partial\Gamma}{\partial E_{\rm probe}}\right|_{\mathcal S}=0\qquad(\text{akromatiklik})
```

$$T(c_0)=\bot_0\ (\text{henüz kurulmamış}),\qquad T(c^+)=\bot_+\ (\text{çözünmüş}),\qquad \bot_0\neq\bot_+\neq0,\qquad dt_{c^+}=0\ \ (\text{yalnız pedagojik kısaltma})$$

```latex
T(c_0)=\bot_0\ (\text{henüz kurulmamış}),\qquad T(c^+)=\bot_+\ (\text{çözünmüş}),\qquad \bot_0\neq\bot_+\neq0,\qquad dt_{c^+}=0\ \ (\text{yalnız pedagojik kısaltma})
```

| Sembol | Anlamı |
|---|---|
| $dt$ | Cₘ'de üretilen fiziksel zaman aralığı |
| $\Gamma$, $\tilde\Gamma$, $\tau_0$ | Okuma katsayısı, boyutsuz biçimi, zaman ölçeği |
| $\mathcal G_{C_m}$ | Cₘ içinde ölçülebilir değişim ve ayrışma yapısı |
| $\tau$, $\lambda$ | Sıralama parametresi, boyutsuz parametrizasyon |
| $\rho_{C_m}$ | Cₘ durum tanımlayıcısı |
| $E_{\rm probe}$ | Sınama sinyalinin enerjisi |
| $\mathcal S$ | Sabit tutulan bağlam |
| $T(\cdot)$ | Bir fazın zaman durumu |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Zamanın yalnız Cₘ'de üretildiğini, okumanın enerjiden bağımsız olduğunu ve iki dış fazdaki zaman yokluklarının farklı olduğunu kaydeder |
| **Neden yapıyor?** | "Zaman c₀'da durmuş" ya da "c⁺'ta sıfır" gibi hatalı okumaları önlemek için |
| **Nasıl yapıyor?** | Zaman iskelesini, bir model gerçeklemesini, akromatiklik kısıtını ve iki farklı tanımsızlık sembolünü yan yana yazar |
| **Ne sonuç bekleniyor?** | $\mathcal G_{C_m}$'nin kapalı bir tanımı |
| **Ne sonuç elde ediliyor?** | İskele ve tanımsızlık ayrımı **çekirdektir**; model gerçeklemesi **modeldir**; $\mathcal G_{C_m}$ henüz kapanmamış bir nesnedir (Bölüm 7) |

## C.4 Metrik, madde ve c₀ tek-yapısı

$$\mathrm{Dom}(g_{\mu\nu})=C_m,\qquad g_{\mu\nu}\big|_{c_0}=\bot_0,\qquad g_{\mu\nu}^{(C_m)}\big|_{c^+}\to\bot_+,\qquad \mathrm{supp}_{C_m}(\mathrm{madde})\to\varnothing\ \ (c^+)$$

```latex
\mathrm{Dom}(g_{\mu\nu})=C_m,\qquad g_{\mu\nu}\big|_{c_0}=\bot_0,\qquad g_{\mu\nu}^{(C_m)}\big|_{c^+}\to\bot_+,\qquad \mathrm{supp}_{C_m}(\mathrm{madde})\to\varnothing\ \ (c^+)
```

$$\lim_{C_m\to c_0}g_{\mu\nu}^{(C_m\text{-okuma})}\to0\qquad(\text{koşullu tarihsel model; türetim yok})$$

```latex
\lim_{C_m\to c_0}g_{\mu\nu}^{(C_m\text{-okuma})}\to0\qquad(\text{koşullu tarihsel model; türetim yok})
```

$$C_m\to c_0:\ \text{metrik boşluksuz tek-yapı},\qquad C_m\to c^+:\ \text{Cₘ madde desteğinin çözülmesi}$$

```latex
C_m\to c_0:\ \text{metrik boşluksuz tek-yapı},\qquad C_m\to c^+:\ \text{Cₘ madde desteğinin çözülmesi}
```

$$\xi_{\rm sat}=\pi_{\rm sat}(X)\to\xi_{\rm sat}^{\max},\qquad N_{c_0}=\frac{M}{m_P},\qquad \rho_{c_0}\le\rho_P,\qquad V_{c_0}\ge N_{c_0}\ell_P^3,\qquad R_{c_0}\propto M^{1/3}\ \&\ \frac{R_{c_0}}{R_s}\propto M^{-2/3}\ \ (\rho_{c_0}=\rho_*\ \text{sabit})$$

```latex
\xi_{\rm sat}=\pi_{\rm sat}(X)\to\xi_{\rm sat}^{\max},\qquad N_{c_0}=\frac{M}{m_P},\qquad \rho_{c_0}\le\rho_P,\qquad V_{c_0}\ge N_{c_0}\ell_P^3,\qquad R_{c_0}\propto M^{1/3}\ \&\ \frac{R_{c_0}}{R_s}\propto M^{-2/3}\ \ (\rho_{c_0}=\rho_*\ \text{sabit})
```

$$c^+\equiv\text{DM}\equiv\text{DE}\equiv\text{Vakum},\qquad \text{Cₘ'de "boşluk" okunan her bölge (atom içi dahi)} = c^+ \text{'ın Cₘ okuması}$$

```latex
c^+\equiv\text{DM}\equiv\text{DE}\equiv\text{Vakum},\qquad \text{Cₘ'de "boşluk" okunan her bölge (atom içi dahi)} = c^+ \text{'ın Cₘ okuması}
```

| Sembol | Anlamı |
|---|---|
| $\mathrm{Dom}(g_{\mu\nu})$ | Metriğin tanım alanı |
| $\mathrm{supp}_{C_m}$ | Cₘ'deki madde desteği |
| $N_{c_0}$, $\rho_P$, $V_{c_0}$, $R_{c_0}$, $R_s$ | c₀ kapasite sayımı, Planck yoğunluğu, tek-yapı hacmi ve yarıçapı, Schwarzschild yarıçapı |
| DM, DE | Karanlık madde, karanlık enerji |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Metriğin alanını, iki farklı madde geçişini, c₀ tek-yapısının kapasite ilişkilerini ve c⁺ kimliğini kaydeder |
| **Neden yapıyor?** | Dış fazlara metrik taşınmasını önlemek ve 2026-10-14 yazar onaylarını çekirdek koruma kaydına almak için |
| **Nasıl yapıyor?** | Metriği Cₘ'ye sınırlar; c₀ ve c⁺'taki tanımsızlıkları ayrı sembollerle yazar; c₀ kapasitesini Planck birimleriyle ölçekler; c⁺ ≡ vakum kimliğini yazar |
| **Ne sonuç bekleniyor?** | Tek-yapının iç profilinin ve ufukla nicel ilişkisinin türetilmesi |
| **Ne sonuç elde ediliyor?** | Metrik alanı ve madde geçişleri **çekirdektir**; c₀ kapasite ilişkileri ve c⁺ ≡ vakum **yazar hükmüdür**; tarihsel limit **modeldir** |

## C.5 Geçiş, damga ve arşiv

$$(X,\Theta_{ij})\in\mathcal D_{ij}^{\rm adm}\Longleftrightarrow\mathcal A_{ij}(X,\Theta_{ij})=1$$

```latex
(X,\Theta_{ij})\in\mathcal D_{ij}^{\rm adm}\Longleftrightarrow\mathcal A_{ij}(X,\Theta_{ij})=1
```

$$\mathrm{Seal}([p^-,p^+])=(\mathrm{rid},\,\mathrm{kenar},\,\mathrm{damga},\,[p^-,p^+]),\qquad \text{kayıt kanalı: } C_m\to c^+\ \text{(tek yönlü; mühür sabit)}$$

```latex
\mathrm{Seal}([p^-,p^+])=(\mathrm{rid},\,\mathrm{kenar},\,\mathrm{damga},\,[p^-,p^+]),\qquad \text{kayıt kanalı: } C_m\to c^+\ \text{(tek yönlü; mühür sabit)}
```

$$M=\langle s,s',\kappa_{0m},\kappa_{+m}\mid\kappa_{0m}^2=\kappa_{0m},\;\kappa_{+m}^2=\kappa_{+m}\rangle,\qquad \mathrm{Idem}(M)=\{e,\kappa_{0m},\kappa_{+m}\},\qquad G_{\rm univ}(M)\cong F_2,\quad K(M)\cong\mathbb Z^2$$

```latex
M=\langle s,s',\kappa_{0m},\kappa_{+m}\mid\kappa_{0m}^2=\kappa_{0m},\;\kappa_{+m}^2=\kappa_{+m}\rangle,\qquad \mathrm{Idem}(M)=\{e,\kappa_{0m},\kappa_{+m}\},\qquad G_{\rm univ}(M)\cong F_2,\quad K(M)\cong\mathbb Z^2
```

$$\Omega(m)=\log\frac{W_{\rm önce}}{W_{\rm sonra}},\qquad \omega_{AB}(s)=\ln W_A(s)-\ln W_B(s),\qquad \Omega_{\rm enc}(m)=\left[\log\frac{W_A^-}{W_B^+},\ \log\frac{W_A^+}{W_B^-}\right]$$

```latex
\Omega(m)=\log\frac{W_{\rm önce}}{W_{\rm sonra}},\qquad \omega_{AB}(s)=\ln W_A(s)-\ln W_B(s),\qquad \Omega_{\rm enc}(m)=\left[\log\frac{W_A^-}{W_B^+},\ \log\frac{W_A^+}{W_B^-}\right]
```

$$\omega(\kappa)=0,\qquad 0\in\Omega_{\rm enc}(\kappa),\qquad \Pi_\kappa:\mathcal B\to\mathcal B,\quad \Pi_\kappa^2=\Pi_\kappa$$

```latex
\omega(\kappa)=0,\qquad 0\in\Omega_{\rm enc}(\kappa),\qquad \Pi_\kappa:\mathcal B\to\mathcal B,\quad \Pi_\kappa^2=\Pi_\kappa
```

$$A+[r_1]+[r_2]\neq A+[r_1]\ \ (\mathrm{rid}(r_1)\neq\mathrm{rid}(r_2)),\qquad \mathrm{NoDup}(A.\mathrm{map}\;\mathrm{rid}),\qquad A\preceq A',\qquad \mathrm{append}(A,r)\ \text{yalnız}\ \mathrm{rid}(r)\notin\mathrm{IDs}(A)$$

```latex
A+[r_1]+[r_2]\neq A+[r_1]\ \ (\mathrm{rid}(r_1)\neq\mathrm{rid}(r_2)),\qquad \mathrm{NoDup}(A.\mathrm{map}\;\mathrm{rid}),\qquad A\preceq A',\qquad \mathrm{append}(A,r)\ \text{yalnız}\ \mathrm{rid}(r)\notin\mathrm{IDs}(A)
```

$$\mathrm{emittedStamp}(T_{0+})=\texttt{None},\qquad \Sigma(T_{0+})=e,\qquad q(T_{ji})=q(T_{ij})^{-1}$$

```latex
\mathrm{emittedStamp}(T_{0+})=\texttt{None},\qquad \Sigma(T_{0+})=e,\qquad q(T_{ji})=q(T_{ij})^{-1}
```

$$\mathcal R^X_{0+}\subseteq\mathcal X_0\times\mathcal X_+,\qquad \mathcal X_0\xleftarrow{p_0}\mathfrak F^X_{0+}\xrightarrow{p_+}\mathcal X_+\qquad(\text{biçimsel aday})$$

```latex
\mathcal R^X_{0+}\subseteq\mathcal X_0\times\mathcal X_+,\qquad \mathcal X_0\xleftarrow{p_0}\mathfrak F^X_{0+}\xrightarrow{p_+}\mathcal X_+\qquad(\text{biçimsel aday})
```

| Sembol | Anlamı |
|---|---|
| $\mathcal D_{ij}^{\rm adm}$, $\mathcal A_{ij}$ | Kenarın kabul edilebilir alanı ve kabul göstergesi (13.2) |
| $\mathrm{Seal}$ | Mühürleme işlemi; aralığı koruyarak kayıt üretir |
| $M$, $s$, $s'$, $\kappa$ | Damga monoidi, serbest üreteçler, kilitler (14.2) |
| $W$, $\Omega$, $\omega$, $\Omega_{\rm enc}$ | Genişlik, ağırlık, kesin karakter, kapsama aralığı (14.3) |
| $\Pi_\kappa$ | Kilidin izdüşümcü temsili |
| $A$, $[r]$ | Ham arşiv, tek kayıt |
| $\Sigma$, $q$ | Damga haritası, unutkan harita (14.6) |
| $\mathcal R^X_{0+}$, $\mathfrak F^X_{0+}$ | c₀ ↔ c⁺ uyumluluk ilişkisi ve lifi (13.5) |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Geçiş izni, mühürleme, damga cebiri, ağırlık, ham arşiv ve damgasız kenar kayıtlarını bir arada tutar |
| **Neden yapıyor?** | Kapı çift yönlü, damga tek yönlü yapısının bütün cebirsel ve biçimsel ifadelerinin tutarlı kalması için |
| **Nasıl yapıyor?** | Her ilişkiyi en kısa koruma biçimiyle yazar; biçimsel aday olanları ayrıca işaretler |
| **Ne sonuç bekleniyor?** | Arşiv–Σ bütünleştirmesinin ve yön anlamının biçimsel olarak kapanması |
| **Ne sonuç elde ediliyor?** | Damga cebiri **kanıtlanmıştır**; kayıt kanalının yönü **yazar hükmüdür**; c₀ ↔ c⁺ lifi **biçimsel adaydır** |

## C.6 Topoloji, köprü ve yöntem

$$V=3,\quad E=3,\quad \beta_1=1,\quad H_1\cong\mathbb Z\ \ (\text{sınır üçgeni}),\qquad H_1=0\ \ (\text{dolu üçgen})$$

```latex
V=3,\quad E=3,\quad \beta_1=1,\quad H_1\cong\mathbb Z\ \ (\text{sınır üçgeni}),\qquad H_1=0\ \ (\text{dolu üçgen})
```

$$[\Delta_{\rm kabuk}]_{\rm ET}=[\mu_A]\odot[\Delta_{\rm kabuk}]_{\rm yapı}$$

```latex
[\Delta_{\rm kabuk}]_{\rm ET}=[\mu_A]\odot[\Delta_{\rm kabuk}]_{\rm yapı}
```

$$N_{\rm serbest}<N_{\rm gözlenebilir},\qquad D_{\rm model}=N_{\rm skaler}+N_{\rm fonksiyonel}+N_{\rm hiper}$$

```latex
N_{\rm serbest}<N_{\rm gözlenebilir},\qquad D_{\rm model}=N_{\rm skaler}+N_{\rm fonksiyonel}+N_{\rm hiper}
```

$$D_{\rm türetim}\cap D_{\rm kör}=\varnothing,\qquad \theta_{\rm köprü}\ \text{kör veri açılmadan önce dondurulur}$$

```latex
D_{\rm türetim}\cap D_{\rm kör}=\varnothing,\qquad \theta_{\rm köprü}\ \text{kör veri açılmadan önce dondurulur}
```

$$\Delta X_{\rm pred}\cap\Delta X_{\rm obs}=\varnothing\Longrightarrow \text{öngörü reddedilir}$$

```latex
\Delta X_{\rm pred}\cap\Delta X_{\rm obs}=\varnothing\Longrightarrow \text{öngörü reddedilir}
```

| Sembol | Anlamı |
|---|---|
| $V$, $E$, $\beta_1$, $H_1$ | Köşe ve kenar sayısı, Betti sayısı, homoloji (19.5) |
| $[\mu_A]$, $[\Delta_{\rm kabuk}]$ | Zarf modülasyonu ve kabuk boşluğu bantları (22.2) |
| $N_{\rm serbest}$, $N_{\rm gözlenebilir}$, $D_{\rm model}$ | Parametre bütçesi nicelikleri (23.5) |
| $D_{\rm türetim}$, $D_{\rm kör}$, $\theta_{\rm köprü}$ | Katı Kör Soyağacı nicelikleri (22.5) |
| $\Delta X_{\rm pred}$, $\Delta X_{\rm obs}$ | Öngörü ve gözlem aralıkları |

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Topoloji, nükleer köprü ansatz'ı, parametre bütçesi, kör soyağacı ve ampirik ret koşulunu kaydeder |
| **Neden yapıyor?** | Çerçevenin gözlemle temas kurallarının sembol düzeyinde sabitlenmesi için |
| **Nasıl yapıyor?** | Her yöntem kuralını tek bir denklemle yazar |
| **Ne sonuç bekleniyor?** | Bütün köprü testlerinin bu kurallarla yürütülmesi |
| **Ne sonuç elde ediliyor?** | Topoloji sonuçları **kanıtlanmıştır**; nükleer ansatz **koşullu yapısal adaydır**; yöntem kuralları **bağlayıcıdır** |

## EK C.7 Bölüm 27 aday envanteriyle eşleme notu

Bölüm 27'deki envanter, bu ekin koruma kayıtlarının aday ailesini listeler. Bir denklemin Bölüm 27'de adı geçmesi, EK C'deki çekirdek statüsüne yükseldiği anlamına gelmez. Statü, ilgili gövde bölümündeki işaretle belirlenir.

---

# EK D — DÜŞÜNCE DENEYLERİ VE BENZETMELER

Aşağıdakiler **kavramsal araçlardır**. Hiçbiri kanıt ya da türetim değildir.

## Bilgisel sıkıştırma

c₀'da bir durum tam ve farklılaşmamış, metrik boşluksuz tek bir bütündür. Cₘ'ye geçişte bu bütün **çözülerek okunur**: sonlu çözünürlükte, ayrık nesneler hâlinde. Bu, Cₘ ölçümünün neden sonlu çözünürlüklü olduğunun sezgisel resmidir.

## Gösterge paneli

Cₘ gerçekliğin **okunabilir yüzeyidir**. Bir panel motorun kendisi değildir; motorun okunabilir hâlidir. Ama panel olmadan motor hakkında hiçbir şey söylenemez.

## Sinema perdesi

Perdede görülen hareket perdenin kendisinde değildir; ardışık karelerin okunmasından doğar. Zaman da böyledir: "akan" bir şey değil, **birikimden doğan** bir okuma.

## Değnek Ambarı

Çalışma yönteminin adıdır. Birden fazla bağımsız aracın birbirini denetleyerek çalıştığı bir düzen. Hiçbiri tek başına yetkili değildir; değer **çaprazlamadan** gelir. Son karar yazarındır.

## Toplu davranış

Bose–Einstein yoğuşması ve süperakışkanlık, ayrık nesnelerin toplu bir bütün gibi davranmasının laboratuvarda erişilebilir örnekleridir. **BEC c₀ değildir; madde fazında c₀ ortamına en yakın ortamdır** (18.5). Bu yüzden c₀'ın tek-yapı sezgisine Cₘ içinden bakmanın en iyi penceresidir; ama pencere, baktığı şeyin kendisi değildir.

## Çözücü çağrısı

$X$, bir değer değil, bir **çözümleme çağrısının sonucudur**: bağlamı alır, o bağlamda geçerli olanı döndürür. Yalnız bir programlama benzetmesidir.

## Ay / bilgisel çözünürlük benzetmesi

Tarihsel "Ay benzetmesi", fazlar arası okuma sırasında tam ontolojik durum ile Cₘ'nin sonlu okuma kapasitesini ayırmak için kullanılmıştır. Benzetmenin güvenli özü şudur: **bir kaynağın tam durumu ile ondan alınan Cₘ izdüşümü aynı bilgi türü değildir**. Bu, fiziksel veri sıkıştırmasının kanıtı ya da özel bir bit sayısı türetimi değildir.

## Hartman etkisi

Standart fizik açısından Hartman etkisi, opak tünelleme bariyerlerinde grup gecikmesinin doygunluğa ulaşması olgusudur; standart kuramda bu doygunluk, grup gecikmesinin bir geçiş süresi değil, bariyerde depolanan enerjinin boşalma süresiyle ilişkili olmasıyla açıklanır (Winful 2003). Evertophy okuması bu yüzden **uyumlu okumadır**, doğrulama değildir. Evertophy'de yalnız şu düşünce deneyini güdüler: faz eşiği bölgesinde saf Cₘ geçiş süresi dili yetersiz olabilir.

$$\boxed{\;\text{Hartman doygunluğu} \neq \text{geçiş süresi gerçekten sıfır} \neq \text{ışıktan hızlı sinyal kanıtı}\;}$$

```latex
\boxed{\;\text{Hartman doygunluğu} \neq \text{geçiş süresi gerçekten sıfır} \neq \text{ışıktan hızlı sinyal kanıtı}\;}
```

## Schwinger etkisi

Schwinger çift üretimi, güçlü bir dış alanın enerjisinden parçacık çifti üretimidir. c⁺ ≡ vakum kimliği altında bu olgu, c⁺ → Cₘ kenarında dış enerjiyle tetiklenen yerel bir faz geçişi olarak **okunur** (aday okuma, 18.4). Ama:

$$\boxed{\;\text{Schwinger etkisi} \neq c^+\to C_m \text{ ontolojik geçişinin kanıtı}\;}$$

```latex
\boxed{\;\text{Schwinger etkisi} \neq c^+\to C_m \text{ ontolojik geçişinin kanıtı}\;}
```

Enerji "hiçlikten" gelmez: dış alanın enerjisi bütçeye girer.

## Kara delik düşünce deneyi

Kara delik ≡ c₀ yazarın ontolojik tanımıdır; olay ufku ile faz sınırının birebir özdeşliği ise kurulmuş değildir. Yoğunluk Planck değerinde alındığında ($\rho_*=\rho_P$; en küçük yarıçap) Güneş kütleli bir kara delikte tek-yapının yarıçap ölçeği ($\sim10^{-23}$ m) ufuk yarıçapından (~3 km) çok küçüktür. Güncel çekirdek şu ayrımı korur:

```text
ufuk = Cₘ nedensel / geometrik yapısı
c₀   = zaman-öncesi, metrik boşluksuz tümleşik tek-yapı fazı
```

## Arşiv / kütüphane benzetmesi

Bir arşivde kayıtların birlikte erişilebilir olması, arşivin kendi "akan zamanına" sahip olduğunu göstermez. Bu benzetme, c⁺'ta kaynak sırası ile fiziksel zamanın ayrılmasını sezgisel olarak anlatır.

## Tarihsel işlemleme benzetmeleri

**Kayıt defteri doygunluğu**, ısı ölümü yerine arşiv doygunluğu düşüncesini anlatan bir yorumdur; termodinamik sonuç ya da c⁺ yasası değildir. **IPW, işlemleme titreşimi, kare hızı** ve **vites kutusu** dili, Cₘ okumasındaki sonlu işlemleme / örnekleme sezgisini taşır; $H_0$ için "vites debisi" kanonik öngörüsü üretmez. "c⁺ ağ / iskelet" ve "tutuklu / serbest doku" ifadeleri de tarihsel anlatı yüzleridir; c⁺'ın güncel tanımının yerine geçmez.

## Değnek Ambarı — dört katmanlı yöntem notu

Tarihsel anlatıda Değnek Ambarı dört ayrı koruma katmanı taşır: fizik denetimi, yöntem denetimi, yapay zekâ kayması riski ve etik / bilinç kilidi. Bu katmanlar çalışma disiplinidir; fiziksel faz ya da ontolojik temel öğe değildir.

## Uydu–elektron düşünce deneyi zinciri

Uydu–elektron düşünce deneyleri zinciri: (1) yörünge elektronu — saf uzay ortamında elektronun çok uzun süreli davranışı; (2) evrensel Planck yoğunluğu izdüşümü. Zincirin amacı c₀'ın laboratuvar-uzay ilişkisini sezdirmektir; ölçüm önerisi değildir.

## Vakum deneyi düşünce alıştırması

Mükemmel bir vakumda (kozmik ya da laboratuvar) sürecin nasıl okunacağı alıştırmasıdır. Güncel kanonda **vakum, c⁺'ın Cₘ okumasıdır** (c⁺ ≡ vakum, Bölüm 3); kuantum alan kuramının vakum durumu bu kimliğin hesap dilidir. Alıştırma iki şeyi hatırlatır: vakumun "boş" görünmesi c⁺'ın yokluğu değil, Cₘ'deki okunuş biçimidir; maddenin yokluğu da c₀'ı kanıtlamaz, çünkü c₀ maddenin yokluğu değil, metrik boşluksuz tek-yapı hâlidir.

## BEC süper-atom ve süperakışkan helyum-4 benzetme tablosu

| Laboratuvar sistemi | c₀ sezgisine katkı |
|---|---|
| BEC süper-atom | Toplu, tek kuantum durumlu davranış — madde fazında c₀'a en yakın ortam |
| Süperakışkan He-4 | Sürtünmesiz toplu akış |

Her ikisi de Bölüm 3'teki benzetme ailesinin örnekleridir; gerçek kimlik değildir.

## Frekans dönüşümü düşünce deneyi

25.32'deki kaydın benzetme düzeyindeki ifadesidir.

## "Yumuşak düğmeden ani anahtara" — faz rejimi – eşik sınırı benzetmesi

Sınır bandının davranışını sezdiren gündelik bir benzetmedir: yumuşak düğme (kademeli) ile ani anahtar (eşik) arasındaki geçiş. 25.1'deki terim kilidi burada da geçerlidir — gündelik anahtar kelime akademik metne girmez.

---

# EK E — EPİSTEMİK DÜZEN

## Kim neyi belirler

| Kaynak | Yetki |
|---|---|
| **Doğrudan mimar (yazar) açıklaması** | Kanon — kaynak kod statüsü |
| **Güncel çekirdek** | Yürürlükteki ontoloji |
| **Güncel biçimsel kanon** | Doğrulanmış biçimsel sonuç |
| **Uyumlu biçimsel aday** | Onaya tabi |
| **Tarihsel arşiv** | Korunur, karıştırılmaz |
| **Araç yorumu** | Taslak |

$$\boxed{\;\text{Yöntem kuralları ARAÇLARI bağlar, MİMARI bağlamaz.}\;}$$

```latex
\boxed{\;\text{Yöntem kuralları ARAÇLARI bağlar, MİMARI bağlamaz.}\;}
```

Bir kural "yeni kanonik içerik üretme" diyorsa, bu **araçlara** yöneliktir.

## Doğrudan kanon maddeleri

Aşağıdakiler mimarın doğrudan ontolojik girdileridir ve araç yorumuyla değiştirilemez:

- $U_0$'ın üç fazı **eş zamanlı** — aynı kuruluşta birlikte — oluşturması
- **Tam çift yönlü üçgen** topolojisi
- $c^+ \equiv$ karanlık madde $\equiv$ karanlık enerji $\equiv$ **vakum** iç ontolojik kimliği
- Atomu oluşturan parçacıklar arasındaki boşluğun dahi c⁺ olması
- **Kara delik ≡ c₀** ve c₀'daki maddenin Planck ölçeğinde metrik boşluksuz duruma yakınsayan derecede bitişik, **tek bir yapı formunda** olması (Planck boyutunda bir çekirdek anlamına gelmez); kapasitenin Planck kütlesiyle sayılması ve yoğunluğun Planck yoğunluğunu aşmaması
- c₀'da zamanın durmuş değil, **henüz kurulmamış** olması; c⁺'ta zamanın çözünmüş olması ($\bot_0\neq\bot_+\neq0$)
- Cₘ kinematik üyelik bandının $0<v<c$ olması; $v=c$'nin Cₘ ile c⁺'ın liminal ortak sınırı olması
- **Kayıt kanalının Cₘ → c⁺ yönünde tek yönlü** olması ve mühürlendiğinde kaydın sabit kalması
- BEC'in c₀ değil, **madde fazında c₀ ortamına en yakın ortam** olması
- c⁺'ın **kapalı devre** olması ve gerekçesinin **önce akademik sınır** olması
- **Faz-parametre matrisi yönteminin** çekirdek statüsü
- $[P,P]$'nin geçerli bir aralık olması
- **Küresel evren düzeyinin varlığı** ($U_0$, $U_x$, $U_+$) ve faz düzeyinden ayrılığı
- **$U_+$ — Mutlak Çözünme ≡ Mutlak Yırtılma**; Big Yırtılma, $U_+$ sınırındaki kritik eşikle ilişkilidir
- **Dinamik evrenin son bulabilir ya da bulmayabilir olması**
- **Sessizlik ilkesi**
- **Üçüncü ilke:** ölçümü doğru yeniden üreten matematiksel temsil o ölçüm kapsamında koşulsuz kabul edilir; temsiller arasında ontolojik öncelik yoktur
- **Kanonik görüntünün çekirdek yapı statüsü** (EK J)

## Yenilik nasıl işler

Sonraki kayıt öncekini geçersiz kılmaz — **üstüne yazar** ve eskisi neden bırakıldığıyla birlikte saklanır. Bir çerçevenin öğrenme tarihi, mevcut hâli kadar bilgilendiricidir.

## Araç hizalama özeti

Bu monografiyle çalışan her araç şu dört şeyi bilmelidir:

1. **Üstünlük sırası** yukarıdaki tablodadır; bir aracın kendi çıktısı en alttadır.
2. **Tarihsel içerik korunur ama güncel çekirdeğe karıştırılmaz.**
3. **Mekanizma ataması türetim değildir**; bir eşleme yazmak bir sayı üretmez.
4. **Sayaç 0/10'dur** ve altı koşul birden sağlanmadan hareket etmez.

---




# EK F — BİÇİMSEL MİMARİ VE UYGULAMA DURUMU

## Katmanlar

Biçimsel çekirdeğin amacı, bütün fiziksel içeriği tek bir yapıya sıkıştırmak değil, anlamsal sınıfları tür düzeyinde ayırmaktır. Bir kavramın hangi katmana ait olduğu tür sistemi tarafından zorlandığında, metindeki "ayrı tutulmalıdır" uyarılarının çoğu derleyicinin kendiliğinden yakaladığı hatalara dönüşür.

```text
Köken / Üst katman:
    U₀
    Uₓ = üçlü faz sisteminin bütünsel gösterimi
    U₊ = Mutlak Çözünme ≡ Mutlak Yırtılma

Ontoloji:
    Faz = {c₀, Cₘ, c⁺}
    X = üst çözücü (skaler değil; okumaları ξ_k = π_k(X))

Kapılar:
    tam çift yönlü üçgen (Δ₀ₘ, Δ₊ₘ damgalı; Δ₀₊ damgasız)

Geçiş:
    Kenar sınıfı + yön + kabul edilebilirlik

Damga:
    Damga sınıfı + damga üretimi + monoid M

Arşiv:
    ham kaynak kayıtları + yalnız eklemeli sıra
    kayıt kanalı: Cₘ → c⁺ (tek yönlü; mühür sabit)

Koordinasyon:
    c₀↔c⁺ X-ilişkisi / lif adayı

Okuma:
    Cₘ gözlenebilirleri (c⁺ ≡ vakum okuması dahil)

Yöntem:
    Parametre Bütçesi + Köprü Bütçesi + ön kayıt
```

## Asgari tür iskeleti

Aşağıdaki şema bir uygulama yönelimidir; ontolojinin nihai programlama dili değildir.

```lean
inductive Phase
  | c0
  | cm
  | cp

inductive TemporalRole
  | preEmergent
  | physicalTime
  | atemporalRecord

inductive EdgeClass
  | e0m
  | emp
  | e0p

inductive ArchiveEffect
  | noMutation
  | append
  | readProject

inductive CoordEffect
  | none
  | xCoord

structure TransitionSemantics where
  src : Phase
  dst : Phase
  edge : EdgeClass
  stampEmission : Option Stamp
  archiveEffect : ArchiveEffect
  coordEffect : CoordEffect
```

`U₀`, `Uₓ` ve `X`, `Phase` türünün kurucusu değildir. `Uₓ`, üç `Phase` kurucusunun sistem bütünü düzeyindeki gösterimidir; yeni bir dördüncü kurucu eklemez.

## Biçimsel kapanış öncelikleri

1. Normal forma indirgeyici / yeniden yazma sistemi için bütün yolların aynı normal biçimde buluşması (konfluans) — **kapandı** (14.2).
2. Genel birleşme özelliği — **kapandı** (14.2).
3. İdempotent sınıflandırması — **kapandı** (14.2); kalan yalnız paket bütünleştirmesi.
4. $I(\mathbb Q)$ / gerçel sayılar için tam aralık karakteri.
5. Arşiv `rid` tekliği ve yalnız eklemeli değişmezler.
6. $q$ / $\Sigma$ / arşiv yön anlamının bütünleştirilmesi (kayıt kanalı Cₘ → c⁺ hükmüyle hizalı).
7. $X$ koordinasyon ilişkisi / lifi için asgari tür ve Parametre Bütçesi muhasebesi.
8. Cₘ metrik yeniden kurma arayüzlerinin biçimsel türü.
9. $\bot_0$ ve $\bot_+$'nın ayrı türler olarak kodlanması (`undefined0` / `dissolvedPlus`) ve $dt_{c^+}=0$ pedagojik kısaltmasının tür düzeyinde sayısal sıfırdan ayrılması.
10. Yön anlamının ayrı türlere bölünmesi: `TransitionDirection`, `StampCarried`, `StampEmitted`, `ArchiveAppend` (13.3, 14.7).
11. Küresel sınır ilişkilerinin (`GlobalBoundary(Uₓ,U₀)`, `Genesis`, `Dissolution`) zaman parametresi içermeyen saf ilişkiler olarak türlenmesi.
12. Bant türlerinin ($B_{\rm kesin}$, $B_{1-\alpha}$, $B_{\rm inanç}$) ayrı türler olarak kodlanması (21.6).
13. Yayın paketi: kanonik görsel dosyasının (`Evertophy_Core_20260919_revize_gerekiyor_v2.png`) belgeyle birlikte paketlenmesi; Lean / toolchain sürümü, kaynak özeti ve aksiyom envanteriyle yeniden üretilebilir derleme kaydı.

## Teorem sayısının yorumu

Önceki envanterde raporlanan 119 teorem bildirimi (tarihsel envanter; güncel envanter $269 = 46$ üretim $+ 223$ arşiv, 23.10), biçimsel tanım ve değişmezlerin makine tarafından denetlenen kısmını gösterir. Bu sayı şunlar anlamına **gelmez**: 119 bağımsız fizik yasası · 119 deneysel başarı · Evertophy'nin doğrulanması.

$$269=46_{\rm üretim}+223_{\rm arşiv},\qquad 223=66_{\rm eski}+53_{\rm V03}+104_{\rm V24}$$

```latex
269=46_{\rm üretim}+223_{\rm arşiv},\qquad 223=66_{\rm eski}+53_{\rm V03}+104_{\rm V24}
```

| Soru | Cevap |
|---|---|
| **Ne yapıyor?** | Biçimsel envanterin bileşimini sayısal olarak açar |
| **Neden yapıyor?** | Teorem sayısının bir fizik başarısı gibi okunmasını önlemek ve sayımın tutarlılığını görünür kılmak için |
| **Nasıl yapıyor?** | Toplamı üretim ve arşiv, arşivi de üç alt pakete ayırır |
| **Ne sonuç bekleniyor?** | Bağımsız bir dış derlemeyle aynı sayının yeniden elde edilmesi |
| **Ne sonuç elde ediliyor?** | **Biçimsel envanterdir**; fiziksel doğrulama sayısı değildir. Sayım kaynak koşusu atfıyla kayıtlıdır (23.10) |

## Güncel biçimsel statü

**Biçimsel / üretim çekirdeği — kapalı:** faz ile küresel düğüm ayrımı · $U_x$'in kutup olmaması · faza göre dizinlenmiş değer tipi · metriğin yalnız Cₘ'de izinliliği · nicelik türü ≠ boyut · içsel / kaynak / gözlem faz rolleri · tipli Cₘ okuma arayüzü · kapı ≠ taşıma izni · Cₘ'ye özgü kapı kilidi · kapı kilidi ⟺ en fazla bir içsel faz · arşiv sayısının ekleme tekdüzeliği · olay türü ve iz politikası ayrımları · damga cebirinin birleşme, sonlanma, tek normal form, konfluans ve idempotent sınıflandırması · köprünün sonlu modelde tekil olmayışı.

**Biçimsel aday / açık:** fiziksel okuma yasası · genel köprü seçicisi · $X$-lifi gerçeklemesi · metrik yeniden inşa · tam genel, genişletilmiş ve bağımlılık izlemeli aralık hesabı · üretim dışı yol ve kategori adayları · c₀ tek-yapı kapasite ilişkilerinin ($N_{c_0}=M/m_P$, $\rho\le\rho_P$) tür düzeyinde kodlanması.

## Tipli ontoloji genişletmesi — Phase / GlobalNode, Gate / GlobalRel, Ux ∉ Pole

Biçimsel öneri: iki ontolojik düzey tür düzeyinde ayrılır — `Phase` (c₀, Cₘ, c⁺) ve `GlobalNode` (U₀, Uₓ, U₊); kapılar `Gate`, küresel oklar `GlobalRel` türündedir ve `Ux ∉ Pole` değişmezi tip düzeyinde zorlanır. Üretim çekirdeğinde **kapalı** olanlar: faz ile küresel düğüm ayrımı, $U_x$'in kutup olmaması, faza göre dizinlenmiş değer tipi, metriğin Cₘ'ye özgülüğü, nicelik türü ≠ boyut, kapı ≠ taşıma izni, faz rolleri ve kapı kilidi. Üretim dışında ve **açık** olanlar: küresel ilişkilerin tam cebiri, yol-grupoid genişletmesi, fiziksel köprü seçicisi, $X$-lifi ve metrik yeniden inşa.

## Değer türleri — CmOnlyValue, MetricAdmissible, QuantityKind / Dimension

**Statü: biçimsel — kapalı (üretim çekirdeği).** Tür ailesi: Cₘ'ye özgü niceliklerin `CmOnlyValue` ile damgalanması, metriğin `MetricAdmissible` koşulu, nicelik türü ile boyut etiketinin ayrıştırılması (5.3a'nın biçimsel karşılığı).

## Köprü tipleri — BridgeSpec, CmReadoutBridge, köprünün tekil olmayışı

**Statü: tekil olmayış biçimsel olarak kapalı; genel seçici açık.** Kanıtlanmış tekil olmayış sonucunun (24.1) biçimsel ifadesi: birden fazla `BridgeSpec` aynı tip ve iyi tanımlılık koşullarını sağlayabilir; bu yüzden köprü seçimi gözlem gerektirir.

## Kapı tiplemesi — tipli kapı, GateRelated ≠ TransportPermission

**Statü: biçimsel — kapalı (üretim çekirdeği).** 13.1a'nın biçimsel karşılığı: `GateRelated(c0, cp)` doğruyken bu, nicelik taşıma izni vermez; taşıma izni ayrı bir `phase-license` türündedir.

## Yol cebiri — sıradan kategori / yol-grupoid ve aşamalı skaler olmayan X + ξ izdüşümleri

13.2'nin biçimsel arka planı: geçişlerin sıradan bir kategoride bileştirilmesi, çıplak katmanda tersinir yol cebiri (yol-grupoid), damga katmanında monoid (grup değil). Skaler olmayan $X$ için kenara özgü okuma izdüşümleri $\xi_{ij}=\pi_{ij}(X)$.

---

# EK G — TARİHSEL OKUMALAR

Bu ek yayın çekirdeğinin dışına alınmıştır; içeriği V24 yürüyen ana kaydında (§688) korunur.

# EK H — SAYISAL VE ÖNGÖRÜ KAYDI

Bu ek yayın çekirdeğinin dışına alınmıştır; içeriği V24 yürüyen ana kaydında (§688) korunur. Arşivdeki sayısal okumaların hiçbiri önceden kayıtlı öngörü değildir (21.24). Bu sürümde çekirdeğe alınan sayısal ilişkiler (c₀ kapasite ölçeklemesi, $\rho_P\approx5.16\times10^{96}\ \mathrm{kg/m^3}$, Güneş kütlesi için $R_{c_0}\approx4.5\times10^{-23}$ m ve $R_s\approx2.95$ km) öngörü değil, yazar hükmünün sayısal açılımıdır (Bölüm 3).

# EK I — MAKİNE TARAFINDAN OKUNABİLİR ONTOLOJİ İSKELETİ

Bu ek bir fizik postülası değildir; anlam kaymasını azaltmak için önerilen **normatif olmayan, makine tarafından okunabilir bir ayna** katmanıdır. Çelişki hâlinde normatif kaynak her zaman ana düzyazı çekirdektir: **ana düzyazı çekirdek > makine tarafından okunabilir ayna**.

```yaml
origin:
  U0:
    phase_object: false
    gate_endpoint: false
    co_genesis: [c0, Cm, cp]          # eş zamanlı: aynı kuruluşta birlikte
    external_physical_clock: false
    pre_layer_form: contiguous_single_form_metric_gapless   # yazar hükmü

system:
  Ux:
    phase_object: false
    phase_constructor: false
    system_whole_of: [c0, Cm, cp]
    identical_to_X: false
    identical_to_U0: false
    full_semantics: open_debt

phases:
  c0:
    temporal_role: pre_emergent       # zaman durmuş değil, henüz kurulmamış
    time_status: not_yet_established  # ⊥₀
    metric_admissible: false
    matter_role: metric_gapless_contiguous_single_form   # Planck boyutunda nokta DEĞİL
    black_hole_identity: true         # yazar tanımı
    capacity_unit: planck_mass        # N = M / m_P
    density_upper_bound: planck_density   # ρ ≤ ρ_P ≈ 5.16e96 kg/m^3
    radius_scaling: "M^(1/3)"         # yalnız sabit yoğunluk gerçeklemesinde (rho_* <= rho_P)
    density_vs_mass: non_increasing   # yazar hükmü; üst sınırdan türetilmez
    geometric_quantities: Cm_readout_parameters   # V, R, rho: c₀'ın içsel geometrisi değil
    BEC_is_c0: false                  # BEC = madde fazında c₀'a en yakın ortam
  Cm:
    temporal_role: physical_time
    metric_admissible: true
    matter_role: differentiated
    direct_measurement: true
    fundamental_space: euclidean_3d_flat
    kinematic_membership_band: "0 < v < c"
    liminal_shared_boundary_with_cp: "v = c"   # sınır ≠ üyelik
  cp:
    temporal_role: atemporal_record
    time_status: dissolved            # ⊥₊ ; dt_cp = 0 yalnız pedagojik
    metric_admissible: false
    matter_role: Cm_support_dissolved
    ontological_identity: [DM, DE, Vacuum]     # c⁺ ≡ DM ≡ DE ≡ Vakum
    QFT_vacuum: Cm_computational_language_of_cp
    interatomic_gaps_are_cp_readout: true      # yazar hükmü
    c_beyond_Cm_regime: true
    matter_structure_outside_0_v_c: not_preserved
    physical_time_admissible: false
    Cm_time_support: dissolved
    temporal_record: sealed
    dark_matter_readout: clustered_cp
    dark_energy_readout: expansion_associated_cp   # yazar: "genişlemeyi sürdüren c⁺"; genişleme Cₘ'de okunan görünümdür, c⁺'a içsel zaman atfetmez
    laboratory_readout: vacuum
    identity_implies_equal_readout_densities: false
    intrinsic_Cm_speed: inadmissible
    signal_channel: false             # ışınlama: c⁺ korelasyon kaynağı + klasik kanal

record_channel:
  direction: Cm_to_cp
  one_way: true
  seal_fixed: true

force_of_attraction:
  status: core_postulate
  ontology: phase_independent_constraint_coherence
  projections: [gravitation, strong, weak, electromagnetism]
  gravitation_is: Cm_metric_projection
  term_lock: "Force of Attraction != Gravitation"
  repulsion_and_charge: deferred

meta_coordination:
  X: MetaCrossPermission        # genel, kesin; fiziksel taşıma değildir; TransportPermission ayrıdır
  X_scalar: false
  readings: "xi_k = pi_k(X)"
  c0_cp_specific_relation: formal_candidate   # §13.6

global_nodes:
  U0:    {role: pole, phase_object: false}
  Ux:    {role: global_node, pole: false, phase_object: false}
  Uplus: {role: pole, phase_object: false, name: "Mutlak Çözünme == Mutlak Yırtılma"}

absence:
  c0: undefined0
  cp: dissolvedPlus
  distinct: true                # ⊥₀ ≠ ⊥₊ ≠ 0
  epistemic: MissingData        # ontolojik yokluk değildir

gate_lock:
  Cm_only_not_transportable: [time, space3, metric, intrinsic_speed, c_bound, rest_mass]
  readout_of_cp_sourced_effects: allowed

representation_principle:      # üçüncü ilke
  valid_within_reproduced_measurement: true
  ontological_priority_between_representations: none

range:
  point_as_degenerate_band: true

topology:
  gates:
    - [c0, Cm]
    - [Cm, cp]
    - [c0, cp]
  bidirectional: true
  stamped_edges: [e0m, emp]
  stampless_edges: [e0p]

cycle_seed:
  double_limit_core: true
  ordinary_phase_transition_to_U0: false
  full_mechanism_reserved_for: V24

counter: "0/10"
```

Örnek ontoloji geriye dönük uyumluluk testleri:

```text
assert U0 not in Phase
assert Ux not in Phase
assert Ux != U0
assert Ux != X
assert gateRelated(c0,cp)
assert physicalTime(c0) == false
assert physicalTime(Cm) == true
assert physicalTime(cp) == false
assert undefined0 != dissolvedPlus
assert undefined0 != 0 and dissolvedPlus != 0
assert metricAllowed(c0) == false
assert metricAllowed(Cm) == true
assert metricAllowed(cp) == false
assert identity(cp) == {DM, DE, Vacuum}
assert BEC != c0
assert membershipBand(Cm) == "0 < v < c"
assert boundary(Cm, cp) == "v = c" and boundary != membership
assert recordChannel == (Cm -> cp) and oneWay
assert MetaCrossPermission(X) == true
assert MetaCrossPermission != TransportPermission
assert Range(P,P) is valid
assert NoStamp != NoTransition
```

Bu testler fiziksel kanıt değildir; **ontoloji uyumluluk korumasıdır**.

## EK I.1 Tipli ontoloji alanlarının iskelete yansıtılması

Aşağıdaki YAML iskeleti, EK F'deki aday tür ailesinin makine tarafından okunabilir karşılığının genişletilmesi önerisidir; normatif değildir:

```yaml
value_types:
  CmOnlyValue: true        # zaman, metrik, durgun kütle
  MetricAdmissible: "phi == cm"
bridge:
  non_unique: true         # BridgeSpec ailesi
  selection: "physical + observation"
gate:
  related_implies_transport: false
global:
  Ux_not_pole: true
```

---




# EK J — KANONİK RENDER (ÇEKİRDEK GÖRSEL YAPI)

Bu ek, çerçevenin kanonik görselini ve kaynak kodunu taşır. Görsel bir illüstrasyon değil, **çekirdek yapının kendisidir**: sonraki sürümlerde ayrıntılar değişebilir, yapı değişmez.

## J.1 Görselin okunuşu

| Öğe | Ontolojik anlam |
|---|---|
| Sol kırmızı daire — $U_0$ (Mutlak Çekirdek) | Küresel doygunluk kutbu; Dinamik Evren'in bütün yapılarının metrik boşluksuz tek bir formda bulunduğu ön katman |
| Sol süslü parantez | Küresel düzey ile faz sisteminin sınırı |
| Siyah çerçeve — üstte $U_x$, altta *Dinamik Evren* | Üç fazın birlikte gerçekleştiği küresel yapı |
| Üç kalın siyah nokta | Faz düğümleri: $c_0$, $C_m$, $c^+$ |
| Üç çift yönlü ok — $\Delta_{0m}$, $\Delta_{0+}$, $\Delta_{+m}$ | Tam çift yönlü üçgen: üç kapı; $\Delta_{0m}$ ve $\Delta_{+m}$ damga taşır, $\Delta_{0+}$ damgasızdır |
| Sağ süslü parantez | Aynı sınır, çözünme tarafı |
| Sağ kırmızı daire — $U_+$ (Mutlak Çözünme ≡ Mutlak Yırtılma) | Küresel çözünme kutbu |
| Kalın dış oklar | **Bütünle ilişki** (doğuş / limit) — faz kapısı değildir |

## J.2 Değişmez çekirdek öğeler

1. **İki seviye:** dış kutuplar ($U_0$, $U_+$) ve iç faz sistemi ($U_x$)
2. **Simetri:** $U_0$ solda, $U_+$ sağda, eşit görsel ağırlıkta
3. **Tam çift yönlü üçgen** ve üç etiketli kenar
4. **Köşelerde kalın siyah nokta** — faz düğümünü sınır bandından ayırır
5. **Dış okların parantezde bitmesi** — hiçbir faz noktasına değmez
6. **Çerçevenin $U_x$ / Dinamik Evren olarak etiketlenmesi**

## J.3 Değişebilecek ayrıntılar

Etiket metinleri ve alt başlıklar · renk tonları ve font büyüklükleri · koordinat ince ayarı · yardımcı katmanlar (faz rejim – eşik sınırı gösterimi, $C_m$ altında hız bandı, dalga boyu faktörü, kara delik eşik faktörü).

## J.4 Semantik korumalar

$$\boxed{\;\leftrightarrow \text{ sembolü küresel düzeyde TERSİNİR İŞLEMCİ iddia etmez.}\;}$$

```latex
\boxed{\;\leftrightarrow \text{ sembolü küresel düzeyde TERSİNİR İŞLEMCİ iddia etmez.}\;}
```

Soldan sağa okuma bir süreç izlenimi verir; **devre bir zaman akışı değildir** (Bölüm 2.8). Görselde faz düğümleri ile global kutuplar **aynı grafik sınıfında değildir**: düğümler siyah nokta, kutuplar kırmızı dairedir — bu ayrım korunmalıdır.

## J.5 Kanonik LaTeX / TikZ kaynak kodu

Kaynak kod, çift mühürleme protokolü (23.10a) gereği minor12'deki biçimiyle birebir korunmuştur.

```latex
\documentclass[border=15pt]{standalone}

\usepackage{tikz}
\usepackage{amsmath}

\usetikzlibrary{
    decorations.pathreplacing,
    calligraphy
}

\begin{document}

\begin{tikzpicture}[>=stealth, thick]

    % ============================================================
    % SOL TARAF: U_0 — Mutlak Çekirdek
    % ============================================================
    \node[
        align=center,
        circle,
        draw=red!70,
        fill=red!5,
        inner sep=5pt,
        very thick
    ] (u0) at (-7, 2.25) {
        \Large $U_0$ \\
        \footnotesize (Mutlak Çekirdek)
    };


    % ============================================================
    % U_x — DİNAMİK EVREN ÇERÇEVESİ
    % ============================================================
    \draw[very thick]
        (-4.15, -0.75)
        rectangle
        (6.15, 5.35);

    % U_x etiketi — üst kenarın ortasında
    \node[
        fill=white,
        inner sep=4pt
    ] at (1.00, 5.35) {
        \Large $U_x$
    };

    % Dinamik Evren etiketi — alt kenarın ortasında
    \node[
        fill=white,
        inner sep=4pt
    ] at (1.00, -0.75) {
        \large Dinamik Evren
    };


    % ============================================================
    % EVERTOPHY FAZ HİYERARŞİSİ
    % Noktalar ve etiketler AYRI tanımlanır
    % Böylece köşe noktalarındaki kalın siyah noktalar görünür olur
    % ============================================================

    % Üçgen köşe koordinatları
    \coordinate (pc0)    at (1, 4.5);
    \coordinate (pcm)    at (-3, 0);
    \coordinate (pcplus) at (5, 0);

    % Köşe noktalarındaki kalın siyah noktalar
    \filldraw[black] (pc0)    circle (4.2pt);
    \filldraw[black] (pcm)    circle (4.2pt);
    \filldraw[black] (pcplus) circle (4.2pt);

    % Etiketler (noktalardan biraz ayrı yerleştirilir)
    \node[align=center, above=10pt] at (pc0) {
        \Large $c_0$ \\
        \footnotesize (Potansiyel)
    };

    \node[align=center, below=10pt] at (pcm) {
        \Large $C_m$ \\
        \footnotesize (Madde/Zaman)
    };

    \node[align=center, below=10pt] at (pcplus) {
        \Large $c^+$ \\
        \footnotesize (Üst-Faz / Koordinasyon)
    };


    % ============================================================
    % ÜÇGEN BAĞLANTILARI
    % Üç kapı da çift yönlü
    % ============================================================

    % C_m <-> c_0
    \draw[<->]
        (pcm)
        --
        node[midway, above left=2pt] {$\Delta_{0m}$}
        (pc0);

    % c^+ <-> c_0
    \draw[<->]
        (pcplus)
        --
        node[midway, above right=2pt] {$\Delta_{0+}$}
        (pc0);

    % C_m <-> c^+
    \draw[<->]
        (pcm)
        --
        node[midway, below=4pt] {$\Delta_{+m}$}
        (pcplus);


    % ============================================================
    % SAĞ TARAF: U_+ — Mutlak Çözünme
    % ============================================================
    \node[
        align=center,
        circle,
        draw=red!70,
        fill=red!5,
        inner sep=5pt,
        very thick
    ] (uplus) at (10, 2.25) {
        \Large $U_+$ \\
        \footnotesize (Mutlak Çözünme)
    };


    % ============================================================
    % KAPSAYICI SÜSLÜ PARANTEZLER
    % ============================================================

    % Sol parantez
    \draw[
        decorate,
        decoration={
            calligraphic brace,
            amplitude=15pt
        },
        ultra thick,
        gray
    ]
        (-4.5, -0.8)
        --
        (-4.5, 5.4);

    % Sağ parantez
    \draw[
        decorate,
        decoration={
            calligraphic brace,
            amplitude=15pt,
            mirror
        },
        ultra thick,
        gray
    ]
        (6.5, -0.8)
        --
        (6.5, 5.4);


    % ============================================================
    % U_0 <-> U_x / FAZ SİSTEMİ
    % ============================================================
    \draw[<->, ultra thick]
        (u0)
        --
        (-4.5, 2.25);


    % ============================================================
    % U_x / FAZ SİSTEMİ <-> U_+
    % ============================================================
    \draw[<->, ultra thick]
        (6.5, 2.25)
        --
        (uplus);

\end{tikzpicture}

\end{document}
```

---



---

# EK K — AÇIK BORÇLAR VE BEKLEYEN KARARLAR

## K.1 Dondurulmuş açık borçlar

Bunlar tarih değil, ontolojinin bugünkü gerçek sınırlarıdır:

- **Genel fiziksel seçici** — $X$'ten fiziksel niceliğe giden köprüyü tekil kılan ilke ($J_X$, $\mathcal E_\phi$).
- **Çekim Kuvveti'nin izdüşüm işleminin biçimsel tanımı** ($\Pi$) ve **üç faz dengesinin denklemi**.
- **İtmenin ve yükün izdüşüm biçimi** (elektromanyetizma); güçlü ve zayıf kuvvetin izdüşüm anlatımı.
- **c⁺'tan karanlık madde ve karanlık enerjiye** nicel mekanizma; **c⁺ ≡ vakum** kimliği altında vakum enerjisi ile gözlenen karanlık enerji yoğunluğu arasındaki nicel köprü (kozmolojik sabit problemi).
- **Entropi ile mühürleme arasındaki nicel harita.**
- $v$'nin **üyelik okuması** $\mathcal R_v$ ve c⁺'ın c-ötesiliğinin **matematiksel temsili**; $v=c$ liminal ortak sınırının biçimsel tipi.
- $X$'in kesin tipi ve fiziksel izdüşümü · doygunluk okuması $\xi_{\rm sat}=\pi_{\rm sat}(X)$'in biçimsel tanımı · fiziksel okuma yasası · ontolojiden metriğin yeniden inşası.
- Faz sayısının temel mi türetilmiş mi olduğu · $U_x$'in yapısal tipi ve küresel devre yasaları.
- Standart Model, Yukawa ve QCD köprüleri · önceden kayıtlı ampirik öngörü.
- Etkin 3+1 metrikten genel göreliliğin gözlemsel sonuçlarının **geri kazanılması**.
- Kuantum okumasında Born olasılıkları, girişim, Bell korelasyonları, bağlamsallık ve sinyalsizliğin geri kazanılması.
- $X$ için genel **algoritmik yakınsama** güvencesi.
- Ham arşiv birleşiminde kayıt kimliği tekilliği; biçimsel damga yönünün ($\kappa_{+m}$), yazar hükmüyle Cₘ → c⁺ olarak sabitlenen kayıt yönüyle hizalanması (7.1, 13.3).
- Kara delik ≡ c₀ kimliğinin nicel ve gözlemsel haritası: olay ufku–faz sınırı ilişkisi, kütle kanalının eşik ve geçiş yasası.
- **c₀ tek-yapısının iç profili ve olay ufkuyla nicel ilişkisi:** yoğunluğun Planck sınırında sabit mi yoksa profilli mi olduğu; $R_{c_0}/R_s\propto M^{-2/3}$ oranının gözlemsel sonuçları.
- c₀ kapasitesinin kütle ve alan bağımlılığının nicel biçimi; entropi (alanla) ile kapasite (kütleyle) ayrışmasının kanon dili (3.2).
- c₀'dan ayrılış kuralının (hız ve / veya yoğunluk) nicel biçimi ve birleşmede azalan kapasitenin dağılımı (3.2).
- BEC'in "madde fazında c₀ ortamına en yakın ortam" olmasının nicel bir yakınlık ölçüsüyle ifade edilmesi.
- Doğrudan c₀ ⇄ c⁺ kenar kilidi altında atom altı döngü hızı için entropi üretimi kaynaklı üst sınır — model (13.6).
- c₀ okuma haritası $\mathcal O^{C_m}_{c_0}$ (tek-yapının Cₘ etkin hacim, yarıçap ve yoğunluk parametreleri) ve sabit yoğunluk $\rho_*$'ın türetilmesi (3.2).
- Faz sınırı ekseni $q_\partial$'ın tipi ve ölçüsü; kinematik üyelik okuması $\beta$ ile ilişkisi (18.0).
- $\Pi$'nin sektörlere özgü biçimi ($\Pi_a:\mathcal A\to\mathcal L_a$, sektöre özgü etkin eylem ya da denklem kategorisi) ve ayar değişmezliği, spin / kiralite ve fermiyon kütlesinin geri kazanımı.
- Etkin geometri haritası $g^{\rm eff}_{\mu\nu}[E^3,X,\Delta]$'nın kapsadığı genel görelilik çözüm aileleri (düz uzaysal dilimlemeye izin vermeyen aileler dahil; 9.2a).
- c⁺ okuma haritası $\mathrm{Okuma}_{C_m}(c^+;\mathcal C)$'nin her bağlam için fiziksel seçicisi (11.1a).

Kısmen kurulu olanlar: tam aralık hesabı · değişkenleri bağımlı ters problemler · bazı model ailelerinin kaynak türetimi · tam Morse aralık sertifikası.

$$\boxed{\;\text{AÇIK} \;\neq\; \text{BAŞARISIZ}\;}$$

```latex
\boxed{\;\text{AÇIK} \;\neq\; \text{BAŞARISIZ}\;}
```

## K.2 Yazarın kararını bekleyenler

**Kapanan kararlar (önceki sürümler):** Cₘ'nin temel uzayı düz üç boyutlu Öklid uzayıdır, zaman sonradan ortaya çıkar (9.2a); yayın paketi Çekirdek Ontoloji, V24'ün son sürümü ve maraton son derlemesinden oluşur; kara delik ile c₀ fazı ontolojik olarak özdeştir (3.2) · c₀ mutlak sıfır değildir ve c₀'da sıcaklık tanımsızdır (3.2) · zaman yalnız Cₘ'de ve tek yönlüdür, kayıt kanalı Cₘ → c⁺ yönündedir (7.1) · kara delik yok oluş ya da sonsuz tekillik değildir (3.2) · fazlar Cₘ'den türetilmez (2.4) · doğrudan c₀ ⇄ c⁺ kenarı için model kuralı (13.6).

**Bu sürümde kapanan kararlar (2026-10-14 yazar onayları):**

- Cₘ kinematik üyelik bandı $0<v<c$; $v=c$ Cₘ ile c⁺'ın liminal ortak sınırıdır (sınır ≠ üyelik).
- **c⁺ ≡ karanlık madde ≡ karanlık enerji ≡ vakum**; kuantum alan kuramının vakumu bu kimliğin Cₘ hesap dilidir; "c⁺ ≠ vakum" ifadesi kaldırılmıştır.
- Atomu oluşturan parçacıklar arasındaki boşluk dahi c⁺'tır.
- c⁺'ta zaman çözünmüştür: $\bot_+$ ontolojik durum, $dt_{c^+}=0$ yalnız pedagojik kısaltma; $\bot_0\neq\bot_+\neq0$.
- c₀ doygunluğu $X$'in kendisi üzerinden değil, okuması $\xi_{\rm sat}=\pi_{\rm sat}(X)\to\xi_{\rm sat}^{\max}$ üzerinden yazılır.
- **"Planck yoğunluklu boşluksuz çekirdek" okuması kapanmıştır:** c₀'daki madde Planck ölçeğinde metrik boşluksuz duruma yakınsayan derecede bitişik, sonlu, **tek bir yapı formundadır**; bu "çekirdek Planck boyutundadır" anlamına gelmez. Kapasite Planck kütlesiyle sayılır ($N_{c_0}=M/m_P$), yoğunluk Planck yoğunluğunu aşamaz ($\rho_{c_0}\le\rho_P$), hacim kütleyle büyür ($V_{c_0}\ge N_{c_0}\ell_P^3$); hacmin kütleyle tam doğru orantısı ve $R_{c_0}\propto M^{1/3}$ sabit yoğunluk gerçeklemesinde ($\rho_{c_0}=\rho_*$) geçerlidir. Güneş kütlesi için verilen en küçük yarıçap, yoğunluğun Planck değerinde ($\rho_*=\rho_P$) alınmasıyla hesaplanır. Yoğunluğun kütleyle artmaması üst sınırdan türetilmiş değil, ayrı bir hükümdür; $V$, $R$, $\rho$ Cₘ etkin okuma parametreleridir (3.2). Yoğunluğun tam olarak Planck değerine kilitli olduğu ayrıca iddia edilmez; yalnız üst sınır vardır (3.2, 25.28).
- c₀'da zaman **durmuş değil, henüz kurulmamıştır**; "sıfır diferansiyel" özet dili düşmüştür.
- Bütün $U_x$ yapısı $U_+$ formuna eriştiğinde **Mutlak Yırtılma ile Mutlak Çözünme aynı şeyi ifade eder**.
- Emekli ölçütler emekli kalır (örneğin karanlık madde için $\nabla\ln\chi_S\neq0$).
- Mühürleme maliyeti $C_s$ "aday okuma" kipindedir.
- Deney okumaları (gecikmeli kuantum silici, ışınlama vb.) "uyumlu okuma" kipindedir; ışınlama klasik kanal gerektirir, c⁺ korelasyon kaynağıdır.
- BEC c₀ değildir; madde fazında c₀ ortamına en yakın ortamdır.
- Üçüncü ilke: ölçümü doğru yeniden üreten matematiksel temsil o ölçüm kapsamında koşulsuz kabul edilir; temsiller arasında ontolojik öncelik yoktur.

**Hâlâ bekleyenler:**

- Arşiv sayısının ham arşivin kayıt sayısı olarak tanımlanıp tanımlanmayacağı · faz hafızası tekdüzeliğinin mimari kural olarak kabulü.
- SYNTAX ile $U_x$ arasındaki ilişkinin tipi.
- Kanal asimetrisi köprüsünün akıbeti · bazı model ailelerinin kaynak metninin teyidi.
- Hawking sıcaklığının ufkun Cₘ okuma sıcaklığı olarak kanonlaştırılması (3.2).
- $\Pi_{+\to m}$ ve "c₀ üzerinden zorunlu" tarihsel hükmünün tam üçgen kanonuyla uyumlaştırılması (23.10b).

## K.3 Güven sınıfları

Bu belgede her ifadenin hangi güvenle söylendiği cümlede belirtilir: **kanon** (yazarın onayladığı hüküm) · **yazar hükmü** (yazarın doğrudan açıklaması) · **biçimsel olarak kanıtlanmış** (kodlanmış sistem kapsamında) · **model** (kendi varsayımları içinde doğru) · **köprü** (çekirdek ile gözlem arasında bağlantı adayı) · **aday okuma** / **uyumlu okuma** · **açık** · **emekli**. Her denklemin ardından gelen "Ne sonuç elde ediliyor?" satırı, o denklemin güven sınıfını okura doğrudan söyler.

# KAPANIŞ

Evertophy, gerçekliğin **iki ontolojik düzeyden** oluştuğunu öne süren bir çerçevedir: içeride üç fazın kurduğu dinamik evren, dışarıda o evrenin iki uç koşulu. Fazlar arasında tam çift yönlü bir üçgen, hepsinin üstünde tek bir dinamik üst çözücü, ve hepsinden önce numarasız bir öncül — Çekim Kuvveti'nin temel ontolojik postüla olması.

Bu belge, çerçevenin **ontolojik iskeletini** eksiksiz ortaya koymayı amaçladı. Tam kanıt gövdelerini içermez; biçimsel kanıtların sonuçlarını ve kaynağını özetler. Asıl sunduğu, kavramsal düzendir. Bu sürümde o düzen bir adım daha açık hâle getirildi: her denklem, sembolleriyle ve "ne yapıyor, neden yapıyor, nasıl yapıyor, ne sonuç bekleniyor, ne sonuç elde ediliyor" sorularıyla birlikte okura sunuldu; böylece bir formülün ne söylediği kadar, neyi **söylemediği** de görünür oldu.

Beş şey açıkça söylenmelidir.

**Birincisi:** Çerçeve matematiksel olarak eksiktir. $X$'ten fiziksel fonksiyonlara giden merkezî zincir yazılmamıştır. Bu eksiklik gizlenmemiş, çerçevenin kendi muhasebesinde kayıtlı tutulmuştur. $X$'in tam matematiksel gerçeklemesi **bilinçli olarak açık bırakılmıştır**.

**İkincisi:** Çerçevenin etkin hiçbir ampirik kanıt iddiası yoktur. Bir dönem en güçlü sayılan hat, **iç denetimle** kapatılmıştır. Bu kapanışın kendisi, çerçevenin en güvenilir davranışıdır: bir iddiayı dışarıdan bir hakem değil, kendi protokolü çürütmüştür.

**Üçüncüsü:** Küresel düzey yeni ve en az tanımlanmış katmandır. $U_+$'nın işlev cümlesi, küresel okların matematiksel tipi ve devre bağı açıktır. İki kutup arasındaki doğrudan ilişki hakkında çerçeve bilinçli olarak **sessiz kalır** — çünkü temsili olmayan bir şey hakkında hüküm vermek, gözlem ve deney çizgisinden çıkmak olurdu.

**Dördüncüsü:** Çerçevenin bugünkü değeri, ürettiği sayılarda değil, **kurduğu düzende ve koyduğu yasaklardadır**. Bir çerçeve ne kadar çok şeyi açıklarsa değil, ne kadar net biçimde **yanlışlanabilir hâle gelirse** o kadar değerlidir.

**Beşincisi:** Bu metindeki biçimsel sonuçlar kodlanmış sistem kapsamında geçerlidir; metnin bütünü çapraz denetimden geçmiştir, ama çapraz denetim bir kanıt değildir. Denetim, iskeletin tip ve cebir düzeyinde tutarlı olduğunu gösterdi, otuzu aşkın iddiayı ayıkladı ve merkezî açığın yerini kesinleştirdi. Bu sürümdeki ontolojik değişiklikler — c⁺ ≡ vakum, atom içi boşluğun c⁺ okuması, c₀'ın metrik boşluksuz tek-yapısı, $0<v<c$ bandı ve $v=c$ liminal sınırı — araçların değil, **yazarın** hükümleridir. Denetimden geçmek doğru olmak demek değildir; ama nerede yanılabileceğini bilmek, doğruya giden yolun ilk adımıdır.

Evertophy şu anda bu ölçüde tamamlanmış bir kuram değil, **Her Şeyin Kuramı hedefi taşıyan bir ontoloji ve fizik araştırma programıdır**. Bu sürümün iç statüsü **Kararlı Kapanış Adayı / Güncel Çekirdek Referansıdır**: doğrudan mimar revizyonuna açıktır ve V24 devre mekanizması gibi ayrılmış katmanlar henüz kapanmış değildir.

---

*Uğur Yılmaz · Bağımsız Araştırmacı · İstanbul · `ugur@data24k.com`*

*Bu sürüm, çoklu sistem çapraz denetim yöntemiyle hazırlanmış; pozitif düzeltme kümeleri ve negatif kısıt kümeleri birlikte uygulanarak, yazarın 2026-10-14 hükümleriyle hizalanmış tek tutarlı çekirdek hâline getirilmiştir.*

---

$$\boxed{0/10}$$

```latex
\boxed{0/10}
```


