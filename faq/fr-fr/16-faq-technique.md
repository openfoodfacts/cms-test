---
title: "{{< fa brands github size=2x >}} FAQ technique"
description: "1 question"
lang: fr-fr
order: 16
category-level: 0
icon: brands github
---

{{< fa brands github size=3x >}}

## Dois-je mettre à jour tous les fichiers de langue quand je change une chaîne source ?

Non.

Il suffit de mettre à jour le fichier anglais

Puis créer votre PR

Une fois mergé, nous rebaserons la branche crowdin-trigger manuellement et le système de traduction Crowdin déclenché par GitHub Actions fera le reste pour les autres langues.

Le bot GitHub crée ensuite automatiquement une nouvelle PR que nous examinons ensuite.

---

