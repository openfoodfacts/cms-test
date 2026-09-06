---
title: "{{< fa brands github size=2x >}} FAQ technique"
description: "1 question"
lang: en-gb
order: 16
category-level: 0
icon: brands github
---

{{< fa "marques" "github" size=3x >}}

## Dois-je mettre à jour tous les fichiers de langue lorsque je modifie une chaîne source ?

Non, ce n'est pas nécessaire. Vous avez seulement besoin de mettre à jour la version anglaise

- Créer votre PR

Une fois fusionnée, nous effectuerons un rebase manuel de crowdin-trigger et le système de traduction Crowdin, déclenché par GitHub Actions, fera le reste pour les autres langues.

Le bot GitHub crée ensuite automatiquement une nouvelle PR que nous examinons.

---

