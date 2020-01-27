---
title: DataResponsibly - Courses
layout: gridlay
excerpt: "Data Responsibly - Courses"
sitemap: false
permalink: /courses/
---


## Data Responsibly Courses

Here list the courses that are taught by Prof. [Julia Stoyanovich](http://stoyanovich.org/) at NYU. 

{% for coursei in site.data.courses %}

  {{ coursei.title }} <br />
  <em>{{ coursei.authors }} </em>

  {% if coursei.number_link == 1 %}
  <a href="{{ coursei.link.url }}">{{ coursei.link.display }}</a>
  {% endif %}

  {% if coursei.number_link == 2 %}
  <a href="{{ coursei.link1.url }}">{{ coursei.link1.display }}</a>,
  <a href="{{ coursei.link2.url }}">{{ coursei.link2.display }}</a>
  {% endif %}

  {% if coursei.number_link == 3 %}
  <a href="{{ coursei.link1.url }}">{{ coursei.link1.display }}</a>,
  <a href="{{ coursei.link2.url }}">{{ coursei.link2.display }}</a>,
  <a href="{{ coursei.link3.url }}">{{ coursei.link3.display }}</a>
  {% endif %}

  {% if coursei.number_link == 4 %}
  <a href="{{ coursei.link1.url }}">{{ coursei.link1.display }}</a>,
  <a href="{{ coursei.link2.url }}">{{ coursei.link2.display }}</a>,
  <a href="{{ coursei.link3.url }}">{{ coursei.link3.display }}</a>,
  <a href="{{ coursei.link4.url }}">{{ coursei.link4.display }}</a>
  {% endif %}

{% endfor %}
