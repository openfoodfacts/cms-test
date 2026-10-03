---
title: "Hur kan jag få tillgång till historisk data?"
order: 105
lang: sv-gb
category: 12-api-data-återanvändning
breadcrumbs: [ '/sv-gb/', '/sv-gb/12-api-data-återanvändning/' ]
---

För närvarande erbjuder vi inte historisk datadumpning (JSONL, MongoDB, CSV).

För enskilda produkter är det dock möjligt att komma åt tidigare versioner av produktdata med hjälp av API:et eller på produktsidan med hjälp av revisioner.

Varje gång en produkt uppdateras skapas en ny revision (ökande siffra från 1).

För att till exempel hämta den första revisionen (=första produktversionen) av den här produkten, använd

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

På liknande sätt kan parametern rev användas med API:et:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
