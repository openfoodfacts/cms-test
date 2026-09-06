---
title: "Kijan mwen ka jwenn aksè a done istorik yo?"
order: 105
lang: en-gb
category: 12-api-done-reitilizasyon
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-done-reutilize/' ]
---

Kounye a, nou pa ofri sèvis pou ranmase done istorik (JSONL, MongoDB, CSV).

Sepandan, pou pwodwi endividyèl yo, li posib pou jwenn aksè a vèsyon done pwodwi anvan yo lè l sèvi avèk API a oswa sou paj pwodwi a lè l sèvi avèk revizyon yo.

Chak fwa yo mete yon pwodwi ajou, yo kreye yon nouvo revizyon (chif k ap ogmante apati 1).

Pa egzanp, pou jwenn premye revizyon an (=premye vèsyon pwodwi) nan pwodwi sa a, sèvi ak

https://world.openfoodfacts.org/product/7623186089763/jogurt-baumnuss-migros?rev=1.

Menm jan an tou, ou ka itilize paramèt rev la avèk API a:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
