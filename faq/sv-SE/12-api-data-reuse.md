---
title: "{{< fa wrench size=2x >}} API och vidareutnyttjande av data"
description: "6 frågor"
lang: en-gb
order: 12
category-level: 0
icon: wrench
---

{{< fa "wrench" size=3x >}}

## Finns det några rekommendationer någonstans i dokumentationen om vilken storlek som är lämplig för uppladdade foton?

Det kan bero på landet och på om nätverksanslutningen är långsam eller dyr. Allt över 5000 pixlar i bredd eller höjd är förmodligen inte särskilt användbart. Om det går att upptäcka att nätverket är långsamt räcker till och med en bild på 2000 pixlar bra (det är definitivt bättre än ingen bild alls!).

---

## Vad gäller livsmedel utan streckkoder?

Open Food Facts innehåller endast information om förpackade livsmedelsprodukter. För genomsnittsvärden för frukt, grönsaker (till exempel tomater eller bananer) och andra livsmedel kan du i stället använda en officiell nationell näringsdatabas.

**Obs!** Listan nedan innehåller några av de viktigaste nationella livsmedelsdatabaserna. Om du tror att någon annan databas bör inkluderas i listan, kontakta oss på: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Lista över nationella livsmedelsdatabaser**

-

**Australien** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Belgien** - NUBEL - Belgiska data om livsmedelssammansättning: [https://www.internubel.be](https://www.internubel.be/)

-

**Kanada** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**Tjeckien** - Livsmedelssammansättningsdatabas vid Nationella institutet för folkhälsa: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Danmark** - Dansk livsmedelssammansättningsdatabas: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Estland** - Estnisk livsmedelssammansättningsdatabas: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finland** - Finländsk livsmedelssammansättningsdatabas - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**Frankrike** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Tyskland** - Souci-Fachmann-Kraut Online Database: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) eller den officiella tyska databasen: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

-  **Italien** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Nederländerna** - Nederländsk livsmedelssammansättningsdatabas: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Norge** - Norsk livsmedelstabell 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Polen** - Livsmedelstabeller: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Spanien** - Spansk livsmedelssammansättningsdatabas - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Schweiz** - Schweizisk livsmedelssammansättningsdatabas: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**Storbritannien** - Integrerad datauppsättning om livsmedelssammansättning (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**USA** – USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Kan jag söka efter ett exakt produktnamn via API:t?

Det är tyvärr ännu inte möjligt att enkelt och exakt söka endast på produktnamnet via API:t.

Att använda ett filter på kategori kan dock hjälpa dig att göra din sökning mer precis.

---

## Hur får jag tillgång till eller samlar in data för mina projekt?

På Open Food Facts-huvudsidan finns en rullgardinsmeny längst upp till vänster på skärmen. Längst ned i menyn hittar du alternativet ”avancerad sökning”, som du kan klicka på. Sedan väljer du de kriterier som är mest relevanta för dina projekt. När du har valt kriterierna kan du hämta resultaten genom att gå längst ned på sidan och klicka på ”Hämta resultat”.

Du kan också läsa:

- Vår API-dokumentation: [https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Open Food Facts-användningsvillkor:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- Om vår data: [ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Finns det några villkor för att använda API:t?

All dokumentation om API-användning finns på [API-dokumentationssidan](https://openfoodfacts.github.io/openfoodfacts-server/api/), men här är en snabb sammanfattning:

- Open Food Facts-databasen är tillgänglig som öppna data enligt Open Database License (ODbL); se [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) för juridisk information. De två villkoren är källangivelse och delning på samma villkor (share-alike). Om du kombinerar data från Open Food Facts med andra databaser kräver ODbL att även den resulterande databasen publiceras som öppna data. Det innebär också att du bara kan kombinera data med källor som tillåter sådan vidaredistribution.

- Du måste **alltid** använda en anpassad User-Agent när du gör API-anrop för att identifiera din app.

- Hastighetsbegränsningar tillämpas för varje API-slutpunkt.

---

## Hur får jag tillgång till historiska data?

För närvarande erbjuder vi ingen export av historiska data (JSONL, MongoDB, CSV).

För enskilda produkter går det däremot att komma åt tidigare versioner av produktdata via API:et eller via versionshistoriken på produktsidan.

Varje gång en produkt uppdateras skapas en ny revision (ett stigande nummer som börjar med 1).

Använd till exempel följande för att hämta produktens första revision (=den första produktversionen):

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

På samma sätt kan parametern rev användas i API-anrop:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

