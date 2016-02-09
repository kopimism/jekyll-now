---
layout: page
title: Latest Posts
permalink: /blog/
---

{% for post in site.posts %}
<article class="post">    

<h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

<a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>

</article>

{% endfor %}