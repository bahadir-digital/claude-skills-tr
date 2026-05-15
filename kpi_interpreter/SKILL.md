---
name: kpi_interpreter
description: Yüklenen dashboard, rapor verisi veya KPI tablosunu yöneticiler için 3 cümlelik insight'lara dönüştüren skill. Operasyonel veri yöneticiye sunulurken "neden önemli, ne değişti, ne yapmalıyız" sorularını cevaplar. Excel, CSV, dashboard ekran görüntüsü veya tablo yüklendiğinde tetiklenir. BI uzmanları, raporlama ekipleri, operasyon yöneticileri için.
---

# KPI Yorumlayıcı

## Amaç

Ham KPI verisini yöneticilerin saniyeler içinde anlayabileceği, eylem alabileceği insight'lara çevirir.

## Kullanım

Kullanıcı şunları sağlamalı:
1. KPI verisi (Excel, CSV, dashboard ekran görüntüsü, tablo)
2. (Opsiyonel) Karşılaştırma dönemi (önceki ay, geçen yıl)
3. (Opsiyonel) Hedef değerler
4. (Opsiyonel) Hedef kitle (CEO, departman müdürü, ekip lideri)

## Çıktı Formatı

Her KPI için 3 cümlelik insight:

### Cümle 1: NE
- Mevcut değer
- Önceki dönem ile karşılaştırma
- Trend yönü

### Cümle 2: NEDEN
- Olası nedenler
- Etkili faktörler
- Bağlam

### Cümle 3: NE YAPMALI
- Önerilen aksiyon
- Sorumlu kişi/ekip (varsa)
- Aciliyet seviyesi

## Örnek Çıktı

> **Müşteri Memnuniyeti (NPS): 42 → 38 (-4)**
>
> NPS skorumuz son ayda 4 puan düştü ve sektör ortalamasının altına indi. Düşüş özellikle çağrı bekleme sürelerindeki artış ve birinci temas çözüm oranındaki azalma ile paralel seyrediyor. Operasyon ekibi ile bu hafta acil bir kök neden analizi toplantısı yapılmalı.

## Önemli Kurallar

- 3 cümleyi geçme
- Jargon kullanma (CEO seviyesi için)
- Her zaman bir aksiyon önerisi içer
- Sayıları somut ver, "biraz arttı" deme
- Veri yoksa veya yeterli değilse belirt, uydurma
- Türkçe çıktı üret
