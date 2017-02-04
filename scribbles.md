---
layout: page
permalink: /scribbles/
title: scribbles
description: drawings, pictures, writing and other trivial works
---

<ul class="post-list">
{% for scribbles in site.scribbles reversed %}
    <li>
        <h2><a class="scribbles-title" href="{{ scribbles.url | prepend: site.baseurl }}">{{ scribbles.title }}</a></h2>
        <p class="post-meta">{{ scribbles.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>
