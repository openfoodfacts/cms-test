---
title: "Czy powinienem aktualizować wszystkie pliki językowe po zmianie ciągu źródłowego?"
order: 59
lang: en-gb
category: 16-techniczne-faq
breadcrumbs: [ '/pl-pl/', '/pl-pl/16-technical-faq/' ]
---

Nie, nie zrobisz tego. Wystarczy zaktualizować wersję angielską

- Utwórz swój PR

Po scaleniu ręcznie zmienimy bazę crowdin-trigger, a system tłumaczeń Crowdin uruchomiony przez GitHub Actions zajmie się resztą w przypadku innych języków.

Bot GitHub automatycznie tworzy nowe żądanie żądania, które następnie sprawdzamy.
