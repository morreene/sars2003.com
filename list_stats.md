---
layout: page
title: Chinese offical statistics on SARS in 2003
---

<ul>
  {% for post in site.categories.stats %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>      <span> - {{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
  <li><a href="http://news.sina.com.cn/c/2003-04-30/19521025930.shtml">内地非典型肺炎每日疫情(即时更新)</a></li>
</ul>

