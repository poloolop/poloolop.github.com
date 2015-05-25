---
layout: page
title: Existence Exists!
tagline: Website of Umang Saini
description: Landing page of Umangsaini.in. Personal website of Umang saini.
---
{% include JB/setup %}
   
## Posts

<ul>
  
<h1>Latest Post</h1>
{% for post in site.posts limit:2 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <br>
      {{ post.excerpt | remove: '<p>' | remove: '</p>' }}
    </li>

{% endfor %}
<h1>Recent Posts</h1>
{% for post in site.posts offset:2 limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>

{% endfor %}	
	

</ul>

## New

Learning Jekyll and Github Pages. This site is work in progress.


