---
title:  "Welcome to Jekyll!"
categories: jekyll
---

# Presentations

{% for presentation in site.presentations %}
{% if presentation.is_draft == nil or presentation.is_draft == false %}
<p>
  <h3><a href="{{ presentation.url }}">{{ presentation.title }}</a></h3>
</p>
{% endif %}
{% endfor %}

