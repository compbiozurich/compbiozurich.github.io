---
title: "Gunnar R&auml;tsch"
layout: default
date: 2016-05-01
excerpt_separator: <!--more-->
excerpt_link: 'http://bmi.inf.ethz.ch/people/person/gunnar-raetsch/'
image_file: 'Raetsch.png'
category:
  - people
tags:
  - ETHZ
  - SIB
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Professor of Biomedical Informatics 
* ETH Zurich 
* Department of Computer Science 

<!--more-->





