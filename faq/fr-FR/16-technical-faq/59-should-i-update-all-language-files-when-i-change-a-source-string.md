---
title: "Dois-je mettre à jour tous les fichiers de langue lorsque je modifie une chaîne source ?"
order: 59
lang: en-gb
category: FAQ technique n° 16
breadcrumbs: [ '/en-gb/', '/en-gb/16-faq-technique/' ]
---

Non, vous n'en avez pas besoin. Il vous suffit de mettre à jour la version anglaise.

- Créez votre communiqué de presse

Une fois la fusion effectuée, nous rebaserons manuellement crowdin-trigger et le système de traduction Crowdin, déclenché par GitHub Actions, fera le reste pour les autres langues.

Le bot GitHub crée ensuite automatiquement une nouvelle PR que nous examinons ensuite.
