---
layout: default
title: Roles
permalink: /roles
---

<article class="roles main-content">
  <a class="role row">
    <div class="col-md-3 col-sm-6 col-xs-12">
      <div class="role__logo">
        <picture>
          <source srcset="/images/logos/regrow/regrow_logo_white.png" media="(prefers-color-scheme: dark)">
          <img src="/images/logos/regrow/regrow_logo_color.png" alt="Regrow">
        </picture>
      </div>
    </div>
    <div class="role__info col-md-3 col-sm-6 col-xs-12">
      <p>Director of Product Design</p>
      <p>2022 – Present</p>
    </div>
    <div class="role__summary col-md-6">
      <p>Currently collaborating with a global team of farmers and climate scientists to create a more resilient food system and reverse climate change by accelerating the world's transition to regenerative agriculture.</p>
    </div>
  </a>

  <a class="role row">
    <div class="col-md-3 col-sm-6 col-xs-12">
      <div class="role__logo">
        <picture>
          <source srcset="/images/logos/ideo/ideo_logo_white.png" media="(prefers-color-scheme: dark)">
          <img src="/images/logos/ideo/ideo_logo_color.png" alt="Ideo">
        </picture>
      </div>
    </div>
    <div class="role__info col-md-3 col-sm-6 col-xs-12">
      <p>Interaction Design Lead</p>
      <p>2021 – 2022</p>
    </div>
    <div class="role__summary col-md-6">
      <p>Led interdisciplinary teams to create positive impact by working with clients to create human-centered products, services, and organizations.</p>
    </div>
  </a>

  {% for post in site.categories.roles %}
  <a href="{{ post.url }}" class="role row">
    <div class="col-md-3 col-sm-6 col-xs-12">
      <div class="role__logo">
        {% if post.logo%}
        <picture>
          <source srcset="{{ post.logo }}_white.png" media="(prefers-color-scheme: dark)">
          <img src="{{ post.logo }}_color.png" alt="CIID">
        </picture>
        {% endif %}
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