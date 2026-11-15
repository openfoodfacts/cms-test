---
title: "Como posso acessar dados históricos?"
order: 105
lang: en-gb
category: 12-reutilização de dados da API
breadcrumbs: [ '/en-gb/', '/en-gb/12-api-data-reuse/' ]
---

Atualmente, não oferecemos a opção de exportar dados históricos (JSONL, MongoDB, CSV).

No entanto, para produtos individuais, é possível acessar versões anteriores dos dados do produto usando a API ou na página do produto, por meio das revisões.

Sempre que um produto é atualizado, uma nova revisão (dígito crescente a partir de 1) é criada.

Por exemplo, para obter a primeira revisão (=primeira versão do produto) deste produto, use

https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1.

Da mesma forma, o parâmetro rev pode ser usado com a API:

https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1
