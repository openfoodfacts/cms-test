---
title: "{{< fa wrench size=2x >}} API e reutilização de dados"
description: "6 perguntas"
lang: en-gb
order: 12
category-level: 0
icon: chave inglesa
---

{{< fa "chave inglesa" size=3x >}}

## Existe alguma recomendação na documentação sobre qual seria um bom tamanho para as fotos enviadas?

Isso pode depender do país, se a rede for lenta ou cara. Qualquer coisa acima de 5000 pixels em largura ou altura provavelmente não é muito útil. E se você conseguir detectar de alguma forma que a rede está lenta, então mesmo uma imagem de 2000 pixels seria ótima (certamente melhor do que não ter imagem nenhuma!).

---

## E quanto aos alimentos sem código de barras?

O Open Food Facts contém apenas informações sobre alimentos embalados. Para valores médios de produtos agrícolas (por exemplo, tomates ou bananas) e outros produtos alimentícios, você pode usar um dos bancos de dados nacionais oficiais de nutrição.

**Nota:** A lista abaixo contém alguns dos bancos de dados nacionais de alimentos mais importantes. Se você acha que algum outro banco de dados deveria ser incluído na lista, entre em contato conosco em: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Lista de Bancos de Dados Nacionais de Alimentos**

-

**Austrália** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Bélgica** - NUBEL - Dados de composição de alimentos belgas: [https://www.internubel.be](https://www.internubel.be/)

-

**Canadá** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**República Tcheca** - Banco de Dados de Composição de Alimentos no Instituto Nacional de Saúde Pública: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Dinamarca** - Banco de Dados Dinamarquês de Composição de Alimentos: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Estônia** - Banco de Dados de Composição de Alimentos da Estônia: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finlândia** - Banco de Dados Finlandês de Composição de Alimentos - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**França** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Alemanha** - Banco de dados online Souci-Fachmann-Kraut: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) ou o banco de dados oficial alemão: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **Itália** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Países Baixos** - Banco de Dados Holandês de Composição de Alimentos: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Noruega** - Tabela de Composição de Alimentos da Noruega 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Polônia** - Tabelas de Composição de Alimentos: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Espanha** - Banco de Dados de Composição de Alimentos Espanhóis - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Suíça** - Banco de Dados Suíço de Composição de Alimentos: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**Reino Unido** - Conjunto de dados integrados sobre a composição dos alimentos (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**EUA** - USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Posso pesquisar um nome de produto específico usando a API?

Infelizmente, ainda não é possível pesquisar facilmente e com precisão apenas pelo nome do produto através da API.

Utilizar um filtro por categoria pode ajudar a tornar sua busca mais precisa.

---

## Como posso acessar/coletar dados para meus projetos?

Na página principal do Open Food Facts, no canto superior esquerdo da tela, há um menu de rolagem. Na parte inferior, você encontrará a opção "busca avançada", na qual você pode clicar. Caberá a você determinar quais critérios são os mais relevantes para o(s) seu(s) projeto(s). Após selecionar a opção desejada, você poderá baixar os resultados obtidos rolando a página até o final e clicando em “Baixar resultados”.

Você também pode consultar:

- Nossa documentação da API: [ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Termos de Uso do Open Food Facts: [ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- Em nossos dados: [ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Existem condições para usar a API?

Toda a documentação sobre o uso da API pode ser encontrada na [página de documentação da API](https://openfoodfacts.github.io/openfoodfacts-server/api/), mas aqui está um breve resumo:

- O banco de dados Open Food Facts está disponível como dados abertos sob a Licença de Banco de Dados Aberto (ODbL), veja [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) para detalhes legais. As duas condições são atribuição e compartilhamento igual. Se você combinar dados do Open Food Facts com outros bancos de dados, o ODbL exige que o banco de dados resultante também seja disponibilizado como dados abertos. Significa também que você só pode combinar os dados com fontes que permitam essa redistribuição.

- Você deve **sempre** usar um User-Agent personalizado ao realizar chamadas de API para identificar seu aplicativo.

- Os limites de taxa são aplicados a cada endpoint da API.

---

## Como posso acessar dados históricos?

Atualmente, não oferecemos a opção de exportar dados históricos (JSONL, MongoDB, CSV).

No entanto, para produtos individuais, é possível acessar versões anteriores dos dados do produto usando a API ou na página do produto, por meio das revisões.

Sempre que um produto é atualizado, uma nova revisão (dígito crescente a partir de 1) é criada.

Por exemplo, para obter a primeira revisão (=primeira versão do produto) deste produto, use

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

Da mesma forma, o parâmetro rev pode ser usado com a API:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

