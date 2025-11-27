---
layout: default
title: "Agentic Coding Dispatch"
description: "Comparative studies, adoption playbooks, and enterprise architecture insights for AI-first software development."
permalink: /
---

<!-- Hero / Header -->
<div style="text-align:center; padding: 2.5rem 1rem;">
  <img src="/assets/images/header-starwars-antigravity-vs-copilot.png" alt="Antigravity vs Copilot" style="max-width: 980px; width: 100%; border-radius: 8px;">
ploring Google Antigravity, GitHub Copilot, and the agentic future of development—
    with practical guidance for enterprise architects and engineering leaders.
  </p>
</div>

---

## Featured Article

- **Google Antigravity vs GitHub Copilot: A New Hope for Developers**  
  Comparative study, enterprise recommendation matrix, and implementation roadmap.  
  <a href="/blog/antigravity-vs-cop now →</a>

> If your post lives in `_posts/` (e.g., `2025-11-26-antigravity-vs-copilot.md`), Jekyll will generate it under your blog prefix.  
> You can set a custom permalink inside the post’s front matter, e.g.:
> `permalink: /blog/antigravity-vs-copilot/`

---

## Latest Posts

<ul>
  {% for post in site.posts limit:6 %}
    <li style="margin-bottom:0.75rem;">
      <a href="{{ post.url | relative_urlt.title }}</a>
      <span style="color:#888;"> — {{ post.date | date: "%b %d, %Y" }}</span><br>
      <span style="color:#666; font-size:0.95rem;">{{ post.description | default: post.excerpt | strip_html | truncate: 160 }}</span>
    </li>
  {% endfor %}
</ul>

<p>/blog/View all posts →</a></p>

---

## Topics & Tags

<div style="display:flex; flex-wrap:wrap; gap:0.6rem;">
{% assign tags_list = site.tags | sort %}
{% for tag in tags_list %}
  <a href="/tag/{{ tag[0] | slugify }}/" style="font-size:0.95rem; background:#f4f4f4;%}
</div>

---

## Subscribe

- **RSS:** <a href="{{ "/feed.xml"LinkedIn:** Follow Bhuban Mishra for new articles and visuals.

---

## About

I’m **Bhuban Mishra**, Enterprise Architect. I write about agentic development, AI governance, and the shift to autonomous workflows—translating cutting-edge tools into actionable enterprise strategies.

---

<!-- Footer banner -->
<div style="text-align:center; padding: 2rem 0;">
  <img src="/assets/images/footer-may-the-code-be-with-youtle.png
</div>
