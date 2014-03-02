---
layout: default
---
{% include JB/setup %}

### [Works](http://syon.github.io/works/)

<ul>
<h2>Posts</h2>
  {% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
