---
layout: default
title: {{ site.name }}
---

# [](#header-1)Blog Posts

{% for post in site.posts %}
<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}


# [](#header-1)Links

[Style](css.md)
