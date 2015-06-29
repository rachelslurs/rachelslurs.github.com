---
layout: list
title: Snippets
permalink: /snippets/
---

{% for post in site.posts %}
	{% if post.layout == 'post' %}
	<a href="{{ site.baseurl }}{{ post.url }}" target="_self">{{ post.title }}</a>
	{% endif %}
{% endfor %}