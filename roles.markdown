---
layout: default
title: Roles
permalink: /roles
---

<article class="roles main-content">
  {% for post in site.categories.roles %}
  <a href="{{ post.url }}" class="role row">
    <div class="col-md-3 col-sm-6 col-xs-12">
      <div class="role__logo">
        {% if post.logo%}{% picture {{ post.logo }} %}{% endif %}
      </div>
    </div>
    <div class="role__info col-md-3 col-sm-6 col-xs-12">
    {% for detail in post.details %}
      <p>{{ detail }}</p>
    {% endfor %}
      <p>{{ post.dates }}</p>
    </div>
    <div class="role__summary col-md-6">
      <p>{{ post.description }} <span class="role__link"></span></p>
    </div>
  </a>
  {% endfor %}
</article>