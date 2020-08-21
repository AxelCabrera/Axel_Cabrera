---
layout: page
title: "Indice del Blog"
permalink: /Index/
---

Aqui puede ver las entradas en el Blog, empezando con la mas reciente:


<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

    </article>
  {% endfor %}
</div>
