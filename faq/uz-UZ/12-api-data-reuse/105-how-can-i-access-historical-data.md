---
title: "Tarixiy ma'lumotlarga qanday kirishim mumkin?"
order: 105
lang: en-gb
category: 12-api-ma'lumotlarini qayta ishlatish
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

Hozirda biz tarixiy ma'lumotlarni (JSONL, MongoDB, CSV) saqlashni taklif qilmaymiz.

Biroq, individual mahsulotlar uchun mahsulot ma'lumotlarining oldingi versiyalariga API yordamida yoki mahsulot sahifasida tuzatishlar yordamida kirish mumkin.

Har safar mahsulot yangilanganda, yangi tahrir (1 dan boshlab ortib boruvchi raqam) yaratiladi.

Masalan, ushbu mahsulotning birinchi versiyasini (=birinchi mahsulot versiyasini) olish uchun foydalaning

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Xuddi shunday, rev parametri API bilan ishlatilishi mumkin:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
