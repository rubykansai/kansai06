---
layout: default
title:  Blog
---

{% for post in site.posts %}
<p><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> <span class="text-muted">{{ post.date | date: "%B %-d, %Y" }}</span></p>
{% endfor %}
