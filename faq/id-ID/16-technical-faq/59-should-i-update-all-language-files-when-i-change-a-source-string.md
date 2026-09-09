---
title: "Apakah saya perlu memperbarui semua file bahasa ketika saya mengubah string sumber?"
order: 59
lang: bahasa Inggris
category: 16-pertanyaan-umum-teknis
breadcrumbs: [ '/en-gb/', '/en-gb/16-technical-faq/' ]
---

Tidak, kamu tidak perlu. Anda hanya perlu memperbarui yang berbahasa Inggris.

- Buat PR Anda

Setelah digabungkan, kami akan melakukan rebase crowdin-trigger secara manual dan sistem terjemahan Crowdin yang dipicu oleh GitHub Actions akan melakukan sisanya untuk bahasa lain.

Bot GitHub kemudian secara otomatis membuat PR baru yang kemudian kami tinjau.
