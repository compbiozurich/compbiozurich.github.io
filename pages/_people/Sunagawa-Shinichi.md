---
title: "Shinichi Sunagawa"
layout: default
date: 2016-05-01
excerpt_separator: <!--more-->
excerpt_link: 'https://www.micro.biol.ethz.ch/people/lab-leaders/ssunagaw.html'
image_file: 'Sunagawa.png'
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

* Assistant Professor of Microbiome Research
* ETHZ Institute of Microbiology

<!--more-->

