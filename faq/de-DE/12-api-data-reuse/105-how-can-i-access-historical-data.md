---
title: "Wie kann ich auf historische Daten zugreifen?"
order: 105
lang: en-gb
category: 12-API-Datenwiederverwendung
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

Aktuell bieten wir keinen Export historischer Daten (JSONL, MongoDB, CSV) an.

Bei einzelnen Produkten ist es jedoch möglich, über die API oder auf der Produktseite über die Revisionsfunktion auf frühere Versionen der Produktdaten zuzugreifen.

Bei jeder Aktualisierung eines Produkts wird eine neue Revisionsnummer (mit steigender Ziffer, beginnend mit 1) erstellt.

Um beispielsweise die erste Revision (=erste Produktversion) dieses Produkts zu erhalten, verwenden Sie

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Der Parameter „rev“ kann analog dazu mit der API verwendet werden:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
