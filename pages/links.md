---
layout: page
title: Links
description: outside links
keywords: link
comments: false
menu: Link
permalink: /links/
---



{% for link in site.data.links %}
  {% if link.src == 'life' %}
* [{{ link.name }}]({{ link.url }})
  {% endif %}
{% endfor %}



{% for link in site.data.links %}
  {% if link.src == 'www' %}
* [{{ link.name }}]({{ link.url }})
  {% endif %}
{% endfor %}
