---
layout: category
title: Poèmes
permalink: /poemes/
---

<div class="posts">
  {% for post in site.posts %}
    {% if post.categories contains "Poèmes" %}
      <article>
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.excerpt }}</p>
      </article>
    {% endif %}
  {% endfor %}
</div>
