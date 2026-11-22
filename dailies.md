---
layout: default
title: Dailies
permalink: /dailies/
---

<h1>Daily Posts</h1>
<p>Short updates and daily logs.</p>

<ul>
  {% for post in site.categories.dailies %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> 
      <span>({{ post.date | date: "%B %-d, %Y" }})</span>
    </li>
  {% endfor %}
</ul>
