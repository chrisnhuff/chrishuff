---
layout: default
title: Home
---
# Working as intended

This is the personal site of Chris Huff.

## Posts
{{ site.url }}
{% assign post = site.posts.first %}

{% for post in site.posts %}
      [{{ post.title }}]({{ site.url }}{{ post.url | relative_url }})
      {{ post.excerpt }}
  {% endfor %}
