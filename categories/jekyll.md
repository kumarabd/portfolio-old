---
layout: page
title: Jekyll
permalink: /blog/categories/jekyll/
---

<h1> Posts by Category : {{ page.title }} </h1>

<div class="card">
{% for post in site.categories.jekyll %}
 <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>