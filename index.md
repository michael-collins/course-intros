---
layout: default
title: Course Introductions
---

# Course Introductions

<ul>
{% for post in site.posts %}
  <li>
    <p>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      <button class="copy-button" onclick="copyIframe('{{ site.url }}/{{ site.baseurl }}{{ post.url }}')">Copy iframe</button>
    </p>
  </li>
{% endfor %}
</ul>
