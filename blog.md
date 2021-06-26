---
layout: default
permalink: /blog/
---
# BLOG
<br>

→ [RSS](https://gerhardla.nz/feed.xml)<br>
→ [JSON](https://feed2json.org)<br>

<ul>
  {% for post in site.posts %}
    <li>
        <span>{{ post.date | date: "%Y-%m-%d" }}</span>&emsp;<a href="{{ post.url }}" title="{{ post.subtitle }}">{{post.title}}</a>
    </li>
  {% endfor %}
</ul>
