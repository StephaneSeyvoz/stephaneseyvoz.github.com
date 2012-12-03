---
layout: page
title: Welcome to my developer page !
tagline: Supporting tagline
---
{% include JB/setup %}

## Welcome to my developer page !

The aim of this page is to enable discussion around my contributions to the Mind toolchain, to talk about the mind compiler and mindEd editor internals, and the plugins I contribute to with the Mind4SE team.

## Post updates

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Author

Having trouble with minEd or one of my plugins ? Feel free to contact me: @StephaneSeyvoz
