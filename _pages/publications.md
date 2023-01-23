---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

For the most updated version of my publications page, see my [Google Scholar profile](https://scholar.google.com/citations?user=hzSOg6MAAAAJ).

## Peer-Reviewed


<ul>{% for post in site.publications reversed %}
{% unless post.preprint %}
  {% include archive-single-publication.html %}
{% endunless %}
{% endfor %}</ul>

## Preprints / Under Review

<ul>{% for post in site.publications reversed %}
{% if post.preprint %}
  {% include archive-single-publication.html %}
{% endif %}
{% endfor %}</ul>