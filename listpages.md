---
title: List Pages
---

# site.time
{{ site.time }}

# site.url
{{ site.url }}

# posts
{% for p in site.posts %}
  {{ p.path }},{{ p.url }}
{% endfor %}

# pages
{% for p in site.pages %}
  {{ p.path }},{{ p.url }}
{% endfor %}


# documents
{{ site.documents | size }}
{% for p in site.documents %}
  {{ p.path }},{{ p.url }}
{% endfor %}

