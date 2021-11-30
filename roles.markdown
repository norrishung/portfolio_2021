---
layout: default
title: Roles
permalink: /roles
---

<article class="roles main-content">
  <a class="role row">
    <div class="col-md-3 col-sm-6 col-xs-12">
      <div class="role__logo">
        {% picture /roles/ideo/ideo_hero.png %}
      </div>
    </div>
    <div class="role__info col-md-3 col-sm-6 col-xs-12">
      <p>Interaction Design Lead</p>
      <p>2021 – Present</p>
    </div>
    <div class="role__summary col-md-6">
      <p>Leading tight-knit design teams in partnership with clients to craft innovative human-centered products and services.</p>
    </div>
  </a>

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
      <p>{{ post.description }} <span class="link--arrow"></span></p>
    </div>
  </a>
  {% endfor %}
</article>