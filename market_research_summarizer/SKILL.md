---
name: market_research_summarizer
description: Birden fazla makale, rapor URL'si veya araştırma dokümanını ortak bulgular, çelişkiler ve stratejik çıkarımlarla özetleyen skill. Strateji ekipleri, ürün yöneticileri, danışmanlar için. Birden fazla kaynak paylaşıldığında ve sentez istendiğinde tetiklenir.
---

# Pazar Araştırma Özetleyici

## Amaç

Birden fazla kaynaktan gelen bilgileri tek bir sentez raporuna dönüştürür.

## Kullanım

Kullanıcı şunları sağlamalı:
1. En az 3 kaynak (makale, rapor, link, PDF)
2. Araştırma sorusu veya konu
3. (Opsiyonel) Karar bağlamı (hangi kararı destekleyecek)

## Çıktı Formatı

### 1. Araştırma Sorusu
Kullanıcının sorduğu net soru.

### 2. Yönetici Özeti (5 madde)
- En önemli 5 bulgu

### 3. Kaynaklar

| # | Kaynak | Tarih | Güvenilirlik | Ana Tezi |
|---|--------|-------|--------------|----------|
| 1 | ... | ... | Yüksek/Orta/Düşük | ... |
| 2 | ... | ... | ... | ... |

### 4. Ortak Bulgular (Konsensüs)

Birden fazla kaynağın hemfikir olduğu noktalar:

- **Bulgu 1**: ... (Kaynaklar: 1, 2, 4)
- **Bulgu 2**: ... (Kaynaklar: 1, 3, 5)

### 5. Çelişkiler ve Tartışmalı Konular

Kaynaklar arasında ayrılık olan noktalar:

- **Konu**: ...
  - **Görüş A** (Kaynak 1): ...
  - **Görüş B** (Kaynak 3): ...
  - **Hangi taraf daha güvenilir**: Neden

### 6. Sektör Trendleri / Pazar Dinamikleri
- Yükselişte olan
- Düşüşte olan
- Belirsiz alanlar

### 7. Rakip Analizi (varsa)
- Lider oyuncular
- Yeni girişler
- Pazar payı dağılımı

### 8. Stratejik Çıkarımlar

Kullanıcının kararı için somut öneriler:

- **Fırsatlar**: Bu araştırmanın gösterdiği açık fırsatlar
- **Tehditler**: Dikkat edilmesi gerekenler
- **Eylem önerileri**: Şimdi ne yapılmalı

### 9. Daha Fazla Araştırma Önerisi
Bu sentezin kapsamadığı, derinleştirilmesi gereken alanlar.

### 10. Kaynakça
Tüm kaynaklar APA veya basit liste formatında.

## Önemli Kurallar

- Her iddia için kaynak belirt
- Birincil kaynaklara öncelik ver (orijinal araştırma > haber > blog)
- Bias riskini değerlendir (kim finanse etmiş, hangi taraf)
- Veri tarihini önemse, eski veriyi işaretle
- Spekülatif sonuçlardan kaçın, sadece kanıta dayalı
