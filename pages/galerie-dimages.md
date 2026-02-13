---
layout: page
title: "Galerie d'images"
teaser: "Quelques photos prises lors de nos interventions !"
header:
   image_fullwidth: "header-ondes-internes.jpg"
permalink: "/ressources/galerie-dimages/"
---
<ul>
    {% for image in site.categories.image %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ image.url }}">{{ image.title }}</a></li>
    {% endfor %}
</ul>