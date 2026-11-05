---
title: "Cumu possu accede à i dati storichi?"
order: 105
lang: en-gb
category: 12-api-data-reuse
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

Attualmente, ùn offremu micca dump di dati storichi (JSONL, MongoDB, CSV).

Tuttavia, per i prudutti individuali, hè pussibule accede à e versioni precedenti di i dati di u pruduttu aduprendu l'API o nantu à a pagina di u pruduttu aduprendu revisioni.

Ogni volta chì un pruduttu hè aggiornatu, una nova revisione (cifra crescente à partesi da 1) hè creata.

Per esempiu, per ottene a prima revisione (= prima versione di u pruduttu) di stu pruduttu, aduprate

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

In listessu modu, u parametru rev pò esse adupratu cù l'API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
