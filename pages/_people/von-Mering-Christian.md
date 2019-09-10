---
title: "Christian von Mering"
layout: default
date: 2007-04-01
excerpt_separator: <!--more-->
excerpt_link: 'https://www.imls.uzh.ch/en/research/vonmering.html'
image_file: 'Mering.png'
category:
  - people
tags:
  - UZH
  - SIB
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Professor of Statistical Genomics
* Institute of Molecular Life Sciences
* IMLS Director of the Institute
* University of Zurich

<!--more-->





