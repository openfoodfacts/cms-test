---
title: "Trebam li ažurirati sve jezične datoteke kada promijenim izvorni niz?"
order: 59
lang: hr-gb
category: 16-tehnička-česta pitanja
breadcrumbs: [ '/hr-gb/', '/hr-hr/16-tehnička-česta pitanja/' ]
---

Ne, ne moraš. Samo trebaš ažurirati englesku verziju.

- Kreirajte svoj PR

Nakon što se spoji, ručno ćemo rebazirati crowdin-trigger, a Crowdinov sustav prevođenja koji se pokreće putem GitHub Actionsa će učiniti ostalo za ostale jezike.

GitHub bot zatim automatski kreira novi PR koji mi zatim pregledavamo.
