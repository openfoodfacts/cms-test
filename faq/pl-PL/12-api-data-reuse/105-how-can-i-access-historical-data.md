---
title: "Jak mogę uzyskać dostęp do danych historycznych?"
order: 105
lang: en-gb
category: 12-api-data-reuse
breadcrumbs: [ '/pl-pl/', '/en-gb/12-api-data-reuse/' ]
---

Obecnie nie oferujemy zrzutu danych historycznych (JSONL, MongoDB, CSV).

Jednak w przypadku poszczególnych produktów można uzyskać dostęp do poprzednich wersji danych produktu za pomocą interfejsu API lub na stronie produktu, korzystając z opcji rewizji.

Za każdym razem, gdy produkt jest aktualizowany, tworzona jest nowa rewizja (cyfra rosnąca, począwszy od 1).

Na przykład, aby uzyskać pierwszą rewizję (=pierwszą wersję produktu) tego produktu, użyj

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Podobnie parametr rev można wykorzystać z API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
