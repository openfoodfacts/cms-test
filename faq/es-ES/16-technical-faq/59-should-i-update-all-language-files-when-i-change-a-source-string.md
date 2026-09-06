---
title: "¿Debo actualizar todos los archivos de idioma cuando cambio una cadena de origen?"
order: 59
lang: es-gb
category: 16 preguntas frecuentes técnicas
breadcrumbs: [ '/es-gb/', '/es-gb/16-preguntas-tecnicas/' ]
---

No, no lo haces. Solo necesitas actualizar el de inglés.

- Crea tu PR

Una vez fusionado, rebasaremos crowdin-trigger manualmente y el sistema de traducción de Crowdin activado por GitHub Actions hará el resto para otros idiomas.

Luego, el bot de GitHub crea automáticamente un nuevo PR que luego revisamos.
