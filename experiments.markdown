---
layout: default
title: Experiments
permalink: /experiments
---

<article class="projects main-content">
  {% for post in site.categories.experiments %}
  <a href="{{ post.url }}" class="project row">
    <div class="project__info col-sm-5">
      <h2 class="project__title">{{ post.title }}<span class="link--arrow"></span></h2>
      <p class="project__summary">{{ post.description }}</p>
      <div class="project__details">
        <p>{{ post.role }}</p>
        <p>{{ post.dates }}</p>
        <p>{{ post.organization }}</p>
      </div>
    </div>
    <div class="project__thumbnail col-sm-6 col-sm-offset-1 first-xs last-sm">
      {% picture {{ post.hero }} %}
    </div>
  </a>
  {% endfor %}
</article>