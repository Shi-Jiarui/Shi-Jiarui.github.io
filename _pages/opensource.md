---
layout: archive
title: "open code"
permalink: /opensource/
author_profile: true
---

{% include base_path %}

{% for project in site.data.opensource %}
  <div class="archive__item">
    <h3 class="archive__item-title">
      <a href="{{ project.url }}">{{ project.name }}</a>
    </h3>
    <div class="archive__item-excerpt">
      <p>{{ project.description }}</p>
    </div>
  </div>
{% endfor %}