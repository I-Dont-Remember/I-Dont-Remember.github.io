---
layout: page
title: Blog
permalink: /blog/
---

<!---
# <ul>
# {% for post in site.posts %}
#  <li>
#    <a href="{{ post.url }}">
#      <h2>{{ post.title }}</h2>
#    </a>
#  </li>
# {% endfor %}
# </ul>
--->

{% for post in site.posts %}
  {% include post-grid.html %}
{% endfor %}
