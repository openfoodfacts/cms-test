---
title: "{{< fa edit size=2x >}} Bénévolat / Contribution"
description: "3 questions"
lang: fr
order: 13
category-level: 0
icon: modifier
---

{{< fa "modifier" size=3x >}}

## Existe-t-il un moyen de supprimer les images téléchargées pour les produits ?

Seuls les modérateurs peuvent supprimer des photos, afin d'éviter tout vandalisme potentiel.

Demandez simplement sur Slack ou à **contact@openfoodfacts.org** de supprimer vos doublons ou toute photo inappropriée (essayez de fournir le numéro de code-barres ou l'URL pour ce faire).

Nous avons également une nouvelle API de signalement d'images si vous êtes programmeur.

---

## Je suis designer. Comment puis-je aider ?

Nous coordonnons toutes les activités liées au design sur [https://github.com/openfoodfacts/openfoodfacts-design](https://github.com/openfoodfacts/openfoodfacts-design) et sur un canal de discussion dédié. Nous organisons régulièrement des réunions d'équipe et des séances de brainstorming sur des défis spécifiques.

---

## Dans certains cas, un même produit peut avoir des valeurs nutritionnelles différentes selon le pays, comment cela est-il géré dans Open Food Facts ?

Dans 99 % des cas, les producteurs créent des codes-barres différents pour les différentes versions de leurs produits. Un exemple célèbre est la différence entre le Nutella français et allemand en termes d'épaisseur, due à la différence de pain selon les pays. 2 formules différentes, 2 codes-barres différents.

Des conflits de codes-barres peuvent cependant survenir sur des codes plus courts (EAN-8) qui sont généralement réutilisés par certains magasins en Europe et aux États-Unis. Nous ne gérons pas actuellement ces conflits de codes-barres, mais cela devrait être réalisable en obtenant la localisation générale de l'utilisateur (il est encore plus rare d'avoir des conflits de codes-barres au sein d'un même pays).

À long terme, nous encourageons les producteurs à passer à l'EAN-13 pour éviter ces conflits de codes-barres.

---

