---
title: "Jak mohu získat přístup k historickým datům?"
order: 105
lang: en-gb
category: 12-api-data-reuse
breadcrumbs: [ '/cs-gb/', '/cs-gb/12-api-data-reuse/' ]
---

V současné době nenabízíme výpis historických dat (JSONL, MongoDB, CSV).

U jednotlivých produktů je však možné přistupovat k předchozím verzím produktových dat pomocí API nebo na stránce produktu pomocí revizí.

Pokaždé, když je produkt aktualizován, vytvoří se nová revize (zvyšující se číslice od 1).

Například pro získání první revize (=první verze produktu) tohoto produktu použijte

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Podobně lze parametr rev použít s API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
