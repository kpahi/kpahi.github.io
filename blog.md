---
layout: page
title: Blog
permalink: /blog/
---
<p>My blog posts (Coming Soon...)</p>

<ul>
  {% for post in site.posts %}
    <li class="spaced">
      <a href="{{ post.url }}">{{ post.title }}</a> {{ post.date | date_to_long_string }}
    </li>
  {% endfor %}
</ul>