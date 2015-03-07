---
layout: page
title: Blog
---

# Blog

{% if site.posts == empty %}
<p>Coming soon</p>
{% else %}
{% for post in site.posts %}
<div class="blogtitle"><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> <span>{{ post.date| date: "%A %e %B %Y" }}</span></div>
{% endfor %}
{% endif %}
