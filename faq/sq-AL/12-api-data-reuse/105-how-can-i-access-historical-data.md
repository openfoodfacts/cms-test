---
title: "Si mund të hyj në të dhënat historike?"
order: 105
lang: en-gb
category: Ripërdorimi i të dhënave 12-api
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

Aktualisht, ne nuk ofrojmë grumbullim të të dhënave historike (JSONL, MongoDB, CSV).

Megjithatë, për produkte individuale, është e mundur të qaseni në versionet e mëparshme të të dhënave të produktit duke përdorur API-n ose në faqen e produktit duke përdorur rishikimet.

Sa herë që përditësohet një produkt, krijohet një version i ri (shifër në rritje duke filluar nga 1).

Për shembull, për të marrë versionin e parë (=versionin e parë të produktit) të këtij produkti, përdorni

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Në mënyrë të ngjashme, parametri rev mund të përdoret me API-në:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
