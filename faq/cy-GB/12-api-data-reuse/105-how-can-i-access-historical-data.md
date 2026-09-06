---
title: "Sut alla i gael mynediad at ddata hanesyddol?"
order: 105
lang: en-gb
category: ailddefnyddio-data-12-api
breadcrumbs: [ '/cy-gb/', '/cy-gb/12-api-data-ailddefnyddio/' ]
---

Ar hyn o bryd, nid ydym yn cynnig dymp data hanesyddol (JSONL, MongoDB, CSV).

Fodd bynnag, ar gyfer cynhyrchion unigol, mae'n bosibl cael mynediad at fersiynau blaenorol o ddata'r cynnyrch gan ddefnyddio'r API neu ar dudalen y cynnyrch gan ddefnyddio diwygiadau.

Bob tro y caiff cynnyrch ei ddiweddaru, crëir diwygiad newydd (digid cynyddol gan ddechrau o 1).

Er enghraifft, i gael y diwygiad cyntaf (=fersiwn cynnyrch cyntaf) o'r cynnyrch hwn, defnyddiwch

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Yn yr un modd, gellir defnyddio'r paramedr rev gyda'r API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
