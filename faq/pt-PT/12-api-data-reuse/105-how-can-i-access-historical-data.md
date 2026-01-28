---
title: "Como posso aceder aos dados históricos?"
order: 105
lang: pt-gb
category: 12-reutilização de dados da API
breadcrumbs: [ '/pt-gb/', '/pt-gb/12-api-data-reuse/' ]
---

Atualmente não disponibilizamos a opção de exportar dados históricos (JSONL, MongoDB, CSV).

No entanto, para produtos individuais, é possível aceder a versões anteriores dos dados do produto utilizando a API ou na página do produto, através das revisões.

Sempre que um produto é atualizado, é criada uma nova revisão (dígito crescente a partir de 1).

Por exemplo, para obter a primeira revisão (=primeira versão do produto) deste produto, utilize

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Da mesma forma, o parâmetro rev pode ser utilizado com a API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
