---
title: "Cum pot accesa datele istorice?"
order: 105
lang: en-gb
category: 12-api-data-reuse
breadcrumbs: [ '/ro-gb/', '/ro-gb/12-api-data-reuse/' ]
---

În prezent, nu oferim servicii de dump de date istorice (JSONL, MongoDB, CSV).

Totuși, pentru produse individuale, este posibil să accesați versiunile anterioare ale datelor despre produs utilizând API-ul sau pe pagina produsului, utilizând revizii.

De fiecare dată când un produs este actualizat, se creează o nouă revizie (cifră crescătoare începând de la 1).

De exemplu, pentru a obține prima revizie (=prima versiune a acestui produs), utilizați

https://world.openfoodfacts.org/product/7623186089763/jogurt-baumnuss-migros?rev=1.

În mod similar, parametrul rev poate fi utilizat cu API-ul:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
