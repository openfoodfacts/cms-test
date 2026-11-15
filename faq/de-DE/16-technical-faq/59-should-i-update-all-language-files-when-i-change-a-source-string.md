---
title: "Soll ich alle Sprachdateien aktualisieren, wenn ich eine Quellzeichenfolge ändere?"
order: 59
lang: en-gb
category: 16-technische-FAQ
breadcrumbs: [ '/en-gb/', '/en-gb/16-technical-faq/' ]
---

Nein, das tust du nicht. Sie müssen lediglich die englische Version aktualisieren.

- Erstellen Sie Ihren PR

Sobald die Zusammenführung abgeschlossen ist, werden wir crowdin-trigger manuell neu basieren, und das von GitHub Actions ausgelöste Crowdin-Übersetzungssystem erledigt den Rest für andere Sprachen.

Der GitHub-Bot erstellt dann automatisch einen neuen Pull Request, den wir anschließend überprüfen.
