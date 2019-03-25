---
title: "Tuncay Baubec"
layout: default
date: 2016-05-01
excerpt_separator: <!--more-->
excerpt_link: 'https://www.baubeclab.org'
www_link:
www_links_formatted:
image_file: 'Baubec.png'
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

* SNF Professor
* Department of Molecular Mechanisms of Disease
* Science Faculty and Vetsuisse Faculty
* University of Zürich

<!--more-->

