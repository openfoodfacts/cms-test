---
title: "Kif nista' naċċessa dejta storika?"
order: 105
lang: en-gb
category: 12-api-data-use mill-ġdid
breadcrumbs: [ '/mt-gb/', '/mt-gb/12-api-data-reuse/' ]
---

Bħalissa, ma noffrux dump ta' dejta storika (JSONL, MongoDB, CSV).

Madankollu, għal prodotti individwali, huwa possibbli li taċċessa verżjonijiet preċedenti tad-dejta tal-prodott permezz tal-API jew fuq il-paġna tal-prodott permezz ta' reviżjonijiet.

Kull darba li prodott jiġi aġġornat, tinħoloq reviżjoni ġdida (ċifra tiżdied li tibda minn 1).

Pereżempju, biex tikseb l-ewwel reviżjoni (=l-ewwel verżjoni tal-prodott) ta' dan il-prodott, uża

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Bl-istess mod, il-parametru rev jista' jintuża mal-API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
