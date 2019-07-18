---
layout: page
title: Posts
permalink: /posts/
---

{% for post in site.posts %}

## [{{ post.title }}]({{ post.url }})

{{post.description}}

{{ post.date | date_to_long_string }}
{% endfor %}
