---
layout: page
title: Opinionated Library
tagline: by Will Wykeham
---
{% include JB/setup %}

Conventional wisdom holds that "Writing is like a muscle", "you can get good at anything, you just need to practice".
Conventional wisdom is probably correct on this.
My job title may be Consultant, but I am primarily a software engineer. Mostly I write code, and when I do write English it's generally a technical document.
None of this gives me a lot of practice at writing the kind of fluid prose that is actually needed sometimes. Even this paragraph has taken a couple of attempts and some pausing.

Conveniently there are some things that I want to say.
Responses to threads of discussion on the Internet (<https://xkcd.com/386/>).
The struggle between software engineering purity and actually building something useful.
This cool picture of a giant duck (<http://www.bbc.co.uk/news/world-asia-25560771>).

To use another cliche: "Opinions are like arseholes: everyone's got one".
Except that I don't have one, I've got hundreds (opinions obviously, not arseholes), and they're just waiting to be shared.
I would actually quite like to keep some of my friends, so rather than haranguing them continually, you all get to benefit.

---

## Posts
<ul class="posts">
  {% for post in site.posts %}
    <li>{{ post.date | date_to_string }} &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


