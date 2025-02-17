---
aliases:
  - Primeiro Porque Uma Versão Estática
confidence: possible
date: 2025-01-01T16:03:24.540Z
dg-publish: true
flowerbed:
  - geral
importance: trivial
linter-yaml-title-alias: Primeiro Porque Uma Versão Estática
maturity: sprout
modified: 2025-01-13T15:06:43-03:00
status: draft
tags:
  - TaskBlog
title: Blog compilado estaticamente em PHP
---

# Primeiro Porque Uma Versão Estática

Porque versões estáticas são portáteis, podem ser hospedadas gratuitamente em vários lugares e ainda permitem ser distribuídas por IPFS ou pelo Protocolo Hypercore. Em suma, é a versão definitiva de um site pessoal.

Estou pensando em usar como base o [simple-template-engine](https://github.com/ddycai/simple-template-engine/tree/master) ou talvez [lightweight template engine](https://codeshack.io/lightweight-template-engine-php/)

Embora já esteja sem atualizações há 10 anos, aparentemente está bem alinhando com a minha ideia.

Na verdade eu penso muito em fazer simplesmente uma versão PHP do bashblog, então, até que estamos indo bem.

Os tipos que serão aceitos são:

1. Nota: um texto curto* sem imagem
1. Imagem: uma ou mais fotos seguidas de um texto curto*.
1. Artigo: Texto longo, com ou sem fotos no texto.
1. Resposta: Texto de qualquer tamanho sobre outra publicação.
1. Marcadores: Apenas o link para outra publicação, sem comentários
1. Curtidas: Uma aprovação sobre outra publicação.
1. Leituras: Ficha de leitura de um livro
1. Republicações: Republicação do conteúdo total ou parcial de outro site com referências
1. Confirmações: Confirmações de presenças em eventos
1. Pensamentos: Postagens feitas a partir da wiki de pensamentos conclusos ou não
1. Diários: Pequenos textos sobre como foi o dia

* Texto curto: até 480 caracteres (conceito arbitrário dado por mim)
