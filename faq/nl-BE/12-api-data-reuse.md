---
title: "{{< fa wrench size=2x >}} API & hergebruik van gegevens"
description: "6 vragen"
lang: nl-nl
order: 12
category-level: 0
icon: moersleutel
---

{{< fa "moersleutel" size=3x >}}

## Worden er in de documentatie ergens aanbevelingen gedaan over wat een geschikt formaat is voor geüploade foto's?

Dat kan afhangen van het land, en van het netwerk. Alles boven de 5000 pixels in breedte of hoogte is waarschijnlijk niet erg nuttig. En als je op de een of andere manier zou vaststellen dat het netwerk traag is, dan zou zelfs een afbeelding van 2000 pixels al geweldig zijn (zeker beter dan helemaal geen afbeelding!).

---

## En hoe zit het met voedsel zonder barcodes?

Open Food Facts bevat alleen informatie over verpakte voedingsmiddelen. Voor gemiddelde waarden van groenten en fruit (zoals tomaten of bananen) en andere voedingsmiddelen kunt u in plaats daarvan een van de officiële nationale voedingswaardetabellen raadplegen.

**Let op:** De onderstaande lijst bevat enkele van de belangrijkste nationale voedseldatabases. Als u denkt dat er nog andere databases aan de lijst moeten worden toegevoegd, neem dan contact met ons op via: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Lijst van nationale voedseldatabases**

-

**Australië** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**België** - NUBEL - Belgische voedingswaardetabel: [https://www.internubel.be](https://www.internubel.be/)

-

**Canada** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**Tsjechië** - Voedingswaardetabel van het Nationaal Instituut voor Volksgezondheid: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Denemarken** - Deense voedingswaardedatabank: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Estland** - Estlandse voedingswaardetabel: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finland** - Finse voedingswaardetabel - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**Frankrijk** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Duitsland** - Souci-Fachmann-Kraut online database: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) of de officiële Duitse database: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **Italië** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Nederland** - Nederlandse Voedingswaardetabel: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Noorwegen** - De Noorse Voedingswaardetabel 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Polen** - Voedingswaardetabellen: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Spanje** - Spaanse voedingswaardetabel - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Zwitserland** - Zwitserse voedingswaardetabel: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**VK** - Geïntegreerde dataset voor de samenstelling van voedingsmiddelen (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**VS** - USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Can I search a precise product name with the API?

Unfortunately it's not yet possible to easily search on product name only and precisely through the API.

Using a filter on category might help you make your search more precise though.

---

## How can I access/collect data for my projects?

On Open Food Facts’ main page, at the top left corner of the screen, there’s a scrolling menu. At the bottom of it, you’ll find the “advanced search” option, on which you can click. It is then up to you to determine which criteria are the most relevant to your project(s). Once chosen, you’ll be able to download the obtained results by scrolling down at the bottom of the page and clicking on “Download results”.

You can also consult:

- Our API documentation:[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Open Food Facts' Terms of Use:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- On our data:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Zijn er voorwaarden verbonden aan het gebruik van de API?

All the documentation about API usage can be found on the [API documentation page](https://openfoodfacts.github.io/openfoodfacts-server/api/), but here is a quick summary:

- The Open Food Facts database is available as open data under the Open Database License (ODbL), see [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) for the legal details. The two conditions are attribution and share-alike. If you combine data from Open Food Facts with other databases, then the ODbL requires that the resulting database must be released as open data as well. It also means that you can combine the data only with sources that would allow such redistribution.

- You must **always** use a custom User-Agent when performing API calls to identify your app.

- Rate-limits are enforced for each API endpoint.

---

## Hoe krijg ik toegang tot historische gegevens?

Momenteel bieden we geen export van historische gegevens aan (JSONL, MongoDB, CSV).

However, for individual products, it's possible to access previous versions of the product data using the API or on the product page using revisions.

Every time a product is updated, a new revision (increasing digit starting from 1) is created.

Om bijvoorbeeld de eerste revisie (=eerste productversie) van dit product te verkrijgen, gebruikt u...

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

Similarly, the rev parameter can be used with the API:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

