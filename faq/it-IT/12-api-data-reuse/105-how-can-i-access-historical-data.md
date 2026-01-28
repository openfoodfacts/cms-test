---
title: "Come posso accedere ai dati storici?"
order: 105
lang: en-gb
category: 12-api-riutilizzo-dati
breadcrumbs: [ '/it-it/', '/it-it/12-riutilizzo-dati-api/' ]
---

Al momento non offriamo il dump dei dati storici (JSONL, MongoDB, CSV).

Tuttavia, per i singoli prodotti, è possibile accedere alle versioni precedenti dei dati del prodotto tramite l'API o sulla pagina del prodotto tramite le revisioni.

Ogni volta che un prodotto viene aggiornato, viene creata una nuova revisione (cifra crescente a partire da 1).

Ad esempio, per ottenere la prima revisione (=prima versione del prodotto) di questo prodotto, utilizzare

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Allo stesso modo, il parametro rev può essere utilizzato con l'API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
