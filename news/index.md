---
layout: default
title: "News"
---

<h2>News & Updates</h2>

<p>Welcome to the News section! Here you'll find the latest updates, blog posts, and short notes on my research and activities.</p>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
