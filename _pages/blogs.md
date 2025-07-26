---
title: "Blog"
layout: page
permalink: /blogs/
---

<p>Total posts: {{ site.posts | size }}</p>

<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date: "%b %-d, %Y" }} — 
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
