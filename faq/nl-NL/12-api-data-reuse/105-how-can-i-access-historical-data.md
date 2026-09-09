---
title: "Hoe krijg ik toegang tot historische gegevens?"
order: 105
lang: en-gb
category: 12-api-data-reuse
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

Momenteel bieden we geen export van historische gegevens aan (JSONL, MongoDB, CSV).

Voor individuele producten is het echter mogelijk om eerdere versies van de productgegevens te raadplegen via de API of op de productpagina via revisies.

Telkens wanneer een product wordt bijgewerkt, wordt een nieuwe revisie (oplopend cijfer beginnend bij 1) aangemaakt.

Om bijvoorbeeld de eerste revisie (=eerste productversie) van dit product te verkrijgen, gebruikt u...

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Op dezelfde manier kan de parameter 'rev' met de API worden gebruikt:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
