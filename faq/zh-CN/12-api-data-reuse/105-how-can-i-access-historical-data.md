---
title: "如何获取历史数据？"
order: 105
lang: 英语-英国
category: 12-api-数据重用
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

目前，我们不提供历史数据转储（JSONL、MongoDB、CSV）。

但是，对于单个产品，可以使用 API 或在产品页面上使用修订版本来访问产品数据的先前版本。

每次产品更新时，都会创建一个新的版本（数字从 1 开始递增）。

例如，要获取该产品的第一个修订版本（=第一个产品版本），请使用

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

同样，rev 参数也可以与 API 一起使用：

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
