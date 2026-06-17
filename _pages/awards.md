---
title: "Awards"
layout: gridlay
sitemap: false
permalink: /awards/
---

## Awards

<div class="section-card">
<h3>Academic Awards and Honors</h3>
<ul>
{% for award in site.data.awards %}
<li>{{ award.name }}</li>
{% endfor %}
</ul>
</div>

<div class="section-card">
<h3>Others</h3>
<ul>
<li>TODO</li>
</ul>
</div>
