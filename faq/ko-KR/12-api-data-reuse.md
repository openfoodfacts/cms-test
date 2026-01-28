---
title: "{{< fa wrench size=2x >}} API 및 데이터 재사용"
description: "6개의 질문"
lang: 영어-영국
order: 12
category-level: 0
icon: 렌치
---

{{< fa "렌치" size=3배 >}}

## 업로드할 사진의 적절한 크기에 대한 권장 사항이 문서 어디에 있나요?

네트워크 속도가 느리거나 비용이 많이 드는지 여부에 따라 국가별로 다를 수 있습니다. 두께나 높이가 5000픽셀을 넘는 것은 그다지 유용하지 않을 가능성이 높습니다. 만약 네트워크 속도가 느리다는 것을 어떻게든 감지할 수 있다면, 2000픽셀 정도의 이미지라도 있으면 아주 좋을 겁니다 (이미지가 아예 없는 것보다는 훨씬 낫겠죠!).

---

## 바코드가 없는 식품은 어떻게 되나요?

Open Food Facts는 포장 식품에 대한 정보만 제공합니다. 농산물(예: 토마토 또는 바나나) 및 기타 식품의 평균 영양 성분 값은 국가 공식 영양 데이터베이스를 이용할 수 있습니다.

**참고:** 아래 목록에는 가장 중요한 국가별 식품 데이터베이스 중 일부가 포함되어 있습니다. 목록에 포함되어야 할 다른 데이터베이스가 있다고 생각하시면 다음 주소로 문의해 주세요: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**국가별 식품 데이터베이스 목록**

-

**호주** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**벨기에** - NUBEL - 벨기에 식품 성분 데이터: [https://www.internubel.be](https://www.internubel.be/)

-

**캐나다** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**체코 공화국** - 국립 공중보건연구소 식품 성분 데이터베이스: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**덴마크** - 덴마크 식품 성분 데이터베이스: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**에스토니아** - 에스토니아 식품 성분 데이터베이스: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**핀란드** - 핀란드 식품 성분 데이터베이스 - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**프랑스** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**독일** - Souci-Fachmann-Kraut 온라인 데이터베이스: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) 또는 공식 독일 데이터베이스: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **이탈리아** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**네덜란드** - 네덜란드 식품 성분 데이터베이스: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**노르웨이** - 2006년 노르웨이 식품 성분표: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**폴란드** - 식품 성분표: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**스페인** - 스페인 식품 성분 데이터베이스 - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**스위스** - 스위스 식품 성분 데이터베이스: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**영국** - 식품 성분 통합 데이터 세트(CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**미국** - USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## API를 이용해 정확한 제품명으로 검색할 수 있나요?

아쉽게도 현재로서는 API를 통해 제품명만으로 정확하게 검색하는 것은 불가능합니다.

카테고리 필터를 사용하면 검색 범위를 좁히는 데 도움이 될 수 있습니다.

---

## 프로젝트에 필요한 데이터를 어떻게 수집/접근할 수 있나요?

Open Food Facts 메인 페이지의 왼쪽 상단에는 스크롤 가능한 메뉴가 있습니다. 맨 아래쪽에 "고급 검색" 옵션이 있는데, 그걸 클릭하시면 됩니다. 그다음은 여러분의 프로젝트에 가장 적합한 기준이 무엇인지 판단하는 것입니다. 선택이 완료되면 페이지 하단으로 스크롤하여 "결과 다운로드"를 클릭하면 얻은 결과를 다운로드할 수 있습니다.

다음 자료도 참고하실 수 있습니다.

- 저희 API 문서는 여기에서 확인하실 수 있습니다: [ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Open Food Facts 이용 약관:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- 저희 데이터에 따르면:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## API를 사용하기 위한 조건이 있나요?

API 사용에 관한 모든 문서는 [API 문서 페이지](https://openfoodfacts.github.io/openfoodfacts-server/api/)에서 찾을 수 있지만, 간단히 요약하면 다음과 같습니다.

- Open Food Facts 데이터베이스는 Open Database License(ODbL)에 따라 오픈 데이터로 제공됩니다. 법적 세부 사항은 [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)를 참조하십시오. 두 가지 조건은 저작자 표시와 동일 조건 공유입니다. Open Food Facts의 데이터를 다른 데이터베이스와 결합하는 경우, ODbL(Open Data Base License)에 따라 결과 데이터베이스 또한 오픈 데이터로 공개되어야 합니다. 또한, 그러한 재배포를 허용하는 소스의 데이터와만 결합할 수 있다는 의미이기도 합니다.

- API 호출 시 앱을 식별하려면 **반드시** 사용자 지정 User-Agent를 사용해야 합니다.

- 각 API 엔드포인트에 대해 속도 제한이 적용됩니다.

---

## 과거 데이터에 어떻게 접근할 수 있나요?

현재 저희는 과거 데이터 덤프(JSONL, MongoDB, CSV)를 제공하지 않습니다.

하지만 개별 제품의 경우 API를 사용하거나 제품 페이지에서 수정 내역을 통해 이전 버전의 제품 데이터에 접근할 수 있습니다.

제품이 업데이트될 때마다 새로운 버전(1부터 시작하여 숫자가 증가하는 버전)이 생성됩니다.

예를 들어, 이 제품의 첫 번째 수정 버전(첫 번째 제품 버전)을 얻으려면 다음을 사용하십시오.

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

마찬가지로 rev 매개변수는 API와 함께 사용할 수 있습니다.

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

