---
title: "{{< fa wrench size=2x >}} API és adatok újrafelhasználása"
description: "6 kérdés"
lang: hu-gb
order: 12
category-level: 0
icon: csavarkulcs
---

{{< fa "csavarkulcs" size=3x >}}

## Vannak-e ajánlások a dokumentációban arra vonatkozóan, hogy mi lenne a megfelelő méret a feltöltött képekhez?

Ez országonként függhet, hogy a hálózat lassú vagy drága-e. Bármi, ami 5000 pixelnél nagyobb súlyú vagy magasságú, valószínűleg nem túl hasznos. és ha valahogyan észlelhető, hogy lassú a hálózat, akkor akár egy 2000 pixeles kép is nagyszerű lenne (mindenképpen jobb, mintha nem lenne kép!).

---

## Mi a helyzet a vonalkód nélküli ételekkel?

Az Open Food Facts csak a csomagolt élelmiszerekről tartalmaz információkat. A termények (például paradicsom vagy banán) és más élelmiszerek átlagértékeinek meghatározásához használhatja a hivatalos nemzeti táplálkozási adatbázisok egyikét.

**Megjegyzés:** Az alábbi lista a legfontosabb nemzeti élelmiszer-adatbázisok közül néhányat tartalmaz. Ha úgy gondolja, hogy más adatbázist is fel kellene venni a listára, kérjük, vegye fel velünk a kapcsolatot a következő címen: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Nemzeti Élelmiszer-adatbázisok listája**

-

**Ausztrália** – FSANZ – NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Belgium** - NUBEL - Belga élelmiszer-összetételi adatok: [https://www.internubel.be](https://www.internubel.be/)

-

**Kanada** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**Cseh Köztársaság** - Élelmiszer-összetételi adatbázis a Nemzeti Közegészségügyi Intézetben: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Dánia** - Dán Élelmiszer-összetételi Adatbank: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Észtország** - Észt élelmiszer-összetétel adatbázis: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finnország** - Finn élelmiszer-összetétel adatbázis - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**Franciaország** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Németország** - Souci-Fachmann-Kraut online adatbázis: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) vagy a hivatalos német adatbázis: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsb)

- **Olaszország** – Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Hollandia** - Holland Élelmiszer-összetételi Adatbázis: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Norvégia** - A norvég élelmiszer-összetételi táblázat 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Lengyelország** - Élelmiszer-összetételi táblázatok: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Spanyolország** - Spanyol élelmiszer-összetételi adatbázis - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Svájc** - Svájci Élelmiszer-összetételi Adatbázis: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**Egyesült Királyság** - Élelmiszer-összetétel integrált adatkészlet (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**USA** – USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Rákereshetek egy pontos terméknévre az API-val?

Sajnos még nem lehetséges egyszerűen és pontosan a terméknév alapján keresni az API-n keresztül.

Egy kategória szerinti szűrő használata azonban segíthet a keresés pontosításában.

---

## Hogyan férhetek hozzá/gyűjthetek adatokat a projektjeimhez?

Az Open Food Facts főoldalán, a képernyő bal felső sarkában található egy görgethető menü. Alul találod a „Speciális keresés” opciót, amire rákattinthatsz. Ezután rajtad múlik, hogy melyik kritériumok a legrelevánsabbak a projekted(eid) szempontjából. A kiválasztás után a lap alján görgetve, majd az „Eredmények letöltése” gombra kattintva letöltheti az eredményeket.

Konzultálhat még:

- API dokumentációnk:[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Az Open Food Facts felhasználási feltételei:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- Az adatainkról:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Vannak feltételei az API használatának?

Az API használatával kapcsolatos összes dokumentáció megtalálható az [API dokumentációs oldalon](https://openfoodfacts.github.io/openfoodfacts-server/api/), de itt egy rövid összefoglaló:

- Az Open Food Facts adatbázis nyílt adatként érhető el az Open Database License (ODbL) alatt, a jogi részletekért lásd a [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) oldalt. A két feltétel a forrásmegjelölés és a hasonló jogú felhasználás. Ha az Open Food Facts adatbázisból származó adatokat más adatbázisokkal kombinálod, akkor az ODbL előírja, hogy a kapott adatbázist is nyílt adatként kell közzétenni. Ez azt is jelenti, hogy az adatokat csak olyan forrásokkal kombinálhatja, amelyek lehetővé teszik az ilyen újraelosztást.

- **Mindig** egyéni felhasználói ügynököt kell használnod, amikor API-hívásokat hajtasz végre az alkalmazásod azonosítására.

- A sebességkorlátok minden API-végpontra érvényesek.

---

## Hogyan férhetek hozzá a korábbi adatokhoz?

Jelenleg nem kínálunk historikus adatkiírást (JSONL, MongoDB, CSV).

Azonban az egyes termékek esetében a termékadatok korábbi verzióihoz az API-n vagy a termékoldalon a revíziók segítségével lehet hozzáférni.

Minden alkalommal, amikor egy termék frissül, új verzió jön létre (1-től növekvő számjeggyel).

Például a termék első verziójának (=első termékverzió) lekéréséhez használja a következőt:

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

Hasonlóképpen, a rev paraméter használható az API-val:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

