---
title: "{{< fa wrench size=2x >}} API och dataåteranvändning"
description: "6 frågor"
lang: sv-gb
order: 12
category-level: 0
icon: rycka
---

{{< fa "rycka" size=3x >}}

## Finns det rekommendationer någonstans i dokumentationen om vad som skulle vara en bra storlek för uppladdade foton?

Det kan bero på länder, om nätverket är långsamt eller dyrt. Allt över 5000 pixlar i vikt eller höjd är förmodligen inte särskilt användbart. och om du på något sätt kan upptäcka att nätverket är långsamt, så skulle även en bild på 2000 pixlar vara utmärkt (absolut bättre än att inte ha någon bild!).

---

## Vad gäller mat utan streckkoder?

Open Food Facts innehåller endast information om förpackad mat. För genomsnittsvärden för produkter (till exempel tomater eller bananer) och andra livsmedelsprodukter kan du istället använda en av de officiella nationella näringsdatabaserna.

**Obs!** Listan nedan innehåller några av de viktigaste nationella livsmedelsdatabaserna. Om du anser att någon annan databas borde inkluderas i listan, vänligen kontakta oss på: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Lista över nationella livsmedelsdatabaser**

-

**Australien** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Belgien** - NUBEL - Data om belgisk livsmedelssammansättning: [https://www.internubel.be](https://www.internubel.be/)

-

**Kanada** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**Tjeckien** - Databas över livsmedelssammansättning vid Nationella folkhälsoinstitutet: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Danmark** - Dansk databank för livsmedelssammansättning: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Estland** - Estlands databas över livsmedelssammansättning: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finland** - Finlands databas över livsmedelssammansättning - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**Frankrike** - CIQUAL: [https://www.anses.fr/en/search/site/Tabell%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Tyskland** - Souci-Fachmann-Kraut Online Database: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) eller den officiella tyska databasen: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **Italien** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Nederländerna** - Nederländsk databas över livsmedelssammansättning: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Norge** - Den norska livsmedelssammansättningstabellen 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Polen** - Tabeller över livsmedelssammansättning: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Spanien** - Spansk databas över livsmedelssammansättning - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Schweiz** - Schweizisk databas över livsmedelssammansättning: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**Storbritannien** - Sammansättning av livsmedelsintegrerade dataset (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**USA** - USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Kan jag söka efter ett exakt produktnamn med API:et?

Tyvärr är det ännu inte möjligt att enkelt söka enbart på produktnamn och exakt via API:et.

Att använda ett filter på kategori kan dock hjälpa dig att göra din sökning mer exakt.

---

## Hur kan jag komma åt/samla in data för mina projekt?

På Open Food Facts huvudsida, längst upp till vänster på skärmen, finns en rullmeny. Längst ner hittar du alternativet "avancerad sökning", som du kan klicka på. Det är sedan upp till dig att avgöra vilka kriterier som är mest relevanta för ditt/dina projekt. När du har valt kan du ladda ner de erhållna resultaten genom att scrolla ner längst ner på sidan och klicka på "Ladda ner resultat".

Du kan också konsultera:

- Vår API-dokumentation:[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Användarvillkor för Open Food Facts:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- På vår data:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Finns det villkor för att använda API:et?

All dokumentation om API-användning finns på [API-dokumentationssidan](https://openfoodfacts.github.io/openfoodfacts-server/api/), men här är en snabb sammanfattning:

- Open Food Facts-databasen är tillgänglig som öppen data under Open Database License (ODbL), se [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) för juridisk information. De två villkoren är attribution och delning på samma sätt. Om du kombinerar data från Open Food Facts med andra databaser kräver ODbL att den resulterande databasen också måste släppas som öppen data. Det betyder också att du endast kan kombinera informationen med källor som tillåter sådan omdistribution.

- Du måste **alltid** använda en anpassad användaragent när du utför API-anrop för att identifiera din app.

- Hastighetsgränser tillämpas för varje API-slutpunkt.

---

## Hur kan jag få tillgång till historisk data?

För närvarande erbjuder vi inte historisk datadumpning (JSONL, MongoDB, CSV).

För enskilda produkter är det dock möjligt att komma åt tidigare versioner av produktdata med hjälp av API:et eller på produktsidan med hjälp av revisioner.

Varje gång en produkt uppdateras skapas en ny revision (ökande siffra från 1).

För att till exempel hämta den första revisionen (=första produktversionen) av den här produkten, använd

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1] (https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

På liknande sätt kan parametern rev användas med API:et:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

