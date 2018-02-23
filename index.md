---
layout: page
search_omit: true
---

# Welcome to Prophage

Welcome to the **Prophage** blog 2.0! This is version 2.0 because it is a new location and structure of the original Prophage blog that started back in 2013. The old blog was very successful, with well over 100,000 views, but it was time to update the site.

This blog is written and maintained by Dr. Geoffrey Hannigan. Check out the latest blog entries below, navigate the site using the menu above, and check out the [original Prophage here](http://prophage.blogspot.com). Read more about Dr. Hannigan in the "about the author" section.

# Latest Posts

<ul class="post-list">
{% for post in site.posts limit:10 %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
