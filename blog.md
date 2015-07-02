---
layout: content
title: Blog
permalink: /blog/
---

{% for post in site.posts %}
	{% if post.layout == 'blog' %}
		<h4>{{ post.title }}</h4>
		<p>{{ site.baseurl }}{{ post.url }}</p>
	{% endif %}
{% endfor %}