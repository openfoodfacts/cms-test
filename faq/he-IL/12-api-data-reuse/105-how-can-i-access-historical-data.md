---
title: "כיצד ניתן לגשת לנתונים היסטוריים?"
order: 105
lang: en-gb
category: 12-API-שימוש חוזר בנתונים
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

נכון לעכשיו, איננו מציעים אפשרות לאיסוף נתונים היסטוריים (JSONL, MongoDB, CSV).

עם זאת, עבור מוצרים בודדים, ניתן לגשת לגרסאות קודמות של נתוני המוצר באמצעות ה-API או בדף המוצר באמצעות גרסאות.

בכל פעם שמוצר מתעדכן, נוצרת גרסה חדשה (ספרה עולה החל מ-1).

לדוגמה, כדי לקבל את הגרסה הראשונה (=גרסת המוצר הראשונה) של מוצר זה, השתמש

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

באופן דומה, ניתן להשתמש בפרמטר rev עם ה-API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
