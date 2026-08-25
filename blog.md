---
layout: page
title: Blog
permalink: /blog/
---

# All posts

I started blogging in 2012. I share what I’ve learned along the way.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>({{ post.date | date: "%B %d, %Y" }})</span>
    </li>
  {% endfor %}
</ul>