---
title: "Base de conocimientos de Open Food Facts - ¿Debo actualizar todos los archivos de idioma cuando cambie una cadena de origen?"
order: 59
lang: es-es
category: 16-faq-tecnico
breadcrumbs: ['/es-es/', '/es-es/16-faq-tecnico/']
---

No es necesario.

sólo actualice el inglés

Crea tu PR

Una vez que se fusiona, vamos a rebase crowdin-trigger manualmente y el sistema de traducción Crowdin triggerd por GitHub Acciones hará el resto para otros idiomas.

GitHub bot entonces crea un nuevo PR automáticamente que luego revisamos.
