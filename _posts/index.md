---
layout: default
title: "All Posts"
permalink: /blog/
---

# All Posts

<ul>
  {% for post in site.posts %}
    <li style="margin-bottom:0.75rem;">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</pan style="color:#888;"> — {{ post.date | date: "%b %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
