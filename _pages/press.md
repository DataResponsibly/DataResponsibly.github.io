---
title: "DataResponsibly - Press"
layout: gridlay
excerpt: "Data Responsibly - Press"
sitemap: false
permalink: /press/
---


## Press


{% assign number_printed = 0 %}
{% for pressi in site.data.press %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if pressi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ pressi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/{{ pressi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ pressi.description }}</p>
  <p><em>{{ pressi.authors }}</em></p>
  <p><strong><a href="{{ pressi.link.url }}">{{ pressi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ pressi.news1 }}</strong></p>
  <p> {{ pressi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}