---
layout: page
title: Tulisan
permalink: /tulisan/
---

<h3>Posts</h3>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} {{ post.date }} </a>
    </li>
  {% endfor %}
</ul>
[jekyll-organization]: https://github.com/jekyll
