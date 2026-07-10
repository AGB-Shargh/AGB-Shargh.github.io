---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
---

## Publications

<input type="text" class="pub-search" id="pubSearch" placeholder="Filter by title, author, or year...">

<div class="section-card" id="pubList">

{% assign pubs_sorted = site.data.publications | sort: "year" | reverse %}


<h3>Journal Publications</h3>

<ul>
{% for pub in pubs_sorted %}
{% if pub.type == "journal" %}
<li>

<strong>
<a href="{{ pub.url }}" target="_blank" class="pub-title">{{ pub.title }}</a>
</strong><br>

{{ pub.authors }} ({{ pub.year }})<br>
<em>{{ pub.journal }}</em>
{% if pub.note %}
<br>{{ pub.note }}
{% endif %}

</li>
{% endif %}
{% endfor %}
</ul>


<h3>Conference Publications</h3>

<ul>
{% for pub in pubs_sorted %}
{% if pub.type == "conference" %}
<li>

<strong>
<a href="{{ pub.url }}" target="_blank" class="pub-title">{{ pub.title }}</a>
</strong><br>

{{ pub.authors }} ({{ pub.year }})<br>
<em>{{ pub.journal }}</em>
{% if pub.note %}
<br>{{ pub.note }}
{% endif %}

</li>
{% endif %}
{% endfor %}
</ul>





</div>