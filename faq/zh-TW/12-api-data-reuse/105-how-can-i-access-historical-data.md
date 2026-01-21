---
title: "如何取得歷史數據？"
order: 105
lang: 英語-英國
category: 12-api-資料重用
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

目前，我們不提供歷史資料轉儲（JSONL、MongoDB、CSV）。

但是，對於單一產品，可以使用 API 或在產品頁面上使用修訂版本來存取產品資料的先前版本。

每次產品更新時，都會建立一個新的版本（數字從 1 開始遞增）。

例如，要取得該產品的第一個修訂版本（=第一個產品版本），請使用

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

同樣，rev 參數也可以與 API 一起使用：

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
