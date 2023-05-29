---
layout: page
---

<ul>
  {% for post in site.categories.stats %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>      <span>{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

