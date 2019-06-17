---
layout: default
title: Blog
---

# Some random thoughts

<ul class="posts">
  {% for post in site.posts %}
    <li class="entry">
        <span class="date">{{ post.date | date_to_long_string }}</span>
        <div class="title">
            <a href="{{ post.url }}">{{ post.title }}</a>
        </div>
        
    </li>
  {% endfor %}
</ul>