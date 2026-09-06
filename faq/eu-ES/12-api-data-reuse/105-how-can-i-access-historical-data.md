---
title: "Nola sar naiteke datu historikoetara?"
order: 105
lang: eu-gb
category: 12-api-datuak-berrerabiltzea
breadcrumbs: [ '/eu-es/', '/eu-es/12-api-datuak-berrerabiltzea/' ]
---

Gaur egun, ez dugu datu historikoen iraulketarik eskaintzen (JSONL, MongoDB, CSV).

Hala ere, produktu indibidualetarako, produktuaren datuen aurreko bertsioetara sar daiteke APIa erabiliz edo produktuaren orrialdean berrikuspenak erabiliz.

Produktu bat eguneratzen den bakoitzean, berrikuspen berri bat sortzen da (1etik hasita digitu gero eta handiagoa).

Adibidez, produktu honen lehen berrikuspena (=lehen produktuaren bertsioa) lortzeko, erabili

https://world.openfoodfacts.org/product/7623186089763/jogurt-baumnuss-migros?rev=1.

Era berean, rev parametroa APIarekin erabil daiteke:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
