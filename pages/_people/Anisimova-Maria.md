---
title: "Maria Anisimova"
layout: default
date: 2014-07-01
excerpt_separator: <!--more-->
excerpt_link: 'https://www.zhaw.ch/de/ueber-uns/person/anis/'
www_link:
www_links_formatted:
image_file: 'Anisimova.jpg'
category:
  - people
tags: # please delete unneeded options
  - ZHAW
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* ZHAW Life Sciences und Facility Management
* Fachstelle Computational Genomics

<!--more-->





