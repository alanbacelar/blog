---
layout: post
title:  "Iniciando o nosso blog com Jekyll"
resume: "Há algum tempo eu mantinha uma vontade de aprender novas linguagens, ferramentas e compartilhar esses novos conhecimentos com quem está começando. Daí saiu a ideia de criar um blog e a ferramenta escolhida para desenvolvê-lo foi o Jekyll."
date:   2014-04-23 20:34
update: 2014-04-23 20:34
categories: jekyll
---

[Jekyll](http://jekyllrb.com) é um gerador de códigos estáticos, desenvolvido em Ruby, para criação de sites e blogs sem a necessidade de usar banco de dados. Mas como funciona? Jekyll usa a linguagem de template [Liquid](http://docs.shopify.com/themes/liquid-basics) para processar seus dados. Assim, você cria suas páginas em HTML e utiliza as tags de template para exibir os dados de maneira dinâmica. 

Para criar um novo post, por exemplo, basta criar uma nova página no formato [Markdown](http://daringfireball.net/projects/markdown) (ou [Textile](http://textile.sitemonks.com)), nomeá-la com um padrão determinado e salvá-la no diretório ``_post``. Automaticamente, esses arquivos serão convertidos em HTML e organizados em ordem cronológica. Massa, né?

##Quick-start

Para começar a brincar com o Jekyll é bem simples, veja:

**Instalando:**

	gem install jekyll

**Criando um novo projeto:**

	jekyll new meublog

**Startando o servidor:**

	cd meublog
	jekyll serve --watch

Quem usa pré-processadores como Sass ou Less, vai estar bem familiarizado com o parâmetro ``--watch`` ou simplesmente ``--w``, que server para construir o projeto toda vez que você fizer alguma modificação em seus arquivos.

Pronto! Agora basta acessar o endereço <http://localhost:4000> para ver a aplicação rodando. Lembrando que é necessário ter instalado o Ruby e a RubyGems na sua máquina.

##Conclusão

Escolhi Jekyll por achá-lo bem simples, produtivo e por fornecer acesso rápido ao usuário. Mas existem várias outras ferramentas semelhantes como o [Middleman](http://middlemanapp.com/) e o [Nanoc](http://nanoc.ws/). Veja qual se encaixa melhor em seu projeto e corra pro abraço! :)
