---
title: "Quomodo ad notitias historicas accedere possum?"
order: 105
lang: en-gb
category: 12-api-data-reuse
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

In praesenti, collectionem datorum historicorum (JSONL, MongoDB, CSV) non offerimus.

Attamen, pro singulis productis, versiones priores datorum producti per API vel in pagina producti per revisiones accedere licet.

Quotiescumque productum renovatur, nova recensio (digito crescente ab 1 incipiens) creatur.

Exempli gratia, ad primam revisionem (=primam versionem producti) huius producti obtinendam, utere

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Similiter, parametrus `rev` cum API adhiberi potest:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
