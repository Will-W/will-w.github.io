---
layout: page
title: Opinionated Library
tagline: Welcome
---
{% include JB/setup %}

The saying goes that "Opinions are like arse-holes: everyone's got one". Speaking for myself though, I've got hundreds of them (opinions obviously, not arseholes), and they're just waiting to be shared.

Rather than inflict them on my friends who, to be honest, have enough to deal with from me, I'll spare them and pretend to myself that someone on the internet might actually care.

## Posts
<ul class="posts">
  {% for post in site.posts %}
    <li>{{ post.date | date_to_string }} &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


