---
title: "{{< fa wrench size=2x >}} API та повторне використання даних"
description: "6 питань"
lang: en-gb
order: 12
category-level: 0
icon: гайковий ключ
---

{{< fa "гайковий ключ" size="3 рази" >}}

## Чи є десь у документації рекомендації щодо того, який розмір буде оптимальним для завантажених фотографій?

Це може залежати від країни, якщо мережа повільна або дорога. будь-що, що перевищує 5000 пікселів за вагою чи висотою, ймовірно, не дуже корисне. і якщо ви якимось чином можете виявити, що мережа повільна, то навіть зображення з розміром 2000 пікселів було б чудовим (звичайно, краще, ніж взагалі не мати зображення!).

---

## А як щодо їжі без штрих-кодів?

«Відкриті факти про їжу» містять інформацію лише про упаковані продукти харчування. Щоб дізнатися середні значення цін на продукти харчування (наприклад, помідори чи банани) та інші харчові продукти, ви можете скористатися однією з офіційних національних баз даних про харчування.

**Примітка:** Наведений нижче список містить деякі з найважливіших національних баз даних про харчові продукти. Якщо ви вважаєте, що до списку слід включити якусь іншу базу даних, зв’яжіться з нами за адресою: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Список національних баз даних про продукти харчування**

-

**Австралія** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Бельгія** - NUBEL - Дані про склад бельгійських продуктів харчування: [https://www.internubel.be](https://www.internubel.be/)

-

**Канада** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**Чеська Республіка** - База даних складу харчових продуктів у Національному інституті громадського здоров'я: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Данія** - Данський банк даних про склад харчових продуктів: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=en)

-

**Естонія** - Естонська база даних про склад харчових продуктів: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Фінляндія** - Фінська база даних складу харчових продуктів - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**Франція** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Німеччина** - Інтернет-база даних Souci-Fachmann-Kraut: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) або офіційна німецька база даних: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **Італія** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Нідерланди** - База даних складу харчових продуктів Нідерландів: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Норвегія** - Норвезька таблиця складу харчових продуктів 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Польща** - Таблиці складу харчових продуктів: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**Іспанія** - База даних складу харчових продуктів Іспанії - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Швейцарія** - Швейцарська база даних складу харчових продуктів: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**Велика Британія** - Інтегрований набір даних про склад харчових продуктів (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**США** - USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## Чи можу я знайти точну назву продукту за допомогою API?

На жаль, поки що неможливо легко та точно шукати лише за назвою продукту через API.

Однак використання фільтра за категорією може допомогти вам зробити пошук точнішим.

---

## Як я можу отримати доступ до даних/зібрати їх для своїх проектів?

На головній сторінці Open Food Facts, у верхньому лівому куті екрана, є меню, що прокручується. Внизу ви знайдете опцію «розширений пошук», на яку можна натиснути. Тоді вам вирішувати, які критерії є найбільш релевантними для вашого(-их) проекту(-ів). Після вибору ви зможете завантажити отримані результати, прокрутивши вниз сторінку та натиснувши кнопку «Завантажити результати».

Ви також можете проконсультуватися:

- Документація нашого API:[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Умови використання Open Food Facts:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- За нашими даними:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## Чи є умови для використання API?

Всю документацію щодо використання API можна знайти на [сторінці документації API](https://openfoodfacts.github.io/openfoodfacts-server/api/), але ось короткий виклад:

- База даних Open Food Facts доступна як відкриті дані за ліцензією Open Database License (ODbL), юридичні деталі див. за посиланням [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use). Дві умови – це атрибуція та поширення на тих самих умовах. Якщо ви поєднуєте дані з Open Food Facts з іншими базами даних, то ODbL вимагає, щоб отримана база даних також була опублікована як відкриті дані. Це також означає, що ви можете поєднувати дані лише з тими джерелами, які дозволяють такий перерозподіл.

- Ви повинні **завжди** використовувати власний User-Agent під час виконання викликів API для ідентифікації вашої програми.

- Обмеження швидкості застосовуються для кожної кінцевої точки API.

---

## Як я можу отримати доступ до історичних даних?

Наразі ми не пропонуємо дамп історичних даних (JSONL, MongoDB, CSV).

Однак для окремих продуктів можна отримати доступ до попередніх версій даних про продукт за допомогою API або на сторінці продукту за допомогою редакцій.

Щоразу, коли продукт оновлюється, створюється нова редакція (збільшується цифра, починаючи з 1).

Наприклад, щоб отримати першу редакцію (=першу версію продукту) цього продукту, використовуйте

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

Аналогічно, параметр rev можна використовувати з API:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

