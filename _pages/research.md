---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

## Job Market Paper

<ul>{% for post in site.ongoing-projects reversed %}
  {% include archive-single-publication.html %}
{% endfor %}</ul>

## Under Review

<ul>{% for post in site.publications reversed %}
{% if post.preprint %}
  {% include archive-single-publication.html %}
{% endif %}
{% endfor %}</ul>

## Published

<ul>{% for post in site.publications reversed %}
{% unless post.preprint %}
  {% include archive-single-publication.html %}
{% endunless %}
{% endfor %}</ul>
