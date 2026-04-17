---
layout: default
title: Home
---

# Posts

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <small>{{ post.date | date: "%Y-%m-%d" }}</small>
  </li>
{% endfor %}
</ul>

<p>
  <a href="https://dofahy.github.io/blog/">blog</a> 
  © 2026 by <a href="https://github.com/dofahy">dofahy</a> is licensed under 
  <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a>
  <img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em; max-height: 1em; margin-left: .2em;">
  <img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em; max-height: 1em; margin-left: .2em;">
  <img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" alt="" style="max-width: 1em; max-height: 1em; margin-left: .2em;">
  <img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" alt="" style="max-width: 1em; max-height: 1em; margin-left: .2em;">
</p>
