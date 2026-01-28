---
title: "Hvordan får jeg tilgang til historiske data?"
order: 105
lang: no-no
category: 12-api-data-gjenbruk
breadcrumbs: [ '/radgiver/', '/no/nb/12-api-data/' ]
---

Vi tilbyr for tiden ikke historiske data dump (JSONL, MongoDB, CSV).

For enkeltprodukter er det imidlertid mulig å få tilgang til tidligere versjoner av produktdataene ved hjelp av API eller produktsiden ved hjelp av versjoner.

Hver gang et produkt oppdateres, blir en ny revisjon (øker siffer fra 1) opprettet.

For eksempel, for å få den første revisjonen (=første produktversjon) av dette produktet, bruk

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

På samme måte kan rev parameteren brukes med API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
