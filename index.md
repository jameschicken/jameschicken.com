---
layout: default
---

# Welcome!

Welcome to James' Chicken. Check out some of the movie, food and accessability reviews authored by our own resident food and movie critic extraordinare, [James](/about/)!

## Most Recent Posts

{% for i in (0..4) %}
* {{ site.posts[i].date | date: "%B %d, %Y" }} - [{{ site.posts[i].title }}]({{ site.posts[i].url }})
{% endfor %}

[View all {{ site.posts | size }} posts...](/posts/)
