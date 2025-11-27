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

---

## Latest Posts

{% for post in site.posts limit:6 %}
- {{ post.url | relative_url }}  
  *{{ post.date | date: "%b %d, %Y" }}*  
  {{ post.description | default: post.excerpt | strip_html | truncate: 160 }}
{% endfor %}

{{ "/blog/" | relative_url }}

---

## About

I’m **Bhuban Mishra**, Enterprise Architect. I write about agentic development, AI governance, and the shift to autonomous workflows—translating cutting-edge tools into actionable enterprise strategies.
