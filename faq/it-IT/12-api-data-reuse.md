---
title: "{{< fa wrench size=2x >}} API e riutilizzo dei dati"
description: "6 domande"
lang: en-gb
order: 12
category-level: 0
icon: chiave
---

{{< fa "chiave" size=3x >}}

## Ci sono suggerimenti nella documentazione su quale sarebbe la dimensione giusta per le foto caricate?

Dipende dal Paese, se la rete è lenta o costosa. qualsiasi cosa che superi i 5000 pixel di peso o altezza probabilmente non è molto utile. e se in qualche modo riesci a rilevare che la rete è lenta, allora anche un'immagine da 2000 pixel sarebbe l'ideale (certamente meglio che non avere un'immagine!)

---

## E il cibo senza codici a barre?

Open Food Facts contiene solo informazioni sugli alimenti confezionati. Per i valori medi dei prodotti ortofrutticoli (ad esempio, pomodori o banane) e di altri alimenti, è possibile utilizzare uno dei database nutrizionali nazionali ufficiali.

**Nota:** L'elenco seguente contiene alcuni dei più importanti database alimentari nazionali. Se ritieni che un altro database debba essere incluso nell'elenco, contattaci a: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Elenco dei database alimentari nazionali**

-

**Australia** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Belgio** - NUBEL - Dati sulla composizione degli alimenti belgi: [https://www.internubel.be](https://www.internubel.be/)

-

**Canada** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**Repubblica Ceca** - Banca dati sulla composizione degli alimenti presso l'Istituto nazionale di sanità pubblica: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Danimarca** - Banca dati danese sulla composizione degli alimenti: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Estonia** - Database estone sulla composizione degli alimenti: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finlandia** - Banca dati finlandese sulla composizione degli alimenti - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**Francia** - CIQUAL: [https://www.anses.fr/it/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Germania** - Database online Souci-Fachmann-Kraut: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) o il database ufficiale tedesco: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **Italia** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Paesi Bassi** - Banca dati olandese sulla composizione degli alimenti: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Norvegia** - Tabella norvegese di composizione degli alimenti 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Polonia** - Tabelle di composizione degli alimenti: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Spagna** - Database di composizione degli alimenti in Spagna - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Svizzera** - Banca dati svizzera sulla composizione degli alimenti: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**Regno Unito** - Dataset integrato sulla composizione degli alimenti (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**USA** - USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Posso cercare un nome di prodotto preciso con l'API?

Purtroppo non è ancora possibile effettuare ricerche semplici e precise solo in base al nome del prodotto tramite l'API.

Tuttavia, l'utilizzo di un filtro per categoria potrebbe aiutarti a rendere la tua ricerca più precisa.

---

## Come posso accedere/raccogliere dati per i miei progetti?

Nella pagina principale di Open Food Facts, nell'angolo in alto a sinistra dello schermo, è presente un menu a scorrimento. In fondo troverai l'opzione "ricerca avanzata", sulla quale potrai cliccare. Spetta poi a te determinare quali criteri sono più pertinenti per il tuo/i progetto/i. Una volta effettuata la scelta, potrai scaricare i risultati ottenuti scorrendo verso il basso nella parte inferiore della pagina e cliccando su “Scarica risultati”.

Puoi anche consultare:

- La nostra documentazione API:[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Termini di utilizzo di Open Food Facts:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- Sui nostri dati:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Esistono delle condizioni per utilizzare l'API?

Tutta la documentazione sull'utilizzo dell'API può essere trovata nella [pagina di documentazione dell'API](https://openfoodfacts.github.io/openfoodfacts-server/api/), ma ecco un breve riepilogo:

- Il database Open Food Facts è disponibile come dati aperti secondo la licenza Open Database License (ODbL); per i dettagli legali, vedere [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use). Le due condizioni sono l'attribuzione e la condivisione allo stesso modo. Se si combinano i dati di Open Food Facts con altri database, l'ODbL richiede che anche il database risultante venga rilasciato come dati aperti. Ciò significa anche che è possibile combinare i dati solo con fonti che consentano tale ridistribuzione.

- Devi **sempre** utilizzare uno User-Agent personalizzato quando esegui chiamate API per identificare la tua app.

- Per ogni endpoint API vengono applicati limiti di velocità.

---

## Come posso accedere ai dati storici?

Al momento non offriamo il dump dei dati storici (JSONL, MongoDB, CSV).

Tuttavia, per i singoli prodotti, è possibile accedere alle versioni precedenti dei dati del prodotto tramite l'API o sulla pagina del prodotto tramite le revisioni.

Ogni volta che un prodotto viene aggiornato, viene creata una nuova revisione (cifra crescente a partire da 1).

Ad esempio, per ottenere la prima revisione (=prima versione del prodotto) di questo prodotto, utilizzare

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

Allo stesso modo, il parametro rev può essere utilizzato con l'API:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

