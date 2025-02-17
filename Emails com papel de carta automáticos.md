---
confidence: certain
date: 2025-02-16T15:11:25-03:00
dg-publish: true
flowerbed:
  - geral
importance: "Trivial "
maturity: sprout
modified: 2025-02-17T17:58:30-03:00
tags: []
---

Tive essa ideia há anos, mas nunca parei para implementá-la.

Papel de carta em #e-mail era comuns nos primórdios do Outlook, onde as pessoas usavam aqueles conteúdos em #HTML e cheio de detalhes.

Hoje, em tempos de pocket e webmails, isso parece um sonho distante.

Então a ideia é jogar essa produção para o servidor #SMTP e isolar o conteúdo do #e-mail, jogar em um HTML e encaminhar para o destinatário. Simples, belo e moral.

Estou pensando em montar um Milter para isso.

<div class="rich-link-card-container"><a class="rich-link-card" href="https://lloydrochester.com/post/unix/process-mail-script-postfix/" target="_blank">
	<div class="rich-link-image-container">
		<div class="rich-link-image" style="background-image: url('https://lloydrochester.com/favicon.ico')">
	</div>
	</div>
	<div class="rich-link-card-text">
		<h1 class="rich-link-card-title">Processing Emails with a script in Postfix</h1>
		<p class="rich-link-card-description">
		Updated Feb 7, 2020 After thinking about this post more, it’s true you can process emails with a script in Postfix. The post provides the right answer to the wrong question!! You can certainly process emails with Postfix but it’s hard, brittle, reduces performance and really isn’t recommended. What is better is to have a client program that reads the mail and does what you desire. This client can be put on a cron job, triggered or run however you want. The client is very flexible and so many different programming languages support them. This gives a lot of power to mark emails read, manage folders, etc … It’s just a cleaner, better, easier to use and test architecture than having a script in Postfix. So I’ll leave this up, but, I wouldn’t use it unless there is some reason I cannot think of how it would be better.
		</p>
		<p class="rich-link-href">
		https://lloydrochester.com/post/unix/process-mail-script-postfix/
		</p>
	</div>
</a></div>

