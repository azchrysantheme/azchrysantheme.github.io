---
layout: category
title: Projets
permalink: /projets/
---

<div class="posts">
  {% for post in site.posts %}
    {% if post.categories contains "Projets" %}
      <article>
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.excerpt }}</p>
      </article>
    {% endif %}
  {% endfor %}
</div>
