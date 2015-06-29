---
layout: content
title: Blog
permalink: /blog/
---

{% for post in site.posts %}
	{% if post.layout == 'blog' %}
		<core-item label="{{ post.title }}" url="{{ site.baseurl }}{{ post.url }}">
		</core-item>
	{% endif %}
{% endfor %}