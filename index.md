---
layout: default
title: "Agentic Coding Dispatch"
description: "Comparative studies, adoption playbooks, and enterprise architecture insights for AI-first software development."
permalink: /
---

# Agentic Coding Dispatch

Exploring Google Antigravity, GitHub Copilot, and the agentic future of development—with practical guidance for enterprise architects and engineering leaders.

---

## Featured Article

**Google Antigravity vs GitHub Copilot: A New Hope for Developers**  
Comparative study, enterprise recommendation matrix, and implementation roadmap.

{{ "/blog/antigravity-vs-copilot/" | relative_url }}

> If your post lives in `_posts/` (e.g., `2025-11-26-antigravity-vs-copilot.md`), set a permalink in the post’s front matter:
>
> ```yaml
> permalink: /blog/antigravity-vs-copilot/
> ```

---

## Latest Posts

<ul>
  {% for post in site.posts limit:6 %}
  <li style="margin-bottom:0.75rem;">
    {{ post.url | relative_url }}{{ post.title }}</a>
    <span style="color:#888;"> — {{ post.date | date: "%b %d, %Y" }}</span><br>
    <span style="color:#666; font-size:0.95rem;">
      {{ post.description | default: post.excerpt | strip_html | truncate: 160 }}
    </span>
  </li>
  {% endfor %}
</ul>

<p>
  {{ View all posts →</a>
</p>

---

## Topics & Tags

<div style="display:flex; flex-wrap:wrap; gap:0.6rem;">
{% assign tags_list = site.tags | sort %}
{% for tag in tags_list %}
  {{ 
    #{{ tag[0] }} ({{ tag[1].size }})
  </a>
{% endfor %}
</div>

---

## Subscribe

- **RSS:** {{ Subscribe to feed</a>  
- **LinkedIn:** Follow **Bhuban Mishra** for new articles and visuals.

---

## About

I’m **Bhuban Mishra**, Enterprise Architect. I write about agentic development, AI governance, and the shift to autonomous workflows—translating cutting-edge tools into actionable enterprise strategies.

---
