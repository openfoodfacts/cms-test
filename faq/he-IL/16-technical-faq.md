---
title: "{{< fa brands github size=2x >}} Technical FAQ"
description: "שאלה אחת"
lang: en-gb
order: 16
category-level: 0
icon: brands github
---

{{< fa "מותגים" "github" size=3x >}}

## האם עליי לעדכן את כל קובצי השפה עקב שינוי מחרוזת מקור?

לא, אין צורך. צריך לעדכן רק את המחרוזת באנגלית

- ליצור את בקשת המשיכה (PR) שלך

Once it's merged, we will rebase crowdin-trigger manually and the Crowdin translation system triggerd by GitHub Actions will do the rest for other languages.

GitHub bot then creates a new PR automatically that we then review.

---

