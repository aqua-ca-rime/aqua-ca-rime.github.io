---
layout: page
title: "Anecdotes"
teaser: "Liste d'anecdotes en lien avec les objets géoscientifiques."
header:
   image_fullwidth: "header-ondes-internes.jpg"
permalink: "/anecdotes/"
---
<ul>
    {% for anecdote in site.categories.anecdotes %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ anecdote.url }}">{{ anecdote.title }}</a></li>
    {% endfor %}
</ul>