---
layout: page
title: Archive
---

<ul class="this">
{%for post in site.posts %}
  <li><time>{{ post.date | date:"%d %b %y" }}</time> <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
