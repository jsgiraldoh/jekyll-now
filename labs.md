---
layout: page
title: Labs de Docker en Español
permalink: /Labs/
---

<div class="posts">
  {% for post in site.categories.labs %}
    <article class="post">
      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
        <div class="entry">
          {{ post.excerpt }}
        </div>
        <div class="date">
          Publicado el {{ post.date | date: "%d/%m/%Y" }}
        </div>
      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">LEER MÁS...</a>
    </article>
  {% endfor %}
</div>