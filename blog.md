---
layout: page
title: Blog
subtitle: Notes and write-ups
---

<div>
{% assign postsCategory = site.posts | group_by_exp:"post", "post.categories"  %}
{% for category in postsCategory %}
<h4 class="post-teaser__month"><strong>{{ category.name }}</strong></h4>
<ul class="list-posts">
{% for post in category.items %}
<li class="post-teaser">
<a href="{{ post.url | relative_url }}">
<span class="post-teaser__title">{{ post.title }}</span>
<span class="post-teaser__date">{{ post.date | date: "%d %B %Y" }}</span>
</a>
</li>
{% endfor %}
</ul>
{% endfor %}
{% if site.posts.size == 0 %}
<p class="empty-post-list">Nothing here yet.</p>
{% endif %}
</div>
