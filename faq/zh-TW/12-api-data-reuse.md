---
title: "{{< fa wrench size=2x >}} API 與資料重用"
description: "6個問題"
lang: 英語-英國
order: 12
category-level: 0
icon: 扳手
---

{{< fa "扳手" size=3倍 >}}

## 文件中是否有關於上傳照片合適尺寸的建議？

這可能取決於各國的網路速度是否慢或費用是否昂貴。 寬度或高度超過 5000 像素的任何物體可能都不太實用。 如果你能偵測到網路速度慢，那麼即使是 2000 像素的圖像也很好（當然比沒有圖像要好得多！）

---

## 如果沒有條碼，食品會怎麼樣？

Open Food Facts 僅包含包裝食品的相關資訊。 對於農產品（例如番茄或香蕉）和其他食品的平均值，您可以使用官方的國家營養資料庫之一。

**註：** 以下列表包含一些最重要的國家食品資料庫。 如果您認為應該將其他資料庫新增至清單中，請透過以下方式與我們聯絡：[https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**國家食品資料庫清單**

-

**Australia** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**比利時** - NUBEL - 比利時食品成分資料：[https://www.internubel.be](https://www.internubel.be/)

-

**加拿大** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**捷克共和國** - 美國國家公共衛生研究所食品成分資料庫：[http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**丹麥** - 丹麥食品成分資料庫：[https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**愛沙尼亞** - 愛沙尼亞食品成分資料庫：[https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**芬蘭** - 芬蘭食品成分資料庫 - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**法國** - CIQUAL：[https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**德國** - Souci-Fachmann-Kraut 線上資料庫：[https://www.sfk.online/#/home](https://www.sfk.online/#/home) 或官方德國資料庫：Bundeslebensmittelschlüssel：[https://blsdb.de/](https://blsdb.de/)

- **義大利** - Banca Dati di Composizione degli Alimenti CREA：[https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**荷蘭** - 荷蘭食物成分資料庫：[https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**挪威** - 2006 年挪威食品成分錶：[https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**波蘭** - 食物成分錶：[http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**西班牙** - 西班牙食品成分資料庫 - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**瑞士** - 瑞士食品成分資料庫：[https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

英國 - 食品成分綜合資料集 (CoFID)：[https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**美國** - 美國農業部：[https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## 我可以透過 API 搜尋精確的產品名稱嗎？

遺憾的是，目前還無法透過 API 輕鬆地僅按產品名稱進行精確搜尋。

使用類別篩選器或許能幫助你更精確地進行搜尋。

---

## 我如何取得/收集項目所需的資料？

在 Open Food Facts 的主頁上，螢幕左上角有一個滾動選單。 在頁面底部，你會找到「進階搜尋」選項，點擊即可。 接下來，您需要自行確定哪些標準與您的專案最相關。 選擇完成後，您可以透過向下捲動到頁面底部並點擊「下載結果」來下載所獲得的結果。

您也可以參考：

- 我們的 API 文件：[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Open Food Facts 的使用條款：[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- 根據我們的資料：[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## 使用 API 有什麼條件嗎？

所有關於 API 使用的文件都可以在[API 文件頁](https://openfoodfacts.github.io/openfoodfacts-server/api/)上找到，但這裡有一個簡要概述：

- Open Food Facts 資料庫根據開放資料庫許可證 (ODbL) 作為開放資料提供，有關法律詳情，請參閱 [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)。 這兩個條件是歸屬和相同方式共享。 如果將 Open Food Facts 的資料與其他資料庫的資料結合起來，那麼 ODbL 要求產生的資料庫也必須作為開放資料發布。 這也意味著，你只能將數據與允許此類重新分發的來源結合。

- 在執行 API 呼叫時，必須**始終**使用自訂 User-Agent 來識別您的應用程式。

- 每個 API 端點都強制執行速率限制。

---

## 如何取得歷史數據？

目前，我們不提供歷史資料轉儲（JSONL、MongoDB、CSV）。

但是，對於單一產品，可以使用 API 或在產品頁面上使用修訂版本來存取產品資料的先前版本。

每次產品更新時，都會建立一個新的版本（數字從 1 開始遞增）。

例如，要取得該產品的第一個修訂版本（=第一個產品版本），請使用

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

同樣，rev 參數也可以與 API 一起使用：

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

