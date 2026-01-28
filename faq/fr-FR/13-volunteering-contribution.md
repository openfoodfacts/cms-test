---
title: "Bénévolat / Contribution"
description: "3 questions"
lang: en-gb
order: 13
category-level: 0
icon: modifier
---

{{< fa "modifier" size=3x >}}

## Existe-t-il un moyen de supprimer les images téléchargées pour les produits ?

Seuls les modérateurs peuvent supprimer les photos, afin d'éviter tout risque de vandalisme.

Il suffit de demander sur Slack ou à **contact@openfoodfacts.org** pour supprimer vos doublons ou toute photo inappropriée (vous devrez essayer de fournir le numéro de code-barres ou l'URL à cet effet).

Nous proposons également une nouvelle API de rapports d'images si vous êtes programmeur.

---

## Je suis designer. Comment puis-je vous aider ?

Nous coordonnons toutes les activités liées à la conception sur [https://github.com/openfoodfacts/openfoodfacts-design](https://github.com/openfoodfacts/openfoodfacts-design) et sur un canal de discussion dédié. Nous organisons régulièrement des réunions d'équipe et des séances de brainstorming sur des problématiques spécifiques.

---

## Dans certains cas, un même produit peut avoir des valeurs nutritionnelles différentes selon les pays. Comment cela est-il géré dans Open Food Facts ?

Dans 99 % des cas, les producteurs créent des codes-barres différents pour les différentes versions de leurs produits. Un exemple célèbre est la différence d'épaisseur entre le Nutella français et le Nutella allemand, due aux différences de pain entre les pays. Deux formules différentes, deux codes-barres différents.

Cependant, des conflits de codes-barres peuvent survenir sur des codes plus courts (EAN-8) qui sont généralement réutilisés par certains magasins en Europe et aux États-Unis. Nous ne gérons pas actuellement ces conflits de codes-barres, mais cela devrait être possible en obtenant la localisation générale de l'utilisateur (les conflits de codes-barres à l'intérieur d'un même pays sont encore plus rares).

À long terme, nous encourageons les producteurs à adopter le format EAN-13 afin d'éviter les conflits de codes-barres.

---

