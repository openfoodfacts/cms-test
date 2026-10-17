---
title: "Paano ko maa-access ang mga dating datos?"
order: 105
lang: en-gb
category: 12-api-muling-paggamit-ng-datos
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-muling paggamit/' ]
---

Sa kasalukuyan, hindi kami nag-aalok ng historical data dump (JSONL, MongoDB, CSV).

Gayunpaman, para sa mga indibidwal na produkto, posibleng ma-access ang mga nakaraang bersyon ng data ng produkto gamit ang API o sa pahina ng produkto gamit ang mga rebisyon.

Sa bawat oras na ina-update ang isang produkto, isang bagong rebisyon (pataas na digit simula sa 1) ang nalilikha.

Halimbawa, para makuha ang unang rebisyon (=unang bersyon ng produkto) ng produktong ito, gamitin ang

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Katulad nito, maaaring gamitin ang rev parameter kasama ng API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
