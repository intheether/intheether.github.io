---
layout: default
title: {{ site.name }}
---

# [](#header-1)Welcome

Hello and welcome!

This site has been tracked to follow and record my journey in the rocky world of Crypto Mining; starting off at a very small scale in the hope of turning this into a 'proper' operation.

You will find information on my rigs, how I network them (and posts on Networking in general), how I maintain and monitor them and the struggle with HMRC and tax ;-)

# [](#header-1)Posts

{% for post in site.posts %}
<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}


