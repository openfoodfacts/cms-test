---
title: "{{< fa wrench størrelse=2x >}} API & data gjenbruk"
description: "6 spørsmål"
lang: no-no
order: 12
category-level: 0
icon: skiftenøkkel
---

{{< fa "skiftenøkkel" size="3 x" >}}

## Er det anbefalinger i dokumentasjonen på hva som ville være en god størrelse for de opplastede bildene?

Det kan avhenge av land, hvis nettverket er langsomt eller dyrt. Noe over 5000 piksler i vekt eller høyde er sannsynligvis ikke særlig nyttig. og hvis du på en eller annen måte oppdager at nettverket er treg, da vil et 2000 piksler bilde være stort (absolutt bedre enn ikke å ha et bilde!)

---

## Hva med mat uten strekkoder?

Open Food Facts inneholder kun informasjon om pakket mat. For gjennomsnittsverdier som produseres (f.eks. tomater eller bananer) og andre matprodukter, kan du i stedet bruke en av de offisielle nasjonale ernæringsdatabasene.

**Merk:** Listen under inneholder noen av de viktigste nasjonale matdatabasene. Dersom du tror noen annen database skal inkluderes i listen, vennligst kontakt oss på: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

\*\*Liste over nasjonale matdatabaser

-

**Australia** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Belgium** - NUBEL - Belgia Food Composition Data: [https://www.internubel.be](https://www.internubel.be/)

-

**Canada** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**Tsjekkisk Republic** - Food Composition Database at National Institute of Public Health: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Danmark** - Dansk Food Composition Databank: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=no)

-

**Estland** - Estlands matkomposisjon Database: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finland** - Finsk matkomposisjon Database - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/no/index)

-

**Frankrike** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Tyskland** - Souci-Fachmann-Kraut Online Database: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) eller den offisielle tyske database: Bundeslebensmittelschlu@nofima.no [https://blsdb.de/](https://blsdb.de/)

- **Italy** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Nederland** - nederlandsk Food Composition Database: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Norge** - Norges Matkomposisjon Tabell 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Polen** - Food Composition Tables: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Spain** - Spansk Food Composition Database - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

\*\*Sveits \*\* - Sveitsisk Food Composition Database: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**UK** - Sammenstilling av matvarer integrert (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**USA** - USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Kan jeg søke etter et presist produktnavn med API?

Dessverre er det ikke mulig å enkelt søke på produktnavn bare og nøyaktig gjennom API-et.

Ved å bruke et filter på en kategori kan det hjelpe deg med å gjøre søket ditt mer presis.

---

## Hvordan får jeg tilgang/samle inn data til prosjektene mine?

På Open Food Facts’ hovedside, øverst til venstre på skjermen finnes det en rullemeny. På bunnen av programmet finner du alternativet "avansert søk" som du kan klikke på. Det er så opp til deg å avgjøre hvilke kriterier som er mest relevante for prosjektet(ene). Når valgt, vil du kunne laste ned de oppnådde resultatene ved å rulle ned nederst på siden og klikke på "Last ned resultater".

Du kan også konsultere:

- Vår API dokumentasjon:[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-dokumentation/)
- Open Food Facts' Terms of Use:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- I våre data:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Er det betingelser å bruke API?

All dokumentasjon om bruk av API kan finnes på [API dokumentasjonssiden] (https://openfoodfacts.github.io/openfoodfacts-server/api/), men her er en rask oppsummering:

- Open Food Facts databasen er tilgjengelig som åpne data under Open Database License (ODbL), se [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) for de juridiske detaljene. De to forholdene er attribusjon og share-alike. Dersom du kombinerer data fra Open Food Facts med andre databaser, da krever ODbL at den resulterende databasen må frigis som åpne data også. Det betyr også at man kan kombinere data kun med kilder som muliggjør slik omfordeling.

- Du må **alltid** bruke en egendefinert Bruker-Agent når du utfører API-samtaler for å identifisere appen din.

- Raty-grenser tvinges for hvert API endepunkt.

---

## Hvordan får jeg tilgang til historiske data?

Vi tilbyr for tiden ikke historiske data dump (JSONL, MongoDB, CSV).

For enkeltprodukter er det imidlertid mulig å få tilgang til tidligere versjoner av produktdataene ved hjelp av API eller produktsiden ved hjelp av versjoner.

Hver gang et produkt oppdateres, blir en ny revisjon (øker siffer fra 1) opprettet.

For eksempel, for å få den første revisjonen (=første produktversjon) av dette produktet, bruk

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

På samme måte kan rev parameteren brukes med API:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

