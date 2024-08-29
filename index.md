---
layout: default
title: Home
---
# Working as intended

This is the personal site of Chris Huff.

## Posts

{% assign post = site.posts.first %}

{% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
