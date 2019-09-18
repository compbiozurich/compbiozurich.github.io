---
title: "Daniel Stekhoven"
layout: default
date: 2014-09-01
excerpt_separator: <!--more-->
excerpt_link: 'https://www.nexus.ethz.ch'
image_file: 'Stekhoven.png'
category:
  - people
tags:
  - NEXUS
  - ETHZ
  - SIB
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* NEXUS Personalized Health Technologies
* Head, Clinical Bioinformatics

<!--more-->





