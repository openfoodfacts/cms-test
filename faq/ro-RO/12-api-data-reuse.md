---
title: "{{< dimensiunea cheii fa=2x >}} API și reutilizarea datelor"
description: "6 întrebări"
lang: en-gb
order: 12
category-level: 0
icon: cheie
---

{{< fa "cheie" size="de 3 ori" >}}

## Există recomandări undeva în documentație cu privire la dimensiunea potrivită pentru fotografiile încărcate?

Asta poate depinde de țară, dacă rețeaua este lentă sau scumpă. Orice element cu o greutate sau o înălțime mai mare de 5000 de pixeli probabil nu este foarte util. și dacă poți cumva detecta că rețeaua este lentă, atunci chiar și o imagine de 2000 de pixeli ar fi grozavă (cu siguranță mai bună decât să nu ai o imagine!).

---

## Dar cum rămâne cu mâncarea fără coduri de bare?

Open Food Facts conține doar informații despre alimentele ambalate. Pentru valorile medii ale produselor agricole (de exemplu, roșii sau banane) și ale altor produse alimentare, puteți utiliza în schimb una dintre bazele de date naționale oficiale privind nutriția.

**Notă:** Lista de mai jos conține unele dintre cele mai importante baze de date naționale privind alimentele. Dacă considerați că o altă bază de date ar trebui inclusă în listă, vă rugăm să ne contactați la: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Lista bazelor de date naționale privind alimentele**

-

**Australia** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Belgia** - NUBEL - Date belgiene privind compoziția alimentelor: [https://www.internubel.be](https://www.internubel.be/)

-

**Canada** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**Republica Cehă** - Baza de date privind compoziția alimentelor la Institutul Național de Sănătate Publică: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Danemarca** - Banca de date daneză privind compoziția alimentelor: [[https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Estonia** - Baza de date estonă privind compoziția alimentelor: [[https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finlanda** - Baza de date finlandeză privind compoziția alimentelor - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**Franța** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Germania** - Baza de date online Souci-Fachmann-Kraut: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) sau baza de date oficială germană: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **Italia** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Țările de Jos** - Baza de date olandeză privind compoziția alimentelor: [[https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Norvegia** - Tabelul norvegian de compoziție a alimentelor 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Polonia** - Tabele de compoziție a alimentelor: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Spania** - Baza de date spaniolă privind compoziția alimentelor - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Elveția** - Baza de date elvețiană privind compoziția alimentelor: [[https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**Regatul Unit** - Set de date integrate privind compoziția alimentelor (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**SUA** - USDA: [[https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Pot căuta un nume precis de produs cu ajutorul API-ului?

Din păcate, nu este încă posibil să căutați cu ușurință doar după numele produsului și cu precizie prin intermediul API-ului.

Folosirea unui filtru pe categorie te-ar putea ajuta să faci căutarea mai precisă.

---

## Cum pot accesa/colecta date pentru proiectele mele?

Pe pagina principală Open Food Facts, în colțul din stânga sus al ecranului, există un meniu derulant. În partea de jos a paginii, veți găsi opțiunea „căutare avansată”, pe care puteți face clic. Apoi, depinde de tine să stabilești care criterii sunt cele mai relevante pentru proiectul/proiectele tale. După ce ați ales, veți putea descărca rezultatele obținute derulând în josul paginii și făcând clic pe „Descărcați rezultatele”.

De asemenea, puteți consulta:

- Documentația noastră API:[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Termenii și condițiile Open Food Facts:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- Pe baza datelor noastre:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Există condiții pentru utilizarea API-ului?

Toată documentația despre utilizarea API-ului poate fi găsită pe [pagina de documentație API](https://openfoodfacts.github.io/openfoodfacts-server/api/), dar iată un scurt rezumat:

- Baza de date Open Food Facts este disponibilă ca date deschise sub licența Open Database License (ODbL), consultați [[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) pentru detalii legale. Cele două condiții sunt atribuirea și distribuirea în mod similar. Dacă combinați date din Open Food Facts cu alte baze de date, atunci ODbL impune ca baza de date rezultată să fie publicată și ca date deschise. De asemenea, înseamnă că puteți combina datele doar cu surse care ar permite o astfel de redistribuire.

- Trebuie să folosești **întotdeauna** un User-Agent personalizat atunci când efectuezi apeluri API pentru a identifica aplicația.

- Limitele de rată sunt impuse pentru fiecare punct final API.

---

## Cum pot accesa datele istorice?

În prezent, nu oferim servicii de dump de date istorice (JSONL, MongoDB, CSV).

Totuși, pentru produse individuale, este posibil să accesați versiunile anterioare ale datelor despre produs utilizând API-ul sau pe pagina produsului, utilizând revizii.

De fiecare dată când un produs este actualizat, se creează o nouă revizie (cifră crescătoare începând de la 1).

De exemplu, pentru a obține prima revizie (=prima versiune a acestui produs), utilizați

[[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joughurt-baumnuss-migros?rev=1).

În mod similar, parametrul rev poate fi utilizat cu API-ul:

[[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

