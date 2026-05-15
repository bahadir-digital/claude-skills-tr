---
name: meeting_notes_extractor
description: Toplantı transkriptini veya not metnini özet, alınan kararlar listesi ve sorumlu/tarih içeren aksiyon planına dönüştüren skill. Kullanıcı bir toplantı transkripti (Teams, Zoom, Google Meet) veya toplantı notu yüklediğinde otomatik tetiklenir. Yöneticiler, proje liderleri, asistanlar için her toplantı sonrası vazgeçilmez bir araçtır.
---

# Toplantı Notu Çıkarıcı

## Amaç

Uzun toplantı transkriptlerini veya dağınık notları yapılandırılmış özete, karar listesine ve aksiyon planına dönüştürür.

## Kullanım

Kullanıcı şunları sağlamalı:
1. Toplantı transkripti veya notu (metin, PDF, DOCX)
2. (Opsiyonel) Toplantı tarihi ve katılımcı listesi

## Çıktı Formatı

### Toplantı Özeti
- **Tarih**: [Tarih]
- **Katılımcılar**: [İsimler]
- **Süre**: [X dakika]
- **Ana Gündem**: [3-4 madde]

### Alınan Kararlar
1. Karar 1 — gerekçesi
2. Karar 2 — gerekçesi
3. Karar 3 — gerekçesi

### Aksiyon Planı

| # | Aksiyon | Sorumlu | Termin | Öncelik |
|---|---------|---------|--------|---------|
| 1 | ... | ... | ... | Yüksek/Orta/Düşük |
| 2 | ... | ... | ... | ... |

### Açık Konular
- Bir sonraki toplantıda görüşülecek
- Cevaplanmamış sorular

### Tartışma Özetleri (opsiyonel)
- Önemli görüş ayrılıkları
- Risk olarak görülen noktalar

## Önemli Kurallar

- Aksiyon maddelerinde sorumlu kişi belirsizse "?" koy
- Tarih belirtilmemişse "Belirsiz" yaz, varsayım yapma
- Öncelik seviyesini toplantı tonundan çıkar
- Türkçe çıktı üret
