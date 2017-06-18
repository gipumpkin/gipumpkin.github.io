---
layout: page
title: Working with data
permalink: /mlab-data/
---

<ul>
{% for monument in site.data.mlab2 %}
  <li>
    <img src="{{ monument.form_image_b }}">
    <strong>{{ monument.name }}</strong>

  </li>
{% endfor %}
</ul>
