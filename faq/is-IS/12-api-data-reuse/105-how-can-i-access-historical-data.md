---
title: "Hvernig get ég nálgast söguleg gögn?"
order: 105
lang: en-gb
category: 12-api-gagnaendurnotkun
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-gagna-endurnýting/' ]
---

Eins og er bjóðum við ekki upp á að safna sögulegum gögnum (JSONL, MongoDB, CSV).

Hins vegar er hægt að fá aðgang að fyrri útgáfum af vörugögnunum fyrir einstakar vörur með því að nota API-viðmótið eða á vörusíðunni með því að nota endurskoðanir.

Í hvert skipti sem vara er uppfærð er ný útgáfa (hækkandi tölustafur frá og með 1) búin til.

Til dæmis, til að fá fyrstu útgáfuna (=fyrsta vöruútgáfuna) af þessari vöru, notaðu

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Á sama hátt er hægt að nota rev breytuna með API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
