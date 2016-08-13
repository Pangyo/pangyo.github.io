---
layout: page
title:  Python
tags: tech
permalink: /python/index
---

<ul class="post-list">
  {% for post in site.tags.python %}
    <li style="display:list-item">
      <h2>
        <a class="post-link" style="color:white" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h2>
    </li>
  {% endfor %}
</ul>
