---
title: "Bør jeg oppdatere alle språkfiler når jeg endrer en kildestreng?"
order: 59
lang: en-gb
category: 16-tekniske-FAQ
breadcrumbs: [ '/en-gb/', '/no-gb/16-tekniske-vanlige-spørsmål/' ]
---

Nei, det gjør du ikke. Du trenger bare å oppdatere den engelske versjonen

- Lag din PR

Når det er slått sammen, vil vi manuelt endre basen til crowdin-trigger, og Crowdin-oversettelsessystemet, som utløses av GitHub Actions, vil gjøre resten for andre språk.

GitHub-boten oppretter deretter automatisk en ny PR som vi deretter gjennomgår.
