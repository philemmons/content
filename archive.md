---
layout: page
title: Archive
permalink: /archive/
---


{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ site.baseurl }}{{ post.url }})
{% endfor %}

