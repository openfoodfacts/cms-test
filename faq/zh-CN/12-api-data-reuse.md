---
title: "{{< fa wrench size=2x >}} API 和数据重用"
description: "6个问题"
lang: 英语-英国
order: 12
category-level: 0
icon: 扳手
---

{{< fa "扳手" size=3倍 >}}

## 文档中是否有关于上传照片合适尺寸的建议？

这可能取决于各国的网络速度是否慢或费用是否昂贵。 宽度或高度超过 5000 像素的任何物体可能都不太实用。 如果你能检测到网络速度慢，那么即使是 2000 像素的图像也很好（当然比没有图像要好得多！）

---

## 如果没有条形码，食品会怎么样？

Open Food Facts 仅包含包装食品的相关信息。 对于农产品（例如西红柿或香蕉）和其他食品的平均值，您可以使用官方的国家营养数据库之一。

**注：** 以下列表包含一些最重要的国家食品数据库。 如果您认为应该将其他数据库添加到列表中，请通过以下方式联系我们：[https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**国家食品数据库列表**

-

**澳大利亚** - FSANZ - NUTTAB 2006：[https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**比利时** - NUBEL - 比利时食品成分数据：[https://www.internubel.be](https://www.internubel.be/)

-

**加拿大** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**捷克共和国** - 国家公共卫生研究所食品成分数据库：[http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**丹麦** - 丹麦食品成分数据库：[https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**爱沙尼亚** - 爱沙尼亚食品成分数据库：[https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**芬兰** - 芬兰食品成分数据库 - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**法国** - CIQUAL：[https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**德国** - Souci-Fachmann-Kraut 在线数据库：[https://www.sfk.online/#/home](https://www.sfk.online/#/home) 或官方德国数据库：Bundeslebensmittelschlüssel：[https://blsdb.de/](https://blsdb.de/)

- **意大利** - Banca Dati di Composizione degli Alimenti CREA：[https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**荷兰** - 荷兰食物成分数据库：[https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**挪威** - 2006 年挪威食品成分表：[https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**波兰** - 食物成分表：[http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**西班牙** - 西班牙食品成分数据库 - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**瑞士** - 瑞士食品成分数据库：[https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

英国 - 食品成分综合数据集 (CoFID)：[https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**美国** - 美国农业部：[https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## 我可以通过 API 搜索精确的产品名称吗？

遗憾的是，目前还无法通过 API 轻松地仅按产品名称进行精确搜索。

使用类别筛选器或许能帮助你更精确地进行搜索。

---

## 我如何获取/收集项目所需的数据？

在 Open Food Facts 的主页上，屏幕左上角有一个滚动菜单。 在页面底部，你会找到“高级搜索”选项，点击即可。 接下来，您需要自行确定哪些标准与您的项目最相关。 选择完成后，您可以通过向下滚动到页面底部并点击“下载结果”来下载获得的结果。

您还可以参考：

- 我们的 API 文档：[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Open Food Facts 的使用条款：[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- 根据我们的数据：[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## 使用 API 有什么条件吗？

所有关于 API 使用的文档都可以在[API 文档页面](https://openfoodfacts.github.io/openfoodfacts-server/api/)上找到，但这里是一个简要概述：

- Open Food Facts 数据库根据开放数据库许可证 (ODbL) 作为开放数据提供，有关法律详情，请参阅 [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)。 这两个条件是归属和相同方式共享。 如果将 Open Food Facts 的数据与其他数据库的数据结合起来，那么 ODbL 要求生成的数据库也必须作为开放数据发布。 这也意味着，你只能将数据与允许此类重新分发的来源结合起来。

- 在执行 API 调用时，必须**始终**使用自定义 User-Agent 来识别您的应用程序。

- 每个 API 端点都强制执行速率限制。

---

## 如何获取历史数据？

目前，我们不提供历史数据转储（JSONL、MongoDB、CSV）。

但是，对于单个产品，可以使用 API 或在产品页面上使用修订版本来访问产品数据的先前版本。

每次产品更新时，都会创建一个新的版本（数字从 1 开始递增）。

例如，要获取该产品的第一个修订版本（=第一个产品版本），请使用

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

同样，rev 参数也可以与 API 一起使用：

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

