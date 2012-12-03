---
layout: page
title: Where is my Mind ?
tagline: A Mind contributor's blog
---
{% include JB/setup %}
    
### Welcome to my developer page

This blog is aimed to provide information, important or not, about the contributions I make to the Mind compiler and MindEd editor.
Content will be added according to issues and solutions I meet and when any idea comes... to my mind.

### Post updates

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

### Author

I'm a french developer from Grenoble, working for Assystem and currently in mission for Schneider-Electric.
My work focuses on making the Mind tools more robust and user-friendly. I also like freestyle skiing and music.
Contact information can be found below.


