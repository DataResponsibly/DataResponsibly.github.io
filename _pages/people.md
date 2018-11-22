---
title: "DataResponsibly - People"
layout: gridlay
excerpt: "Data Responsibly - People"
sitemap: false
permalink: /people/
---

## Professors
{% assign number_printed = 0 %}
{% for member in site.data.professor %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">
  {% if member.number_org == 1 %}
  <li> {{ member.org1 }} </li>
  {% endif %}

  {% if member.number_org == 2 %}
  <li> {{ member.org1 }} </li>
  <li> {{ member.org2 }} </li>
  {% endif %}

  {% if member.number_org == 3 %}
  <li> {{ member.org1 }} </li>
  <li> {{ member.org2 }} </li>
  <li> {{ member.org3 }} </li>
  {% endif %}

  {% if member.number_org == 4 %}
  <li> {{ member.org1 }} </li>
  <li> {{ member.org2 }} </li>
  <li> {{ member.org3 }} </li>
  <li> {{ member.org4 }} </li>
  {% endif %}

  {% if member.number_org == 5 %}
  <li> {{ member.org1 }} </li>
  <li> {{ member.org2 }} </li>
  <li> {{ member.org3 }} </li>
  <li> {{ member.org4 }} </li>
  <li> {{ member.org5 }} </li>
  {% endif %}
  </ul>
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


## PhD Students
{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i><br>
  <i>{{ member.org }}</i>
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

