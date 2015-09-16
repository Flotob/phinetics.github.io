---
layout: page
title: Hi Folks!
tagline: Supporting tagline
---
{% include JB/setup %}

Read the introductury post to [phinetics](http://phinetics.github.io/lessons/2015/09/16/phinetics-introduction/)

    
## Our higher knowledge

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

- Get a grip
- Enjoy Madness
- Learn Jekyll
- Acquire higher consciousness


