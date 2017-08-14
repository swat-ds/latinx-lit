---
layout: article
permalink: /blog/
title: Blog
image:
    banner: images/banner-large.jpg
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
      by {{ post.author }}
      {{ post.date }}
      <hr/>
      
    </li>
  {% endfor %}
</ul>