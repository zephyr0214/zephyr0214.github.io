---
permalink: /posts/
title: "Posts"
excerpt: ""
author_profile: true
---

{% for post in site.posts %}
<h2><a href="{{ post.url }}" target="_blank" rel="noopener">{{ post.title }}</a></h2>
<p class="post-date">{{ post.date | date: "%Y-%m-%d" }}</p>
{% assign post_excerpt = post.excerpt | strip_html | strip %}
{% if post_excerpt != "" %}
<p class="post-excerpt">{{ post_excerpt | truncatewords: 60 }}</p>
{% endif %}
<hr>
{% else %}
<p>No posts yet.</p>
{% endfor %}
