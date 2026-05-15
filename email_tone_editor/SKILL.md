---
name: email_tone_editor
description: Verilen e-posta taslağını veya mesajı 3 farklı tonda (nazik, kararlı, resmi) yeniden yazan skill. Hassas e-postalar göndermeden önce farklı yaklaşımları karşılaştırmak isteyen kullanıcılar için. Kullanıcı bir e-posta taslağı paylaştığında veya "bunu daha kibar/sert/resmi yaz" istediğinde tetiklenir.
---

# E-posta Tonu Düzenleyici

## Amaç

Aynı mesajı 3 farklı tonda yazarak kullanıcının duruma en uygun olanı seçmesini sağlar.

## Kullanım

Kullanıcı şunları sağlamalı:
1. E-posta taslağı veya iletmek istediği mesajın özü
2. (Opsiyonel) Alıcı ile ilişki bilgisi (yönetici, müşteri, iş ortağı)
3. (Opsiyonel) Bağlam (gecikme, şikayet, talep, vb.)

## Çıktı Formatı

### Versiyon 1: Nazik / Yumuşak Ton
- Empati ile başlar
- Soft language kullanır
- Çözüm odaklı kapanış

[E-posta metni]

### Versiyon 2: Kararlı / Profesyonel Ton
- Doğrudan ifade
- Net beklenti ortaya koyar
- Zaman çizelgesi içerir

[E-posta metni]

### Versiyon 3: Resmi / Mesafeli Ton
- Formal hitap
- Yasal/kurumsal dilde
- Yazışma kayıt değeri olan üslupta

[E-posta metni]

### Tavsiye
Her versiyonun ne zaman uygun olduğuna dair 1-2 cümlelik öneri.

## Önemli Kurallar

- Mesajın özünü ve isteklerini değiştirme
- Sadece tonu değiştir
- Konu satırı da her versiyon için ayrı önerilebilir
- Türkçe e-posta için Türkçe çıktı, İngilizce için İngilizce
- Patronizing dilden ("size yardımcı olmaya çalışacağım" gibi) kaçın
