---
title: "{{< fa wrench size=2x >}} API og datagenbrug"
description: "6 spørgsmål"
lang: en-gb
order: 12
category-level: 0
icon: skruenøgle
---

{{< fa "skruenøgle" size=3x >}}

## Er der anbefalinger et sted i dokumentationen til, hvad der ville være en god størrelse til uploadede billeder?

Det kan afhænge af landet, om netværket er langsomt eller dyrt. alt over 5000 pixels i vægt eller højde er sandsynligvis ikke særlig nyttigt. og hvis du på en eller anden måde kan registrere, at netværket er langsomt, så ville selv et billede på 2000 pixels være fantastisk (helt sikkert bedre end ikke at have et billede!).

---

## Hvad med fødevarer uden stregkoder?

Open Food Facts indeholder kun information om emballerede fødevarer. For gennemsnitsværdier af frugt og grønt (f.eks. tomater eller bananer) og andre fødevarer kan du i stedet bruge en af de officielle nationale ernæringsdatabaser.

**Bemærk:** Listen herunder indeholder nogle af de vigtigste nationale fødevaredatabaser. If you think some other database should be included in the list, please contact us at: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**List of National Food Databases**

-

**Australia** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Belgium** - NUBEL - Belgian Food Composition Data: [https://www.internubel.be](https://www.internubel.be/)

-

**Canada** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**Czech Republic** - Food Composition Database at National Institute of Public Health: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Danmark** - Dansk Fødevaredatabank: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Estonia** - Estonian Food Composition Database: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finland** - Finnish Food Composition Database - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**France** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Germany** - Souci-Fachmann-Kraut Online Database: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) or the official German Database: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

-  **Italy** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Netherlands** - Dutch Food Composition Database: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Norway** - The Norwegian Food Composition Table 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Poland** - Food Composition Tables: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Spain** - Spanish Food Composition Database - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Switzerland** - Swiss Food Composition Database: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**UK** - Composition of foods integrated dataset (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**USA** - USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Kan jeg søge efter et præcist produktnavn med API'en?

Desværre er det endnu ikke muligt nemt at søge udelukkende på produktnavn og præcist via API'en.

Brug af et filter på kategori kan dog hjælpe dig med at gøre din søgning mere præcis.

---

## Hvordan kan jeg tilgå og indsamle data til mine projekter?

På Open Food Facts' hovedside er der en rullemenu i øverste venstre hjørne af skærmen. Nederst finder du muligheden "avanceret søgning", som du kan klikke på. Det er derefter op til dig at afgøre, hvilke kriterier der er mest relevante for dig. Når du har valgt, kan du downloade de opnåede resultater ved at scrolle ned i bunden af siden og klikke på "Download resultater".

Du kan også besøge:

- Vores API-dokumentation:[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Open Food Facts' brugsbetingelser:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- På vores data:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Er der betingelser for at bruge API'en?

Al dokumentation om API-brug kan findes på [API-dokumentationssiden](https://openfoodfacts.github.io/openfoodfacts-server/api/), men her er en hurtig opsummering:

- Open Food Facts-databasen er tilgængelig som åbne data under Open Database License (ODbL). Se [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) for juridiske detaljer. De to betingelser er tilskrivning og deling på samme vilkår. Hvis du kombinerer data fra Open Food Facts med andre databaser, derefter ODbL kræver, at den resulterende database også frigives som åbne data. Det betyder også, at du kun kan kombinere data med kilder, der giver mulighed for en sådan omfordeling.

- Du skal **altid** bruge en brugerdefineret brugeragent, når du udfører API-kald for at identificere din app.

- Rate-limits are enforced for each API endpoint.

---

## How can I access historical data?

Currently, we don't offer historical data dump (JSONL, MongoDB, CSV).

However, for individual products, it's possible to access previous versions of the product data using the API or on the product page using revisions.

Every time a product is updated, a new revision (increasing digit starting from 1) is created.

For example, to get the first revision (=first product version) of this product, use

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

Similarly, the rev parameter can be used with the API:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

