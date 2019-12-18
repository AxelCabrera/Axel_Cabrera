---
layout: page
title: "Indice de clases"
permalink: /Index/
---

Aqui puede ver las clases agregadas, empezando con la mas reciente:


<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

    </article>
  {% endfor %}
</div>
