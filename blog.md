---
layout: page
title: Blogs
permalink: /blog/
---

## Latest Posts
  {% for post in site.posts %}
    <article class="post">    
      
      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}