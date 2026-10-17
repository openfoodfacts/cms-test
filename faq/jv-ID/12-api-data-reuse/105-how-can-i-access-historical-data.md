---
title: "Kepiye carane aku bisa ngakses data historis?"
order: 105
lang: en-gb
category: Panggunaan maneh data 12-api
breadcrumbs: [ '/en-gb/', '/en-gb/panggunaan-maneh-data-12-api/' ]
---

Saiki, kita ora nawakake dump data historis (JSONL, MongoDB, CSV).

Nanging, kanggo produk individu, bisa ngakses versi data produk sadurunge nggunakake API utawa ing kaca produk nggunakake revisi.

Saben produk dianyari, revisi anyar (angka sing mundhak diwiwiti saka 1) digawe.

Umpamane, kanggo entuk revisi pisanan (=versi produk pisanan) saka produk iki, gunakake

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Semono uga, parameter rev bisa digunakake karo API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
