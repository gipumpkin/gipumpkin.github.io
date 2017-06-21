---
layout: page
title: Working with data
permalink: /mlab-data/
---

**Here is a very annoying thing to know!!** If you open this data in excel and save it, it will stop working as a csv. Use google sheets instead. Or, even better, work with data that is yaml or json.

 <ul>
{% for monument in site.data.mlab2 %}
  <li>
    <img src="{{ monument.form_image_b }}">
    <strong>{{ monument.name }}</strong>
  </li>
{% endfor %}
</ul>
