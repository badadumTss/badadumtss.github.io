---
layout: true_default
title: Posts
permalink: /posts
---
Here's a list of all posts in this site:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>