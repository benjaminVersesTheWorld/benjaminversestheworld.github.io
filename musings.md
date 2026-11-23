---
layout: page
title: Musings
permalink: /musings/
---

<h1>Musings</h1>
<p>Odd bits that keep it interesting</p>

<ul>
  {% for post in site.categories.musings %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
      <span>({{ post.date | date: "%B %-d, %Y" }})</span>
    </li>
  {% endfor %}
</ul>
