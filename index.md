---
layout: default
title: {{ site.name }}
---

# [](#header-1)Welcome

Hello and welcome!

I have this blog to detail my move into the rocky crypto-mining world. 

I exchange power for hashrate, which in turns secures a PoW consensus based block-chain.

Currently I mine Sia exclusively which rewards me with Utility Tokens (Siacoin) that users can use to rent storage space within the sia network.


# [](#header-1)Posts

{% for post in site.posts %}
<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}


