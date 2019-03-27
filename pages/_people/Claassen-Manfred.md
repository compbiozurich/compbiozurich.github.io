---
title: "Manfred Claassen"
layout: default
date: 2013-01-01
excerpt_separator: <!--more-->
excerpt_link: 'http://www.imsb.ethz.ch/research/claassen.html'
www_link:
www_links_formatted:
image_file: 'Claassen.jpg'
category:
  - people
tags: # please delete unneeded options
  - ETHZ
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Institute of Molecular Systems Biology
* ETHZ

<!--more-->
