---
title: "Tarixi məlumatlara necə daxil ola bilərəm?"
order: 105
lang: en-gb
category: 12-api-məlumatların-təkrar-istifadəsi
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

Hazırda tarixi məlumatların (JSONL, MongoDB, CSV) silinməsi təklif etmirik.

Lakin, fərdi məhsullar üçün məhsul məlumatlarının əvvəlki versiyalarına API istifadə edərək və ya məhsul səhifəsində düzəlişlərdən istifadə edərək daxil olmaq mümkündür.

Hər dəfə bir məhsul yeniləndikdə, yeni bir düzəliş (1-dən başlayaraq artan rəqəm) yaradılır.

Məsələn, bu məhsulun ilk versiyasını (=ilk məhsul versiyasını) əldə etmək üçün istifadə edin

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Eynilə, rev parametri API ilə istifadə edilə bilər:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
