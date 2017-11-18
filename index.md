---
layout: page
search_omit: true
---

# Welcome to Prophage

Welcome to the **Prophage** blog. This blog is written and maintained by Dr. Geoffrey Hannigan. Check out the latest posts below, or read more about Dr. Hannigan in the "about the author" section.

# Latest Posts

<ul class="post-list">
{% for post in site.posts limit:10 %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
