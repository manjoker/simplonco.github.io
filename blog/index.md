---
layout: default
title: Blog
---

Blog
----

{% for post in site.posts %}
  * [{{ post.title }}]({{ post.url }})
{% endfor %}
