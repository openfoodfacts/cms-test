---
title: "Cossí pòdi accedir a de donadas istoricas?"
order: 105
lang: es-gb
category: 12-api-reutilizacion de donadas
breadcrumbs: [ '/es-gb/', '/oc-gb/12-api-data-reuse/' ]
---

Actualament, ofrissèm pas de dump de donadas istoricas (JSONL, MongoDB, CSV).

Pasmens, pels produches individuals, es possible d'accedir a de versions precedentas de las donadas del produch en utilizant l'API o sus la pagina del produch en utilizant de revisions.

Cada còp qu'un produch es mes a jorn, una novèla revision (chifra creissenta a partir de 1) es creada.

Per exemple, per obténer la primièra revision (=version de primièr produch) d'aqueste produch, utilizatz

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

De manièra similara, lo paramètre rev pòt èsser utilizat amb l'API :

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
