---
title: Through My Mind
permalink: /blog/
layout: other_pages
---

# {{ page.title }}

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">> {{ post.title }}</a>
    </li>
    {{post.intro | truncate: 256}}
  {% endfor %}
<!-- </ul> -->