---
layout: page
title: Tulisan
permalink: /tulisan/
---

<h3>Posts</h3>
  {% for post in site.posts %}
    <a href="{{ post.url }}"> <p>{{ post.title }}</p> </a>
  {% endfor %}

[jekyll-organization]: https://github.com/jekyll
