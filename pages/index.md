---
title: "Bioinformatics, Biomedical Data Science and Computational Biology in the Zurich Area"
layout: default
permalink: '/index.html'
date:   2022-01-04
---

<h2><a href="https://compbiozurich.github.io">{{ page.title }}</a></h2>

Computational biology aims to answer fundamental biological questions with computational approaches, and it develops methods to analyze, manage, and integrate massive amounts of heterogeneous data.

Multiple research groups at the University of Zurich (UZH), the ETH Zurich (ETHZ) and other larger Zürich area institutions (PSI, ZHAW ...) carry out research in computational biology, biomedical data science and bioinformatics methods. Activities span fields as diverse as statistical and functional genomics, evolutionary biology, biostatistics, medical informatics, and neurobiology. The individual research groups form a loose confederation of scientists that is held together by common research interests and collaborations, as well as by shared teaching activities. This website provides an overview of some of the related research and teaching activities in the Zurich area.

<object id="collab_svg" style="width: 100%" type="image/svg+xml" data="">Loading ...</object>

<script>
$(document).ready(function() {

/*podmd
The collaboration plot is embedded with the width corresponding to the current document's
main text area ("section").

TODO: Dynamic scaling or separate legend (i.e. floating).

end_podmd*/

	var width							=		$("section").width();
	var imgh							=		500;
	var query							=		"https://progenetix.org/cgi-bin/collabplots.cgi?nodes=https://raw.githubusercontent.com/compbiozurich/compbiozurich.github.io/master/collab/people.tab&nodesort=random&connections=https://raw.githubusercontent.com/compbiozurich/compbiozurich.github.io/master/collab/connections.tab&plot_bgcolor_hex=%23ffffff&fontcol=%23000000&circradius=50&legendw=60&legendpos=top&legendsort=label+length&fontpx=11&legendfpx=12&imgtype=SVG&transparent=opaque&Submit=Submit&embed=1";
	query 								= 	query+"&imgh="+imgh+"&imgw="+width;

	$("#collab_svg").attr("data",query);

});

</script>

{% comment %}
	Some news ...
{% endcomment %}


{%- assign this_name = "news" -%}
{%- assign this_category = "news" -%}
{%- assign max_list = 5 -%}
{%- assign count_list = 0 -%}

{%- assign today = site.time | date: '%Y%m%d' -%}

{%- assign cat_posts = site.emptyArray -%}
{%- for post in site.documents -%}
  {%- if post.categories contains this_category or post.tags contains this_category -%}
    {%- assign cat_posts = cat_posts | push: post -%}
  {%- endif -%}
{%- endfor -%}

{%- assign cat_posts = cat_posts | sort: 'date' | reverse -%}

{% for post in cat_posts limit: max_list %}
  {% unless post.tags contains '.prepend' or post.tags contains '.append' %}
    {%- assign post_author = post.author | downcase -%}
    {%- assign excerpt_link = post.url | relative_url -%}
    {%- if post.excerpt_link contains '/' -%}
      {%- assign excerpt_link = post.excerpt_link -%}
    {%- endif -%}
		{%- assign post_day = post.date | date: '%Y%m%d' -%}
		{%- assign post_year = post.date | date: '%Y' -%}
    {%- if post_day > today -%}
      {%- assign post_year = 'Upcoming' -%}
    {%- endif %}
		{%- if current_year != post_year -%}
      {% assign current_year = post_year %}
<h2 id="y{{post.date | date: "%Y"}}" style="margin-top: 20px;">{{ current_year }}</h2>
    {% endif %}

<div class="excerpt">
		{%- if post_day > today -%}
<h3 style="color: red">{{ post.date | date: "%Y-%m-%d" }}</h3>
		{%- endif -%}
<a href="{{ excerpt_link }}">{{ post.excerpt }}</a>
  <p class="footnote">
    {%- if post.author -%}{{ post.author | join: " | " }}&nbsp;{%- endif -%}
    {%- if post.date -%}{{ post.date | date: "%Y-%m-%d" }}: {% endif %}
 <a href="{{ excerpt_link }}">more ...</a>
  </p>
</div>
  {% endunless %}  
{% endfor %}

{% comment %}
	More static content ...
{% endcomment %}
