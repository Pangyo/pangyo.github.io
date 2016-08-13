---
layout: page
title : Categories
description :

---

<ul class="post-list">

  {% for post in site.tags.tech %}
    <li style="display:list-item">
      <h2>
        <a class="post-link" style="color:white" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h2>
    </li>
  {% endfor %}
</ul>
