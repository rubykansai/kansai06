---
layout: default
title:  Blog
---

[準備中](#){:width="" class="btn btn-warning"}

{% for post in site.posts %}
<h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
<p class="text-muted">{{ post.date | date: "%B %-d, %Y" }}<p>
{{ post.content }}
<hr>
{% endfor %}
