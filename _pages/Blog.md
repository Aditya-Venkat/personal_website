---
permalink: /blog/
title: "Blogs"
author_profile: true
---
<style>
/* Theme-aware blog cards */
.blog-card {
  background-color: var(--card-bg);
  border: 1px solid var(--card-border);
  border-radius: 1rem;
  padding: 1.2rem 1.5rem;
  margin-bottom: 1.5rem;
  box-shadow: 0 2px 6px var(--card-shadow);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  text-decoration: none;
  color: var(--card-text);
}

.blog-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 12px var(--card-hover-shadow);
}

.blog-card h3 {
  margin-top: 0;
  color: var(--card-heading);
}

/* clickable behaviour */
.clickable-card { cursor: pointer; }
.clickable-card:focus {
  outline: 3px solid rgba(59,130,246,0.25);
  outline-offset: 4px;
}

/* LIGHT MODE COLORS */
:root {
  --card-bg: #f9fafb;
  --card-border: #e5e7eb;
  --card-shadow: rgba(0, 0, 0, 0.05);
  --card-hover-shadow: rgba(0, 0, 0, 0.08);
  --card-text: #1f2937;      /* dark grey */
  --card-heading: #111827;  /* near-black */
}

/* DARK MODE COLORS */
html.dark {
  --card-bg: #1f1f1f;
  --card-border: #3a3a3a;
  --card-shadow: rgba(255, 255, 255, 0.05);
  --card-hover-shadow: rgba(255, 255, 255, 0.08);
  --card-text: #e5e5e5;      /* light text */
  --card-heading: #ffffff;   /* white title */
}
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
