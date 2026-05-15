---
name: risk_matrix_generator
description: Proje veya operasyon tanımından olası riskleri tespit eden, olasılık ve etki skorlarıyla risk matrisine döken, azaltma önerileri sunan skill. Proje yöneticileri, operasyon liderleri, risk yönetimi sorumluları için. Bir proje veya süreç tanımlandığında tetiklenir.
---

# Risk Matrisi Çıkarıcı

## Amaç

Bir projedeki veya operasyondaki riskleri yapılandırılmış şekilde tespit eder, önceliklendirir ve aksiyon planı oluşturur.

## Kullanım

Kullanıcı şunları sağlamalı:
1. Proje veya operasyon tanımı
2. (Opsiyonel) Bağlam (sektör, ölçek, paydaşlar)
3. (Opsiyonel) Geçmiş risk verileri
4. (Opsiyonel) Risk kategorileri (operasyonel, finansal, regülasyon, vb.)

## Risk Kategorileri

Standart kategoriler:
- **Operasyonel**: Süreç, kaynak, kapasite
- **Finansal**: Bütçe, nakit akışı, ödeme
- **Teknik**: Sistem, altyapı, güvenlik
- **İnsan Kaynakları**: Yetenek, motivasyon, ayrılış
- **Regülatif**: Yasa, denetim, uyum
- **İtibar**: Marka, müşteri algısı, medya
- **Pazar**: Rekabet, talep, fiyat
- **Tedarik Zinciri**: Tedarikçi, lojistik
- **Strateji**: Yön değişimi, paydaş hizalanması

## Çıktı Formatı

### 1. Risk Listesi

| ID | Risk | Kategori | Olasılık (1-5) | Etki (1-5) | Skor | Seviye |
|----|------|----------|----------------|------------|------|--------|
| R1 | ... | Operasyonel | 4 | 5 | 20 | Kritik |
| R2 | ... | Finansal | 2 | 4 | 8 | Orta |

**Skor hesabı**: Olasılık × Etki

**Seviyeler**:
- 1-4: Düşük
- 5-9: Orta
- 10-14: Yüksek
- 15-25: Kritik

### 2. Risk Matrisi (Görsel)

```
ETKİ
  5 │ M  H  H  K  K
  4 │ D  M  H  H  K
  3 │ D  M  M  H  H
  2 │ D  D  M  M  H
  1 │ D  D  D  M  M
    └─────────────
      1  2  3  4  5
        OLASILIK
```
(D=Düşük, M=Orta, H=Yüksek, K=Kritik)

### 3. Kritik Riskler (Detaylı Analiz)

Her kritik risk için:

#### R1: [Risk adı]
- **Tanım**: ...
- **Tetikleyiciler**: Bu risk hangi durumda gerçekleşir
- **Etki**: Gerçekleşirse neler olur
- **Erken uyarı sinyalleri**: Hangi göstergelere bakmalı
- **Azaltma stratejisi**:
  - Önleyici: Riskin gerçekleşmemesi için
  - Tepkisel: Gerçekleşirse ne yapacağız
- **Sorumlu**: ...
- **Bütçe etkisi**: ...
- **Takip sıklığı**: Haftalık / Aylık / Çeyreklik

### 4. Risk İzleme Planı

| Risk | Takip Eden | Sıklık | Eskalasyon Kriteri |
|------|-----------|--------|---------------------|
| R1 | ... | Haftalık | Skor 15+ olduğunda |

### 5. Genel Değerlendirme
- Toplam risk sayısı
- Kritik risk sayısı
- En riskli kategori
- Risk profili (yüksek mi, düşük mü)

## Önemli Kurallar

- Olasılık ve etkiyi ayrı ayrı puanla (1-5 skala)
- Aynı kategoriden çok risk değil, farklı kategorileri tara
- Her risk için somut bir azaltma önerisi olmalı
- "Risk var" demek yetmez, ne yapacağız netleşsin
- Türkçe yazılsın ama "risk", "mitigation", "trigger" gibi terimler kullanılabilir
