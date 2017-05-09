---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
---

# Coming Soon...

{% for post in site.posts %}
<p>
  <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
  {{ post.excerpt }}
</p>
{% endfor %}
