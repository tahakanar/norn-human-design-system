---
document_name: START HERE
project: Norn / Norn Human Icon System
version: 1.0
status: Ready for Brand OS
language: tr-TR
last_updated: 2026-07-16
---

# Norn / Norn Human Icon System — Başlangıç Dosyası

Bu klasör, Norn Human Brand OS içindeki:

```text
05 Visual Direction/
└── Asset Library/
    └── Icons/
```

konumuna doğrudan eklenmek için hazırlanmıştır.

## 1. Sistem Özeti

```text
Norn Human Icon System v1
├── Base UI Icons → Lucide
└── Brand Custom Icons → Norn Human için özel çizim
```

Ana kullanıcı arayüzü ikonları Lucide üzerinden seçilir. Marka, kategori ve Norn perspektifine özgü ikonlar ise Lucide geometrisine uyumlu biçimde özel çizilir.

## 2. Dosyaları Bu Sırayla Oku

1. `00_START_HERE.md`
2. `01_ICON_SYSTEM.md`
3. `02_LUCIDE_BASE_SET.json`
4. `03_SEMANTIC_ICON_MAP.json`
5. `04_CUSTOM_ICON_BRIEFS.md`
6. `05_ICON_MANIFEST.csv`
7. `06_CLAUDE_DESIGN_PROMPT.md`
8. Alt klasörlerdeki `README.md` dosyaları

## 3. Klasör Yapısı

```text
Icons/
├── 00_START_HERE.md
├── 01_ICON_SYSTEM.md
├── 02_LUCIDE_BASE_SET.json
├── 03_SEMANTIC_ICON_MAP.json
├── 04_CUSTOM_ICON_BRIEFS.md
├── 05_ICON_MANIFEST.csv
├── 06_CLAUDE_DESIGN_PROMPT.md
├── Base UI/
├── Brand Custom/
│   ├── Source SVG/
│   └── Exports/
│       ├── SVG/
│       └── PNG/
├── States/
└── Archive/
```

## 4. Ne Nereye Eklenir?

### Base UI/

Lucide ikonlarının bireysel SVG kopyalarını burada saklamak zorunlu değildir.

Bu klasör:

- seçilmiş icon listesi,
- Figma component seti,
- export gerekiyorsa kontrollü SVG çıktıları

için kullanılır.

Kod tarafında ikonlar Lucide paketinden import edilmelidir.

### Brand Custom/Source SVG/

Norn Human için özel çizilen kaynak SVG dosyaları buraya eklenir.

### Brand Custom/Exports/SVG/

Onaylı ve optimize edilmiş final SVG çıktıları buraya eklenir.

### Brand Custom/Exports/PNG/

Sosyal medya, sunum veya raster gerektiren kullanım alanları için PNG exportlar buraya eklenir.

### States/

Selected, active, off, disabled veya filled durumlar için özel varyantlar yalnızca gerekiyorsa burada tutulur.

### Archive/

Kullanımdan kaldırılmış, reddedilmiş veya eski ikonlar burada saklanır.

## 5. İlk Üretim Önceliği

Önce:

1. Base UI icon seçim listesi doğrulanır.
2. Semantic icon map kontrol edilir.
3. Sekiz özel marka ikonu siyah-beyaz çizilir.
4. 16 / 20 / 24 / 32 px testleri yapılır.
5. Claude Design veya tasarımcı çıktıları manifestte kaydedilir.
6. İnsan onayı sonrası final SVG export alınır.

## 6. Ana Kural

**One meaning, one icon, one system.**

Aynı anlam için farklı ekranlarda farklı ikon kullanılmaz.

---

**Başlangıç talimatı:** Şimdi `01_ICON_SYSTEM.md` dosyasını oku.
