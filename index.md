---
layout: page
title: Recipes
tagline: by Brian and Kimberly
---
{% include JB/setup %}

Recipes thus far:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
