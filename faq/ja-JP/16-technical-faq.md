---
title: "{{< fa brands github size=2x >}} 技術的なよくある質問"
description: "1件の質問"
lang: en-gb
order: 16
category-level: 0
icon: ブランド github
---

{{< fa "ブランド" "ギットハブ" size=3倍 >}}

## ソース文字列を変更するときに、すべての言語ファイルを更新する必要がありますか?

いいえ、そうではありません。 英語版を更新するだけでいい

- PRを作成する

マージが完了したら、crowdin-trigger を手動でリベースし、GitHub Actions によってトリガーされた Crowdin 翻訳システムが他の言語の残りの作業を実行します。

その後、GitHub ボットが自動的に新しい PR を作成し、それをレビューします。

---

