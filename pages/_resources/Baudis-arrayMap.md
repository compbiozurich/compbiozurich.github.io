---
title: "arrayMap - cancer genome profiling"
layout: default
date: 2012-01-01
excerpt_separator: <!--more-->
excerpt_link: 'https://arraymap.org'
www_link:
www_links_formatted:
image_file: 'arraymap-logo-160.png'
category:
  - resources
tags: # please delete unneeded options
  - databases
  - tools
---

{% for static_file in site.static_files %}
  {% if static_file.path contains page.image_file %}
<img style="float: right; max-width: 160px;" src="{{ static_file.path | relative_url}}" />
  {% endif %}
{% endfor %}

## arrayMap - genomic profiling in cancer

arrayMap tracks, annotates and analyzes all accessible genomic arrays used in cancer studies.

<!--more-->

