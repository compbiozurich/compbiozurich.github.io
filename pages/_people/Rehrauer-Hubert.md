---
title: "Hubert Rehrauer"
layout: default
date: 2007-07-01
excerpt_separator: <!--more-->
excerpt_link: 'http://www.fgcz.ch/the-center/people/rehrauer.html'
image_file: 'Rehrauer.jpg'
category:
  - people
tags:
  - FGZC
  - SIB
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Genome Informatics
* FGZC

<!--more-->
