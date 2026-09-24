---
layout: default
title: Updates
description: Full archive of research and academic updates.
permalink: /updates/
---

<section class="container">
  <h1>All Updates</h1>
  <ul class="updates-list">
  {% for update in site.data.updates %}
    <li><strong>{{ update.date }}:</strong> {{ update.description | markdownify | remove: '<p>' | remove: '</p>' | strip }}</li>
  {% endfor %}
  </ul>
  <p class="blog-back">
    <a href="{{ '/' | relative_url }}">← Back to home</a>
  </p>
</section>
