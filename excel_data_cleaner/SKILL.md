---
name: excel_data_cleaner
description: Yüklenen Excel veya CSV dosyasındaki tekrarlayan kayıtları, hatalı formatları, eksik verileri ve boşlukları tespit edip temizleme önerileri sunan ve temizlenmiş versiyonu oluşturan skill. Veri analisti olmayan beyaz yakalılar için en sık ihtiyaç duyulan işlerden biri. Excel veya CSV dosyası yüklendiğinde otomatik tetiklenir.
---

# Excel Veri Temizleyici

## Amaç

Yüklenen Excel/CSV dosyasındaki kalite sorunlarını tespit eder ve temizlenmiş versiyonunu üretir.

## Kullanım

Kullanıcı şunları sağlamalı:
1. Excel (.xlsx, .xls) veya CSV dosyası
2. (Opsiyonel) Hangi sütunlara odaklanılması gerektiği
3. (Opsiyonel) Veri tipinin ne olduğu (müşteri listesi, satış kayıtları, vb.)

## Yapılacak Kontroller

### 1. Tekrar Eden Kayıtlar
- Birebir aynı satırlar
- Anahtar sütun bazında tekrarlar (e-posta, TCKN, telefon)
- Yaklaşık eşleşmeler (yazım farkları)

### 2. Format Tutarsızlıkları
- Tarih formatları (DD/MM/YYYY vs MM/DD/YYYY karışıklığı)
- Telefon numarası formatları (+90, 0, parantezli)
- Büyük/küçük harf tutarsızlığı (isim sütunlarında)
- Baştaki/sondaki boşluklar

### 3. Eksik Veri
- Zorunlu görünen sütunlardaki boşluklar
- Anlamsız değerler ("N/A", "-", "yok")

### 4. Hatalı Veri
- Sayısal sütundaki metin
- Geçersiz e-posta/telefon formatları
- Mantıksız tarihler (gelecek doğum tarihi gibi)

## Çıktı Formatı

### Veri Kalite Raporu
- Toplam satır sayısı: X
- Bulunan sorun sayısı: X
- Sorun türleri ve adetleri

### Temizleme Önerileri Tablosu
Her sorun için: ne, nerede, önerilen düzeltme

### Temizlenmiş Dosya
- Yeni Excel/CSV dosyası olarak
- Değişiklikler bir log sayfasında

## Önemli Kurallar

- Veri silmeden önce kullanıcıya onaylat
- Otomatik düzeltmelerde mantıklı varsayımları belirt
- Orijinal dosyayı koru, temizlenmiş versiyonu ayrı dosya olarak üret
