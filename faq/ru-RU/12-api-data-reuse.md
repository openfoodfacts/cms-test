---
title: "{{< fa wrench size=2x >}} API и повторное использование данных"
description: "6 вопросов"
lang: en-gb
order: 12
category-level: 0
icon: гаечный ключ
---

{{< fa "гаечный ключ" size=3x >}}

## Есть ли в документации рекомендации относительно оптимального размера загружаемых фотографий?

Это может зависеть от страны, от того, насколько медленной или дорогой является сеть. Значения больше 5000 пикселей по весу или высоте, вероятно, не очень полезны. А если вам каким-то образом удастся обнаружить, что сеть работает медленно, то даже изображение в 2000 пикселей будет отличным вариантом (безусловно, лучше, чем отсутствие изображения!).

---

## А что насчет продуктов без штрих-кодов?

Сайт Open Food Facts содержит только информацию о продуктах питания в упаковке. Для получения информации о средних значениях пищевой ценности овощей, фруктов и других продуктов питания (например, помидоров или бананов) можно использовать одну из официальных национальных баз данных по питанию.

**Примечание:** В приведенном ниже списке представлены некоторые из наиболее важных национальных баз данных по продуктам питания. Если вы считаете, что в список следует включить какую-либо другую базу данных, пожалуйста, свяжитесь с нами по адресу: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Список национальных баз данных продуктов питания**

-

**Австралия** – FSANZ – NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Бельгия** - NUBEL - Данные о составе бельгийских продуктов питания: [https://www.internubel.be](https://www.internubel.be/)

-

**Канада** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**Чехия** - База данных состава пищевых продуктов Национального института общественного здравоохранения: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Дания** - Датская база данных состава пищевых продуктов: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Эстония** - Эстонская база данных состава пищевых продуктов: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Финляндия** - Финская база данных состава пищевых продуктов - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**Франция** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Германия** – онлайн-база данных Souci-Fachmann-Kraut: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) или официальная база данных Германии: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **Италия** – Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Нидерланды** - Голландская база данных состава пищевых продуктов: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Норвегия** - Норвежская таблица состава пищевых продуктов 2006 года: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Польша** - Таблицы состава пищевых продуктов: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Испания** - База данных состава испанских продуктов питания - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Швейцария** - Швейцарская база данных состава пищевых продуктов: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**Великобритания** - Интегрированный набор данных о составе продуктов питания (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**США** – Министерство сельского хозяйства США: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Можно ли выполнить поиск по точному названию товара с помощью API?

К сожалению, пока что через API невозможно легко и точно выполнить поиск только по названию продукта.

Использование фильтра по категории может помочь сделать поиск более точным.

---

## Как я могу получить доступ к данным для своих проектов и собрать их?

На главной странице Open Food Facts, в верхнем левом углу экрана, находится прокручиваемое меню. Внизу вы найдете опцию «расширенный поиск», на которую можно нажать. Далее вам предстоит определить, какие критерии наиболее актуальны для вашего проекта (проектов). После выбора вы сможете загрузить полученные результаты, прокрутив страницу вниз и нажав на кнопку «Загрузить результаты».

Вы также можете обратиться за консультацией по следующим вопросам:

- Документация по нашему API: [ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Условия использования Open Food Facts:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- На основе наших данных: [ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Существуют ли какие-либо условия для использования API?

Всю документацию по использованию API можно найти на странице [документации API](https://openfoodfacts.github.io/openfoodfacts-server/api/), но вот краткое изложение:

- База данных Open Food Facts доступна в открытом доступе в соответствии с лицензией Open Database License (ODbL). Подробную юридическую информацию см. в [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use). Эти два условия — это присвоение авторства и равноправное распределение. Если вы объединяете данные из Open Food Facts с данными из других баз данных, то ODbL требует, чтобы полученная база данных также была опубликована как открытые данные. Это также означает, что вы можете объединять данные только с источниками, которые допускают такое распространение.

- Для идентификации вашего приложения при выполнении вызовов API необходимо **всегда** использовать собственный User-Agent.

- Для каждой конечной точки API действуют ограничения на количество запросов.

---

## Как получить доступ к историческим данным?

В настоящее время мы не предоставляем возможность выгрузки исторических данных (JSONL, MongoDB, CSV).

Однако для отдельных товаров можно получить доступ к предыдущим версиям данных о товаре, используя API или на странице товара, используя раздел "Ревизии".

При каждом обновлении продукта создается новая версия (цифра порядкового номера, начиная с 1).

Например, чтобы получить первую редакцию (=первую версию продукта) этого продукта, используйте

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

Аналогичным образом параметр rev можно использовать с API:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

