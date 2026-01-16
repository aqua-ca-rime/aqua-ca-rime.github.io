---
layout: blog
show_meta: false
title: "Galerie d'images"
subheadline: "Quelques photos prises lors de nos interventions !"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/ressources/galerie-dimages/"
---
<ul>
    {% for image in site.categories.image %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ image.url }}">{{ image.title }}</a></li>
    {% endfor %}
</ul>