---
layout: page
---

<ul>
  {% for post in site.categories.news %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
