---

title: Welcome to My Blog
---

Check out The regular updates as well as special articles on projects and missions. You can reach me via email at [benjaminversestheworld@gmail.com] 

## Recent Posts
<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%b %-d, %Y" }}
    </li>
  {% endfor %}
</ul>
