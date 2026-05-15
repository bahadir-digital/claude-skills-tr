---
name: rfp_summarizer
description: Uzun teklif belgesi (RFP, RFQ, ihale dokümanı) veya gelen teklifleri ana koşullar, riskler ve aksiyon noktaları olarak özetleyen skill. Satış ekipleri, satın alma uzmanları, hukuki ekipler için. Uzun bir doküman yüklendiğinde ve "özetle" denildiğinde tetiklenir.
---

# RFP / Teklif Özetleyici

## Amaç

Onlarca sayfalık RFP veya teklif dökümanını saniyeler içinde stratejik özete dönüştürür.

## Kullanım

Kullanıcı şunları sağlamalı:
1. RFP, RFQ veya teklif dökümanı (PDF, DOCX)
2. (Opsiyonel) Bakış açısı: alıcı mı, satıcı mı
3. (Opsiyonel) Odaklanılması gereken alanlar

## Çıktı Formatı

### 1. Yönetici Özeti (5 satır)
- Kim, ne istiyor
- Bütçe / değer
- Zaman çizelgesi
- Kritik gereksinim
- Ana risk

### 2. Temel Bilgiler

| Alan | Detay |
|------|-------|
| Müşteri/Tedarikçi | ... |
| Proje/Hizmet | ... |
| Bütçe / Tahmini Değer | ... |
| Süre | ... |
| Teslimat Tarihi | ... |
| İletişim Kişisi | ... |

### 3. Kapsam ve Gereksinimler

#### Zorunlu Gereksinimler
- Madde 1
- Madde 2
- Madde 3

#### Tercih Edilen (Bonus) Gereksinimler
- Madde 1
- Madde 2

#### Belirsiz / Açık Bırakılmış Konular
- Madde 1 — soru sorulmalı
- Madde 2 — soru sorulmalı

### 4. Önemli Şart ve Koşullar

- Ödeme şartları
- Cezai şartlar
- Sözleşme süresi
- IP / mülkiyet hakları
- Gizlilik
- KVKK / Veri koruma

### 5. Riskler

| Risk | Etki | Olasılık | Öneri |
|------|------|----------|-------|
| ... | Yüksek/Orta/Düşük | ... | ... |

### 6. Aksiyon Listesi

- [ ] Aksiyon 1 (sorumlu — tarih)
- [ ] Aksiyon 2
- [ ] Aksiyon 3

## Önemli Kurallar

- Hukuki ifadeleri yorumlama, olduğu gibi aktar
- Önemli rakamları (bütçe, ceza) net göster
- Belirsiz noktaları "BELİRSİZ" işareti ile vurgula
- Politik / yorumlayıcı dilden kaçın
