---
title: "FAQ technique {{< fa brands github size=2x >}}"
description: "1 question"
lang: en-gb
order: 16
category-level: 0
icon: marques github
---

{{< fa "marques" "github" size=3x >}}

## Dois-je mettre à jour tous les fichiers de langue lorsque je modifie une chaîne source ?

Non, vous n'en avez pas besoin. Il vous suffit de mettre à jour la version anglaise.

- Créez votre communiqué de presse

Une fois la fusion effectuée, nous rebaserons manuellement crowdin-trigger et le système de traduction Crowdin, déclenché par GitHub Actions, fera le reste pour les autres langues.

Le bot GitHub crée ensuite automatiquement une nouvelle PR que nous examinons ensuite.

---

