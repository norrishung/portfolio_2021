---
layout: default
title: Thoughts
permalink: /thoughts
---

<article class="thoughts main-content">
  {% for post in site.categories.thoughts %}
  <a href="{{ post.url }}" class="thought row">
    <div class="thought__date col-sm-offset-3 col-sm-3 last-xs first-sm">{{ post.date | date: "%b %-d, %Y" }}</div>
    <div class="thought__info col-sm-6">
      <h2 class="thought__title">{{ post.title }}<span class="thought__link"></span></h2>
      <p class="thought__summary">{{ post.description }}</p>
    </div>
  </a>
  {% endfor %}
</article>