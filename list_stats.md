---
layout: page
---

<ul>
  {% for post in site.categories.stats %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

