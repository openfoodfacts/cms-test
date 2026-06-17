---
title: "{{< fa brands github size=2x >}} Technical FAQ"
description: "1 question"
lang: en-gb
order: 16
category-level: 0
icon: brands github
---

{{< fa "brands" "github" size=3x >}}

## Should I update all language files when I change a source string?

No you don't. You just need to update the English one

- Create your PR

Once it's merged, we will rebase crowdin-trigger manually and the Crowdin translation system triggerd by GitHub Actions will do the rest for other languages.

GitHub bot then creates a new PR automatically that we then review.

---

