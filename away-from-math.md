---
title: ε-Away from Math
layout: default
permalink: /gallery/
---

When I'm not doing math, I enjoy nature.

<div class="gallery-grid">
  {% assign pics = site.static_files | where_exp: "f", "f.path contains '/assets/gallery/'" %}
  {% assign pics = pics | sort: "path" %}

  {% for img in pics %}
    {% if img.extname == '.jpg' or img.extname == '.jpeg' or img.extname == '.png' or img.extname == '.webp' %}
      <a class="gallery-item" href="{{ img.path | relative_url }}" target="_blank" rel="noopener">
        <img src="{{ img.path | relative_url }}" alt="{{ img.name }}">
      </a>
    {% endif %}
  {% endfor %}
</div>
