---
title: "Kuidas ma pääsen ligi ajaloolistele andmetele?"
order: 105
lang: et-gb
category: 12-API-andmete-taaskasutamine
breadcrumbs: [ '/et-ee/', '/et-ee/12-api-andmete-taaskasutamine/' ]
---

Hetkel me ajalooliste andmete väljavõtet (JSONL, MongoDB, CSV) ei paku.

Üksikute toodete puhul on aga võimalik pääseda juurde tooteandmete varasematele versioonidele API kaudu või tootelehel muudatuste abil.

Iga kord, kui toodet värskendatakse, luuakse uus versioon (alates 1-st suurenev number).

Näiteks selle toote esimese redaktsiooni (=esimese tooteversiooni) saamiseks kasutage

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Samamoodi saab parameetrit rev kasutada API-ga:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
