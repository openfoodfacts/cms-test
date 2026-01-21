---
title: "Kiel mi povas aliri historiajn datumojn?"
order: 105
lang: en-gb
category: 12-api-datumoj-reuzo
breadcrumbs: [ '/en-gb/', '/eo-gb/12-api-datumoj-reuzo/' ]
---

Nuntempe ni ne ofertas historiajn datumojn (JSONL, MongoDB, CSV).

Tamen, por individuaj produktoj, eblas aliri antaŭajn versiojn de la produktaj datumoj per la API aŭ sur la produkta paĝo per revizioj.

Ĉiufoje kiam produkto estas ĝisdatigita, nova revizio (kreskanta cifero komencante de 1) estas kreita.

Ekzemple, por akiri la unuan revizion (=unuan produktoversion) de ĉi tiu produkto, uzu

https://world.openfoodfacts.org/product/7623186089763/jogurt-baumnuss-migros?rev=1.

Simile, la parametro `rev` povas esti uzata kun la API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
