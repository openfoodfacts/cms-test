---
title: "{{< fa edit size=2x >}} Voluntariado / Contribución"
description: "3 preguntas"
lang: es-gb
order: 13
category-level: 0
icon: modificar
---

{{< fa "modificar" size=3x >}}

## ¿Hay alguna forma de eliminar las imágenes cargadas de los productos?

Sólo los moderadores pueden eliminar fotos, para evitar posibles actos vandálicos.

Simplemente pregunte en Slack o en **contact@openfoodfacts.org** para eliminar sus duplicados o cualquier foto inapropiada (debe intentar proporcionar el número de código de barras o la URL para hacerlo).

También tenemos una nueva API de informes de imágenes si eres programador.

---

## Soy diseñador. ¿Cómo puedo ayudar?

Coordinamos todas las actividades relacionadas con el diseño en [https://github.com/openfoodfacts/openfoodfacts-design](https://github.com/openfoodfacts/openfoodfacts-design) y en un canal de chat dedicado. Regularmente realizamos reuniones de equipo y sesiones de reflexión sobre desafíos específicos.

---

## En algunos casos el mismo producto puede tener diferentes valores nutricionales para cada país, ¿cómo se gestiona esto en Open Food Facts?

El 99% de las veces, los productores crearán códigos de barras diferentes para diferentes versiones de sus productos. Un ejemplo famoso es la diferencia entre la Nutella francesa y la alemana en términos de grosor, debido a las diferencias en el pan de los distintos países. 2 fórmulas diferentes, 2 códigos de barras diferentes.

Sin embargo, pueden producirse conflictos de códigos de barras en códigos más cortos (EAN-8) que suelen reutilizar algunas tiendas en Europa y Estados Unidos. Actualmente no manejamos esos conflictos de códigos de barras, pero debería ser posible hacerlo obteniendo la ubicación general del usuario (es aún más raro tener conflictos de códigos de barras dentro de un país).

A largo plazo, alentamos a los productores a migrar a EAN-13 para evitar conflictos de códigos de barras.

---

