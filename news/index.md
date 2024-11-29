---
layout: default
title: "News"
---

<nav>
  <ul>
    <li><a href="{{ site.baseurl }}/">Home</a></li>
    <li><a href="{{ site.baseurl }}/news/">News</a></li>
    <li><a href="{{ site.baseurl }}/group/">Group</a></li>
    <li><a href="{{ site.baseurl }}/research/">Research</a></li>
    <li><a href="{{ site.baseurl }}/Students' projects/">Students' projects</a></li>
    <li><a href="{{ site.baseurl }}/women-in-science/">Women in Science</a></li>
    <li><a href="{{ site.baseurl }}/books-for-children/">Books for Children</a></li>
    <li><a href="{{ site.baseurl }}/positions/">Positions</a></li>
  </ul>
</nav>

<h1>News</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ 2024-11-08-adam }}</a>
      <span>{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
