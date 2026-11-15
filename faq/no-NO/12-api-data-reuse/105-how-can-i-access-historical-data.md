---
title: "Hvordan kan jeg få tilgang til historiske data?"
order: 105
lang: en-gb
category: 12-api-data-gjenbruk
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

For øyeblikket tilbyr vi ikke historisk datadumping (JSONL, MongoDB, CSV).

For individuelle produkter er det imidlertid mulig å få tilgang til tidligere versjoner av produktdataene ved hjelp av API-et eller på produktsiden ved hjelp av revisjoner.

Hver gang et produkt oppdateres, opprettes en ny revisjon (økende siffer fra 1).

For eksempel, for å få den første revisjonen (=første produktversjon) av dette produktet, bruk

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

På samme måte kan rev-parameteren brukes med API-et:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
