---
title: "Wéi kann ech op historesch Donnéeën zougräifen."
order: 105
lang: en-gb
category: 12-api-Daten-Wiederverwendung
breadcrumbs: [ '/lb-gb/', '/lb-gb/12-api-data-reuse/' ]
---

Aktuell bidden mir keen Dump vun historeschen Daten (JSONL, MongoDB, CSV) un.

Wéi och ëmmer, fir eenzel Produkter ass et méiglech, op fréier Versioune vun de Produktdaten iwwer d'API oder op der Produktsäit mat Hëllef vu Revisiounen zouzegräifen.

All Kéier wann e Produkt aktualiséiert gëtt, gëtt eng nei Revisioun (mat enger zouhuelender Ziffer vun 1) erstallt.

Zum Beispill, fir déi éischt Revisioun (=éischt Produktversioun) vun dësem Produkt ze kréien, benotzt

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Ähnlech kann de rev-Parameter mat der API benotzt ginn:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
