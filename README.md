# 🔄 SOAP vs REST Karşılaştırma Aracı

<div align="center">

![Version](https://img.shields.io/badge/version-2.0-blue.svg)
![Python](https://img.shields.io/badge/Python-3.7+-green.svg)
![License](https://img.shields.io/badge/license-MIT-orange.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)

<br/>

### 🎯 SOAP XML ve REST JSON servis çıktılarını karşılaştırmak için güçlü ve kullanıcı dostu bir web aracı

<br/>

[Özellikler](#-özellikler) • [Hızlı Başlangıç](#-hızlı-başlangıç) • [Kullanım](#-kullanım) • [Ekran Görüntüleri](#-ekran-görüntüleri) • [API Referansı](#-api-referansı)

<br/>

---

### 💡 Neden Bu Araç?

Servis dönüşüm projelerinde **AS-IS (SOAP)** ve **TO-BE (REST)** çıktılarını manuel karşılaştırmak zaman alıcı ve hataya açıktır. Bu araç, **otomatik karşılaştırma** ve **profesyonel Excel raporlama** ile bu süreci saniyeler içinde tamamlamanızı sağlar.

---

</div>

## 📋 İçindekiler

- [Özellikler](#-özellikler)
- [Hızlı Başlangıç](#-hızlı-başlangıç)
- [Kullanım Kılavuzu](#-kullanım-kılavuzu)
- [Ekran Görüntüleri](#-ekran-görüntüleri)
- [API Referansı](#-api-referansı)
- [Proje Yapısı](#-proje-yapısı)
- [Teknik Detaylar](#-teknik-detaylar)
- [Katkıda Bulunma](#-katkıda-bulunma)

---

## ✨ Özellikler

### 🎯 Temel Özellikler

| Özellik | Açıklama |
|---------|----------|
| 🔍 **Akıllı Karşılaştırma** | SOAP XML ve REST JSON formatlarını otomatik parse ederek alan bazlı karşılaştırma yapar |
| 📊 **Excel Dışa Aktarma** | Karşılaştırma sonuçlarını profesyonel formatlı Excel dosyasına aktarır |
| 🎨 **Modern Arayüz** | Koyu tema ile göz yormayan, responsive tasarım |
| 📈 **Özet İstatistikler** | Toplam alan, eşleşen ve farklı alan sayıları ile fark oranı |
| 📄 **Çoklu Doküman Desteği** | Birden fazla dokümanı ayrı ayrı karşılaştırabilme |
| 🏷️ **Detaylı Raporlama** | Meta bilgiler, template alanları ve index değerlerini ayrıntılı gösterir |

### 🛠️ Teknik Özellikler

- ✅ **Bağımsız Çalışma** - Harici sunucu gerektirmez, yerel olarak çalışır
- ✅ **Tek Dosya Python Backend** - Basit kurulum ve çalıştırma
- ✅ **Responsive Tasarım** - Mobil ve masaüstü uyumlu
- ✅ **UTF-8 Desteği** - Türkçe karakter desteği
- ✅ **Hızlı Performans** - Anlık karşılaştırma sonuçları

---

## 🚀 Hızlı Başlangıç

### Gereksinimler

| Gereksinim | Minimum Versiyon |
|------------|------------------|
| Python | 3.7+ |
| openpyxl | 3.0+ |

### 3 Adımda Kurulum

```bash
# 1️⃣ Projeyi klonlayın
git clone https://github.com/kullaniciadi/soap-rest-compare.git
cd soap-rest-compare

# 2️⃣ Bağımlılıkları yükleyin
pip install openpyxl

# 3️⃣ Uygulamayı başlatın
python web_compare.py
```

> 🌐 Tarayıcınızda **http://localhost:8080** adresini açın ve kullanmaya başlayın!

---

## 📖 Kullanım Kılavuzu

### Uygulamayı Başlatma

```bash
python web_compare.py
```

<details>
<summary>📋 Konsol Çıktısı</summary>

```
📂 Script dizini: /path/to/project
📂 Exports dizini: /path/to/project/exports
🚀 SOAP vs REST Karşılaştırma Aracı
📍 Tarayıcıda aç: http://localhost:8080
❌ Durdurmak için: Ctrl+C
```

</details>

### Adım Adım Kullanım

| Adım | İşlem | Açıklama |
|------|-------|----------|
| **1** | 🌐 Tarayıcıyı Açın | `http://localhost:8080` adresine gidin |
| **2** | 📋 Verileri Yapıştırın | Sol panele SOAP XML, sağ panele REST JSON yapıştırın |
| **3** | 🔍 Karşılaştırın | "Karşılaştır" butonuna tıklayın |
| **4** | 📊 Sonuçları İnceleyin | Özet istatistikleri ve detaylı tabloları görüntüleyin |
| **5** | 📥 Excel'e Aktarın | "Excel'e Aktar" butonu ile raporu indirin |

---

## 📸 Ekran Görüntüleri

### 🖥️ Ana Sayfa - Veri Girişi Arayüzü

Modern ve kullanıcı dostu koyu tema tasarımı ile göz yormayan bir deneyim:
<img width="1814" height="646" alt="image" src="https://github.com/user-attachments/assets/eeeddd7f-d4da-4946-9da1-fbb60f13332e" />




### 📊 Sonuç Özeti

Karşılaştırma sonuçlarının anlaşılır özeti:
<img width="1481" height="746" alt="image" src="https://github.com/user-attachments/assets/95489534-1dbf-433c-bbb3-e32fc97cc8eb" />





### 📋 Detaylı Karşılaştırma Tablosu

Alan bazlı karşılaştırma sonuçları renkli göstergelerle:

<img width="1408" height="1294" alt="image" src="https://github.com/user-attachments/assets/29e474a2-967c-4dca-b636-17748bda8f08" />



### 📑 Excel Rapor Çıktısı

Oluşturulan Excel dosyası profesyonel formatlama ile:

| Sheet Adı | İçerik | Açıklama |
|-----------|--------|----------|
| 📋 **Üst Seviye & Müşteri** | Genel ve müşteri bilgileri | ResultCode, identifier, müşteri alanları |
| 📄 **[Doküman Adı]** | Her doküman için ayrı sheet | Meta, template fields, indexes |
| 🔴 **ÖZET - Tüm Farklar** | Tüm farklılıkların listesi | Hızlı gözden geçirme için |

**Excel Formatı Özellikleri:**
- 📘 **Mavi başlıklar** - Profesyonel görünüm
- 🟢 **Yeşil metin** - Eşleşen değerler
- 🔴 **Kırmızı metin** - Farklı değerler
- 📐 **Otomatik sütun genişlikleri** - Kolay okuma
- 🔲 **Kenarlıklı hücreler** - Net ayrım

---

## 🔌 API Referansı

### Karşılaştırma Endpoint'i

<details>
<summary><code>POST /compare</code> - SOAP ve REST içeriklerini karşılaştırır</summary>

**Request:**
```http
POST /compare
Content-Type: application/x-www-form-urlencoded

soap=<SOAP_XML_CONTENT>&rest=<REST_JSON_CONTENT>
```

**Response:**
```json
{
  "topLevel": [
    { "field": "resultCode", "soap": "0", "rest": "0", "status": "same" }
  ],
  "customer": [...],
  "documents": [...],
  "summary": {
    "total": 156,
    "same": 142,
    "diff": 14
  },
  "restData": {...}
}
```

</details>

### Excel Export Endpoint'i

<details>
<summary><code>POST /export-excel</code> - Karşılaştırma sonuçlarını Excel'e aktarır</summary>

**Request:**
```http
POST /export-excel
Content-Type: application/json

{
  "comparison_data": {...},
  "rest_data": {...}
}
```

**Response:**
```json
{
  "success": true,
  "filename": "2069890366 - 20260410_123456.xlsx",
  "filepath": "/path/to/exports/..."
}
```

</details>

### Dosya İndirme Endpoint'i

<details>
<summary><code>GET /download/{filename}</code> - Oluşturulan Excel dosyasını indirir</summary>

**Request:**
```http
GET /download/2069890366%20-%2020260410_123456.xlsx
```

**Response:** Excel dosyası (binary)

</details>

---

## 📁 Proje Yapısı

```
soap-rest-compare/
│
├── 📄 web_compare.py      # Python backend - HTTP sunucu ve karşılaştırma mantığı
├── 📄 index.html          # Frontend - Web arayüzü
├── 📄 README.md           # Proje dokümantasyonu
│
└── 📁 exports/            # Excel çıktılarının kaydedildiği klasör (otomatik oluşturulur)
    └── *.xlsx             # Karşılaştırma raporları
```

---

## ⚙️ Teknik Detaylar

### Mimari

```
┌─────────────────┐     HTTP      ┌──────────────────┐
│                 │ ◄───────────► │                  │
│   index.html    │   Request/    │  web_compare.py  │
│   (Frontend)    │   Response    │   (Backend)      │
│                 │               │                  │
└─────────────────┘               └────────┬─────────┘
                                           │
                                           ▼
                                  ┌──────────────────┐
                                  │   exports/*.xlsx │
                                  │   (Excel Files)  │
                                  └──────────────────┘
```

### Backend Modülleri (web_compare.py)

| Modül | Açıklama |
|-------|----------|
| `parse_soap_xml()` | SOAP XML içeriğini parse eder |
| `parse_rest_json()` | REST JSON içeriğini parse eder |
| `compare_data()` | İki veri setini karşılaştırır |
| `export_to_excel()` | Sonuçları Excel'e aktarır |
| `CompareHandler` | HTTP isteklerini yönetir |

### Karşılaştırılan Alanlar

<details>
<summary>🔝 Üst Seviye Alanlar</summary>

- `resultCode` - İşlem sonuç kodu
- `resultDescription` - İşlem sonuç açıklaması
- `identifier` - Sipariş numarası
- `catalogProcessId` - Katalog işlem ID
- `operationTypeId` - Operasyon tipi ID

</details>

<details>
<summary>👤 Müşteri Bilgileri</summary>

- `type` - Müşteri tipi
- `customerNumber` - Müşteri numarası
- `nationality` - Uyruk
- `citizenNumber` - TC Kimlik No
- `taxNumber` - Vergi numarası
- `firstName` - Ad
- `lastName` - Soyad
- `mobilePhone` - Cep telefonu
- `birthDate` - Doğum tarihi

</details>

<details>
<summary>📄 Doküman Bilgileri</summary>

**Meta Bilgiler:**
- `documentType`, `mandatory`, `printable`, `signatureRequired`
- `willBeScanned`, `sendEmail`, `fromCampaign`, `canBeSentLater`
- `minPage`, `maxPage`, `barcodeCode`, `templateId`

**Template Fields:** Dinamik doküman alanları

**Document Indexes:** DocStoreSystem değerleri

</details>

### Excel Formatı

```
┌────────────────────────────────────────────────────────┐
│  📘 Mavi Başlıklar    │  Profesyonel görünüm          │
│  🟢 Yeşil Metin       │  Eşleşen değerler             │
│  🔴 Kırmızı Metin     │  Farklı değerler              │
│  � Auto-fit Kolonlar │  Kolay okuma                  │
│  🔲 Kenarlıklı Hücre  │  Net görsel ayrım             │
└────────────────────────────────────────────────────────┘
```

---

## 🤝 Katkıda Bulunma

Katkılarınızı bekliyoruz! 

### Nasıl Katkıda Bulunabilirsiniz?

1. 🍴 **Fork** edin
2. 🌿 **Feature branch** oluşturun
   ```bash
   git checkout -b feature/YeniOzellik
   ```
3. 💾 **Commit** edin
   ```bash
   git commit -m 'Yeni özellik eklendi'
   ```
4. 📤 **Push** edin
   ```bash
   git push origin feature/YeniOzellik
   ```
5. 🔃 **Pull Request** açın

### Önerilen İyileştirmeler

- [ ] Farklı servis formatları desteği
- [ ] Toplu karşılaştırma özelliği
- [ ] Karşılaştırma geçmişi
- [ ] Dark/Light tema seçeneği

---

## 📝 Lisans

Bu proje **MIT Lisansı** altında lisanslanmıştır.

```
MIT License

Copyright (c) 2024

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...
```

Detaylar için [LICENSE](LICENSE) dosyasına bakın.

---

<div align="center">

### 🌟 Bu Projeyi Beğendiyseniz

**⭐ Yıldız vererek destek olabilirsiniz!**

<br/>

[![GitHub stars](https://img.shields.io/github/stars/kullaniciadi/soap-rest-compare?style=social)](https://github.com/kullaniciadi/soap-rest-compare)

<br/>

---

**Made with ❤️ for Service Transformation Projects**

*SOAP'tan REST'e geçiş projelerinizde yanınızda.*

</div>
