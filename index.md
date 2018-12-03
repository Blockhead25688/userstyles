---
layout: default
---

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title | escape }} ]({{ post.url }})
{% endfor %}