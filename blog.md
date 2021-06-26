---
layout: default
permalink: /blog/
---
# BLOG
<br>

→ [RSS](https://gerhardla.nz/feed.xml)<br>
→ [JSON](https://feed2json.org/convert?url=https%3A%2F%2Fgerhardla.nz%2Ffeed.xml)<br>

<ul>
  {% for post in site.posts %}
    <li>
        <span>{{ post.date | date: "%Y-%m-%d" }}</span>&emsp;<a href="{{ post.url }}" title="{{ post.subtitle }}">{{post.title}}</a>
    </li>
  {% endfor %}
</ul>
