---
title: "Ar trebui să actualizez toate fișierele de limbă când modific un șir sursă?"
order: 59
lang: en-gb
category: 16-întrebări frecvente tehnice
breadcrumbs: [ '/ro-gb/', '/ro-gb/16-întrebări-întrebări-tehnice/' ]
---

Nu, nu trebuie. Trebuie doar să o actualizezi pe cea în limba engleză.

- Creează-ți propria PR

Odată ce este fuzionat, vom reface manual baza crowdin-trigger, iar sistemul de traducere Crowdin declanșat de GitHub Actions va face restul pentru celelalte limbi.

Botul GitHub creează apoi automat un nou PR pe care îl revizuim.
