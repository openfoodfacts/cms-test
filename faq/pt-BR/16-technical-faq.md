---
title: "{{< fa brands github size=2x >}} Perguntas frequentes técnicas"
description: "1 pergunta"
lang: en-gb
order: 16
category-level: 0
icon: marcas github
---

{{< fa "marcas" "github" size=3x >}}

## Devo atualizar todos os arquivos de idioma quando altero uma string de origem?

Não, você não precisa. Você só precisa atualizar a versão em inglês.

- Crie seu RP

Assim que a integração for concluída, faremos o rebase do crowdin-trigger manualmente e o sistema de tradução do Crowdin, acionado pelo GitHub Actions, cuidará do restante para os outros idiomas.

O bot do GitHub cria então um novo PR automaticamente, que depois revisamos.

---

