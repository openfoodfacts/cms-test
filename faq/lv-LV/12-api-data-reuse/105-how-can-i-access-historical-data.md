---
title: "Kā es varu piekļūt vēsturiskajiem datiem?"
order: 105
lang: lv-lv
category: 12-API-datu-atkārtota-izmantošana
breadcrumbs: [ '/lv-lv/', '/lv-lv/12-api-datu-atkārtota-izmantošana/' ]
---

Pašlaik mēs nepiedāvājam vēsturisko datu izgāztuvi (JSONL, MongoDB, CSV).

Tomēr atsevišķiem produktiem ir iespējams piekļūt iepriekšējām produktu datu versijām, izmantojot API vai produkta lapā, izmantojot pārskatītās versijas.

Katru reizi, kad produkts tiek atjaunināts, tiek izveidota jauna versija (palielinošs cipars, sākot no 1).

Piemēram, lai iegūtu šī produkta pirmo pārskatīšanu (=pirmo produkta versiju), izmantojiet

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Līdzīgi parametru rev var izmantot ar API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
