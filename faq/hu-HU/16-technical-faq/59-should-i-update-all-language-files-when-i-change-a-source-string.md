---
title: "Frissítsem az összes nyelvi fájlt, amikor módosítok egy forrásszöveget?"
order: 59
lang: hu-gb
category: 16-műszaki-gyik-kérdés
breadcrumbs: [ '/hu-hu/', '/hu-hu/16-technikai-gyik/' ]
---

Nem, nem. Csak frissítened kell az angol verziót.

- Hozza létre PR-ját

Miután összevontuk, manuálisan újraalapozzuk a crowdin-trigger függvényt, és a GitHub Actions által aktivált Crowdin fordítórendszer elvégzi a többit a többi nyelv esetében.

A GitHub bot ezután automatikusan létrehoz egy új PR-t, amelyet mi felülvizsgálunk.
