---
name: prd_writer
description: Birkaç fikir notundan veya feature isteğinden tam Ürün Gereksinim Dokümanı (PRD) çıkaran skill. Amaç, kapsam, kullanıcı senaryoları, başarı kriterleri ve teknik gereksinimler içerir. Ürün yöneticileri, proje liderleri, yazılım takım liderleri için. Ürün fikri veya feature isteği paylaşıldığında tetiklenir.
---

# PRD Hazırlayıcı

## Amaç

Ham ürün fikirlerini geliştirici ve paydaşların kullanabileceği tam PRD'lere dönüştürür.

## Kullanım

Kullanıcı şunları sağlamalı:
1. Ürün/feature fikri (kısa açıklama yeterli)
2. (Opsiyonel) Hedef kullanıcı
3. (Opsiyonel) Mevcut ürün bağlamı
4. (Opsiyonel) İş hedefi

## PRD Yapısı

### 1. Genel Bilgiler
- **Ürün/Feature Adı**: ...
- **Doküman Yazarı**: ...
- **Tarih**: ...
- **Versiyon**: 1.0
- **Durum**: Taslak / Onay Bekliyor / Onaylandı

### 2. Yönetici Özeti (2-3 cümle)
Bu ürünün/feature'ın ne olduğunun ve neden yaptığımızın özeti.

### 3. Problem Tanımı
- **Hangi problemi çözüyoruz**: ...
- **Kimin için**: ...
- **Mevcut durum nasıl**: ...
- **Bu problemi çözmemek bizi ne kadar etkiliyor**: ...

### 4. Hedefler ve Başarı Kriterleri

#### Birincil Hedefler
- Hedef 1: Ölçülebilir kriter
- Hedef 2: Ölçülebilir kriter

#### Başarı Metrikleri (KPI'lar)
- KPI 1: Baseline → Hedef
- KPI 2: Baseline → Hedef

### 5. Hedef Kullanıcılar
- **Birincil persona**: Detay
- **İkincil persona**: Detay

### 6. Kullanıcı Senaryoları (User Stories)

```
KULLANICI OLARAK
[ne yapmak istiyorum]
[KARŞILIĞINDA ne elde ediyorum]
```

Her senaryo için:
- Acceptance Criteria
- Edge cases
- Hata durumları

### 7. Fonksiyonel Gereksinimler

| # | Gereksinim | Öncelik | Notlar |
|---|------------|---------|--------|
| F1 | ... | Must | ... |
| F2 | ... | Should | ... |
| F3 | ... | Could | ... |

### 8. Non-Fonksiyonel Gereksinimler
- **Performans**: ...
- **Güvenlik**: ...
- **Erişilebilirlik**: ...
- **Lokalizasyon**: ...

### 9. Kapsam Dışı (Out of Scope)
Bu sürümde yapılmayacaklar — beklenti yönetimi için.

### 10. Bağımlılıklar ve Riskler
- Bağımlılık 1: ...
- Risk 1: Olasılık — Etki — Azaltma

### 11. Zaman Çizelgesi
- Discovery: ...
- Design: ...
- Development: ...
- Testing: ...
- Launch: ...

### 12. Ekler
- Mockup linkleri (varsa)
- Araştırma sonuçları
- İlgili dokümanlar

## Önemli Kurallar

- "Should" vs "must" ayrımı çok net olmalı
- Eksik bilgileri "BELİRLENECEK" diye işaretle, varsayım yapma
- Teknik detayları minimum tut, "ne" ye odaklan, "nasıl" geliştiriciye bırak
- Her senaryo için acceptance criteria zorunlu
- Türkçe yaz, teknik terimleri olduğu gibi koru (acceptance criteria, edge case vb.)
