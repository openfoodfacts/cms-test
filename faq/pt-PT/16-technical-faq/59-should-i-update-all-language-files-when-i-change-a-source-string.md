---
title: "Devo atualizar todos os ficheiros de idioma quando altero uma string de origem?"
order: 59
lang: pt-gb
category: 16-perguntas-técnicas
breadcrumbs: [ '/pt-gb/', '/pt-gb/16-faq-técnicas/' ]
---

Não, não precisa. Só precisa de atualizar a versão em inglês.

- Crie o seu RP

Assim que a integração estiver concluída, faremos o rebase do crowdin-trigger manualmente e o sistema de tradução do Crowdin, acionado pelo GitHub Actions, tratará do restante para os outros idiomas.

O bot do GitHub cria então um novo PR automaticamente, que depois revemos.
