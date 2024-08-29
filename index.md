---
layout: default
title: Home
---
# Working as intended

This is the personal site of Chris Huff.

## Posts

{% assign post = site.posts.first %}

{% for post in site.posts %}
      [{{ post.title }}]({{ post.url }})
      {{ post.excerpt }
  {% endfor %}
