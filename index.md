---
title: "Welcome to my blog"
---

My programming and embedded system notes

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/my_random_notes{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
