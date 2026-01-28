---
title: "{{< fa brands github size=2x >}} 技術常見問題解答"
description: "1 個問題"
lang: 英語-英國
order: 16
category-level: 0
icon: 品牌 GitHub
---

{{< fa "品牌" "GitHub" size=3倍 >}}

## 當我更改來源字串時，是否需要更新所有語言檔案？

不，你不需要。 你只需要更新英文版。

- 創建你的公關稿

合併完成後，我們將手動對 crowdin-trigger 進行 rebase 操作，然後由 GitHub Actions 觸發的 Crowdin 翻譯系統將完成其他語言的翻譯工作。

然後 GitHub 機器人會自動建立一個新的 PR，我們隨後會對其進行審核。

---

