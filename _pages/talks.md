---
title: "DataResponsibly - Talks"
layout: gridlay
excerpt: "Data Responsibly - Talks"
sitemap: false
permalink: /talks/
---


## Talks

{% for talki in site.data.talks %}

  {{ talki.title }} <br />
  <em>{{ talki.authors }} </em>

  {% if talki.number_link == 1 %}
  <a href="{{ talki.link.url }}">{{ talki.link.display }}</a>
  {% endif %}

  {% if talki.number_link == 2 %}
  <a href="{{ talki.link1.url }}">{{ talki.link1.display }}</a>,
  <a href="{{ talki.link2.url }}">{{ talki.link2.display }}</a>
  {% endif %}

  {% if talki.number_link == 3 %}
  <a href="{{ talki.link1.url }}">{{ talki.link1.display }}</a>,
  <a href="{{ talki.link2.url }}">{{ talki.link2.display }}</a>,
  <a href="{{ talki.link3.url }}">{{ talki.link3.display }}</a>
  {% endif %}

  {% if talki.number_link == 4 %}
  <a href="{{ talki.link1.url }}">{{ talki.link1.display }}</a>,
  <a href="{{ talki.link2.url }}">{{ talki.link2.display }}</a>,
  <a href="{{ talki.link3.url }}">{{ talki.link3.display }}</a>,
  <a href="{{ talki.link4.url }}">{{ talki.link4.display }}</a>
  {% endif %}

{% endfor %}
