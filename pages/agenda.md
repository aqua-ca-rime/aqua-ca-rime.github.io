---
layout: page
show_meta: false
title: "Agenda"
subheadline: "Agenda de nos actions de médiation scientifique."
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/agenda/"
---
<ul>
    {% for anecdote in site.categories.anecdotes %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ anecdote.url }}">{{ anecdote.title }}</a></li>
    {% endfor %}
</ul>