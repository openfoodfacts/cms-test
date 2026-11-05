---
title: "Bagaimanakah saya boleh mengakses data sejarah?"
order: 105
lang: en-gb
category: penggunaan semula data 12-api
breadcrumbs: [ '/en-gb/', '/ms-gb/penggunaan-semula-data-api-12/' ]
---

Pada masa ini, kami tidak menawarkan lambakan data sejarah (JSONL, MongoDB, CSV).

Walau bagaimanapun, untuk produk individu, versi data produk sebelumnya boleh diakses menggunakan API atau pada halaman produk menggunakan semakan semula.

Setiap kali produk dikemas kini, semakan baharu (digit yang meningkat bermula dari 1) akan dicipta.

Contohnya, untuk mendapatkan semakan pertama (=versi produk pertama) produk ini, gunakan

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Begitu juga, parameter rev boleh digunakan dengan API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
