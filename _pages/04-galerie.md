---
layout: page
title: Recap
images:
  - image_path: /AIP-2024/assets/img/orga_team.jpg
    title: Orga Team des Workshops AI in Production - (vlnr) Ute Schmid, Lukas Bahr, Torsten Munkelt, Martin Krockert, Nick Hartmann, Judith Knoblach, Marvin Matthes
  - image_path: /AIP-2024/assets/img/Mod.png
    title: Moderiert von Dr. Martin Krockert
  - image_path: /AIP-2024/assets/img/IMG_7305.JPG
    title: Full house!
  - image_path: /AIP-2024/assets/img/IMG_7307.JPG
    title: Julius-Maximilians-Universität Würzburg!    
  - image_path: /AIP-2024/assets/img/IMG_7307.JPG
    title: Julius-Maximilians-Universität Würzburg!    
---

<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" class="w-500 shadow-1-strong rounded" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>