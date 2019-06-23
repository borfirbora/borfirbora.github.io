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
{{ pc.excerpt | strip_html | xml_escape | truncatewords: site.excerpt_length }}
        {% assign excerpt_word_count = pc.excerpt | number_of_words %}
        {% if pc.content != pc.excerpt or excerpt_word_count > site.excerpt_length %}
          <a href="{{ pc.url | prepend: site.baseurl }}" class="post-read-more">[Devamını&nbsp;Gör]</a>
</blockquote>
</li>
</ul>
{% endfor %}