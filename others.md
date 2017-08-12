---
layout: page
permalink: /others/
title: others
description: other stuffs
---

<ul class="post-list">
{% for others in site.others reversed %}
    <li>
        <h2><a class="others-title" href="{{ others.url | prepend: site.baseurl }}">{{ others.title }}</a></h2>
        <p class="post-meta">{{ others.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>
