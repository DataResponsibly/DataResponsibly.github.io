---
title: "DataResponsibly - Tools"
layout: gridlay
excerpt: "Data Responsibly - Tools"
sitemap: false
permalink: /tools/
---


## Tools
{% assign number_printed = 0 %}
{% for tooli in site.data.tools %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <a href="{{ tooli.url }}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/{{ tooli.photo }}" class="img-responsive" width="50%" style="float: left" />
  </a>
  <h4><a href="{{ tooli.url }}">{{ tooli.name }}</a></h4>
  <em>{{ tooli.info }}</em><br>
  <p>{{ tooli.description }}</p>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Collaborated projects
{% assign number_printed = 0 %}
{% for coli in site.data.collaborates %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <a href="{{ coli.url }}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/{{ coli.photo }}" class="img-responsive" width="50%" style="float: left" />
  </a>
  <h4><a href="{{ coli.url }}">{{ coli.name }}</a></h4>
  <i>{{ coli.info }}</i>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

