---
layout: page
title: Book Selections and 'AfterWords'
excerpt: "An archive of posts from the BYOBC."
image:
    feature: lr-banner.png
---

### Reading goals and afterthoughts for the lone read.


<ul class="post-list">
{% for post in site.categories.books %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>


<p>
</p>
<center><div markdown="0"><a href="{{ site.url }}/blog/getting-started/" class="btn">Get started with the BYOBC reading/drinking schedule.</a></div></center> 

