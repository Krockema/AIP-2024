---
layout: page
title: Recap
images:
  - image_path: /assets/img/AIP2024.png
    title: Apple Pie
---

<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>