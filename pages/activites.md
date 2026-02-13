---
layout: page
title: "Activités"
teaser: "Liste des activités de médiation scientifique que nous avons menées jusqu'alors."
header:
    image_fullwidth: "header-ondes-internes.jpg"
permalink: "/activites/"
---
<ul>
    {% for activite in site.categories.activite %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ activite.url }}">{{ activite.title }}</a></li>
    {% endfor %}
</ul>