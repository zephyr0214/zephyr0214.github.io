---
permalink: /photos/
title: ""
excerpt: ""
---

<h1 class="page__title"><span class="i18n zh">照片墙</span><span class="i18n en">Photo Gallery</span></h1>

{% assign photos = site.static_files | where_exp: "f", "f.path contains '_photos/'" | sort: "name" %}
{% if photos.size > 0 %}
<div class="photo-grid">
{% for photo in photos %}
  <img src="{{ photo.path | relative_url }}" alt="{{ photo.name }}" loading="lazy">
{% endfor %}
</div>
{% else %}
<p><span class="i18n zh">暂无照片。</span><span class="i18n en">No photos yet.</span></p>
{% endif %}
