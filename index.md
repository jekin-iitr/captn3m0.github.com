---
layout: default
title: captnemo.in
---
{% for post in site.posts %}
  * {{post.date | date_to_string}} \- [{{ post.title }}]({{ post.url }})
{% endfor %}
