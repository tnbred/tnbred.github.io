---
layout: page
title: Articles
permalink: /articles/
---

<ul class="list-unstyled">
 <li><a href="https://instagram-engineering.com/core-modeling-at-instagram-a51e0158aa48">Core Modeling at Instagram</a></li>
 <li><a href="https://instagram-engineering.com/lessons-learned-at-instagram-stories-and-feed-machine-learning-54f3aaa09e56">Lessons Learned at Instagram Stories and Feed Machine Learning</a></li>
  {% for post in site.posts %}
    <li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
