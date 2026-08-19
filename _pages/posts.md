---
permalink: /posts/
title: "Posts"
excerpt: ""
author_profile: true
---

{% assign all_tags = site.tags | sort %}
<div class="tag-filter">
  <button type="button" class="tag-btn active" data-tag="all">{% if page.lang == 'en' %}All{% else %}全部{% endif %}</button>
  {% for tag in all_tags %}
  <button type="button" class="tag-btn" data-tag="{{ tag[0] | escape }}">{{ tag[0] | escape }}</button>
  {% endfor %}
</div>

<div class="post-list">
{% for post in site.posts %}
<article class="post-item" data-tags="{{ post.tags | join: ',' | escape }}">
<h2><a href="{{ post.url }}" target="_blank" rel="noopener">{{ post.title }}</a></h2>
<p class="post-date">{{ post.date | date: "%Y-%m-%d" }}</p>
{% assign post_excerpt = post.excerpt | strip_html | strip %}
{% if post_excerpt != "" %}
<p class="post-excerpt">{{ post_excerpt | truncatewords: 60 }}</p>
{% endif %}
<hr>
</article>
{% else %}
<p>No posts yet.</p>
{% endfor %}
</div>
