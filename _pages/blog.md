---
permalink: /blog/
title: "Blog"
excerpt: "Mycodoc"
---

<h2> Blog posts </h2>


{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

