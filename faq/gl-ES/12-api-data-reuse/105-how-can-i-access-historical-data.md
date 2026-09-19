---
title: "Como podo acceder a datos históricos?"
order: 105
lang: en-gb
category: reutilización de datos de 12 API
breadcrumbs: [ '/gl-gb/', '/gl-gb/reutilización-de-datos-de-12-api/' ]
---

Actualmente, non ofrecemos volcado de datos históricos (JSONL, MongoDB, CSV).

Non obstante, para produtos individuais, é posible acceder a versións anteriores dos datos do produto mediante a API ou na páxina do produto mediante revisións.

Cada vez que se actualiza un produto, créase unha nova revisión (díxito crecente a partir de 1).

Por exemplo, para obter a primeira revisión (=primeira versión do produto) deste produto, use

https://world.openfoodfacts.org/product/7623186089763/jogurt-baumnuss-migros?rev=1.

Do mesmo xeito, o parámetro rev pódese usar coa API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
