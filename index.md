---
layout: page
title: What is Open Government?
tagline: Open Government Explained
---
{% include JB/setup %}

<ul>
{% for post in site.posts %}
	<li>
	<a href="{{ BASE_URL }}{{ post.url }}">{{ post.title }}</a>
	</li>
{% endfor %}
</ul>