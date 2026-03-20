---
title: "Publications"
layout: archive
permalink: /publications/
author_profile: true
---

# Publications

Below is a list of my publications. I have also included these publications in my [About](/) page for convenience.

## First Author Publications

{% for post in site.publications reversed %}
{% if post.title contains "First Author" %}
  {% include archive-single.html %}
{% endif %}
{% endfor %}

## Co-authored Publications

{% for post in site.publications reversed %}
{% if post.title contains "Co-authored" %}
  {% include archive-single.html %}
{% endif %}
{% endfor %}