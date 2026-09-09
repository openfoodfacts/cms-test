---
title: "Mám aktualizovat všechny jazykové soubory, když změním zdrojový řetězec?"
order: 59
lang: en-gb
category: 16-technické-často-kladené otázky
breadcrumbs: [ '/cs-gb/', '/cs-gb/16-technické-časté-otázky/' ]
---

Ne, to neděláš. Stačí jen aktualizovat tu anglickou.

- Vytvořte si svůj PR

Jakmile bude sloučeno, ručně přeložíme crowdin-trigger a zbytek pro ostatní jazyky udělá překladový systém Crowdin spouštěný pomocí GitHub Actions.

Bot GitHubu poté automaticky vytvoří nový PR, který následně zkontrolujeme.
