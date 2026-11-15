---
title: "Devo aggiornare tutti i file di lingua quando modifico una stringa sorgente?"
order: 59
lang: en-gb
category: 16-domande-tecniche
breadcrumbs: [ '/it-it/', '/it-it/16-domande-tecniche/' ]
---

No, non lo fai. Devi solo aggiornare quello inglese

- Crea il tuo PR

Una volta unito, ribaseremo crowdin-trigger manualmente e il sistema di traduzione di Crowdin, attivato da GitHub Actions, farà il resto per le altre lingue.

Il bot di GitHub crea quindi automaticamente una nuova PR che poi esamineremo.
