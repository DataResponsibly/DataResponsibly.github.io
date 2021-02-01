---
title: "DataResponsibly - Comics"
layout: gridlay
excerpt: "Data Responsibly - Comics"
sitemap: false
permalink: /comics/
---

### Volumes

{% assign number_printed = 0 %}
{% for comi in site.data.comics %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if comi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6">
 <div class="well">
  <div class="col-sm-12">
   <img src="{{ site.url }}{{ site.baseurl }}/images/{{ comi.image }}" class="img-responsive" width="30%" height="auto" style="float: left" />
  </div>
  <pubtit>{{ comi.title }}</pubtit>

  <p><em>{{ comi.authors }}</em></p>

  <p style="font-size:13px;">{{ comi.translators }}</p>

  <p><strong><a href="{{ comi.link.url }}">{{ comi.link.display }}</a></strong></p>

  {% if comi.number_link == 1 %}
  <p><strong><a href="{{ comi.link1.url }}">{{ comi.link.display }}</a></strong></p>
  {% endif %}

  {% if comi.number_link == 2 %}
  <p><strong><a href="{{ comi.link1.url }}">{{ comi.link1.display }}</a></strong></p>
  <p><strong><a href="{{ comi.link2.url }}">{{ comi.link2.display }}</a></strong></p>
  {% endif %}
  
  {% if comi.number_link == 3 %}
  <p><strong><a href="{{ comi.link1.url }}">{{ comi.link1.display }}</a></strong></p>
  <p><strong><a href="{{ comi.link2.url }}">{{ comi.link2.display }}</a></strong></p>
  <p><strong><a href="{{ comi.link3.url }}">{{ comi.link3.display }}</a></strong></p>
  {% endif %}
 
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
  