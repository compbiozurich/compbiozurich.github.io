---
title: "Jörg Stelling"
layout: default
date: 2005-07-01
excerpt_separator: <!--more-->
excerpt_link: 'http://www.csb.ethz.ch/group/members/person-detail.MTI1MjYy.TGlzdC8xMDg2LC0xNDY2OTQ0MDU5.html'
image_file: 'Stelling.jpg'
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

* Professor for Computational Systems Biology  
* ETH Zurich 

<!--more-->





