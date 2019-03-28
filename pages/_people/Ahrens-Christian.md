---
title: "Christian Ahrens"
layout: default
date: 2016-07-01
excerpt_separator: <!--more-->
excerpt_link: 'https://www.sib.swiss/christian-ahrens-group'
image_file: 'Ahrens.jpg'
category:
  - people
tags:
  - Agroscope
  - SIB
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Bioinformatics and Proteogenomics Group
* Agroscope, Wädenswil

<!--more-->

