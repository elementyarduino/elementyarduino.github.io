---
layout: page
title: Elementy
---
<ul>
{% for item in site.data.arduino %}
<li style="{% if item.isPoisonous %}color: red{% endif %}">
  {{ item.name }}
  </li>
{% endfor %}
</ul>
