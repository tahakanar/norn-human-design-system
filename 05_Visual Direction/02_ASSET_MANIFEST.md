---
document_name: Asset Manifest
project: Norn / Norn Human Visual Direction
version: 1.0
status: Working Inventory
language: tr-TR
last_updated: 2026-07-16
---

# Asset Manifest

Bu dosya, `Asset Library/` içindeki üretim assetlerinin kaynak, lisans, statü ve kullanım bilgisini kayıt altına almak için kullanılır.

## 1. Statüler

```text
CANDIDATE
REVIEW REQUIRED
APPROVED
RESTRICTED
DEPRECATED
```

## 2. Dosya Adlandırma

```text
PHOTO-001_descriptive-name.ext
TEXTURE-001_descriptive-name.ext
PATTERN-001_descriptive-name.ext
ILLUS-001_descriptive-name.ext
ICON-001_descriptive-name.ext
```

Türkçe karakter, boşluk ve `final-final` gibi sürüm adları kullanılmamalıdır.

## 3. Asset Kayıt Tablosu

| ID | Dosya | Klasör | Tür | Kaynak / Üretici | Lisans | Model Release | Statü | Onay Tarihi | Kullanım Alanı | Not |
|---|---|---|---|---|---|---|---|---|---|---|
| PHOTO-001 |  | Photography | Fotoğraf |  |  |  | CANDIDATE |  |  |  |
| TEXTURE-001 |  | Textures | Texture |  |  | N/A | CANDIDATE |  |  |  |
| PATTERN-001 |  | Patterns | Pattern |  |  | N/A | CANDIDATE |  |  |  |
| ILLUS-001 |  | Illustrations | Illustration |  |  | N/A | CANDIDATE |  |  |  |
| ICON-001 |  | Icons | Icon |  |  | N/A | CANDIDATE |  |  |  |

## 4. Tekil Kayıt Şablonu

```text
## ASSET-ID

Dosya:
Klasör:
Asset türü:
Kaynak / üretici:
Kaynak adresi:
Lisans:
Ticari kullanım:
Model release:
Oluşturulma / erişim tarihi:
Statü:
Onaylayan:
Onay tarihi:

### Kullanım Alanı
-

### Teknik Bilgi
- Boyut:
- Oran:
- Renk alanı:
- Arka plan:
- Vektör / raster:

### Kullanım Sınırları
-

### Düzenleme Notu
-

### Claude Design Talimatı
-
```

## 5. AI Üretimi Asset Kuralı

AI ile üretilen assetlerde ayrıca şu bilgiler tutulmalıdır:

- kullanılan araç,
- kullanılan model,
- ana prompt,
- referans görsel kullanımı,
- düzenleme adımları,
- gerçek kişi benzerliği riski,
- insan onayı,
- ticari kullanım koşulları.

AI üretimi dosya, yalnızca görsel olarak iyi olduğu için `APPROVED` statüsü alamaz.

## 6. Kaynak ve Lisans Kontrolü

Final üretimde kullanılacak asset için:

- ticari kullanım hakkı,
- düzenleme hakkı,
- atıf gereksinimi,
- süre veya bölge kısıtı,
- model release,
- marka / mülk hakkı

kontrol edilmelidir.

---

**Dosya sonu**
