---
title: "Richard Hahnloser"
layout: default
date: 2010-05-01
excerpt_separator: <!--more-->
excerpt_link: 'https://www.ini.uzh.ch/en/research/groups/zfinch'
image_file: 'Hahnloser.png'
category:
  - people
tags:
  - UZH
  - INI
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Professor
* Institute of Neuroinformatics
* University of Zürich

<!--more-->

