---
layout: default
title:  Blog
---

{% for post in site.posts %}
<p><span class="text-muted">{{ post.date | date: "%B %-d, %Y" }}</span> <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></p>
{% endfor %}
