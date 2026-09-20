---
name: sincronizacao-portfolio
metadata:
  category: Operação
description: >-
  Este repositório é só a lista de projetos do portfólio (README.md), nunca código de
  projeto. Ler antes de adicionar, mover ou apagar qualquer arquivo aqui, e antes de
  editar o README pra incluir um projeto novo — o formato e a ordem certa da entrada
  estão aqui.
---

# Este repositório é só a lista — nunca o código

`Luduranoficiall/github.com-Luduranoficiall-portfolio` existe só pra listar, em
`README.md`, todo projeto público do Lucas, separado por tipo. Nunca teve, e nunca deve
ter, código-fonte de projeto nenhum. Isso está na primeira frase do próprio README.

## Antes de commitar qualquer coisa aqui

- **Só `README.md` muda.** Se a tarefa envolve adicionar/editar código, ela é no
  repositório do projeto (`github.com/Luduranoficiall/<nome-do-projeto>`), não aqui.
- Se alguém pedir pra "colocar o projeto aqui" ou "subir o código pra esse repo",
  confirmar antes: quase certamente o pedido é sobre o repositório *próprio* do
  projeto, e a entrada *aqui* é só a linha do índice apontando pra lá.
- Projeto sem repositório próprio ainda **não entra no índice**. Cria o repositório
  dele primeiro, dá push do código, só depois adiciona a linha aqui.

## Formato de cada entrada (seguir exatamente)

Dentro da seção certa (`## Site`, `## Aplicativo`, `## Automação & IA`, `## Sistema`,
`## Jogo`), em ordem alfabética por título:

```markdown
### Título do Projeto

Um ou dois parágrafos curtos: o que é, o que resolve, detalhe técnico que importa.

[Ver online](URL-da-demo) · [Código](URL-do-repo-do-projeto)
```

Sem demo ao vivo: só a linha `[Código](URL-do-repo-do-projeto)`.

## De onde vêm as entradas

O site principal (`Luduranoficiall/Luduranoficiallcom`, pasta `content/projects/*.mdx`)
é sincronizado com este índice — todo projeto que existe lá também existe aqui, com a
mesma URL de repositório. Se uma entrada nova está sendo adicionada aqui, o mesmo
projeto também precisa de entrada em `content/projects/*.mdx` naquele repositório (e um
repositório próprio no GitHub, se ainda não tiver). As três coisas juntas, sempre — ver
a skill `sincronizacao-portfolio` dentro do repositório do site pro checklist completo.
