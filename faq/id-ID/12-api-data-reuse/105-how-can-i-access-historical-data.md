---
title: "Bagaimana cara saya mengakses data historis?"
order: 105
lang: bahasa Inggris
category: 12-api-data-reuse
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

Saat ini, kami tidak menyediakan data historis (JSONL, MongoDB, CSV).

Namun, untuk produk individual, dimungkinkan untuk mengakses versi data produk sebelumnya menggunakan API atau di halaman produk menggunakan revisi.

Setiap kali suatu produk diperbarui, revisi baru (angka yang meningkat mulai dari 1) akan dibuat.

Misalnya, untuk mendapatkan revisi pertama (=versi produk pertama) dari produk ini, gunakan

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Demikian pula, parameter rev dapat digunakan dengan API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
