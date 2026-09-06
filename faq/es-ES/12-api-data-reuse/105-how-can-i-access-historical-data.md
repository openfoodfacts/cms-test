---
title: "¿Cómo puedo acceder a los datos históricos?"
order: 105
lang: es-gb
category: 12-api-reutilización-de-datos
breadcrumbs: [ '/es-gb/', '/es-gb/12-api-reutilización-de-datos/' ]
---

Actualmente, no ofrecemos volcado de datos históricos (JSONL, MongoDB, CSV).

Sin embargo, para productos individuales, es posible acceder a versiones anteriores de los datos del producto utilizando la API o en la página del producto utilizando revisiones.

Cada vez que se actualiza un producto, se crea una nueva revisión (dígito creciente a partir de 1).

Por ejemplo, para obtener la primera revisión (=primera versión del producto) de este producto, utilice

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

De manera similar, el parámetro rev se puede utilizar con la API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
