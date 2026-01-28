---
title: "{{< fa brands github size=2x >}} Teknik SSS"
description: "1 soru"
lang: en-gb
order: 16
category-level: 0
icon: markalar github
---

{{< fa "markalar" "github" size=3x >}}

## Kaynak metni değiştirdiğimde tüm dil dosyalarını güncellemem gerekir mi?

Hayır, gerek yok. Sadece İngilizce olanı güncellemeniz gerekiyor.

- PR'ınızı oluşturun

Birleştirme işlemi tamamlandıktan sonra, crowdin-trigger'ı manuel olarak yeniden temel alacağız ve GitHub Actions tarafından tetiklenen Crowdin çeviri sistemi diğer diller için gerisini halledecek.

GitHub botu daha sonra otomatik olarak yeni bir çekme isteği (PR) oluşturur ve biz de bunu inceleriz.

---

