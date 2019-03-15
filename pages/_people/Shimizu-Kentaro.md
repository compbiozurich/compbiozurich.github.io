---
title: "Kentaro Shimizu"
layout: default
date: 2006-07-01
excerpt_separator: <!--more-->
excerpt_link: 'https://www.ieu.uzh.ch/en/staff/member/shimizu_kentaro.html'
www_link:
www_links_formatted:
image_file: 'Shimizu.png'
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

* Professor, Department of Evolutionary Biology and Environmental Studies
* University of Zürich

<!--more-->

