---
layout: page
title: Hello!
tagline: 
---
{% include JB/setup %}


<ul class="posts">
  {% for post in site.posts %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a> on <span>{{ post.date | date_to_string }}</span></li>
  {% endfor %}
</ul>



