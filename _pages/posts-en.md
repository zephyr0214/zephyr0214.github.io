---
permalink: /en/posts/
title: "Posts"
excerpt: ""
author_profile: true
lang: en
---

{% for post in site.posts %}
<h2><a href="{{ post.url }}" target="_blank" rel="noopener">{{ post.title }}</a></h2>
<p class="post-date">{{ post.date | date: "%Y-%m-%d" }}</p>
{{ post.excerpt }}
<hr>
{% else %}
<p>No posts yet.</p>
{% endfor %}
