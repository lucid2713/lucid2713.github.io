---
layout: page
permalink: /notes/
title: notes
description: notes for research and project
---

<ul class="post-list">
{% for notes in site.notes reversed %}
    <li>
        <h2><a class="notes-title" href="{{ notes.url | prepend: site.baseurl }}">{{ notes.title }}</a></h2>
        <p class="post-meta">{{ notes.date | date: '%B %-d, %Y — %H:%M' }}</p>
      </li>
{% endfor %}
</ul>
