---
layout: default
title: Updates
---
<div class="page">
  <header class="page-header">
    <h1>Updates</h1>
    <p>All progress posts, photos and downloadable measurement data.</p>
  </header>

  <ul class="post-list">
    {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">
        <span class="date">{{ post.date | date: "%B %d, %Y" }}</span>
        <span class="title">{{ post.title }}</span>
      </a>
      <p class="excerpt">{{ post.excerpt | strip_html | truncatewords: 40 }}</p>
    </li>
    {% endfor %}
  </ul>
</div>