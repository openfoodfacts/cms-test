---
title: "{{< fa brands github size=2x >}} Technické dotazy"
description: "1 otázka"
lang: en-gb
order: 16
category-level: 0
icon: značky na GitHubu
---

{{< fa "značky" "github" size=3x >}}

## Mám aktualizovat všechny jazykové soubory, když změním zdrojový řetězec?

Ne, to neděláš. Stačí jen aktualizovat tu anglickou.

- Vytvořte si svůj PR

Jakmile bude sloučeno, ručně přeložíme crowdin-trigger a zbytek pro ostatní jazyky udělá překladový systém Crowdin spouštěný pomocí GitHub Actions.

Bot GitHubu poté automaticky vytvoří nový PR, který následně zkontrolujeme.

---

