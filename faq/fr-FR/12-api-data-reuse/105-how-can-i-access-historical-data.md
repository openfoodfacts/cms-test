---
title: "Comment puis-je accéder aux données historiques ?"
order: 105
lang: en-gb
category: 12-api-data-réutilisation
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-réutilisation-des-données/' ]
---

Actuellement, nous ne proposons pas l'exportation de données historiques (JSONL, MongoDB, CSV).

Toutefois, pour chaque produit, il est possible d'accéder aux versions précédentes des données produit via l'API ou sur la page produit en utilisant les révisions.

À chaque mise à jour d'un produit, une nouvelle révision (numérotée de 1 à 10) est créée.

Par exemple, pour obtenir la première révision (ou première version du produit) de ce produit, utilisez

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

De même, le paramètre rev peut être utilisé avec l'API :

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
