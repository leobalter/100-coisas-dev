---
layout: default
---

Quais são as 100 Coisas que você vai realizar na sua carreira de desenvolvimento
em 2016?

Pode ser um Pull Request em um projeto Open Source, ou aquele commit bacana que
lançou uma nova feature. Que tal um projeto novo? Quem sabe um artigo em um
blog, ou até criar um blog novo? Ir para um evento? Assistir uma palestra ou
apresentar uma? Viajar o mundo e participar de encontros locais de
desenvolvimento, conhecer outros desenvolvedores?

A gente acredita que 2016 vai ser um ano excelente, e a gente quer desafiar você
a realizar pelo menos 100 coisas incríveis. Não precisa ser nada complexo nem
difícil, podem ser pequenos atos.

Você pode mandar um PR com a sua lista ou montar a sua própria, assim como
enviar um vídeo incentivando todas as outras pessoas que podem realizar coisas
incríveis.

## Depoimentos de quem já aceitou o desafio

{{ site.depoimentos }}

<ul class="post-list">
  {% for post in site.categories.depoimentos %}
    <li>
      <h3>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>

        {{ post.content }}
      </h3>
    </li>
  {% endfor %}
</ul>

## Quem já fez o seu?

<ul class="post-list">
  {% for post in site.categories.listas %}
    <li>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

      <h2>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h2>
    </li>
  {% endfor %}
</ul>

<p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
