---
title: "How can I access historical data?"
order: 105
lang: en-gb
category: 12-api-data-reuse
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

Currently, we don't offer historical data dump (JSONL, MongoDB, CSV).

However, for individual products, it's possible to access previous versions of the product data using the API or on the product page using revisions.

Every time a product is updated, a new revision (increasing digit starting from 1) is created.

For example, to get the first revision (=first product version) of this product, use

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Similarly, the rev parameter can be used with the API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
