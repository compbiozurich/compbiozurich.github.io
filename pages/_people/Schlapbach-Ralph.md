---
title: "Ralph Schlapbach"
layout: default
date: 2007-07-01
excerpt_separator: <!--more-->
excerpt_link: 'http://www.fgcz.ch/the-center/people/schlapbach.html'
image_file: 'Schlapbach.jpg'
category:
  - people
tags:
  - FGCZ
  - ETHZ
  - SIB
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Managing Director
* FGZC

<!--more-->
