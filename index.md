---
layout: default
title: {{ site.name }}
---

# [](#header-1)Blog Posts

    {% for post in site.posts %}
      {{ post.date | date_to_string }} 
      {{ site.baseurl }}{{ post.url }}">{{ post.title }}
    {% endfor %}


