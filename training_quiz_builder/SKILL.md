---
name: training_quiz_builder
description: PowerPoint sunumu, PDF eğitim materyali veya metin içeriğinden kolay/orta/zor seviyede 20 soruluk çoktan seçmeli sınav hazırlayan skill. Her soru için açıklamalı cevap anahtarı içerir. İK eğitim ekipleri, akademisyenler, eğitmenler için. Eğitim materyali yüklendiğinde tetiklenir.
---

# Eğitim Sınavı Hazırlayıcı

## Amaç

Eğitim materyalinden katılımcıların öğrenmesini ölçecek profesyonel bir sınav hazırlar.

## Kullanım

Kullanıcı şunları sağlamalı:
1. Eğitim materyali (PPTX, PDF, DOCX)
2. (Opsiyonel) Soru sayısı (varsayılan: 20)
3. (Opsiyonel) Zorluk dağılımı (varsayılan: 5 kolay + 10 orta + 5 zor)
4. (Opsiyonel) Hedef format (Kahoot, Google Forms, Word)

## Soru Türleri

### Kolay Sorular (5 adet)
- Tanım, hatırlama
- Doğrudan sunumda geçen bilgiler
- Tek doğru cevap açıkça belli

### Orta Sorular (10 adet)
- Anlama, uygulama
- Kavramları birleştirme
- Senaryo bazlı

### Zor Sorular (5 adet)
- Analiz, sentez
- Birden fazla kavramı birleştirme
- Yanıltıcı seçenekler içerir

## Çıktı Formatı

### Sınav

**Soru 1** [Kolay]

Soru metni?

A) Seçenek
B) Seçenek
C) Seçenek
D) Seçenek

**Soru 2** [Orta]
...

### Cevap Anahtarı

| Soru | Doğru Cevap | Açıklama |
|------|-------------|----------|
| 1 | C | Sunumun 5. slaydında belirtildiği gibi... |
| 2 | A | ... |

### Sınav İçin Hazır Format Çıktısı

İstenen platforma göre:
- **Kahoot**: CSV formatında, Kahoot'a doğrudan import edilebilir
- **Google Forms**: Forms'a kopyalanabilir format
- **Word**: Yazdırılabilir, A4 format

## Önemli Kurallar

- Her sorunun materyalde dayanağı olmalı
- Yanıltıcı seçenekler mantıklı olmalı (rastgele değil)
- Cevap dağılımı dengeli (A,B,C,D eşit ağırlık)
- "Yukarıdakilerin hepsi" / "hiçbiri" maksimum 2 soruda
- Türkçe içerik için Türkçe sorular, terminolojiyi koru
