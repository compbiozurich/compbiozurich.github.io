---
title: "Nicola Zamboni"
layout: default
date: 2005-07-01
excerpt_separator: <!--more-->
excerpt_link: 'http://www.imsb.ethz.ch/research/zamboni.html'
www_link:
www_links_formatted:
image_file: 'Zamboni.jpg'
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

* Systems Biology of Metabolism
* ETHZ

<!--more-->
