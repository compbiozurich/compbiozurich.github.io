---
title: "Christof Aegerter"
layout: default
date: 2008-07-01
excerpt_separator: <!--more-->
permalink: /people/Christof-Aegerter.html
excerpt_link: 'https://www.physik.uzh.ch/en/groups/aegerter/team.html'
image_file: 'Aegerter.png'
category:
  - people
tags:
  - UZH
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 60px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## {{ page.title }}

* Professor of Physics
* Disordered and Biological Soft Matter
* Physics Department
* University of Zürich

<!--more-->

