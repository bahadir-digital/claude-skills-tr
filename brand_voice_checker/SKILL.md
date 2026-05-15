---
name: brand_voice_checker
description: Yüklenen marka rehberine veya tarz kılavuzuna göre yazılan içeriğin tutarlılığını kontrol eden, sapan ifadeleri işaretleyen ve düzeltme öneren skill. İçerik pazarlama, kurumsal iletişim, marka ekipleri için. Marka rehberi + içerik birlikte yüklendiğinde tetiklenir.
---

# Marka Tonu Kontrolcüsü

## Amaç

İçeriğinizin marka rehberinizdeki ton, dil ve stil kurallarına ne kadar uyduğunu denetler.

## Kullanım

Kullanıcı şunları sağlamalı:
1. Marka rehberi / tarz kılavuzu (PDF, DOCX, metin)
2. Kontrol edilecek içerik (e-posta, post, makale, sunum metni)
3. (Opsiyonel) Hedef platform (web, sosyal medya, yazılı materyal)

## Kontrol Boyutları

### 1. Dil ve Ton
- Resmilik seviyesi (sen mi, siz mi)
- Aktif/pasif yapı tercihi
- Cümle uzunluğu

### 2. Marka Kelime Dağarcığı
- Kullanılması gereken terimler kullanılmış mı
- Yasaklı kelimeler var mı
- Marka adı doğru kullanılmış mı (büyük/küçük harf, boşluk)

### 3. Mesajlaşma Tutarlılığı
- Marka değerleri yansıtılmış mı
- Hedef kitleye uygun mu
- Kaçınılması gereken konular var mı

### 4. Format Kuralları
- Başlık stilleri
- Bullet point kullanımı
- Emoji kuralları
- Hashtag stilleri

### 5. Marka Hikayesi Uyumu
- Marka misyonu ile çelişen ifadeler
- Konumlandırma ile tutarsızlık

## Çıktı Formatı

### Genel Uyum Skoru: X/100

### Tespit Edilen Sorunlar

| # | Sorun | Konum | Önerilen Düzeltme |
|---|-------|-------|-------------------|
| 1 | Resmi olmayan ton | "1. paragraf" | "..." |
| 2 | Yasaklı kelime "ucuz" | "3. cümle" | "uygun fiyatlı" |
| 3 | Marka adı yanlış: "TPay" | "2. başlık" | "Tpay" |

### Düzeltilmiş İçerik

Önerilen tüm düzeltmelerle birlikte temiz versiyonu.

### Genel Öneriler

- Tutarlılık için ekstra ipuçları
- Marka rehberinde geliştirilebilecek noktalar

## Önemli Kurallar

- İçeriği baştan yazma, sadece düzelt
- Yazarın orijinal sesini koru
- Marka rehberindeki kurallar net değilse "BELİRSİZ" diye işaretle
- Otomatik düzeltme yerine öneri sun, kullanıcı seçsin
