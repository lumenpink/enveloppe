---
aliases:
  - Lista De Outras Coisas a Fazer
confidence: possible
date: 2025-01-12T12:57:04.021Z
dg-publish: true
flowerbed:
  - geral
importance: trivial
linter-yaml-title-alias: Lista De Outras Coisas a Fazer
maturity: sprout
modified: 2025-01-13T15:21:03-03:00
status: draft
tags: []
title: Sobre o Blog
---

I have a Dream: One File to Rule Them All

Bom, a ideia é que exista um único arquivo PHP que:

- [ ] compile estaticamente o blog
- [ ] seja um servidor micropub
- [ ] seja uma interface de cliente micropub

[ ] receba e gerencie webmentions

[ ] controle indieauth e indietokens (tá, essa pode esperar)

[ ] Seja um servidor microsub (metade da graça da indieweb está nisso)

Bom, a ideia é que exista um único arquivo PHP para atender todas as demandas, principalmente pela facilidade de implementação que isso traz. Simplesmente coloca um arquivo PHP em uma pasta legível por um servidor web e pronto!

Estou usando parte do mecanismo de usar vários arquivos separados e depois compilá-los em um único arquivo da forma em que é criado a adminer (genial, diga-se de passagem)

Imagine como seria mais simples a adoção da indieweb se o único trabalho fosse de acrescentar um arquivo em um servidor.

E por que estamos pensando em geradores estáticos? Porque é mais fácil de hospedar, mantendo um servidor online apenas para a parte dinâmica (Micropub, microsub e webmentions)

# Lista De Outras Coisas a Fazer

[X] Importar arquivos do Instagram

[X] Suportar duas línguas (português e inglês)

[X] Gerar site a partir da tiddlywiki

[X] Fazer todos os links relativos sempre

[ ] Arrumar o CSS para incluir as abas. (para compartilhar o CSS com o picoshare)

[ ] Ajustar a página inicial dos pensamentos para ser Início ao invés da lista.

[ ] Incluir suporte a uma persona como a Mara <https://xeiaso.net/blog/how-mara-works-2020-09-30/> ou baseado no blobhaj

[ ] Incluir suporte a emojis próprios

[ ] Suportar emojis no nome de quem curtir vindo do Mastodon

[ ] O site deve ser hospedado em IPFS e em Hypercore

[ ] Cópias locais de links externos

[X] Imagens locais

[ ] Implementar suporte aos Whostyles

[ ] Implementar um sistema que permita citar alguém com @

[ ] Permitir o update automático.

[] Editar as imagens com PHP básico.

[] Melhorar o sistema de identificação, como o indielogin

[ ] Implementar Reactions além de curtir

[ ] Corrigir as reactions que vêm do Facebook via webmentions.io

[ ] Implementar um sistema de permalinks reduzidos baseado no picoshare

[] Implementar um sistema de recebimento e moderação de webmentions

# Bugs Conhecidos

[ ] Não aparece o título na lista da artigos

[ ] Não aparece "ahora" na navbar na tradução em espanhol

[ ] Ao clicar no título o link deve apontar para a raiz da língua atual

1. Referências externas

[Minificador](https://github.com/jenstornell/tiny-html-minifier/raw/refs/heads/master/src/TinyHtmlMinifier.php)

[Beautifier](https://github.com/ivanweiler/beautify-html/raw/refs/heads/master/beautify-html.php)

Coisas a fazer no blog
