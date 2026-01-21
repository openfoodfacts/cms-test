---
title: "Base de conocimientos de Open Food Facts - Me gustaría añadir un nuevo logotipo para las etiquetas"
order: 55
lang: es-es
category: 15-mejorar-open-food-facts-en-mi-lengua-pais
breadcrumbs: ['/es-es/', '/es-es/15-mejorar-open-food-facts-en-mi-lengua-pais/']
---

El proceso es el siguiente

encontrar el nombre canónico de la etiqueta en la taxonomía de las etiquetas (es el primer elemento de la lista de sinónimos de las etiquetas, por ejemplo, es:100% vegetal)

conseguir el logotipo en buena calidad: evitar utilizar la foto del colaborador que no es adecuada para este caso; la mayoría de las etiquetas tienen websistes oficiales de logotipos de alta calidad, a veces en formato vectorial (incluso mejor para nosotros); siempre que utilicemos un logotipo para informar objetivamente de la presencia de una etiqueta en el envase de un producto, no hace falta pedir permiso.

Nombre el archivo así: nombre-de-la-etiqueta.[ancho]x90.png donde ancho es el ancho del logotipo cuando tiene 90 píxeles de alto. Los nombres de los archivos deben ir sin acentos, en minúsculas y con "-" en lugar de espacios.

A continuación, añada el logotipo en el directorio que corresponda a su nombre canónico. Si el nombre canónico es es:algo, entonces tienen que estar en /es/. El directorio raíz para los logotipos es https://github.com/openfoodfacts/openfoodfacts-server/tree/main/html/images/lang
