---
title: "履歴データにアクセスするにはどうすればいいですか?"
order: 105
lang: en-gb
category: 12-API-データ再利用
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-データ再利用/' ]
---

現在、履歴データ ダンプ (JSONL、MongoDB、CSV) は提供していません。

ただし、個々の製品については、API を使用するか、製品ページのリビジョンを使用して、以前のバージョンの製品データにアクセスすることが可能です。

製品が更新されるたびに、新しいリビジョン (1 から始まる数字が増加) が作成されます。

例えば、この製品の最初のリビジョン（最初の製品バージョン）を取得するには、

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

同様に、 rev パラメータを API で使用できます。

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
