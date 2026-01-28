---
title: "{{< fa wrench size=2x >}} API et réutilisation des données"
description: "6 questions"
lang: en-gb
order: 12
category-level: 0
icon: clé
---

{{< fa "clé" size=3x >}}

## Existe-t-il dans la documentation des recommandations concernant la taille appropriée des photos téléchargées ?

Cela peut dépendre des pays, si le réseau est lent ou coûteux. Tout ce qui dépasse 5000 pixels en poids ou en hauteur n'est probablement pas très utile. Et si vous parvenez d'une manière ou d'une autre à détecter que le réseau est lent, alors même une image de 2000 pixels serait formidable (certainement mieux que de ne pas avoir d'image du tout !).

---

## Qu’en est-il des aliments sans code-barres ?

Open Food Facts ne contient que des informations sur les aliments emballés. Pour connaître les valeurs moyennes des fruits et légumes (par exemple, des tomates ou des bananes) et autres produits alimentaires, vous pouvez utiliser l'une des bases de données nutritionnelles nationales officielles.

**Remarque :** La liste ci-dessous contient quelques-unes des bases de données alimentaires nationales les plus importantes. Si vous pensez qu'une autre base de données devrait être incluse dans la liste, veuillez nous contacter à l'adresse suivante : [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Liste des bases de données alimentaires nationales**

-

**Australie** - FSANZ - NUTTAB 2006 : [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Belgique** - NUBEL - Données sur la composition des aliments belges : [https://www.internubel.be](https://www.internubel.be/)

-

**Canada** - FCEN : [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**République tchèque** - Base de données sur la composition des aliments de l'Institut national de santé publique : [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Danemark** - Base de données danoise sur la composition des aliments : [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Estonie** - Base de données estonienne sur la composition des aliments : [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finlande** - Base de données finlandaise sur la composition des aliments - FINELI : [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**France** - CIQUAL : [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Allemagne** - Base de données en ligne Souci-Fachmann-Kraut : [https://www.sfk.online/#/home](https://www.sfk.online/#/home) ou la base de données officielle allemande : Bundeslebensmittelschlüssel : [https://blsdb.de/](https://blsdb.de/)

- **Italie** - Banca Dati di Composizione degli Alimenti CREA : [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Pays-Bas** - Base de données néerlandaise sur la composition des aliments : [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Norvège** - Tableau de composition des aliments norvégiens 2006 : [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Pologne** - Tables de composition des aliments : [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Espagne** - Base de données espagnole sur la composition des aliments - BEDCA : [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Suisse** - Base de données suisse sur la composition des aliments : [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**Royaume-Uni** - Ensemble de données intégré sur la composition des aliments (CoFID) : [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**États-Unis** - USDA : [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Puis-je rechercher un produit par son nom précis via l'API ?

Malheureusement, il n'est pas encore possible de rechercher facilement et précisément un produit uniquement par son nom via l'API.

L'utilisation d'un filtre par catégorie peut toutefois vous aider à affiner votre recherche.

---

## Comment puis-je accéder aux données de mes projets et les collecter ?

Sur la page principale d'Open Food Facts, en haut à gauche de l'écran, se trouve un menu déroulant. En bas de la page, vous trouverez l'option « recherche avancée », sur laquelle vous pouvez cliquer. Il vous appartient ensuite de déterminer quels critères sont les plus pertinents pour votre ou vos projets. Une fois votre choix effectué, vous pourrez télécharger les résultats obtenus en faisant défiler la page vers le bas et en cliquant sur « Télécharger les résultats ».

Vous pouvez également consulter :

- Notre documentation API : [ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Conditions d'utilisation d'Open Food Facts : [ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- D'après nos données : [ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Existe-t-il des conditions pour utiliser l'API ?

Toute la documentation relative à l'utilisation de l'API se trouve sur la [page de documentation de l'API](https://openfoodfacts.github.io/openfoodfacts-server/api/), mais voici un bref résumé :

- La base de données Open Food Facts est disponible en tant que données ouvertes sous la licence Open Database License (ODbL), voir [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) pour les détails juridiques. Les deux conditions sont l'attribution et le partage à l'identique. Si vous combinez des données d'Open Food Facts avec d'autres bases de données, l'ODbL exige que la base de données résultante soit également publiée en tant que données ouvertes. Cela signifie également que vous ne pouvez combiner les données qu'avec des sources qui autoriseraient une telle redistribution.

- Vous devez **toujours** utiliser un User-Agent personnalisé lors des appels API pour identifier votre application.

- Des limites de débit sont appliquées à chaque point de terminaison d'API.

---

## Comment puis-je accéder aux données historiques ?

Actuellement, nous ne proposons pas l'exportation de données historiques (JSONL, MongoDB, CSV).

Toutefois, pour chaque produit, il est possible d'accéder aux versions précédentes des données produit via l'API ou sur la page produit en utilisant les révisions.

À chaque mise à jour d'un produit, une nouvelle révision (numérotée de 1 à 10) est créée.

Par exemple, pour obtenir la première révision (ou première version du produit) de ce produit, utilisez

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

De même, le paramètre rev peut être utilisé avec l'API :

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

