---
document_name: Typography
brand: Norn Human
version: 2.0
status: Approved Direction — Production Validation Required
language: tr-TR
last_updated: 2026-07-16
prepared_by: SedInsight — Stratejik Proje Liderliği & İş Geliştirme
primary_use:
  - Brand identity
  - Website and landing pages
  - Social media templates
  - Digital learning platform
  - Mobile application
  - Email and CRM
  - Presentations and campaign materials
  - Claude Design and AI-assisted design production
related_documents:
  - Brand Strategy.md
  - Voice & Messaging.md
  - Color System.md
  - Design System.md
  - Design Tokens.json
---

# Norn Human Typography

## 0. Belgenin Rolü

Bu belge, Norn Human'ın bütün dijital ve fiziksel temas noktalarında kullanacağı tipografi sistemini tanımlar.

Tipografi burada yalnızca estetik bir font seçimi değildir. Marka stratejisindeki temel dengeyi görünür hale getiren işlevsel bir sistemdir:

- derin ama anlaşılır,
- bilge ama ulaşılabilir,
- modern ama köksüz değil,
- kurumsal ama soğuk değil,
- sakin ama güçlü,
- editoryal ama dijital kullanıma uygun.

Bu dosya aşağıdaki kararları standartlaştırır:

- ana ve destek font aileleri,
- fontların marka içindeki rolleri,
- ağırlık kullanımı,
- başlık ve gövde hiyerarşisi,
- responsive web ölçüleri,
- ürün arayüzü metin stilleri,
- sosyal medya tipografi ölçeği,
- satır uzunluğu ve hizalama,
- Türkçe karakter ve yazım kontrolü,
- Figma text style adlandırması,
- CSS ve design token karşılıkları,
- font yükleme ve performans prensipleri,
- doğru ve yanlış kullanım örnekleri,
- Claude Design üretim kuralları.

> **Temel ilke:** Tipografi Norn Human'ı “gizemli bir spiritüel marka” veya “soğuk bir teknoloji platformu” gibi göstermemelidir. Derinlik, insanilik ve sistem duygusunu aynı anda taşımalıdır.

---

# 1. Tipografik Strateji

## 1.1 Temel Yaklaşım

Norn Human iki font ailesinden oluşan bir sistem kullanır:

1. **Source Serif 4**  
   Marka, editoryal anlatı, düşünsel derinlik ve seçilmiş vurgu alanları

2. **Manrope**  
   Gövde metni, kullanıcı arayüzü, sosyal medya, navigasyon, formlar ve işlevsel iletişim

Bu sistem **Norn Human** için hazırlanmıştır. Norn ana marka ile görsel akrabalık korunmalı; ancak Norn Human'ın dijital eğitim ve kullanıcı deneyimi rolü nedeniyle okunabilirlik ve ürün ölçeklenebilirliği önceliklidir. Norn ana markasının gelecekte farklı alt markaları oluşursa bu tipografi sistemi otomatik olarak bütün alt markalara uygulanmaz.

Bu ikili tek bir estetik etki yaratmak için değil, markanın iki temel ihtiyacını dengelemek için seçilmiştir:

| İhtiyaç | Tipografik karşılık |
|---|---|
| Derinlik ve düşünsel ağırlık | Source Serif 4 |
| Açıklık ve dijital kullanılabilirlik | Manrope |
| Modern bilgelik | Serif + sans birlikteliği |
| Uzun okuma | Kontrollü serif başlık + sade sans gövde |
| Ürün ölçeklenebilirliği | Manrope tabanlı UI sistemi |
| Editoryal marka karakteri | Source Serif 4 başlık ve alıntılar |
| Mobil okunabilirlik | Geniş x-height ve sade sans gövde |
| Kurumsal tutarlılık | Sınırlı ağırlık ve tanımlı text style seti |

## 1.2 Ana Tipografik Karar

### Primary Display & Editorial Typeface

**Source Serif 4**

Kullanım alanları:

- marka manifestosu,
- ana sayfa hero başlığı,
- büyük bölüm başlıkları,
- uzun içeriklerin editoryal başlıkları,
- seçilmiş eğitim başlıkları,
- kurucu perspektif yazıları,
- alıntılar,
- kampanya ana mesajları,
- sunumların açılış ve bölüm sayfaları.

### Primary Sans & Interface Typeface

**Manrope**

Kullanım alanları:

- web sitesi gövde metinleri,
- navigasyon,
- butonlar,
- form alanları,
- eğitim kartları,
- sosyal medya açıklama metinleri,
- carousel gövde metinleri,
- uygulama ve platform arayüzü,
- veri, tarih, süre ve fiyat bilgileri,
- e-posta,
- CRM ve bildirimler,
- admin ve eğitmen panelleri.

## 1.3 Neden Tek Font Kullanılmıyor?

Tek bir geometrik sans-serif sistem:

- Norn Human'ı teknoloji girişimine yaklaştırabilir,
- markanın düşünsel ve editoryal derinliğini zayıflatabilir,
- uzun vadede bütün içeriklerin aynı tonda görünmesine neden olabilir.

Tek bir klasik serif sistem ise:

- dijital ürün arayüzünde taramayı zorlaştırabilir,
- markayı fazla akademik, tarihsel veya spiritüel gösterebilir,
- sosyal medya ve mobil ekranlarda ağırlaşabilir.

Source Serif 4 ve Manrope birlikteliği; anlam, beden, gündelik yaşam ve dijital ürün alanlarını aynı marka altında birleştirecek esnekliği sağlar.

---

# 2. Font Kararları

## 2.1 Source Serif 4

### Marka içindeki rolü

Source Serif 4, Norn Human'ın “bilge, derin, kökleri olan ve düşünmeye alan açan” tarafını taşır.

Fontun amacı dekoratif veya mistik bir atmosfer kurmak değildir. Bilgiyi daha editoryal, sakin ve nitelikli hissettirmektir.

### Kullanılacak stiller

- Regular — 400
- Medium — 500
- Semibold — 600
- Italic — 400
- Semibold Italic — 600, yalnızca gerektiğinde

### Varsayılan ağırlık

**500 Medium**

Büyük başlıklarda 500 ağırlık, karakteri korurken aşırı klasik veya ağır bir görünümü engeller.

### Kullanım sınırları

Source Serif 4:

- uzun UI metinlerinde kullanılmaz,
- küçük buton ve form etiketlerinde kullanılmaz,
- uzun sosyal medya gövde metinlerinde kullanılmaz,
- çok küçük boyutlarda kullanılmaz,
- her başlık seviyesinde otomatik kullanılmaz,
- sırf “premium” görünmesi için fazla italik veya büyük harfle kullanılmaz.

### Optical size

Source Serif 4'ün variable sürümündeki optical size özelliği desteklenen ortamlarda otomatik kullanılmalıdır:

```css
font-optical-sizing: auto;
```

Bu özellik manuel olarak dekoratif amaçla değiştirilmemeli; varsayılan otomatik davranış tercih edilmelidir.

---

## 2.2 Manrope

### Marka içindeki rolü

Manrope, Norn Human'ın “açık, modern, erişilebilir, sistemli ve dijital” tarafını taşır.

Ana gövde ve arayüz fontudur.

### Kullanılacak stiller

- Regular — 400
- Medium — 500
- Semibold — 600
- Bold — 700, sınırlı kullanım

### Varsayılan ağırlıklar

- Gövde: 400
- Navigasyon ve etiket: 500
- Buton ve UI başlıkları: 600
- Kritik vurgu: 700, yalnızca sınırlı alanlarda

### Kullanım sınırları

Manrope:

- bütün büyük marka başlıklarında tek başına kullanılmamalı,
- 300 ve daha ince ağırlıklarda uzun metne uygulanmamalı,
- 700 ağırlık bütün başlıklarda kullanılmamalı,
- tamamen büyük harf ve geniş tracking ile teknoloji markası estetiğine çekilmemeli,
- küçük boyutta düşük kontrastlı renkle kullanılmamalı.

---

# 3. Wordmark ve Logo İlişkisi

## 3.1 Kritik Kural

**Norn Human logosu yalnızca Source Serif 4 veya Manrope ile yazılarak oluşturulmamalıdır. Norn ve Norn Human arasındaki wordmark/endorsement ilişkisi ayrı bir logo sistemi olarak tasarlanmalıdır.**

Bu fontlar marka iletişim ve arayüz sisteminin parçalarıdır. Logotype ise ayrı bir tasarım çalışmasıdır.

Norn Human wordmark’ı:

- özel harf aralıkları,
- gerektiğinde özgün harf müdahaleleri,
- Norn isminin iplik, bağlantı, zaman ve yol kavramlarıyla ilişkisi,
- küçük ölçekte okunabilirlik,
- sembolle ilişki,
- Türkçe ve uluslararası kullanım

dikkate alınarak tasarlanmalıdır.

## 3.2 Logo Fontuyla Sistem Fontu Aynı Olmak Zorunda Değildir

Wordmark'ın özel karakteri ile içerik fontlarının işlevi birbirinden farklıdır.

Bu nedenle:

- logo daha özgün olabilir,
- arayüz daha sade kalabilir,
- marka başlıkları logoyu taklit etmemelidir,
- logo içindeki özel karakter müdahaleleri normal metinlerde uygulanmamalıdır.

## 3.3 Geçici Logo Kullanımı

Norn Human wordmark'ı kesinleşene kadar sunum veya iç taslaklarda geçici isim yazımı gerekiyorsa:

```text
Norn Human
```

- Manrope Semibold,
- iki kelime arasında normal boşluk,
- normal harf kullanımı,
- özel tracking uygulanmadan,
- “Norn” ve “Human” farklı renklere bölünmeden,
- logo olarak değil yalnızca metinsel yer tutucu olarak

kullanılmalıdır.

Geçici yazım hiçbir koşulda nihai logo olarak dışarıya sunulmamalıdır.

---

# 4. Tipografik İfade Modları

Norn Human'ın farklı içerik alanları tamamen farklı tipografi sistemleri kullanmaz. Aynı sistem içinde üç ifade modu bulunur.

## 4.1 Editorial / Meaning Mode

Amaç:

- marka yaklaşımı,
- anlam,
- bilinç,
- sembol,
- felsefi ve düşünsel içerik,
- kurucu perspektif.

Tipografi:

- Source Serif 4 daha görünür,
- geniş boşluk,
- orta ağırlık,
- daha sakin ritim,
- kısa ve güçlü başlıklar,
- Manrope gövde ve metadata.

Örnek:

```text
Source Serif 4 — Ana başlık
Manrope — Açıklama
Manrope — Tarih / kategori / CTA
```

## 4.2 Practice / Movement Mode

Amaç:

- beden,
- hareket,
- nefes,
- denge,
- atölye ve uygulama.

Tipografi:

- Manrope daha baskın,
- Source Serif 4 seçilmiş vurgu veya kısa başlıkta,
- daha dinamik boyut farkları,
- net süre, seviye ve program bilgisi,
- okunabilir, hareketli fakat sakin yapı.

Örnek:

```text
Manrope Semibold — Ana bilgi başlığı
Source Serif 4 Medium — Kavramsal vurgu
Manrope — Program ve CTA
```

## 4.3 Institutional / Product Mode

Amaç:

- eğitim kataloğu,
- üyelik,
- profil,
- ilerleme takibi,
- admin ve eğitmen panelleri,
- program detayları,
- kurumsal sunum.

Tipografi:

- Manrope ana font,
- serif yalnızca editoryal eğitim adı veya seçilmiş büyük mesajda,
- yüksek taranabilirlik,
- net hiyerarşi,
- minimum dekoratif kullanım.

Bu modlar ayrı alt markalar değildir. Yalnızca aynı tipografi sisteminin içerik amacına göre farklı ağırlıkta kullanılmasıdır.

---

# 5. Font Ağırlığı Sistemi

## 5.1 Source Serif 4 Ağırlıkları

| Token | Weight | Kullanım |
|---|---:|---|
| `serif-regular` | 400 | Uzun alıntı, italik içerik, özel editoryal metin |
| `serif-medium` | 500 | Ana display ve heading kullanımı |
| `serif-semibold` | 600 | Küçük ölçekte güçlü heading, nadir vurgu |
| `serif-bold` | 700 | Varsayılan sistemde kullanılmaz |

## 5.2 Manrope Ağırlıkları

| Token | Weight | Kullanım |
|---|---:|---|
| `sans-regular` | 400 | Gövde metni |
| `sans-medium` | 500 | Navigasyon, metadata, etiket |
| `sans-semibold` | 600 | UI başlığı, buton, kart başlığı |
| `sans-bold` | 700 | Kritik sayı veya kısa vurgu |
| `sans-extrabold` | 800 | Kullanılmaz |

## 5.3 Ağırlık Kullanım İlkesi

Aynı ekran veya tasarımda gereksiz sayıda ağırlık kullanılmamalıdır.

Önerilen maksimum:

- Sosyal medya görseli: 2 ağırlık
- Web bölümü: 3 ağırlık
- Ürün ekranı: 3 ağırlık
- Sunum slaytı: 2–3 ağırlık

Hiyerarşi yalnızca kalınlıkla değil:

- boyut,
- satır aralığı,
- boşluk,
- renk,
- yerleşim

ile birlikte kurulmalıdır.

---

# 6. Brand & Editorial Type Scale

Bu ölçek, marka web sitesi, landing page, kampanya ve uzun içeriklerde kullanılır.

## 6.1 Desktop Ölçeği

| Style | Font | Weight | Size | Line height | Letter spacing |
|---|---|---:|---:|---:|---:|
| Display XL | Source Serif 4 | 500 | 72px | 76px | -0.025em |
| Display LG | Source Serif 4 | 500 | 60px | 66px | -0.022em |
| Display MD | Source Serif 4 | 500 | 52px | 58px | -0.020em |
| Heading H1 | Source Serif 4 | 500 | 48px | 56px | -0.018em |
| Heading H2 | Source Serif 4 | 500 | 40px | 48px | -0.015em |
| Heading H3 | Source Serif 4 | 500 | 32px | 40px | -0.010em |
| Heading H4 | Manrope | 600 | 24px | 32px | -0.008em |
| Heading H5 | Manrope | 600 | 20px | 28px | -0.005em |
| Lead | Manrope | 400 | 20px | 32px | 0 |
| Body LG | Manrope | 400 | 18px | 30px | 0 |
| Body MD | Manrope | 400 | 16px | 26px | 0 |
| Body SM | Manrope | 400 | 14px | 22px | 0.005em |
| Quote LG | Source Serif 4 Italic | 400 | 32px | 44px | -0.008em |
| Quote MD | Source Serif 4 Italic | 400 | 24px | 36px | 0 |
| Caption | Manrope | 500 | 12px | 18px | 0.015em |

## 6.2 Tablet Ölçeği

| Style | Size | Line height |
|---|---:|---:|
| Display XL | 56px | 62px |
| Display LG | 48px | 54px |
| Display MD | 44px | 50px |
| Heading H1 | 40px | 48px |
| Heading H2 | 34px | 42px |
| Heading H3 | 28px | 36px |
| Heading H4 | 23px | 31px |
| Heading H5 | 20px | 28px |
| Lead | 19px | 31px |
| Body LG | 18px | 30px |
| Body MD | 16px | 26px |
| Body SM | 14px | 22px |

## 6.3 Mobile Ölçeği

| Style | Size | Line height |
|---|---:|---:|
| Display XL | 42px | 46px |
| Display LG | 38px | 43px |
| Display MD | 35px | 41px |
| Heading H1 | 32px | 38px |
| Heading H2 | 28px | 34px |
| Heading H3 | 24px | 31px |
| Heading H4 | 21px | 29px |
| Heading H5 | 19px | 27px |
| Lead | 18px | 29px |
| Body LG | 17px | 28px |
| Body MD | 16px | 26px |
| Body SM | 14px | 22px |
| Caption | 12px | 18px |

## 6.4 Kullanım Notu

Display XL her sayfada kullanılmaz.

Kullanılabileceği alanlar:

- ana sayfa hero,
- manifesto,
- kampanya açılışı,
- sunum kapakları,
- büyük fiziksel afiş.

Kullanılmaması gereken alanlar:

- eğitim kartı,
- modal,
- dashboard,
- mobil uygulama içi normal sayfa,
- uzun metin sayfasındaki her bölüm.

---

# 7. Product & UI Type Scale

Dijital platform, mobil uygulama, eğitmen paneli ve admin panelinde Manrope ana fonttur.

## 7.1 Interface Text Styles

| Style | Font | Weight | Size | Line height | Letter spacing |
|---|---|---:|---:|---:|---:|
| UI Display | Manrope | 600 | 36px | 44px | -0.015em |
| UI Heading XL | Manrope | 600 | 32px | 40px | -0.012em |
| UI Heading LG | Manrope | 600 | 24px | 32px | -0.008em |
| UI Heading MD | Manrope | 600 | 20px | 28px | -0.005em |
| UI Heading SM | Manrope | 600 | 16px | 24px | 0 |
| UI Body LG | Manrope | 400 | 18px | 28px | 0 |
| UI Body MD | Manrope | 400 | 16px | 24px | 0 |
| UI Body SM | Manrope | 400 | 14px | 20px | 0 |
| UI Label LG | Manrope | 600 | 15px | 20px | 0.005em |
| UI Label MD | Manrope | 600 | 14px | 20px | 0.008em |
| UI Label SM | Manrope | 600 | 12px | 16px | 0.015em |
| UI Caption | Manrope | 500 | 12px | 18px | 0.010em |
| UI Overline | Manrope | 600 | 11px | 16px | 0.055em |
| Button LG | Manrope | 600 | 16px | 22px | 0.005em |
| Button MD | Manrope | 600 | 15px | 20px | 0.005em |
| Button SM | Manrope | 600 | 14px | 18px | 0.008em |
| Input | Manrope | 400 | 16px | 24px | 0 |
| Input Label | Manrope | 600 | 14px | 20px | 0 |
| Helper Text | Manrope | 400 | 13px | 18px | 0.005em |

## 7.2 UI İçinde Serif Kullanımı

Source Serif 4 yalnızca şu alanlarda kullanılabilir:

- eğitim detay sayfasındaki büyük eğitim adı,
- editoryal içerik başlığı,
- seçilmiş alıntı,
- tamamlanan yolculuk veya özel milestone mesajı,
- ana keşif ekranındaki kampanya başlığı.

Serif şu alanlarda kullanılmaz:

- buton,
- form,
- menü,
- tablo,
- filtre,
- durum etiketi,
- hata mesajı,
- küçük kart içeriği,
- navigasyon,
- işlem onayı.

## 7.3 Sayı Kullanımı

Fiyat, süre, yüzde, puan ve raporlama alanlarında Manrope kullanılır.

Tablo ve karşılaştırma alanlarında:

```css
font-variant-numeric: tabular-nums;
```

tercih edilmelidir.

Büyük sayılar:

- Manrope 600 veya 700,
- birim Manrope 500,
- açıklama Manrope 400

olarak ayrıştırılabilir.

---

# 8. Responsive Web Uygulaması

## 8.1 Akışkan Tipografi

Büyük web başlıklarında sabit breakpoint sıçramaları yerine kontrollü `clamp()` kullanılabilir.

Örnek:

```css
:root {
  --font-size-display-xl: clamp(2.625rem, 1.7rem + 3.2vw, 4.5rem);
  --font-size-display-lg: clamp(2.375rem, 1.7rem + 2.4vw, 3.75rem);
  --font-size-h1: clamp(2rem, 1.45rem + 1.9vw, 3rem);
  --font-size-h2: clamp(1.75rem, 1.35rem + 1.4vw, 2.5rem);
  --font-size-h3: clamp(1.5rem, 1.28rem + 0.8vw, 2rem);
}
```

## 8.2 Gövde Ölçüsü

Ana web gövde metni:

```css
font-size: 1rem;
line-height: 1.625;
```

Uzun okuma ve editoryal sayfalarda:

```css
font-size: 1.125rem;
line-height: 1.6667;
```

kullanılabilir.

## 8.3 Form Alanları

Mobil ve web form alanlarında varsayılan font boyutu:

```css
font-size: 16px;
```

altına düşürülmemelidir.

## 8.4 Başlık Satır Sayıları

- Hero heading: ideal 2–3 satır
- Section heading: ideal 1–3 satır
- Card title: ideal 1–2 satır
- Reels cover: ideal 2–4 kısa satır
- Buton: ideal tek satır

Başlık metni tasarıma sığdırılmak için ısrarla küçültülmemeli; metin editlenmelidir.

---

# 9. Satır Uzunluğu ve Okuma Ritmi

## 9.1 Gövde Metni

Önerilen satır uzunluğu:

- Web gövde: yaklaşık 55–75 karakter
- Uzun okuma: yaklaşık 60–72 karakter
- Mobil: ekran genişliği içinde doğal akış
- Carousel: paragraf yerine kısa bloklar

CSS örneği:

```css
.prose {
  max-width: 68ch;
}
```

## 9.2 Lead Metni

Lead metin:

- normal gövdeden kısa olmalı,
- 45–65 karakterlik satır aralığında tutulmalı,
- bütün sayfanın özetini taşımamalı,
- maksimum 2–4 satır olmalıdır.

## 9.3 Başlık Uzunluğu

Başlıklar:

- mümkün olduğunca 3–10 kelime,
- bir ana fikir,
- gereksiz sıfatsız,
- doğal Türkçe,
- tasarımı taşıyacak kadar kısa

olmalıdır.

## 9.4 Paragraf Aralığı

Web ve uygulama:

- gövde paragrafları arasında 0.75–1em,
- bölüm başlığı öncesinde daha yüksek boşluk,
- başlık sonrasında başlığın seviyesine göre 0.4–0.75em

kullanılmalıdır.

Boşluk sistemi Design Tokens dosyasındaki spacing değerleriyle eşlenmelidir.

---

# 10. Hizalama Kuralları

## 10.1 Varsayılan Hizalama

**Sol hizalama varsayılandır.**

Sol hizalama:

- daha hızlı tarama,
- daha doğal okuma,
- dijital arayüzde tutarlılık,
- uzun metinde rahatlık

sağlar.

## 10.2 Ortalı Metin

Sınırlı olarak kullanılabilir:

- kısa hero başlığı,
- manifesto cümlesi,
- kampanya açılışı,
- alıntı,
- etkinlik afişi,
- boş durum mesajı.

Ortalı metin:

- 3–4 satırdan uzun olmamalı,
- uzun paragrafta kullanılmamalı,
- form ve işlem ekranlarında kullanılmamalı.

## 10.3 Sağ Hizalama

Yalnızca:

- sayı,
- tablo,
- finansal değer,
- karşılaştırma kolonları

gibi işlevsel alanlarda kullanılabilir.

## 10.4 İki Yana Yaslama

Dijital metinlerde kullanılmaz.

Basılı uzun metinlerde ancak profesyonel dizgi ve heceleme kontrolüyle değerlendirilebilir.

---

# 11. Letter Spacing Kuralları

## 11.1 Büyük Serif Başlıklar

Büyük Source Serif 4 başlıklarda hafif negatif tracking kullanılabilir:

- Display XL: `-0.025em`
- Display LG: `-0.022em`
- H1: `-0.018em`
- H2: `-0.015em`
- H3: `-0.010em`

Daha fazla sıkıştırma harflerin açıklığını ve Türkçe karakterlerin dengesini bozabilir.

## 11.2 Sans Başlıklar

Manrope başlıklarda:

- büyük başlık: `-0.015em` ile `-0.005em`
- normal başlık: `0`
- küçük label: `0.005em` ile `0.015em`

## 11.3 Overline ve Metadata

Küçük overline:

- Manrope 600
- 11–12px
- `0.04em`–`0.06em`
- kısa metin

şeklinde kullanılabilir.

Tamamı büyük harf kullanım gerekiyorsa yalnızca:

- çok kısa kategori,
- durum etiketi,
- mikro metadata

alanında kullanılmalıdır.

Uzun başlıklar veya CTA'lar büyük harfle yazılmaz.

---

# 12. İtalik Kullanımı

## 12.1 Source Serif 4 Italic

Kullanılabileceği alanlar:

- kısa alıntı,
- vurgu cümlesi,
- kitap veya eser adı,
- düşünsel ara ifade,
- editoryal pull quote.

## 12.2 Kullanım Sınırı

- Uzun paragraf italik yazılmaz.
- Buton italik olmaz.
- UI mesajı italik olmaz.
- Her manevi içerikte otomatik italik kullanılmaz.
- İtalik, şiirsellik veya “mistik his” üretmek için fazla kullanılmaz.

## 12.3 Gövde Vurgusu

Manrope gövde içinde vurgu için ilk tercih:

- Medium 500

olmalıdır.

Bold 700, yalnızca kritik bilgi için kullanılır.

---

# 13. Türkçe Tipografi Kuralları

## 13.1 Karakter Seti

Bütün tasarım ve üretimlerde şu karakterler test edilmelidir:

```text
Ç ç
Ğ ğ
İ i
I ı
Ö ö
Ş ş
Ü ü
```

Test metni:

```text
Norn Human, düşünceyi gündelik yaşamla buluşturan bütüncül bir öğrenme alanıdır.
İnsan yalnızca zihinden değil; beden, ilişki, üretim ve anlam katmanlarından oluşur.
```

## 13.2 Büyük ve Küçük I

Türkçe dil ayarlarında:

- `i` → `İ`
- `ı` → `I`

dönüşümü korunmalıdır.

Otomatik büyük harf dönüşümleri tasarım ve yazılım ortamında Türkçe locale ile test edilmelidir.

## 13.3 Başlık Yazımı

Türkçe başlıklarda İngilizce title case kullanılmaz.

**Doğru:**

```text
Beden ve bilinç arasında bağ kurmak
```

**Yanlış:**

```text
Beden Ve Bilinç Arasında Bağ Kurmak
```

## 13.4 Kesme İşareti ve Marka Adı

Norn Human özel marka adı olarak ek aldığında:

```text
Norn Human'ın
Norn Human'da
Norn Human'a
Norn Human'dan
```

şeklinde yazılır.

## 13.5 Tırnak İşaretleri

Türkçe içerikte:

```text
“ ”
```

kullanılır.

İç içe alıntıda:

```text
‘ ’
```

kullanılabilir.

Düz klavye tırnakları tasarım tesliminden önce düzeltilmelidir.

## 13.6 Tire ve Uzun Çizgi

- Normal birleşik ifadelerde kısa tire: `-`
- Açıklayıcı ara ifadede gerektiğinde uzun çizgi: `—`
- Uzun çizgi aşırı kullanılmaz.
- Eğik çizgi `/` yerine mümkünse açık bağlaç kullanılır.

---

# 14. Sosyal Medya Tipografi Sistemi

Sosyal medya ölçüleri Figma şablonlarında final tasarım ölçeğine göre yeniden test edilmelidir.

Aşağıdaki değerler 1080px genişliğindeki post ve carousel çalışmaları için başlangıç standardıdır.

## 14.1 Carousel Cover

| Element | Font | Weight | Önerilen boyut |
|---|---|---:|---:|
| Ana başlık | Source Serif 4 veya Manrope | 500 / 600 | 72–104px |
| Seri etiketi | Manrope | 600 | 24–30px |
| Kısa açıklama | Manrope | 400 | 32–40px |
| Eğitmen / metadata | Manrope | 500 | 24–30px |

### Kullanım seçimi

- Kavram ve düşünsel içerik: Source Serif 4 başlık
- Gündelik yaşam ve pratik içerik: Manrope başlık
- Kurumsal duyuru: Manrope ağırlıklı
- Ana marka manifestosu: Source Serif 4 + Manrope

## 14.2 Carousel İç Sayfa

| Element | Font | Weight | Önerilen boyut |
|---|---|---:|---:|
| Slide başlığı | Manrope | 600 | 44–58px |
| Gövde | Manrope | 400 | 31–38px |
| Vurgu cümlesi | Source Serif 4 | 500 | 42–56px |
| Sayfa numarası | Manrope | 500 | 22–26px |
| Kaynak / dipnot | Manrope | 400 | 21–25px |

## 14.3 Reels Cover

- Ana başlık: 64–92px
- Kısa seri etiketi: 24–30px
- Maksimum 8–12 kelime
- 2–4 kısa satır
- Serif ve sans aynı başlık içinde karıştırılmaz
- Eğitmen adı ve konu başlığı aynı ağırlıkta verilmez

## 14.4 Story

- Ana başlık: 54–80px
- Gövde: 30–38px
- CTA: 28–34px, Manrope Semibold
- Operasyonel bilgi: 24–30px
- Bir story ekranında tek ana mesaj

## 14.5 Sosyal Medyada Kaçınılacaklar

- Çok küçük gövde metni
- Uzun metni sığdırmak için font küçültmek
- 4'ten fazla font boyutu
- 3'ten fazla ağırlık
- Tamamı serif küçük metin
- Uzun italik paragraf
- Aşırı negatif tracking
- Tamamı büyük harf başlık
- Her kelimeyi farklı stil veya renkle vurgulamak

---

# 15. Sunum Tipografi Sistemi

Sunumlarda okunabilirlik ve uzaktan görünürlük önceliklidir.

## 15.1 16:9 Sunum Ölçeği

| Element | Font | Weight | Boyut |
|---|---|---:|---:|
| Kapak başlığı | Source Serif 4 | 500 | 42–56pt |
| Bölüm başlığı | Source Serif 4 | 500 | 34–44pt |
| Slayt başlığı | Manrope | 600 | 28–34pt |
| Ana vurgu | Source Serif 4 | 500 | 26–36pt |
| Gövde | Manrope | 400 | 18–24pt |
| Küçük açıklama | Manrope | 400 | 14–17pt |
| Grafik etiketi | Manrope | 500 | 12–15pt |

## 15.2 Sunum Kuralları

- Bir slayt bir ana fikir taşır.
- Uzun paragraf yerine yapılandırılmış kısa metin kullanılır.
- Gövde 18pt altına düşürülmez.
- Başlıklar 2–3 satırı geçmez.
- Kaynak ve dipnotlar okunamayacak kadar küçültülmez.
- Sayısal veriler Manrope ile sunulur.
- Serif font, veri tablolarında kullanılmaz.

---

# 16. E-posta Tipografi Sistemi

E-posta istemcilerindeki font desteği değişken olabileceği için sistem fallback'leri önemlidir.

## 16.1 Önerilen Ölçek

| Element | Font | Boyut / line height |
|---|---|---|
| E-posta başlığı | Source Serif 4 / serif fallback | 30px / 38px |
| Bölüm başlığı | Manrope / sans fallback | 22px / 30px |
| Gövde | Manrope / sans fallback | 16px / 26px |
| CTA | Manrope Semibold | 15px / 20px |
| Dipnot | Manrope | 12px / 18px |

## 16.2 Güvenli Fallback

Web fontu yüklenmediğinde e-posta okunabilir kalmalıdır.

Serif:

```css
Georgia, "Times New Roman", serif
```

Sans:

```css
Arial, Helvetica, sans-serif
```

E-posta tasarımının yalnızca font karakterine bağlı olmaması gerekir.

---

# 17. Font Stack ve CSS Uygulaması

## 17.1 Font Stack

```css
:root {
  --font-family-display:
    "Source Serif 4",
    "Iowan Old Style",
    "Palatino Linotype",
    "Book Antiqua",
    Georgia,
    serif;

  --font-family-sans:
    "Manrope",
    "Segoe UI",
    Roboto,
    Helvetica,
    Arial,
    sans-serif;
}
```

## 17.2 Temel Uygulama

```css
html {
  font-family: var(--font-family-sans);
  text-rendering: optimizeLegibility;
}

body {
  font-family: var(--font-family-sans);
  font-size: 16px;
  line-height: 1.625;
  font-weight: 400;
}

h1,
h2,
.display-title,
.editorial-title {
  font-family: var(--font-family-display);
  font-weight: 500;
  font-optical-sizing: auto;
}

button,
input,
select,
textarea {
  font: inherit;
}
```

## 17.3 Font Smoothing

Platformlar arası tutarlılık için font smoothing zorunlu bir marka standardı olarak kullanılmamalıdır.

İşletim sisteminin varsayılan metin render davranışı korunmalıdır.

## 17.4 Variable Font Kullanımı

Üretimde variable font dosyaları tercih edilebilir.

Kullanılacak eksenler:

- Source Serif 4: weight + optical size
- Manrope: weight

Gereksiz özel eksen animasyonları veya deneysel tipografi ürün arayüzünde kullanılmaz.

---

# 18. Font Yükleme ve Performans

## 18.1 Dosya Stratejisi

Üretim ortamında:

- optimize edilmiş WOFF2,
- yalnızca gerekli karakter setleri,
- gerekli font aileleri,
- sınırlı ağırlıklar

kullanılmalıdır.

## 18.2 İlk Aşamada Yüklenecek Ağırlıklar

Minimum öneri:

### Source Serif 4

- 400 Italic
- 500 Normal
- 600 Normal, yalnızca gerekiyorsa

### Manrope

- 400
- 500
- 600
- 700, yalnızca ürün veya veri ihtiyacı varsa

## 18.3 Font Display

```css
font-display: swap;
```

veya ürünün görsel stabilite ihtiyacına göre kontrollü bir yükleme yaklaşımı kullanılmalıdır.

## 18.4 Preload

Yalnızca ilk ekranda gerçekten kullanılan kritik font dosyası preload edilmelidir.

Bütün ağırlıkların preload edilmesi performans avantajı sağlamaz.

## 18.5 Subset

Türkçe kullanım için Latin Extended karakterleri korunmalıdır.

Yalnızca temel Latin subset kullanılırsa:

- `ğ`
- `Ğ`
- `ı`
- `İ`
- `ş`
- `Ş`

karakterleri eksik kalabilir.

Üretim öncesinde gerçek Türkçe içerikle font dosyası testi yapılmalıdır.

---

# 19. Figma Text Style Sistemi

## 19.1 Adlandırma Yapısı

```text
Type/Brand/Display XL
Type/Brand/Display LG
Type/Brand/Display MD
Type/Brand/Heading H1
Type/Brand/Heading H2
Type/Brand/Heading H3
Type/Brand/Quote LG
Type/Brand/Quote MD

Type/UI/Heading XL
Type/UI/Heading LG
Type/UI/Heading MD
Type/UI/Heading SM
Type/UI/Body LG
Type/UI/Body MD
Type/UI/Body SM
Type/UI/Label LG
Type/UI/Label MD
Type/UI/Label SM
Type/UI/Caption
Type/UI/Overline
Type/UI/Button LG
Type/UI/Button MD
Type/UI/Button SM
Type/UI/Input
Type/UI/Input Label
Type/UI/Helper
```

## 19.2 Style Oluşturma Kuralları

- Her text style font, weight, size, line height ve tracking içerir.
- Renk text style içine gömülmez.
- Text color ayrı design token ile yönetilir.
- Desktop ve mobile style'lar gerektiğinde ayrı mode veya variable ile yönetilir.
- Aynı işlev için tekrar eden yeni style oluşturulmaz.
- “H1 Bold New” gibi kontrolsüz isimlendirme yapılmaz.

## 19.3 Figma Variable Eşleşmesi

Önerilen collection:

```text
Typography
```

Mode:

```text
Desktop
Tablet
Mobile
```

Responsive font size değişimleri design system uygulamasına göre variable veya component property ile yönetilebilir.

---

# 20. Design Token Eşleşmesi

## 20.1 Font Family Tokens

```json
{
  "fontFamily": {
    "display": "Source Serif 4",
    "sans": "Manrope"
  }
}
```

## 20.2 Font Weight Tokens

```json
{
  "fontWeight": {
    "regular": 400,
    "medium": 500,
    "semibold": 600,
    "bold": 700
  }
}
```

## 20.3 Type Token Örneği

```json
{
  "typography": {
    "brand": {
      "displayXL": {
        "fontFamily": "{fontFamily.display}",
        "fontWeight": "{fontWeight.medium}",
        "fontSize": "72px",
        "lineHeight": "76px",
        "letterSpacing": "-0.025em"
      },
      "headingH1": {
        "fontFamily": "{fontFamily.display}",
        "fontWeight": "{fontWeight.medium}",
        "fontSize": "48px",
        "lineHeight": "56px",
        "letterSpacing": "-0.018em"
      }
    },
    "ui": {
      "bodyMD": {
        "fontFamily": "{fontFamily.sans}",
        "fontWeight": "{fontWeight.regular}",
        "fontSize": "16px",
        "lineHeight": "24px",
        "letterSpacing": "0"
      },
      "buttonMD": {
        "fontFamily": "{fontFamily.sans}",
        "fontWeight": "{fontWeight.semibold}",
        "fontSize": "15px",
        "lineHeight": "20px",
        "letterSpacing": "0.005em"
      }
    }
  }
}
```

Nihai token yapısı `Design Tokens.json` dosyasında merkezi olarak yönetilecektir.

---

# 21. Erişilebilirlik ve Okunabilirlik

## 21.1 Tipografi Tek Başına Kontrast Sağlamaz

Metin okunabilirliği:

- font boyutu,
- ağırlık,
- satır aralığı,
- zemin kontrastı,
- satır uzunluğu,
- boşluk

birlikte değerlendirilerek sağlanır.

## 21.2 İnce Ağırlık Kullanımı

- 300 veya daha ince ağırlık kullanılmaz.
- Açık renk zemin üzerinde 400 altına inilmez.
- Fotoğraf üzerinde gövde metni doğrudan kullanılmaz; uygun overlay gerekir.
- Küçük metinlerde bronz, zeytin veya düşük kontrastlı tonlar ana metin rengi olarak kullanılmaz.

## 21.3 Font Boyutları

- Ana gövde: 16px
- Küçük yardımcı metin: minimum 12px
- Form alanı: 16px
- Buton: 14–16px
- Uzun okuma: 17–18px değerlendirilebilir

## 21.4 Linkler

Link yalnızca renk farkıyla bırakılmamalıdır.

Metin bağlamına göre:

- underline,
- ikon,
- belirgin hover/focus durumu

kullanılmalıdır.

## 21.5 Metin Yakınlaştırma

Arayüz:

- metin büyütüldüğünde kesilmemeli,
- sabit yükseklikteki metin kutularına hapsedilmemeli,
- buton ve kartlar metin uzadığında genişleyebilmeli,
- uzun Türkçe kelimelerle test edilmelidir.

---

# 22. Doğru ve Yanlış Kullanım

## 22.1 Başlık

**Doğru**

```text
Source Serif 4 Medium
Kısa ve güçlü başlık
Doğal satır kırılımı
```

**Yanlış**

```text
Source Serif 4 Bold
Tamamı büyük harf
Aşırı negatif tracking
5–6 satırlık uzun başlık
```

## 22.2 Gövde

**Doğru**

```text
Manrope Regular
16–18px
Rahat satır aralığı
55–75 karakter satır
```

**Yanlış**

```text
Source Serif 4 Light
13px
Sıkışık line height
Çok geniş paragraf
```

## 22.3 Vurgu

**Doğru**

- Manrope Medium
- Kısa Source Serif 4 alıntı
- Boyut ve boşlukla hiyerarşi

**Yanlış**

- Aynı paragrafta çok sayıda bold
- Altı çizili normal vurgu
- Her kelimeyi farklı renge boyamak
- Uzun italic bloklar

## 22.4 Sosyal Medya

**Doğru**

- 1 ana başlık
- 1 destekleyici açıklama
- 1 CTA
- 2 font ağırlığı

**Yanlış**

- Aynı görselde 5 font boyutu
- Serif, sans, script ve dekoratif font birlikte
- Metni sığdırmak için aşırı küçültmek
- Bütün metni ortalamak

## 22.5 UI

**Doğru**

- Manrope tabanlı sistem
- Tutarlı text styles
- Anlamlı weight farkları
- Açık label ve helper text

**Yanlış**

- Serif butonlar
- Çok küçük form metni
- Bütün kartların farklı heading stili
- Hata mesajını yalnızca kırmızı ve bold yapmak

---

# 23. Kaçınılacak Font Yönleri

Norn Human tipografi sisteminde aşağıdaki yönlerden kaçınılmalıdır:

## 23.1 Gotik ve Okült Fontlar

Markayı:

- kapalı,
- korkutucu,
- tarihsel fanteziye yakın,
- spiritüel klişelere bağlı

gösterebilir.

## 23.2 Script ve El Yazısı Fontları

- temel marka fontu olarak kullanılmaz,
- şiirsel alıntılarda dahi varsayılan değildir,
- güven ve sistem duygusunu zayıflatabilir.

## 23.3 Aşırı Yüksek Kontrastlı Moda Serifleri

- lüks kozmetik veya moda markası algısı yaratabilir,
- uzun dijital başlıklarda kırılgan olabilir,
- Norn Human'ın insanilik ve uygulanabilirlik yönünü zayıflatabilir.

## 23.4 Fazla Geometrik Teknoloji Fontları

- ürün sisteminde kullanılabilir görünse de marka bütününde aşırı steril algı yaratabilir,
- bilinç, anlam ve insan deneyimi tarafını zayıflatabilir.

## 23.5 Popüler Font Karışımı

Yalnızca güncel tasarım trendi olduğu için:

- üç veya daha fazla font,
- display script,
- condensed poster font,
- mono font

eklenmez.

Norn Human'ın gücü çeşitlilikten değil, sınırlı sistem içindeki tutarlı kullanımdan gelmelidir.

---

# 24. Uygulama Senaryoları

## 24.1 Ana Sayfa Hero

```text
Eyebrow:
Manrope 600 / 12–14px

Heading:
Source Serif 4 500 / Display XL

Lead:
Manrope 400 / 18–20px

CTA:
Manrope 600 / 15–16px
```

## 24.2 Eğitim Kartı

```text
Kategori:
Manrope 600 / 12px

Eğitim adı:
Manrope 600 / 18–20px
veya büyük editorial kartta Source Serif 4 500 / 22–26px

Eğitmen:
Manrope 500 / 14px

Süre / seviye:
Manrope 400 / 13–14px

CTA:
Manrope 600 / 14px
```

## 24.3 Eğitim Detay Sayfası

```text
Kategori:
Manrope 600

Eğitim adı:
Source Serif 4 500 / H1

Kısa değer açıklaması:
Manrope 400 / Lead

Program bilgisi:
Manrope 500

Uzun açıklama:
Manrope 400 / Body LG

Alıntı:
Source Serif 4 Italic
```

## 24.4 Blog / Kavram Rehberi

```text
Kategori ve tarih:
Manrope 500

Başlık:
Source Serif 4 500

Özet:
Manrope 400 / Lead

Gövde:
Manrope 400 / Body LG

Ara başlık:
Source Serif 4 500 veya Manrope 600

Pull quote:
Source Serif 4 Italic
```

## 24.5 Dashboard

```text
Sayfa başlığı:
Manrope 600 / UI Heading XL

Kart başlığı:
Manrope 600 / UI Heading SM

Ana sayı:
Manrope 700 / 28–36px

Açıklama:
Manrope 400 / UI Body SM

Durum etiketi:
Manrope 600 / UI Label SM
```

---

# 25. Claude Design ve AI Üretim Kuralları

Claude Design veya başka bir yapay zekâ aracı tipografi üretirken aşağıdaki kuralları izlemelidir.

## 25.1 Zorunlu Font Sistemi

- Display/editorial: Source Serif 4
- Body/UI: Manrope
- Üçüncü font eklenmez.
- Logo fontu varsayılmaz.
- Norn Human wordmark'ı sistem fontuyla üretilmez.

## 25.2 Başlık Seçimi

- Kavramsal ve marka anlatısı: Source Serif 4
- İşlevsel ve ürün anlatısı: Manrope
- Tek başlık içinde font karışımı yapılmaz.
- Her tasarımda otomatik serif başlık kullanılmaz.
- Başlığın amacı içerik moduna göre belirlenir.

## 25.3 Metin Yoğunluğu

AI:

- metni tasarıma sığdırmak için küçültmemeli,
- önce metni edit etmeli,
- bir görselde bir ana mesaj kullanmalı,
- sosyal medya tasarımında uzun strateji paragraflarını taşımamalı,
- UI'da marka şiirselliğini işlevin önüne geçirmemelidir.

## 25.4 Hiyerarşi

Her tasarımda:

1. Ana mesaj
2. Destekleyici bilgi
3. Metadata
4. CTA

görsel olarak ayrıştırılmalıdır.

Aynı ağırlık ve boyutla yazılmamalıdır.

## 25.5 Türkçe Kontrol

AI çıktısı şu karakterlerle test edilmelidir:

```text
Ç Ğ İ I Ö Ş Ü
ç ğ i ı ö ş ü
```

Başlıklarda İngilizce title case uygulanmamalıdır.

## 25.6 Yasaklar

AI:

- script veya gotik font eklememeli,
- tüm metni büyük harf yapmamalı,
- aşırı letter spacing kullanmamalı,
- uzun italik paragraf oluşturmamalı,
- serif fontu buton ve formda kullanmamalı,
- sistem dışında rastgele font önermemeli,
- Source Serif 4 veya Manrope'u logo olarak sunmamalıdır.

---

# 26. Üretim Öncesi Kontrol Listesi

## Font

- Doğru font aileleri kullanıldı mı?
- Üçüncü bir font eklenmiş mi?
- Gerekli font ağırlığı sistemde var mı?
- Wordmark sistem fontuyla mı oluşturulmuş?

## Hiyerarşi

- İlk bakışta ana mesaj anlaşılıyor mu?
- Başlık, gövde, metadata ve CTA ayrışıyor mu?
- Fazla sayıda boyut veya ağırlık var mı?
- Hiyerarşi yalnızca bold ile mi kurulmuş?

## Okunabilirlik

- Gövde metni yeterli büyüklükte mi?
- Satır aralığı rahat mı?
- Metin bloğu fazla geniş mi?
- Fotoğraf üzerinde yeterli kontrast var mı?
- Mobilde başlık gereksiz uzun mu?

## Türkçe

- `İ`, `I`, `ı`, `i` doğru mu?
- Türkçe karakterlerde bozulma var mı?
- Başlık İngilizce title case ile mi yazılmış?
- Tırnak ve kesme işaretleri doğru mu?

## Kanal

- Web, sosyal medya veya UI için doğru scale kullanılmış mı?
- UI'da serif gereğinden fazla mı?
- Sosyal medya metni sığdırılmak için küçültülmüş mü?
- Sunum uzaktan okunabilir mi?
- E-posta fallback ile bozuluyor mu?

## Marka Uyumu

- Tipografi fazla mistik mi?
- Fazla teknoloji markası gibi mi?
- Fazla akademik veya resmi mi?
- Sakin fakat güçlü bir ifade var mı?
- Derinlik ve açıklık dengesi korunuyor mu?

---

# 27. Teknik Doğrulama ve Lisans Notu

Seçilen iki font ailesi Google Fonts dağıtımında bulunmaktadır.

- Source Serif 4 variable dosyaları weight ve optical size eksenlerini içerir.
- Manrope variable dosyası weight eksenini içerir.
- Her iki aile için Google Fonts kaynaklarında OFL lisans dosyaları bulunmaktadır.
- Üretim ekibi, proje yayına alınmadan önce kullanılan dosya sürümlerini ve lisans metinlerini teknik repository içinde kayıt altına almalıdır.
- Font dosyaları Brand OS teslim paketine kullanıcıya dağıtılacak varlık olarak eklenmemelidir; bağlantı ve kurulum yöntemi teknik dokümantasyonda tanımlanmalıdır.

---

# 28. Kısa Tipografi Özeti

## Ana fontlar

**Source Serif 4**  
Marka, display ve editoryal anlatı

**Manrope**  
Gövde, sosyal medya, web ve ürün arayüzü

## Varsayılan kullanım

- Büyük marka başlığı: Source Serif 4 Medium
- Bölüm başlığı: Source Serif 4 Medium veya Manrope Semibold
- Gövde: Manrope Regular
- Buton: Manrope Semibold
- Metadata: Manrope Medium
- Alıntı: Source Serif 4 Italic
- UI: Manrope
- Sayılar ve veri: Manrope

## Tipografik karakter

**Modern bilgelik, açık hiyerarşi ve dijital kullanılabilirlik.**

## Değişmez kural

> **Norn Human wordmark'ı seçilen sistem fontlarından birini doğrudan yazarak oluşturulmaz. Logo ayrı ve özgün bir tasarım çalışmasıdır.**

---

# 29. Kaynak Girdileri

Bu tipografi sistemi aşağıdaki proje kararlarının birlikte değerlendirilmesiyle hazırlanmıştır:

- Norn Human Brand Strategy
- Norn Human Voice & Messaging
- Norn Designer Brief — önceki çalışma adıyla hazırlanmış tarihsel kaynak
- Marka için tanımlanan “modern bilgelik” yaratıcı yönü
- Sade, güçlü, modern ve derinlikli görsel dil ihtiyacı
- Aşırı mistik ve aşırı teknolojik görünümden kaçınma kararı
- Web, sosyal medya ve ilerideki dijital ürün arayüzüne taşınabilir sistem ihtiyacı
- Google Fonts ve resmi font repository teknik verileri

---

**Dosya sonu**
