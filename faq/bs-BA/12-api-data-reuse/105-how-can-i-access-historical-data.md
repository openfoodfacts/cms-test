---
title: "Kako mogu pristupiti historijskim podacima?"
order: 105
lang: en-gb
category: 12-api-data-reuse
breadcrumbs: [ '/bs-gb/', '/bs-gb/12-api-data-reuse/' ]
---

Trenutno ne nudimo preuzimanje historijskih podataka (JSONL, MongoDB, CSV).

Međutim, za pojedinačne proizvode moguće je pristupiti prethodnim verzijama podataka o proizvodu pomoću API-ja ili na stranici proizvoda pomoću revizija.

Svaki put kada se proizvod ažurira, kreira se nova revizija (rastuća cifra počevši od 1).

Na primjer, da biste dobili prvu reviziju (=prvu verziju proizvoda) ovog proizvoda, koristite

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Slično tome, parametar rev se može koristiti s API-jem:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
