---
title: "In some cases the same product can have different nutritional values for each country, how is this handled in Open Food Facts ?"
order: 58
lang: en-gb
category: 13-volunteering-contribution
breadcrumbs: [ '/en-gb/', '/en-gb/13-volunteering-contribution/' ]
---

99% of the time, producers will create different barcodes for different versions of their products. A famous example is the difference between French and German Nutella in terms of thickness, due to difference in bread across countries. 2 different formulas, 2 different barcodes.

Barcode clash can however happen on shorter codes (EAN-8) that are typically reused by some stores across Europe and the US. We don't currently handle those barcode clashes, but it should be doable to do so by getting the user's general location (it's even more rare to have barcode clashes within a country).

In the long term, we encourage producers to move to EAN-13 to avoid those barcode clashes.
