---
layout: blog
title: Blog
permalink: /blog/
---
<div class = "posts">
	<ul>
	{% assign sorted_posts = (site.posts | sort: 'date') %}
		{% for post in sorted_posts %}
	    	<li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
		{% endfor %}
	</ul>
</div>