---
title: "{{< fa brands github size=2x >}} Teknisk FAQ"
description: "1 fråga"
lang: en-gb
order: 16
category-level: 0
icon: brands github
---

{{< fa "märken" "github" size=3x >}}

## Ska jag uppdatera alla språkfiler när jag ändrar en källsträng?

Nej, det behöver du inte. Du behöver bara uppdatera den engelska filen

- Skapa din PR

När den har slagits samman kommer vi att köra rebase manuellt för crowdin-trigger och sedan sköter Crowdins översättningssystem, som utlöses av GitHub Actions, resten för de andra språken.

GitHub-boten skapar därefter automatiskt en ny PR som vi granskar.

---

