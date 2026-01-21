---
title: "Comment puis-je accéder aux données historiques ?"
order: 105
lang: fr-fr
category: 12-donnees-api
breadcrumbs: ['/fr-fr/', '/fr-fr/12-donnees-api/']
---

Actuellement, nous ne proposons pas d'export des données historiques (JSONL, MongoDB, CSV).

Cependant, pour des produits individuels, il est possible d'accéder aux versions précédentes des données du produit à l'aide de l'API ou sur la page du produit à l'aide des révisions.

Chaque fois qu'un produit est mis à jour, une nouvelle révision (chiffre croissant à partir de 1) est créée.

Par exemple, pour obtenir la première révision (=première version du produit) de ce produit, utilisez

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

De même, le paramètre rev peut être utilisé avec l'API :

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
