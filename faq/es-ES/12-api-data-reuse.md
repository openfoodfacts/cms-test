---
title: "API y reutilización de datos"
description: "6 preguntas"
lang: es-gb
order: 12
category-level: 0
icon: llave inglesa
---

{{< fa "llave inglesa" size=3x >}}

## ¿Hay recomendaciones en algún lugar de la documentación sobre cuál sería un buen tamaño para las fotos cargadas?

Eso puede depender de los países, si la red es lenta o cara. Cualquier cosa que supere los 5000 píxeles de peso o altura probablemente no sea muy útil. y si de alguna manera puedes detectar que la red es lenta, entonces incluso una imagen de 2000 píxeles sería genial (¡ciertamente mejor que no tener una imagen!)

---

## ¿Qué pasa con los alimentos sin códigos de barras?

Open Food Facts contiene únicamente información sobre alimentos envasados. Para conocer los valores promedio de productos agrícolas (por ejemplo, tomates o plátanos) y otros productos alimenticios, puede utilizar una de las bases de datos nutricionales nacionales oficiales.

**Nota:** La siguiente lista contiene algunas de las bases de datos de alimentos nacionales más importantes. Si cree que alguna otra base de datos debería incluirse en la lista, contáctenos a: [https://world.openfoodfacts.org/contact](https://world.openfoodfacts.org/contact)

**Lista de bases de datos nacionales de alimentos**

-

**Australia** - FSANZ - NUTTAB 2006: [https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf](https://www.foodstandards.gov.au/media/documents/FSANZ%20Conf%20PostersNUTTAB.pdf)

-

**Bélgica** - NUBEL - Datos de composición de alimentos belgas: [https://www.internubel.be](https://www.internubel.be/)

-

**Canadá** - FCEN: [https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp](https://aliments-nutrition.canada.ca/cnf-fce/index-fra.jsp)

-

**República Checa** - Base de datos de composición de alimentos del Instituto Nacional de Salud Pública: [http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp](http://www.chpr.szu.cz/dbdata/foodcomp/nut2001.asp)

-

**Dinamarca** - Banco de datos danés de composición de alimentos: [https://frida.fooddata.dk/?lang=en](https://frida.fooddata.dk/?lang=es)

-

**Estonia** - Base de datos de composición de alimentos de Estonia: [https://tka.nutridata.ee/en/](https://tka.nutridata.ee/en/)

-

**Finlandia** - Base de datos finlandesa de composición de alimentos - FINELI: [https://fineli.fi/fineli/en/index](https://fineli.fi/fineli/en/index)

-

**Francia** - CIQUAL: [https://www.anses.fr/en/search/site/Table%20ciqual](https://www.anses.fr/en/search/site/Table%20ciqual)

-

**Alemania** - Base de datos en línea Souci-Fachmann-Kraut: [https://www.sfk.online/#/home](https://www.sfk.online/#/home) o la base de datos oficial alemana: Bundeslebensmittelschlüssel: [https://blsdb.de/](https://blsdb.de/)

- **Italia** - Banca Dati di Composizione degli Alimenti CREA: [https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati](https://www.crea.gov.it/web/alimenti-e-nutrizione/banche-dati)

-

**Países Bajos** - Base de datos de composición de alimentos holandesa: [https://www.rivm.nl/en/dutch-food-composition-database](https://www.rivm.nl/en/dutch-food-composition-database)

-

**Noruega** - Tabla de composición de alimentos noruega 2006: [https://www.matvaretabellen.no/?language=en](https://www.matvaretabellen.no/?language=en)

-

**Polonia** - Tablas de composición de alimentos: [http://www.izz.waw.pl/en/?lang=en](http://www.izz.waw.pl/en/?lang=en)

-

**España** - Base de datos de composición de alimentos española - BEDCA: [https://www.bedca.net/bdpub/index.php](https://www.bedca.net/bdpub/index.php)

-

**Suiza** - Base de datos suiza de composición de alimentos: [https://www.naehrwertdaten.ch/de/](https://www.naehrwertdaten.ch/de/)

-

**Reino Unido** - Conjunto de datos integrados sobre la composición de los alimentos (CoFID): [https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid](https://www.gov.uk/government/publications/composition-of-foods-integrated-dataset-cofid)

-

**EE.UU.** - USDA: [https://ndb.nal.usda.gov/](https://ndb.nal.usda.gov/)

---

## ¿Puedo buscar un nombre de producto preciso con la API?

Lamentablemente, todavía no es posible realizar búsquedas sencillas y precisas únicamente por nombre de producto a través de la API.

Sin embargo, usar un filtro por categoría podría ayudarle a hacer su búsqueda más precisa.

---

## ¿Cómo puedo acceder/recopilar datos para mis proyectos?

En la página principal de Open Food Facts, en la esquina superior izquierda de la pantalla, hay un menú desplazable. En la parte inferior encontrarás la opción “búsqueda avanzada”, sobre la que podrás hacer clic. Depende entonces de usted determinar qué criterios son los más relevantes para su(s) proyecto(s). Una vez elegido, podrás descargar los resultados obtenidos desplazándote hacia abajo en la parte inferior de la página y haciendo clic en “Descargar resultados”.

También puedes consultar:

- Nuestra documentación de API:[ https://openfoodfacts.github.io/api-documentation/](https://openfoodfacts.github.io/api-documentation/)
- Condiciones de uso de Open Food Facts:[ ](https://world.openfoodfacts.org/terms-of-use)[https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use)
- En nuestros datos:[ https://world.openfoodfacts.org/data](https://world.openfoodfacts.org/data)

---

## ¿Existen condiciones para utilizar la API?

Toda la documentación sobre el uso de la API se puede encontrar en la [página de documentación de la API](https://openfoodfacts.github.io/openfoodfacts-server/api/), pero aquí hay un resumen rápido:

- La base de datos Open Food Facts está disponible como datos abiertos bajo la Licencia de Base de Datos Abierta (ODbL), consulte [https://world.openfoodfacts.org/terms-of-use](https://world.openfoodfacts.org/terms-of-use) para obtener los detalles legales. Las dos condiciones son atribución y compartir por igual. Si combina datos de Open Food Facts con otras bases de datos, entonces la ODbL exige que la base de datos resultante también se publique como datos abiertos. También significa que puedes combinar los datos sólo con fuentes que permitan dicha redistribución.

- **Siempre** debe utilizar un agente de usuario personalizado al realizar llamadas API para identificar su aplicación.

- Se aplican límites de velocidad para cada punto final de API.

---

## ¿Cómo puedo acceder a los datos históricos?

Actualmente, no ofrecemos volcado de datos históricos (JSONL, MongoDB, CSV).

Sin embargo, para productos individuales, es posible acceder a versiones anteriores de los datos del producto utilizando la API o en la página del producto utilizando revisiones.

Cada vez que se actualiza un producto, se crea una nueva revisión (dígito creciente a partir de 1).

Por ejemplo, para obtener la primera revisión (=primera versión del producto) de este producto, utilice

[https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1](https://world.openfoodfacts.org/product/7623186089763/joghurt-baumnuss-migros?rev=1).

De manera similar, el parámetro rev se puede utilizar con la API:

[https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1](https://world.openfoodfacts.org/api/v2/product/7623186089763?rev=1)

---

