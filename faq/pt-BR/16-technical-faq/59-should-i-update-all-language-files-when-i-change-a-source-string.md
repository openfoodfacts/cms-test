---
title: "Devo atualizar todos os arquivos de idioma quando altero uma string de origem?"
order: 59
lang: en-gb
category: 16-perguntas-técnicas
breadcrumbs: [ '/en-gb/', '/en-gb/16-faq-técnicas/' ]
---

Não, você não precisa. Você só precisa atualizar a versão em inglês.

- Crie seu RP

Assim que a integração for concluída, faremos o rebase do crowdin-trigger manualmente e o sistema de tradução do Crowdin, acionado pelo GitHub Actions, cuidará do restante para os outros idiomas.

O bot do GitHub cria então um novo PR automaticamente, que depois revisamos.
