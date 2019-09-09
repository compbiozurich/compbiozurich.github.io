---
title: "Isabelle Mansuy"
layout: default
date: 2019-09-09
excerpt_separator: <!--more-->
excerpt_link: 'https://www.hifo.uzh.ch/en/research/mansuy.html'
image_file: 'Mansuy.png'
category:
  - people
tags:
  - UZH
  - ETHZ
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Professor of Neuroepigenetics
* Brain Research Institute, Medical Faculty of the University of Zürich
* Institute for Neuroscience, Department of Health Sciences and Technology of the ETH Zürich

<!--more-->
