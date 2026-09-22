---
title: "Should I update all language files when I change a source string?"
order: 59
lang: en-gb
category: 16-technical-faq
breadcrumbs: [ '/en-gb/', '/en-gb/16-technical-faq/' ]
---

No you don't. You just need to update the English one

- Create your PR

Once it's merged, we will rebase crowdin-trigger manually and the Crowdin translation system triggerd by GitHub Actions will do the rest for other languages.

GitHub bot then creates a new PR automatically that we then review.
