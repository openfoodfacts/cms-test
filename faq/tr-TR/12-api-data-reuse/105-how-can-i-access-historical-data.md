---
title: "Geçmiş verilere nasıl erişebilirim?"
order: 105
lang: en-gb
category: 12-api-veri-yeniden kullanımı
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-veri-yenidenkullanımı/' ]
---

Şu anda geçmişe ait veri dökümü (JSONL, MongoDB, CSV) hizmeti sunmuyoruz.

Ancak, bireysel ürünler için, API aracılığıyla veya ürün sayfasındaki revizyonlar seçeneğiyle ürün verilerinin önceki sürümlerine erişmek mümkündür.

Bir ürün her güncellendiğinde, yeni bir revizyon (1'den başlayarak artan rakamlı) oluşturulur.

Örneğin, bu ürünün ilk revizyonunu (=ilk ürün sürümünü) almak için şunu kullanın:

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Benzer şekilde, rev parametresi API ile birlikte kullanılabilir:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
