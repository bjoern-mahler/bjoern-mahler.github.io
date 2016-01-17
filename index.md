---
layout: page
title: Agile Requirements
tagline: or how to deal with agile, requirements from a more technical view
---
{% include JB/setup %}

## About

So, yet another blogger talking about Agile, Kanban and stuff you already knew? I hope I'll give some additional inputs around my personal thougts about Agile and especially about Requirements or Specifications in a more agile way. And because I'm an educated software developer I'll want to post regualary more about the technical or practical stuff, e.g. using Cucumber for living specifications beside experiences about our Kanban setup, insights of Retrospectives and how to measure things you want to know about your process.

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>