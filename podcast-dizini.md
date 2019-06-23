---
layout: page
title: PodCast Dizini
---

<h1>{{ site.podcast.title }}</h1>
<p>{{site.podcast.description }}</p>

{% for pc in site.categories.podcast %}
<h1><a href="{{ pc.url | absolute_url }}">{{ pc.title }}</a></h1>
<ul>
<li>Sezon: {{ pc.season }}</li>
<li>Bölüm: {{ pc.episode }}</li>
<li>Açıklama:
<blockquote>
{{ pc.content | xml_escape | strip_newlines }}
</blockquote>
</li>
</ul>
{% endfor %}