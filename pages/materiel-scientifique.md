---
layout: blog
show_meta: false
title: "Matériel scientifique"
subheadline: "Liste du matériel scientifique mobilisé dans le cadre de nos activités de médiation scientifique."
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/ressources/materiel-scientifique/"
---
<ul>
    {% for materiel in site.categories.materiel %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ materiel.url }}">{{ materiel.title }}</a></li>
    {% endfor %}
</ul>