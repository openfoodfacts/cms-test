---
title: "{{< fa wrench size=2x >}} API og gjenbruk av data"
description: "6 spørsmål"
lang: en-gb
order: 12
category-level: 0
icon: skiftenøkkel
---

{{< fa "skiftenøkkel" size="3 ganger" >}}

## Finnes det anbefalinger noe sted i dokumentasjonen om hva som ville være en god størrelse for opplastede bilder?

Det kan avhenge av land, om nettverket er tregt eller dyrt. Alt over 5000 piksler i vekt eller høyde er sannsynligvis ikke særlig nyttig. og hvis du på en eller annen måte kan oppdage at nettverket er tregt, ville selv et bilde på 2000 piksler være flott (absolutt bedre enn å ikke ha et bilde!).

---

## Hva med mat uten strekkoder?

Open Food Facts inneholder kun informasjon om pakket mat. For gjennomsnittsverdier av frukt og grønt (for eksempel tomater eller bananer) og andre matvarer kan du i stedet bruke en av de offisielle nasjonale ernæringsdatabasene.

**Merk:** Listen nedenfor inneholder noen av de viktigste nasjonale matdatabasene. Hvis du mener at en annen database bør inkluderes i listen, kan du kontakte oss på: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Liste over nasjonale matdatabaser**

-

**Australia** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Belgia** - NUBEL - Data om belgisk matsammensetning: [https://www.internubel.be](https://www.internubel.be/)

-

**Canada** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**Tsjekkia** - Database over matsammensetning ved Nasjonalt institutt for folkehelse: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Danmark** - Dansk databank for næringsmiddelsammensetning: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Estland** - Estisk database over matvarer: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finland** - Finsk database over næringsmidler - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**Frankrike** - CIQUAL: [https://www.anses.fr/en/search/site/Tabell%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Tyskland** - Souci-Fachmann-Kraut Online Database: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) eller den offisielle tyske databasen: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **Italia** – Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Nederland** - Nederlandsk database over matsammensetning: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Norge** - Tabellen over norsk matvaresammensetning 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Polen** - Tabeller over matsammensetning: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Spania** - Spansk matvaredatabase - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Sveits** - Sveitsisk database over matvarer: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**Storbritannia** - Integrert datasett for matsammensetning (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**USA** - USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Kan jeg søke etter et presist produktnavn med API-et?

Dessverre er det ennå ikke mulig å enkelt søke kun på produktnavn og presist via API-et.

Å bruke et filter på kategori kan imidlertid hjelpe deg med å gjøre søket ditt mer presist.

---

## Hvordan kan jeg få tilgang til/samle inn data for prosjektene mine?

På hovedsiden til Open Food Facts, øverst til venstre på skjermen, er det en rullemeny. Nederst finner du alternativet «avansert søk», som du kan klikke på. Det er deretter opp til deg å bestemme hvilke kriterier som er mest relevante for prosjektet/prosjektene dine. Når du har valgt, kan du laste ned resultatene ved å bla ned nederst på siden og klikke på «Last ned resultater».

Du kan også konsultere:

- Vår API-dokumentasjon:[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Bruksvilkår for Open Food Facts:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- På våre data:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Finnes det noen betingelser for å bruke API-et?

All dokumentasjon om API-bruk finner du på [API-dokumentasjonssiden](https://openfoodfacts.github.io/openfoodfacts-server/api/), men her er et raskt sammendrag:

- Open Food Facts-databasen er tilgjengelig som åpne data under Open Database License (ODbL), se [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) for juridiske detaljer. De to betingelsene er attribusjon og deling på samme vilkår. Hvis du kombinerer data fra Open Food Facts med andre databaser, krever ODbL at den resulterende databasen også må frigis som åpne data. Det betyr også at du bare kan kombinere dataene med kilder som tillater slik omfordeling.

- Du må **alltid** bruke en tilpasset brukeragent når du utfører API-kall for å identifisere appen din.

- Hastighetsgrenser håndheves for hvert API-endepunkt.

---

## Hvordan kan jeg få tilgang til historiske data?

For øyeblikket tilbyr vi ikke historisk datadumping (JSONL, MongoDB, CSV).

For individuelle produkter er det imidlertid mulig å få tilgang til tidligere versjoner av produktdataene ved hjelp av API-et eller på produktsiden ved hjelp av revisjoner.

Hver gang et produkt oppdateres, opprettes en ny revisjon (økende siffer fra 1).

For eksempel, for å få den første revisjonen (=første produktversjon) av dette produktet, bruk

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

På samme måte kan rev-parameteren brukes med API-et:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

