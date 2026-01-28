---
title: "{{< fa brands github size=2x >}} Tehnička pitanja i odgovori"
description: "1 pitanje"
lang: en-gb
order: 16
category-level: 0
icon: brendovi na GitHubu
---

{{< fa "brands" "github" size=3x >}}

## Trebam li ažurirati sve jezičke datoteke kada promijenim izvorni niz?

Ne, ne moraš. Samo trebaš ažurirati englesku verziju.

- Kreirajte svoj PR

Nakon što se spoji, ručno ćemo ponovo bazirati crowdin-trigger, a Crowdin sistem za prevođenje, pokrenut putem GitHub Actions, će uraditi ostalo za ostale jezike.

GitHub bot zatim automatski kreira novi PR koji mi zatim pregledamo.

---

