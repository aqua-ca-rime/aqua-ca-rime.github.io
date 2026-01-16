---
layout: blog
title: "Interventions passées"
teaser: "Liste des différentes interventions de médiation scientifique que nous avons menées jusqu'alors."
header:
    image_fullwidth: "header-bus.jpg"
permalink: "/interventions-passees/"
---
<ul>
    {% for intervention in site.categories.intervention %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ intervention.url }}">{{ intervention.title }}</a></li>
    {% endfor %}
</ul>