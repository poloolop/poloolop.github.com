---
layout: page
title: Existence Exists!
tagline: Website of Umang Saini
description: Landing page of Umangsaini.in. Personal website of Umang saini.
---
<img class="bm-sh-badge" src="https://www.blogmint.com/blogger/badgeForSefHostedBlog/d97be9f4d5c54ebca98d04deb9f17783?image=one-pixel.png" alt="badge"/>
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


