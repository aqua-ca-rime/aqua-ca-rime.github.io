---
layout: page
title: "Matériel scientifique"
teaser: "Liste du matériel scientifique mobilisé dans le cadre de nos activités de médiation scientifique."
header:
   image_fullwidth: "header-ondes-internes.jpg"
permalink: "/ressources/materiel-scientifique/"
---
<ul>
    {% for materiel in site.categories.materiel %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ materiel.url }}">{{ materiel.title }}</a></li>
    {% endfor %}
</ul>