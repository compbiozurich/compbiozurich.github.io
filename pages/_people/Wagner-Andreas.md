---
title: "Andreas Wagner"
layout: default
date: 2006-01-01
excerpt_separator: <!--more-->
excerpt_link: 'https://www.ieu.uzh.ch/wagner/people.html'
image_file: 'Wagner.png'
category:
  - people
tags:
  - UZH
  - SIB
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Professor and Chairman, Dept. of Evolutionary Biologyand Environmental Studies
* University of Zurich

<!--more-->





