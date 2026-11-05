---
title: "Ska jag uppdatera alla språkfiler när jag ändrar en källsträng?"
order: 59
lang: sv-gb
category: 16-tekniska-FAQ
breadcrumbs: [ '/sv-gb/', '/sv-gb/16-tekniska-faq/' ]
---

Nej, det gör du inte. Du behöver bara uppdatera den engelska versionen

- Skapa din PR

När det är sammanfogat kommer vi att omforma crowdin-trigger manuellt och Crowdins översättningssystem som utlöses av GitHub Actions kommer att göra resten för andra språk.

GitHub-boten skapar sedan automatiskt en ny PR som vi sedan granskar.
