---
title: "Joachim M. Buhmann"
layout: default
date: 2003-07-01
excerpt_separator: <!--more-->
excerpt_link: 'http://www.ise.inf.ethz.ch/people/person-detail.html?persid=113456'
image_file: 'Buhmann.jpg'
category:
  - people
tags:
  - ETHZ
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Professor for Computer Science  
* ETH Zurich 

<!--more-->





