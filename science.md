---
layout: page
title: Science
subtitle: What's Happening In Science!?
permalink: /science/
---

<ul>
  {% for post in site.categories.science %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }} on {{ post.date | date: "%B %e, %Y" }}</a></li>
    {% endif %}
  {% endfor %}
</ul>