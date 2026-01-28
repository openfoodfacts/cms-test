---
title: "{{< fa wrench size=2x >}} API og datagenbrug"
description: "6 spørgsmål"
lang: en-gb
order: 12
category-level: 0
icon: skruenøgle
---

{{< fa "skruenøgle" size="3 gange" >}}

## Er der anbefalinger et sted i dokumentationen til, hvad der ville være en god størrelse til uploadede billeder?

Det kan afhænge af landet, om netværket er langsomt eller dyrt. Alt over 5000 pixels i vægt eller højde er sandsynligvis ikke særlig nyttigt. og hvis du på en eller anden måde kan registrere, at netværket er langsomt, så ville selv et billede på 2000 pixels være fantastisk (helt sikkert bedre end ikke at have et billede!).

---

## Hvad med mad uden stregkoder?

Open Food Facts indeholder kun information om emballerede fødevarer. For gennemsnitsværdier af frugt og grønt (f.eks. tomater eller bananer) og andre fødevarer kan du i stedet bruge en af de officielle nationale ernæringsdatabaser.

**Bemærk:** Listen nedenfor indeholder nogle af de vigtigste nationale fødevaredatabaser. Hvis du mener, at en anden database bør inkluderes på listen, bedes du kontakte os på: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Liste over nationale fødevaredatabaser**

-

**Australien** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Belgien** - NUBEL - Data om belgisk fødevaresammensætning: [https://www.internubel.be](https://www.internubel.be/)

-

**Canada** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**Tjekkiet** - Database over fødevaresammensætning på National Institute of Public Health: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Danmark** - Dansk Fødevaredatabank: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Estland** - Estisk database over fødevarer: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finland** - Finsk database over fødevarer - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**Frankrig** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Tyskland** - Souci-Fachmann-Kraut Online Database: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) eller den officielle tyske database: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **Italien** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Holland** - Hollandsk database over fødevaresammensætning: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Norge** - Den norske fødevaresammensætningstabel 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Polen** - Tabeller over fødevaresammensætning: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Spanien** - Spansk fødevaresammensætningsdatabase - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Schweiz** - Schweizisk database over fødevarer: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**UK** - Integreret datasæt om sammensætning af fødevarer (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**USA** - USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Kan jeg søge efter et præcist produktnavn med API'en?

Desværre er det endnu ikke muligt nemt at søge udelukkende på produktnavn og præcist via API'en.

Brug af et filter på kategori kan dog hjælpe dig med at gøre din søgning mere præcis.

---

## Hvordan kan jeg tilgå/indsamle data til mine projekter?

På Open Food Facts' hovedside er der en rullemenu i øverste venstre hjørne af skærmen. Nederst finder du muligheden "avanceret søgning", som du kan klikke på. Det er derefter op til dig at afgøre, hvilke kriterier der er mest relevante for dit/dine projekt(er). Når du har valgt, kan du downloade de opnåede resultater ved at rulle ned i bunden af siden og klikke på "Download resultater".

Du kan også konsultere:

- Vores API-dokumentation:[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Open Food Facts' brugsbetingelser:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- På vores data:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Er der betingelser for at bruge API'en?

Al dokumentation om API-brug kan findes på [API-dokumentationssiden](https://openfoodfacts.github.io/openfoodfacts-server/api/), men her er en hurtig opsummering:

- Open Food Facts-databasen er tilgængelig som åbne data under Open Database License (ODbL). Se [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) for juridiske detaljer. De to betingelser er tilskrivning og deling på samme vilkår. Hvis du kombinerer data fra Open Food Facts med andre databaser, kræver ODbL, at den resulterende database også skal frigives som åbne data. Det betyder også, at du kun kan kombinere dataene med kilder, der tillader en sådan omdistribution.

- Du skal **altid** bruge en brugerdefineret brugeragent, når du udfører API-kald for at identificere din app.

- Der håndhæves hastighedsgrænser for hvert API-slutpunkt.

---

## Hvordan kan jeg få adgang til historiske data?

Vi tilbyder i øjeblikket ikke historisk datadump (JSONL, MongoDB, CSV).

For individuelle produkter er det dog muligt at få adgang til tidligere versioner af produktdataene ved hjælp af API'en eller på produktsiden ved hjælp af revisioner.

Hver gang et produkt opdateres, oprettes en ny revision (stigende ciffer startende fra 1).

For eksempel, for at få den første revision (=første produktversion) af dette produkt, skal du bruge

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1] (https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

På samme måde kan rev-parameteren bruges med API'en:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

