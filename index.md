---
layout: default
---
{% include JB/setup %}

### [Works](http://syon.github.io/works/)

## Pages

{% for cat in site.category-list %}
### {{ cat }}
<ul>
{% for page in site.pages %}
{% for pc in page.categories %}
{% if pc == cat %}
<li><a href="{{ page.url }}">{{ page.title }}</a></li>
{% endif %}<!-- cat-match-p -->
{% endfor %}<!-- page-category -->
{% endfor %}<!-- page -->
</ul>
{% endfor %}<!-- cat -->

## Posts
<ul>
  {% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
