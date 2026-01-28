---
title: "과거 데이터에 어떻게 접근할 수 있나요?"
order: 105
lang: 영어-영국
category: 12-api-data-reuse
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

현재 저희는 과거 데이터 덤프(JSONL, MongoDB, CSV)를 제공하지 않습니다.

하지만 개별 제품의 경우 API를 사용하거나 제품 페이지에서 수정 내역을 통해 이전 버전의 제품 데이터에 접근할 수 있습니다.

제품이 업데이트될 때마다 새로운 버전(1부터 시작하여 숫자가 증가하는 버전)이 생성됩니다.

예를 들어, 이 제품의 첫 번째 수정 버전(첫 번째 제품 버전)을 얻으려면 다음을 사용하십시오.

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

마찬가지로 rev 매개변수는 API와 함께 사용할 수 있습니다.

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
