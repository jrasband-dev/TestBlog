---
layout: home
title: "Home"
permalink: /home/
---

Welcome to my blog! 🎉  
See the [About page]("/TestBlog/about/").

# Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span> — {{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
