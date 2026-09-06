---
title: "Kaynak metni değiştirdiğimde tüm dil dosyalarını güncellemem gerekir mi?"
order: 59
lang: en-gb
category: 16-teknik-sıkça sorulan sorular
breadcrumbs: [ '/en-gb/', '/en-gb/16-teknik-sıkça sorulan sorular/' ]
---

Hayır, gerek yok. Sadece İngilizce olanı güncellemeniz gerekiyor.

- PR'ınızı oluşturun

Birleştirme işlemi tamamlandıktan sonra, crowdin-trigger'ı manuel olarak yeniden temel alacağız ve GitHub Actions tarafından tetiklenen Crowdin çeviri sistemi diğer diller için gerisini halledecek.

GitHub botu daha sonra otomatik olarak yeni bir çekme isteği (PR) oluşturur ve biz de bunu inceleriz.
