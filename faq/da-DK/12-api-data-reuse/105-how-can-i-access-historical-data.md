---
title: "Hvordan kan jeg få adgang til historiske data?"
order: 105
lang: en-gb
category: 12-api-data-genbrug
breadcrumbs: [ '/da-gb/', '/da-gb/12-api-data-genbrug/' ]
---

Vi tilbyder i øjeblikket ikke historisk datadump (JSONL, MongoDB, CSV).

For individuelle produkter er det dog muligt at få adgang til tidligere versioner af produktdataene ved hjælp af API'en eller på produktsiden ved hjælp af revisioner.

Hver gang et produkt opdateres, oprettes en ny revision (stigende ciffer startende fra 1).

For eksempel, for at få den første revision (=første produktversion) af dette produkt, skal du bruge

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

På samme måde kan rev-parameteren bruges med API'en:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
