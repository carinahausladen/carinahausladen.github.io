---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}


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
