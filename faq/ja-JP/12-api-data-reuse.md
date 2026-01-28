---
title: "{{< fa wrench size=2x >}} APIとデータの再利用"
description: "6つの質問"
lang: en-gb
order: 12
category-level: 0
icon: レンチ
---

{{< fa "レンチ" size=3倍 >}}

## アップロードする写真の適切なサイズに関する推奨事項はドキュメントのどこかに記載されていますか?

ネットワークが遅いか高価かは国によって異なる可能性があります。 幅または高さが 5000 ピクセルを超えるものは、おそらくあまり役に立ちません。 そして、ネットワークが遅いことを何らかの方法で検出できる場合は、2000 ピクセルの画像でも十分です (画像がないよりは間違いなく優れています!)

---

## バーコードのない食品はどうなりますか？

Open Food Facts には、パッケージ化された食品に関する情報のみが含まれています。 農産物（トマトやバナナなど）やその他の食品の平均値については、代わりに公式の国家栄養データベースのいずれかを使用できます。

**注:** 以下のリストには、最も重要な国の食品データベースがいくつか含まれています。 他のデータベースをリストに含めるべきだと思う場合は、[https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact) までご連絡ください。

**国立食品データベースのリスト**

-

**オーストラリア** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**ベルギー** - NUBEL - ベルギーの食品成分データ: [https://www.internubel.be](https://www.internubel.be/)

-

**カナダ** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**チェコ共和国** - 国立公衆衛生研究所の食品成分データベース: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**デンマーク** - デンマーク食品成分データバンク: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**エストニア** - エストニアの食品成分データベース: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**フィンランド** - フィンランド食品成分データベース - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**フランス** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**ドイツ** - Souci-Fachmann-Kraut オンライン データベース: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) または公式ドイツ語データベース: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **イタリア** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**オランダ** - オランダの食品成分データベース: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**ノルウェー** - ノルウェー食品成分表 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**ポーランド** - 食品成分表: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**スペイン** - スペイン食品成分データベース - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**スイス** - スイス食品成分データベース: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**英国** - 食品成分統合データセット (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**米国** - USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## API を使用して正確な製品名を検索できますか?

残念ながら、API を介して製品名のみを簡単に正確に検索することはまだできません。

ただし、カテゴリのフィルターを使用すると、検索をより正確に行うことができます。

---

## プロジェクトのデータにアクセスしたり収集するにはどうすればよいですか?

Open Food Facts のメインページの画面左上には、スクロール メニューがあります。 その下部に「詳細検索」オプションがあり、クリックすることができます。 どの基準がプロジェクトに最も関連しているかを判断するのはあなた次第です。 選択すると、ページの下部までスクロールして「結果をダウンロード」をクリックすると、取得した結果をダウンロードできるようになります。

以下も参照してください:

- 当社の API ドキュメント:[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Open Food Factsの利用規約:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- 当社のデータについて:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## API を使用するための条件はありますか?

API の使用に関するすべてのドキュメントは [API ドキュメント ページ](https://openfoodfacts.github.io/openfoodfacts-server/api/) にありますが、ここでは簡単に要約します。

- Open Food Facts データベースは、Open Database License (ODbL) に基づくオープンデータとして利用できます。法的詳細については、[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) を参照してください。 2 つの条件とは、帰属と均等分配です。 Open Food Facts のデータを他のデータベースと組み合わせる場合、ODbL では、結果のデータベースもオープンデータとして公開する必要があることが規定されています。 また、このような再配布を許可するソースとのみデータを組み合わせることができることも意味します。

- アプリを識別するために API 呼び出しを実行するときは、**常に** カスタム ユーザー エージェントを使用する必要があります。

- レート制限は API エンドポイントごとに適用されます。

---

## 履歴データにアクセスするにはどうすればいいですか?

現在、履歴データ ダンプ (JSONL、MongoDB、CSV) は提供していません。

ただし、個々の製品については、API を使用するか、製品ページのリビジョンを使用して、以前のバージョンの製品データにアクセスすることが可能です。

製品が更新されるたびに、新しいリビジョン (1 から始まる数字が増加) が作成されます。

例えば、この製品の最初のリビジョン（最初の製品バージョン）を取得するには、

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

同様に、 rev パラメータを API で使用できます。

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

