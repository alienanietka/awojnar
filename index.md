---
layout: default
title: "Aneta Wojnar - Homepage"
---

<nav>
  <ul>
    <li><a href="{{ site.baseurl }}/">Home</a></li>
    <li><a href="{{ site.baseurl }}/news/">News</a></li>
    <li><a href="{{ site.baseurl }}/group/">Group</a></li>
    <li><a href="{{ site.baseurl }}/research/">Research</a></li>
    <li><a href="{{ site.baseurl }}/women-in-science/">Women in Science</a></li>
    <li><a href="{{ site.baseurl }}/books-for-children/">Books for Children</a></li>
    <li><a href="{{ site.baseurl }}/positions/">Positions</a></li>
  </ul>
</nav>

<h1>News</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>


<div style="display: flex; justify-content: center; margin-top: 20px;">
  <!-- Left Column: Your photo and brief introduction -->
  <div style="text-align: center; max-width: 600px;">

    <h2>About Me</h2>
    <img src="assets/images/A.png" alt="Your photo" style="width: 100%; max-width: 300px; border-radius: 50%; margin: 20px 0;">
    <p>
      I am a professor assistant at the University of Wrocław and a research fellow at Complutense University of Madrid. 
      My research focuses on seismology, gravitational waves, and geophysics.
    </p>

  </div>
</div>
