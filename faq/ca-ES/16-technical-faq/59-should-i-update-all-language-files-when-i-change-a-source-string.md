---
title: "He d'actualitzar tots els fitxers d'idioma quan canvio una cadena d'origen?"
order: 59
lang: en-gb
category: 16-preguntes freqüents tècniques
breadcrumbs: [ '/en-gb/', '/ca-gb/16-preguntes-fràgils-tècniques/' ]
---

No, no ho fas. Només cal actualitzar l'anglès.

- Crea el teu PR

Un cop fusionat, rebaserem crowdin-trigger manualment i el sistema de traducció Crowdin activat per GitHub Actions farà la resta per a altres idiomes.

El bot de GitHub crea automàticament una nova PR que després revisem.
