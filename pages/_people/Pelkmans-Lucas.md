---
title: "Lucas Pelkmans"
layout: default
date: 2010-07-01
excerpt_separator: <!--more-->
excerpt_link: 'https://www.imls.uzh.ch/en/research/pelkmans.html'
www_link:
www_links_formatted:
image_file: 'Pelkmans.jpg'
category:
  - people
tags: # please delete unneeded options
  - UZH
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Professor of Biology
* Institute of Molecular Life Sciences 
* University of Zurich

<!--more-->





