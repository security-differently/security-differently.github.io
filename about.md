---
layout: page
title: What is Security Differently?
---

## Further Reading

Posts on Security Differently, newest first:

{% assign sd_posts = site.posts | where: "tags", "Security Differently" %}
<ul>
  {% for post in sd_posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
