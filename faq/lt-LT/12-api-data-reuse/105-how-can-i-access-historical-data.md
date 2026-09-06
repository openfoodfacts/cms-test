---
title: "Kaip galiu pasiekti istorinius duomenis?"
order: 105
lang: en-gb
category: 12-API-duomenų-pakartotinis-naudojimas
breadcrumbs:
  [
    '/lt-lt/',
    '/lt-lt/12-api-duomenų-pakartotinis-naudojimas/'
  ]
---

Šiuo metu nesiūlome istorinių duomenų išklotinės (JSONL, MongoDB, CSV).

Tačiau atskirų produktų atveju galima pasiekti ankstesnes produkto duomenų versijas naudojant API arba produkto puslapyje naudojant pataisymus.

Kiekvieną kartą atnaujinus produktą, sukuriama nauja versija (didėjanti nuo 1).

Pavyzdžiui, norėdami gauti pirmąją šio produkto versiją (=pirmąją produkto versiją), naudokite

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Panašiai parametras „rev“ gali būti naudojamas su API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
