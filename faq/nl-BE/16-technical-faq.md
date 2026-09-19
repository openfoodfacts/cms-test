---
title: "{{< fa brands github size=2x >}} Technische FAQ"
description: "1 vraag"
lang: nl-nl
order: 16
category-level: 0
icon: merken github
---

{{< fa "merken" "github" size=3x >}}

## Moet ik alle taalbestanden bijwerken wanneer ik een brontekst wijzig?

Nee, dat is niet nodig. Je hoeft alleen de Engelse versie bij te werken.

- Create your PR

Once it's merged, we will rebase crowdin-trigger manually and the Crowdin translation system triggerd by GitHub Actions will do the rest for other languages.

De GitHub-bot maakt vervolgens automatisch een nieuwe pull request aan, die wij vervolgens beoordelen.

---

