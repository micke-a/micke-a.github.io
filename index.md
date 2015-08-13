---
layout: page
title: Crabdivers!
tagline: Supporting tagline
---
{% include JB/setup %}

<img src="/images/logo/logo_site_inv.png"/>
{% include slogans-carousel %}



{% for post in site.posts %}
<h2> {{ post.title }} </h2>
<p> {{ post.excerpt }} </p>
<p><a class="btn btn-default" href="{{ post.url }}" role="button">Continue reading &raquo;</a></p>
{% endfor %}
