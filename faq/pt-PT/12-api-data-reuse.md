---
title: "{{< fa wrench size=2x >}} API e reutilização de dados"
description: "6 perguntas"
lang: pt-gb
order: 12
category-level: 0
icon: chave inglesa
---

{{< fa "chave inglesa" size=3x >}}

## Existe alguma recomendação na documentação sobre qual seria um bom tamanho para as fotos enviadas?

Isto pode depender do país, se a rede for lenta ou cara. Qualquer coisa acima de 5000 pixels em largura ou altura provavelmente não é muito útil. E se conseguir detetar de alguma forma que a rede está lenta, então mesmo uma imagem de 2000 pixéis seria ótima (certamente melhor do que não ter imagem nenhuma!).

---

## E quanto aos alimentos sem código de barras?

O Open Food Facts contém apenas informações sobre alimentos embalados. Para valores médios de produtos agrícolas (por exemplo, tomate ou banana) e outros produtos alimentares, pode utilizar uma das bases de dados nacionais oficiais de nutrição.

**Nota:** A lista abaixo contém algumas das bases de dados nacionais de alimentos mais importantes. Se acha que alguma outra base de dados deveria ser incluída na lista, por favor contacte-nos para: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Lista de Bases de Dados Nacionais de Alimentos**

-

**Austrália** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Bélgica** - NUBEL - Dados de composição dos alimentos belgas: [https://www.internubel.be](https://www.internubel.be/)

-

**Canadá** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**República Checa** - Base de Dados de Composição de Alimentos no Instituto Nacional de Saúde Pública: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Dinamarca** - Base de Dados Dinamarquesa de Composição de Alimentos: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Estónia** - Base de Dados de Composição de Alimentos da Estónia: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finlândia** - Base de Dados Finlandesa de Composição de Alimentos - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**França** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Alemanha** - Base de dados online Souci-Fachmann-Kraut: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) ou a base de dados oficial alemã: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **Itália** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Países Baixos** - Base de Dados Holandesa de Composição de Alimentos: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Noruega** - Tabela de Composição dos Alimentos da Noruega 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Polónia** - Tabelas de Composição dos Alimentos: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Espanha** - Base de Dados de Composição de Alimentos Espanhóis - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Suíça** - Base de Dados Suíço de Composição de Alimentos: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**Reino Unido** - Conjunto de dados integrados sobre a composição dos alimentos (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**EUA** - USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Posso pesquisar um nome de produto específico utilizando a API?

Infelizmente, ainda não é possível pesquisar facilmente e com precisão apenas pelo nome do produto através da API.

Utilizar um filtro por categoria pode ajudar a tornar a sua pesquisa mais precisa.

---

## Como posso aceder/recolher dados para os meus projetos?

Na página principal do Open Food Facts, no canto superior esquerdo do ecrã, existe um menu de rolagem. Na parte inferior encontrará a opção "pesquisa avançada", na qual pode clicar. Caber-lhe-á a si determinar quais os critérios mais relevantes para o(s) seu(s) projeto(s). Após selecionar a opção pretendida, poderá descarregar os resultados obtidos fazendo scroll até ao final e clicando em “Descarregar resultados”.

Pode também consultar:

- A documentação da nossa API: [ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Termos de Utilização do Open Food Facts: [ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- Nos nossos dados: [ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Existem condições para utilizar a API?

Toda a documentação sobre a utilização da API pode ser encontrada na [página de documentação da API](https://openfoodfacts.github.io/openfoodfacts-server/api/), mas aqui está um breve resumo:

- A base de dados Open Food Facts está disponível como dados abertos sob a Open Database License (ODbL), ver [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) para detalhes legais. As duas condições são a atribuição e a partilha igualitária. Se combinar os dados do Open Food Facts com outras bases de dados, o ODbL exige que a base de dados resultante também seja disponibilizada como dados abertos. Significa também que só pode combinar os dados com fontes que permitam essa redistribuição.

- Deve **sempre** utilizar um User-Agent personalizado ao realizar chamadas de API para identificar a sua aplicação.

- Os limites de taxa são aplicados a cada endpoint da API.

---

## Como posso aceder aos dados históricos?

Atualmente não disponibilizamos a opção de exportar dados históricos (JSONL, MongoDB, CSV).

No entanto, para produtos individuais, é possível aceder a versões anteriores dos dados do produto utilizando a API ou na página do produto, através das revisões.

Sempre que um produto é atualizado, é criada uma nova revisão (dígito crescente a partir de 1).

Por exemplo, para obter a primeira revisão (=primeira versão do produto) deste produto, utilize

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

Da mesma forma, o parâmetro rev pode ser utilizado com a API:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

