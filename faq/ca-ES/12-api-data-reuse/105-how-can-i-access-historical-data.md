---
title: "Com puc accedir a dades històriques?"
order: 105
lang: en-gb
category: 12-api-data-reuse
breadcrumbs: [ '/en-gb/', '/ca-gb/reutilització-de-dades-12-api/' ]
---

Actualment, no oferim abocaments de dades històriques (JSONL, MongoDB, CSV).

Tanmateix, per a productes individuals, és possible accedir a versions anteriors de les dades del producte mitjançant l'API o a la pàgina del producte mitjançant revisions.

Cada vegada que s'actualitza un producte, es crea una nova revisió (dígit creixent a partir d'1).

Per exemple, per obtenir la primera revisió (=primera versió del producte) d'aquest producte, feu servir

https://world.openfoodfacts.org/product/7623186089763/jogurt-baumnuss-migros?rev=1.

De la mateixa manera, el paràmetre rev es pot utilitzar amb l'API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
