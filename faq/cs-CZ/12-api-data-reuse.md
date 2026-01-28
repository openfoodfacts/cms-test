---
title: "{{< fa wrench size=2x >}} API a opětovné použití dat"
description: "6 otázek"
lang: en-gb
order: 12
category-level: 0
icon: klíč
---

{{< fa "klíč" size=3x >}}

## Jsou někde v dokumentaci doporučení, jaká by byla vhodná velikost pro nahrávané fotografie?

To může záviset na zemi, zda je síť pomalá nebo drahá. Cokoli nad 5000 pixelů na tloušťku nebo výšku pravděpodobně není příliš užitečné. a pokud nějakým způsobem dokážete zjistit, že síť je pomalá, pak by i obrázek s 2000 pixely byl skvělý (rozhodně lepší než žádný obrázek!).

---

## A co jídlo bez čárových kódů?

Open Food Facts obsahuje pouze informace o balených potravinách. Pro průměrné hodnoty produktů (například rajčat nebo banánů) a dalších potravinářských výrobků můžete místo toho použít jednu z oficiálních národních nutričních databází.

**Poznámka:** Níže uvedený seznam obsahuje některé z nejdůležitějších národních databází potravin. Pokud si myslíte, že by do seznamu měla být zahrnuta i jiná databáze, kontaktujte nás prosím na adrese: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Seznam národních potravinových databází**

-

**Austrálie** – FSANZ – NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Cna%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Belgie** - NUBEL - Údaje o složení belgických potravin: [https://www.internubel.be](https://www.internubel.be/)

-

**Kanada** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**Česká republika** - Databáze složení potravin v Národním ústavu veřejného zdraví: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Dánsko** - Dánská databanka složení potravin: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Estonsko** - Estonská databáze složení potravin: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finsko** - Finská databáze složení potravin - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**Francie** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Německo** – Souci-Fachmann-Kraut Online databáze: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) nebo oficiální německá databáze: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **Itálie** – Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Nizozemsko** - Nizozemská databáze složení potravin: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Norsko** - Norská tabulka složení potravin 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Polsko** - Tabulky složení potravin: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Španělsko** - Španělská databáze složení potravin - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Švýcarsko** - Švýcarská databáze složení potravin: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**Spojené království** - Integrovaný datový soubor o složení potravin (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**USA** – USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Mohu pomocí API vyhledat přesný název produktu?

Bohužel zatím není možné snadno a přesně vyhledávat pouze podle názvu produktu prostřednictvím API.

Použití filtru podle kategorie vám ale může pomoci zpřesnit vyhledávání.

---

## Jak mohu přistupovat k datům pro své projekty/shromažďovat je?

Na hlavní stránce Open Food Facts se v levém horním rohu obrazovky nachází posuvné menu. Ve spodní části najdete možnost „rozšířené vyhledávání“, na kterou můžete kliknout. Pak je na vás, abyste určili, která kritéria jsou pro váš projekt (projekty) nejrelevantnější. Jakmile si vyberete, budete si moci stáhnout získané výsledky posunutím dolů do dolní části stránky a kliknutím na tlačítko „Stáhnout výsledky“.

Můžete se také poradit:

- Naše dokumentace k API:[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Podmínky použití Open Food Facts:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- Na základě našich dat:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Jsou pro používání API nějaké podmínky?

Veškerou dokumentaci o používání API naleznete na [stránce s dokumentací API](https://openfoodfacts.github.io/openfoodfacts-server/api/), ale zde je stručné shrnutí:

- Databáze Open Food Facts je k dispozici jako otevřená data pod licencí Open Database License (ODbL), právní podrobnosti viz [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use). Dvě podmínky jsou atribuce a sdílení za stejných podmínek. Pokud kombinujete data z Open Food Facts s jinými databázemi, pak ODbL vyžaduje, aby výsledná databáze byla také zveřejněna jako otevřená data. To také znamená, že data můžete kombinovat pouze se zdroji, které by takovou redistribuci umožnily.

- Při provádění volání API musíte **vždy** použít vlastního uživatelského agenta k identifikaci vaší aplikace.

- Pro každý koncový bod API jsou vynucovány limity rychlosti.

---

## Jak mohu získat přístup k historickým datům?

V současné době nenabízíme výpis historických dat (JSONL, MongoDB, CSV).

U jednotlivých produktů je však možné přistupovat k předchozím verzím produktových dat pomocí API nebo na stránce produktu pomocí revizí.

Pokaždé, když je produkt aktualizován, vytvoří se nová revize (zvyšující se číslice od 1).

Například pro získání první revize (=první verze produktu) tohoto produktu použijte

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

Podobně lze parametr rev použít s API:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

