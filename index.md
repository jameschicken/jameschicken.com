---
layout: default
---

# Welcome!

Welcome to James' Chicken. Check out some of the movie, food and accessability reviews authored by our own resident food and movie critic extraordinare, <a href='/about/'>James</a>!

## Most Recent Posts

<ul>
  <li>{{ site.posts[0].date | date: "%B %d, %Y" }} - <a href="{{ site.posts[0].url | prepend: site.baseurl }}">{{ site.posts[0].title }}</a></li>
  <li>{{ site.posts[1].date | date: "%B %d, %Y" }} - <a href="{{ site.posts[1].url | prepend: site.baseurl }}">{{ site.posts[1].title }}</a></li>
  <li>{{ site.posts[2].date | date: "%B %d, %Y" }} - <a href="{{ site.posts[2].url | prepend: site.baseurl }}">{{ site.posts[2].title }}</a></li>
  <li>{{ site.posts[3].date | date: "%B %d, %Y" }} - <a href="{{ site.posts[3].url | prepend: site.baseurl }}">{{ site.posts[3].title }}</a></li>
  <li>{{ site.posts[4].date | date: "%B %d, %Y" }} - <a href="{{ site.posts[4].url | prepend: site.baseurl }}">{{ site.posts[4].title }}</a></li>
</ul>

<a href='/posts/'>View all {{ site.posts | size }} posts...</a>
