---
title: "当我更改源字符串时，是否应该更新所有语言文件？"
order: 59
lang: 英语-英国
category: 16-技术常见问题解答
breadcrumbs: [ '/en-gb/', '/en-gb/16-technical-faq/' ]
---

不，你不需要。 你只需要更新英文版。

- 创建你的公关稿

合并完成后，我们将手动对 crowdin-trigger 进行 rebase，然后由 GitHub Actions 触发的 Crowdin 翻译系统将完成其他语言的翻译工作。

然后 GitHub 机器人会自动创建一个新的 PR，我们随后会对其进行审核。
