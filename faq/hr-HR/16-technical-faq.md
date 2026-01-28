---
title: "{{< fa brands github size=2x >}} Tehnička pitanja i odgovori"
description: "1 pitanje"
lang: hr-gb
order: 16
category-level: 0
icon: brendovi na GitHubu
---

{{< fa "marke" "github" size=3x >}}

## Trebam li ažurirati sve jezične datoteke kada promijenim izvorni niz?

Ne, ne moraš. Samo trebaš ažurirati englesku verziju.

- Kreirajte svoj PR

Nakon što se spoji, ručno ćemo rebazirati crowdin-trigger, a Crowdinov sustav prevođenja koji se pokreće putem GitHub Actionsa će učiniti ostalo za ostale jezike.

GitHub bot zatim automatski kreira novi PR koji mi zatim pregledavamo.

---

