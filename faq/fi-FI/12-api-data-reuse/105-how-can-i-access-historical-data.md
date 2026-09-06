---
title: "Miten voin käyttää historiatietoja?"
order: 105
lang: fi-gb
category: 12-api-datan-uudelleenkäyttö
breadcrumbs: [ '/fi-fi/', '/fi-fi/12-api-datan-uudelleenkäyttö/' ]
---

Tällä hetkellä emme tarjoa historiatietojen tallentamista (JSONL, MongoDB, CSV).

Yksittäisten tuotteiden osalta on kuitenkin mahdollista käyttää tuotetietojen aiempia versioita API:n kautta tai tuotesivulla revisioiden avulla.

Joka kerta, kun tuotetta päivitetään, luodaan uusi versio (kasvava numero alkaen 1:stä).

Esimerkiksi saadaksesi tämän tuotteen ensimmäisen revision (=ensimmäisen tuoteversion), käytä

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Samoin rev-parametria voidaan käyttää API:n kanssa:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
