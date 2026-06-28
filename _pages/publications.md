---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
---

## Publications

<input type="text" class="pub-search" id="pubSearch" placeholder="Filter by title, author, or year...">

<div class="section-card" id="pubList">

<h3>All Publications</h3>

<ul>

{% assign pubs_sorted = site.data.publications | sort: "year" | reverse %}

{% for pub in pubs_sorted %}
<li>

<strong>
<a href="{{ pub.url }}" target="_blank" class="pub-title">{{ pub.title }}</a>
</strong><br>

{{ pub.authors }} ({{ pub.year }})<br>
<em>{{ pub.journal }}</em>

</li>
{% endfor %}

</ul>

</div>