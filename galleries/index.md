---
layout: page
title : Galleries
header : Galleries Header
#group: navigation
---
{% include JB/setup %}

{% for gallery in site.data.galleries %}
- [{{ gallery.description }}]({{ gallery.id }})
{% endfor %}
