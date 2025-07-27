---
layout: default
title: Blog
---
## Blog Terbaru

<ul>
  {% for post in site.posts %}
    <li>
      <h3>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </h3>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
