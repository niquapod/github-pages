---
layout: page
title: Archive
---

## Blog Posts

{% for posts in site.posts %}
    * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
    {% endfor %}