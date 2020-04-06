---
title: "DataResponsibly - Publications"
layout: gridlay
excerpt: "Data Responsibly - Publications"
sitemap: false
permalink: /publications/
---


# Publications

Jump to [full list](#full-list), [reports](#reports), [blogs and popular press](#blogs-and-popular-press).

## Highlights

{% assign number_printed = 0 %}
{% for publi in site.data.publications %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
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

<p> &nbsp; </p>


## Full List

{% for publi in site.data.publications %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br />
  
  {% if publi.number_link == 1 %}
  <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
  {% endif %}

  {% if publi.number_link == 2 %}
  <a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>,
  <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>
  {% endif %}
  
  {% if publi.number_link == 3 %}
  <a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>,
  <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>,
  <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>
  {% endif %}


  {% if publi.number_link == 4 %}
  <a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>,
  <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>,
  <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>,
  <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>
  {% endif %}

  {% if publi.number_link == 5 %}
  <a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>,
  <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>,
  <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>,
  <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>,
  <a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a>
  {% endif %}

  {% if publi.number_link == 6 %}
  <a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>,
  <a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>,
  <a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>,
  <a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>,
  <a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a>,
  <a href="{{ publi.link6.url }}">{{ publi.link6.display }}</a>
  {% endif %}
  
{% endfor %}

## Reports
{% for reporti in site.data.reports %}

  {{ reporti.title }} <br />
  <em>{{ reporti.authors }} </em><br />

  {% if reporti.number_link == 1 %}
  <a href="{{ reporti.link.url }}">{{ reporti.link.display }}</a>
  {% endif %}

  {% if reporti.number_link == 2 %}
  <a href="{{ reporti.link1.url }}">{{ reporti.link1.display }}</a>,
  <a href="{{ reporti.link2.url }}">{{ reporti.link2.display }}</a>
  {% endif %}


  {% if reporti.number_link == 3 %}
  <a href="{{ reporti.link1.url }}">{{ reporti.link1.display }}</a>,
  <a href="{{ reporti.link2.url }}">{{ reporti.link2.display }}</a>,
  <a href="{{ reporti.link3.url }}">{{ reporti.link3.display }}</a>
  {% endif %}


  {% if reporti.number_link == 4 %}
  <a href="{{ reporti.link1.url }}">{{ reporti.link1.display }}</a>,
  <a href="{{ reporti.link2.url }}">{{ reporti.link2.display }}</a>,
  <a href="{{ reporti.link3.url }}">{{ reporti.link3.display }}</a>,
  <a href="{{ reporti.link4.url }}">{{ reporti.link4.display }}</a>
  {% endif %}

{% endfor %}

## Blogs and popular press
{% for blogi in site.data.blogs %}

  {{ blogi.title }} <br />{{ blogi.authors }} <a href="{{ blogi.link.url }}">{{ blogi.link.display }}</a>

{% endfor %}