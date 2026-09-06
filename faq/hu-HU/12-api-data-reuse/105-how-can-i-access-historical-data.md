---
title: "Hogyan férhetek hozzá a korábbi adatokhoz?"
order: 105
lang: hu-gb
category: 12-api-adatok-újrafelhasználása
breadcrumbs: [ '/hu-hu/', '/hu-hu/12-api-adatok-újrafelhasználása/' ]
---

Jelenleg nem kínálunk historikus adatkiírást (JSONL, MongoDB, CSV).

Azonban az egyes termékek esetében a termékadatok korábbi verzióihoz az API-n vagy a termékoldalon a revíziók segítségével lehet hozzáférni.

Minden alkalommal, amikor egy termék frissül, új verzió jön létre (1-től növekvő számjeggyel).

Például a termék első verziójának (=első termékverzió) lekéréséhez használja a következőt:

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Hasonlóképpen, a rev paraméter használható az API-val:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
