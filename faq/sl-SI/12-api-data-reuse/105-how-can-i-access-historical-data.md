---
title: "Kako lahko dostopam do zgodovinskih podatkov?"
order: 105
lang: sl-gb
category: 12-api-data-reuse
breadcrumbs: [ '/sl-si/', '/sl-si/ponovna-uporaba-podatkov-12-api/' ]
---

Trenutno ne ponujamo izpisa zgodovinskih podatkov (JSONL, MongoDB, CSV).

Vendar pa je za posamezne izdelke mogoče dostopati do prejšnjih različic podatkov o izdelku z uporabo API-ja ali na strani izdelka z uporabo revizij.

Vsakič, ko je izdelek posodobljen, se ustvari nova revizija (naraščajoča števka od 1).

Na primer, če želite dobiti prvo revizijo (=prvo različico izdelka) tega izdelka, uporabite

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Podobno se lahko parameter rev uporablja z API-jem:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
