---
layout: post
title: "My Product Portfolio"
---

<ul>
  {% if site.show_excerpts %}
    {% include home.html %}
  {% else %}
    {% include archive.html title="Posts" %}
  {% endif %}  
</ul>
