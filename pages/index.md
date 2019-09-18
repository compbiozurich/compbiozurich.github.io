---
title: "Computational Biology in Zurich"
layout: default
permalink: '/index.html'
date:   2019-09-13
---

<h2><a href="https://compbiozurich.github.io">{{ page.title }}</a></h2>

Computational biology aims to answer fundamental biological questions with computational approaches, and it develops methods to analyze, manage, and integrate massive amounts of heterogeneous data.

Multiple research groups at the University of Zurich (UZH) and the ETH Zurich (ETHZ) carry out research in computational biology. Their activities span fields as diverse as functional genomics, evolutionary biology, biostatistics, medical informatics, and neurobiology. These research groups are affiliated with various institutes and form a loose confederation of scientists that is held together by common research interests and collaborations, as well as by shared teaching activities. This website provides an overview of research and teaching activities in this area in Zurich.

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
