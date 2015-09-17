---
layout: default
---

# Welcome!

Welcome to James' Chicken. Check out some of the movie, food and accessability reviews authored by our own resident food and movie critic extraordinare, <a href='/about/'>James</a>!

## Most Recent Posts

<ul>
  {% for i in (0..4) %}
    <li>{{ site.posts[i].date | date: "%B %d, %Y" }} - <a href="{{ site.posts[i].url | prepend: site.baseurl }}">{{ site.posts[i].title }}</a></li>
  {% endfor %}
</ul>

<a href='/posts/'>View all {{ site.posts | size }} posts...</a>
