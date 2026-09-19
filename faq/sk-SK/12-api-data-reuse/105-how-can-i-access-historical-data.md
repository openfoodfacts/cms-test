---
title: "Ako môžem získať prístup k historickým údajom?"
order: 105
lang: en-gb
category: 12-api-data-reuse
breadcrumbs: [ '/sk-sk/', '/sk-sk/opätovné-použitie-dát-12-api/' ]
---

Momentálne neponúkame výpis historických dát (JSONL, MongoDB, CSV).

V prípade jednotlivých produktov je však možné získať prístup k predchádzajúcim verziám údajov o produkte pomocou rozhrania API alebo na stránke produktu pomocou revízií.

Pri každej aktualizácii produktu sa vytvorí nová revízia (rastúca číslica od 1).

Napríklad, ak chcete získať prvú revíziu (=prvú verziu produktu) tohto produktu, použite

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Podobne možno parameter rev použiť s rozhraním API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
