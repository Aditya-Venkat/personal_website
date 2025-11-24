---
permalink: /blog/
title: "Blogs"
author_profile: true
---
<style>
.blog-card {
  background-color: #f9fafb;
  border: 1px solid #e5e7eb;
  border-radius: 1rem;
  padding: 1.2rem 1.5rem;
  margin-bottom: 1.5rem;
  box-shadow: 0 2px 6px rgba(0,0,0,0.05);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  text-decoration: none;
  color: inherit;
}
.blog-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 12px rgba(0,0,0,0.08);
}
.blog-card h3 { margin-top: 0; }

/* clickable behaviour */
.clickable-card { cursor: pointer; }
.clickable-card:focus { outline: 3px solid rgba(59,130,246,0.25); outline-offset: 4px; }
</style>

{% for story in site.stories %}
<div class="blog-card clickable-card"
     role="link"
     tabindex="0"
     onclick="window.location='{{ story.url | relative_url }}';"
     onkeypress="if(event.key === 'Enter' || event.key === ' ') { window.location='{{ story.url | relative_url }}'; }">
  <h3>{{ story.title }}</h3>
  <p>{{ story.summary }}</p>
</div>
{% endfor %}
