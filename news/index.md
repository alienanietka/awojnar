---
layout: default
title: "News"
---

<nav style="background-color: #f4f4f4; padding: 10px; border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
  <ul style="list-style: none; display: flex; justify-content: center; gap: 15px; padding: 0; margin: 0;">
    <li style="flex: 1; text-align: center;">
      <a href="{{ site.baseurl }}/" 
         style="text-decoration: none; color: #1e90ff; font-family: 'Arial', sans-serif; font-size: 1.1em; padding: 10px 20px; display: inline-block; border-radius: 6px; transition: background-color 0.3s;">
         Home
      </a>
    </li>
    <li style="flex: 1; text-align: center;">
      <a href="{{ site.baseurl }}/news/" 
         style="text-decoration: none; color: #1e90ff; font-family: 'Arial', sans-serif; font-size: 1.1em; padding: 10px 20px; display: inline-block; border-radius: 6px; transition: background-color 0.3s;">
         News
      </a>
    </li>
    <li style="flex: 1; text-align: center;">
      <a href="{{ site.baseurl }}/group/" 
         style="text-decoration: none; color: #1e90ff; font-family: 'Arial', sans-serif; font-size: 1.1em; padding: 10px 20px; display: inline-block; border-radius: 6px; transition: background-color 0.3s;">
         Group
      </a>
    </li>
    <li style="flex: 1; text-align: center;">
      <a href="{{ site.baseurl }}/research/" 
         style="text-decoration: none; color: #1e90ff; font-family: 'Arial', sans-serif; font-size: 1.1em; padding: 10px 20px; display: inline-block; border-radius: 6px; transition: background-color 0.3s;">
         Research
      </a>
    </li>
    <li style="flex: 1; text-align: center;">
      <a href="{{ site.baseurl }}/Students' projects/" 
         style="text-decoration: none; color: #1e90ff; font-family: 'Arial', sans-serif; font-size: 1.1em; padding: 10px 20px; display: inline-block; border-radius: 6px; transition: background-color 0.3s;">
         Students' Projects
      </a>
    </li>
    <li style="flex: 1; text-align: center;">
      <a href="{{ site.baseurl }}/women-in-science/" 
         style="text-decoration: none; color: #1e90ff; font-family: 'Arial', sans-serif; font-size: 1.1em; padding: 10px 20px; display: inline-block; border-radius: 6px; transition: background-color 0.3s;">
         Women in Science
      </a>
    </li>
    <li style="flex: 1; text-align: center;">
      <a href="{{ site.baseurl }}/books-for-children/" 
         style="text-decoration: none; color: #1e90ff; font-family: 'Arial', sans-serif; font-size: 1.1em; padding: 10px 20px; display: inline-block; border-radius: 6px; transition: background-color 0.3s;">
         Books for Children
      </a>
    </li>
    <li style="flex: 1; text-align: center;">
      <a href="{{ site.baseurl }}/positions/" 
         style="text-decoration: none; color: #1e90ff; font-family: 'Arial', sans-serif; font-size: 1.1em; padding: 10px 20px; display: inline-block; border-radius: 6px; transition: background-color 0.3s;">
         Positions
      </a>
    </li>
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
