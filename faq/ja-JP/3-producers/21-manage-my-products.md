---
title: "{{< fa box size=2x >}} 製品の管理"
description: "16の質問"
lang: en-gb
order: 21
category-level: 1
icon: 箱
---

{{< fa "箱" size=3倍 >}}

## Open Food Facts のデータの品質は何が保証するのでしょうか?

**データの品質を継続的に向上させるために、私たちは4つの柱に依存しています。**

1. コミュニティは継続的にデータと写真を追加しており、まさにレビュー担当者のパトロールです。

2. 製品シート上のエラーを識別するためのロジックルールを設定しました。たとえば、原材料の重量の合計が製品の総重量より大きい場合、異常が発生します。 他に約50個の品質チェックを実施しています。

3. 機械学習のおかげで、入力エラーのリスクを制限できます。 当社の技術により、投稿者が撮影した写真からテキストデータを抽出することができます

4. Santé Publique France のサポートのおかげで、生産者が大量生産したデータをアップロードし、コミュニティの貢献を修正/完了できるポータルを開発しました。

---

## 商品を追加するにはどうすればいいですか?

当社のプラットフォームに製品を追加するには、まずどのように進めるかを決める必要があります。 4つのオプションがあります:

- **手動**: 製品数が少ない場合でも、Pro プラットフォームで各製品シートを手動で作成することは可能です。

- **スプレッドシートのインポート経由**: Open Food Facts が提供するスプレッドシート [テンプレート](https://world.pro.openfoodfacts.org/cgi/generate_sample_import_file.pl) をダウンロードするか、IT システムから抽出したものを Pro プラットフォームに直接インポートすることができます。

- **製品カタログのコネクタ経由**。 EQUADIS、AGENA3000、または BAYARD のクライアントの場合は、1 回のクリックで Open Food Facts にデータをアップロードできます。 他のPIM（製品情報管理）をご利用の場合は、producers@openfoodfacts.orgまでご連絡ください。

- **あなたの会社と Open Food Facts の間のカスタマイズされた接続を介して**。 ポートフォリオに 1,000 を超える製品がある場合は、データ転送を容易にするための特定のコネクタを構築する機会についてご相談いただけます。

詳細については、[ユーザーガイド](https://blog.openfoodfacts.org/en/EN-Pro-Plateform-User-Guide.pdf)をダウンロードするか、[ビデオチュートリアル](https://www.youtube.com/playlist?list=PLjAH-USadsF3xgSVfUUBS4we3XBr-1r55)を参照してください:-)

---

## パブリックデータベースへの製品アップデートを自動化する方法はありますか?

はい、EQUADIS、AGENA3000、または BAYARD 製品カタログを使用し、適切な構成を設定すると、インポートが自動的に実行され、Open Food Facts の製品データが更新されます。

→ 詳細については、[ユーザーガイド](https://blog.openfoodfacts.org/en/EN-Pro-Plateform-User-Guide.pdf)をダウンロードするか、[ビデオチュートリアル](https://www.youtube.com/playlist?list=PLjAH-USadsF3xgSVfUUBS4we3XBr-1r55)を参照してください:-)

---

## 追加できる商品の数に制限はありますか？

制限はありません。当社のプラットフォームに必要な数の製品をアップロードできます。

---

## Is it possible to delete products that are no longer sold?

市場で入手できなくなった製品を削除する場合は、製品シートを編集するときに「この製品はもう販売されていません」というボックスをチェックするだけです。

複数の製品を削除する場合は、[ユーザー ガイド](https://blog.openfoodfacts.org/en/EN-Pro-Platform-User-Guide.pdf)の 18 ページに記載されている手順に従うことをお勧めします。

ご質問がある場合は、producers@openfoodfacts.org までお問い合わせください。

商品がアーカイブされると、Open Food Facts に表示されなくなります。ただし、時間の経過とともに販売された製品の履歴を保存できるように、データベースには残ります。

---

## 企業情報は、プラットフォーム上にすでに存在する情報よりも優先されますか?

プロデューサーがプロデューサーアカウントを使用して製品の 1 つをオンラインに配置し、製品シートがすでに存在する場合は、これで製品シートが完了します。

プロデューサーが投稿した情報は常に優先され、情報が記入された後、プロデューサーのみが製品を変更できます。

プラットフォーム経由で送信されたデータが断片化されている場合、パッケージからコミュニティによって追加された情報によってデータが完成する可能性があります。

---

## どのような形式でデータを送信すればよいですか?

[テンプレート](https://world.pro.openfoodfacts.org/cgi/generate_sample_import_file.pl)はOpen Food Factsによって提供されています。

ただし、任意のスプレッドシート形式 (xlsx、csv) をプラットフォームにインポートできます。  
当社のアルゴリズムは、ファイルの属性を Open Food Facts にある属性と自動的に一致させるように設計されています。 いくつかの段階を手動で調整する必要がある場合があるため、マッチング段階を常に再確認するように注意してください。

情報が複数のスプレッドシートに分散している場合は、形式が変更された場合は必ず一致させながら、それらを連続してインポートできます。

データがまだ情報システムにない場合は、EQUADIS または AGENA3000 のインポートに加えて、Excel ファイルをインポートすることもできます。 このような場合は、インターフェースからパブリック データベースへのエクスポートをリクエストすることを忘れないでください。

→ 詳細については、[ユーザーガイド](https://blog.openfoodfacts.org/en/EN-Pro-Plateform-User-Guide.pdf)をダウンロードするか、[ビデオチュートリアル](https://www.youtube.com/playlist?list=PLjAH-USadsF3xgSVfUUBS4we3XBr-1r55)を参照してください:-)

---

## どの製品カタログと統合されていますか?

メーカーは、**Equadis**、**AGENA3000、BAYARD consulting** から Open Food Facts に製品データと写真をリアルタイムで送信できるようになりました。

もちろん、処方変更の提案やプラットフォームのすべての機能も活用していただけます。

[当社のブログ投稿](https://blog.openfoodfacts.org/en/news/real-time-product-data-from-producers-on-open-food-facts-thanks-to-the-new-equadis-integration)では、EQUADIS のお客様であれば実行すべき手順について説明しています。

AGENA3000 のお客様 (製品 A3 PIM INDUSTRY) の場合は、製品シートを送信するときに受信者として「Open Food Facts」を選択するだけです。 [このブログ投稿で詳細をご覧ください](https://blog.openfoodfacts.org/en/news/share-your-product-data-in-1-click-with-the-new-agena3000-connector)。

別の製品データ カタログ (Salsify - 旧 Alkemics、ConsoTrust、1worldSync、Akeneo、PIMWorks など) の顧客の場合 [producers@openfoodfacts.org](mailto:producers@openfoodfacts.org)までご連絡ください。

→ 詳細については、[ユーザーガイド](https://blog.openfoodfacts.org/en/EN-Pro-Plateform-User-Guide.pdf)をダウンロードするか、[ビデオチュートリアル](https://www.youtube.com/playlist?list=PLjAH-USadsF3xgSVfUUBS4we3XBr-1r55)を参照してください:-)

---

## Pro プラットフォーム経由でバーコードのない製品を追加するにはどうすればよいですか?

バーコードのない製品の場合、サイトまたはプロデューサープラットフォームの左側の列に「バーコードのない製品」ボタンがあり、これを使用して製品を追加できます。 識別子が自動的に生成されます。

---

## Can animal products, non-food products, cosmetics and other products be integrated into Open Food Facts?

当社は、化粧品、動物飼料、その他の製品について、それぞれ「Open Beauty Facts」、「Open Pet Food Facts」、「Open Products Facts」という特定のプロジェクトを作成しました。
We are therefore happy to be able to import your products into the project that suits them.

---

## 私の会社の製品データは Open Food Facts で入手できます。 関連するプロデューサーアカウントを制御することは可能ですか?

はい、もちろん！ ビジネス住所を使用して Open Food Facts アカウントを作成することで、関連する生産者アカウントを管理できます。 登録時に、フォームに記載されている組織名を記載して、対応するプロデューサー スペースにアクセスできるようにします。

あなたが本当にプロデューサーであることを確認するために、簡単な検証手順が必要になります。

データの完成、画像の追加、Nutri-Score を改善するための自動推奨事項の取得など、さまざまなことが可能になります。 もちろん、これらはすべて完全に無料です。 EQUADIS、AGENA3000、Bayard consulting などのサードパーティの製品データ管理システムを接続することもできます。

→ 詳細については、[ユーザーガイド](https://blog.openfoodfacts.org/en/EN-Pro-Plateform-User-Guide.pdf)をダウンロードするか、[ビデオチュートリアル](https://www.youtube.com/playlist?list=PLjAH-USadsF3xgSVfUUBS4we3XBr-1r55)を参照してください:-)

---

## Open Food Facts データベースを再利用する他のアプリで生産者データが更新されるまでにどれくらいの時間がかかりますか?

アプリによって異なります。 大多数を占める当社の API を使用するユーザーにとっては、これは即時のことです。  
毎日エクスポートを使用するユーザーの場合、更新すれば D+1 になります。

---

## 製品レコードからデータをインポートすると、既存の製品レコードは完了しますか、それとも上書きされますか?

バーコードを使用して製品を識別します。既存のレコードと同じバーコードを持つレコードをインポートすると、情報が結合されます。

原材料リスト、栄養成分表示（正しい値は 1 つのみ）などのデータについては、プロデューサープラットフォーム経由で送信されたデータによって既存のデータが上書きされます。

ラベル/カテゴリ/ブランドなどのデータ（正しい値は複数存在する可能性があります）の場合、情報は結合されます。 パブリック プラットフォーム上のデータが正しくない場合は、パブリック プラットフォーム上の製品シートを変更して、誤った値を削除できます。

→ 詳細については、[ユーザーガイド](https://blog.openfoodfacts.org/en/EN-Pro-Plateform-User-Guide.pdf)をダウンロードするか、[ビデオチュートリアル](https://www.youtube.com/playlist?list=PLjAH-USadsF3xgSVfUUBS4we3XBr-1r55)を参照してください:-)

---

## 材料の順番は重要ですか？

材料の順序は重要で、量の順序を表します。
材料を詰める最良の方法は、パッケージに書かれている通りにすること。 だからこそ、原材料の写真を印刷しておくこともとても重要なのです。

---

## AGENA3000経由で画像も送信できますか？

画像を送信することはできますが、実際にはメイン画像のみが自動的に選択され、他の画像は送信されますが、原材料や栄養成分などに基づいて切り取られたり選択されたりすることはありません。

---

## Pro プラットフォームのチュートリアルにアクセスするにはどうすればいいですか?

プロ プラットフォームのチュートリアルにアクセスできます。

- プロプラットフォーム自体から：[https://world.pro.openfoodfacts.org/](https://world.pro.openfoodfacts.org/)

- [YouTube](https://www.youtube.com/playlist?list=PLjAH-USadsF3xgSVfUUBS4we3XBr-1r55) で直接

→ [ユーザーガイド](https://blog.openfoodfacts.org/en/EN-Pro-Plateform-User-Guide.pdf)もダウンロードできます。

---

