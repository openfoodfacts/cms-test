---
title: "Dois-je mettre à jour tous les fichiers de langue quand je change une chaîne source ?"
order: 59
lang: fr-fr
category: 16-faq-technique
breadcrumbs: ['/fr-fr/', '/fr-fr/16-faq-technique/']
---

Non.

Il suffit de mettre à jour le fichier anglais

Puis créer votre PR

Une fois mergé, nous rebaserons la branche crowdin-trigger manuellement et le système de traduction Crowdin déclenché par GitHub Actions fera le reste pour les autres langues.

Le bot GitHub crée ensuite automatiquement une nouvelle PR que nous examinons ensuite.
