---
layout: default
title: Course Introductions
---

# Course Introductions

<ul>
{% for post in site.posts %}
  <li>
    <p>
      <a href="{{ site.url }}/{{ post.url }}">{{ post.title }}</a>
      <button class="copy-button" onclick="copyIframe('{{ site.url }}/{{ post.url }}')">Copy iframe</button>
    </p>
  </li>
{% endfor %}
</ul>
