---
layout: page
title: Recap
images:
  - image_path: /AIP-2024/assets/img/orga_team.jpg
    title: Orga Team des Workshops AI in Production - (vlnr) Ute Schmid, Lukas Bahr, Torsten Munkelt, Martin Krockert, Nick Hartmann, Judith Knoblach, Marvin Matthes
  - image_path: /AIP-2024/assets/img/IMG_7305.JPG
    title: Full house!
  - image_path: /AIP-2024/assets/img/IMG_7307.JPG
    title: Julius-Maximilians-Universität Würzburg!    
  - image_path: /AIP-2024/assets/img/Mod.png
    title: Moderiert von Dr. Martin Krockert
---

<h1>Workshop Impressions</h1>

Thank you for having me as your Organizer and Moderator of this awsome Workshop.

<div class="row">
  {% for image in page.images %}
      <div class="col-6"><img src="{{ image.image_path }}" class="shadow-1-strong rounded" style="max-height: 400px;" alt="{{ image.title}}"/></div>
  {% endfor %}
</div>