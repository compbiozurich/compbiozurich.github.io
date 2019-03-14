---
title: "Simple Map Plotting Utility"
date: 2018-07-20
layout: default
author: mbaudis
excerpt_separator: <!--more-->
pdf_file_name:
pdf_file_type:    # slides poster article
www_link: 
www_links_formatted:   # use this for a quoted, complete HTML link with label '<a href="http://" target="_blank">...</a>'
category: 
  - howto      # publication howto presentation
tags: 
  - code          # article talk poster slides
  - API
  - maps
---

## {{ page.title }}

<!--  CONTENT  -->

This utility allows the plotting of Google maps with included proportional markers, based on a file accessible through an URL (e.g. a Dropbox share link).


<!--more-->


#### File Formats:

* tab-delimited text file (no quotes) or .xls
* fixed column order/content


<table>
<tr>
  <th>NAME</th>
  <th>CITY</th>
  <th>COUNTRY</th>
  <th>LATITUDE</th>
  <th>LONGITUDE</th>
  <th>COUNT</th>
  <th>LINK</th>
  <th>ICONLINK</th>
</tr>
<tr>
  <td>Michael Baudis, UZH</td>
  <td>Zurich</td>
  <td>Switzerland</td>
  <td>47.37</td>
  <td>8.55</td>
  <td>5</td>
  <td>http://www.imls.uzh.ch/research/baudis/</td>
  <td>http://progenetix.org/p/UZH_logo_80.png</td>
</tr>
<tr>
  <td>Life Sciences Zurich Graduate School</td>
  <td>Zurich</td>
  <td>Switzerland</td>
  <td>47</td><td>8</td>
  <td>307</td>
  <td>http://www.lszgs.ch</td>
  <td></td>
</tr>
<tr>
  <td> </td>
  <td> </td>
  <td>Germany</td>
  <td>51</td>
  <td>10</td>
  <td>217</td>
  <td> </td>
  <td> </td>
</tr>
<tr>
  <td> </td>
  <td> </td>
  <td>Italy</td>
  <td>44</td>
  <td>11</td>
  <td>75</td>
  <td> </td>
  <td> </td>
</tr>
<tr>
  <td>Walter White</td>
  <td>Albuquerque</td>
  <td>United States</td>
  <td>35</td>
  <td>-106</td>
  <td>2</td>
  <td>https://en.wikipedia.org/wiki/Breaking_Bad</td>
  <td> </td>
</tr>
</table>


#### Example (using defaults):

```
http://compbio.ch/simplemap/?locfile=https://www.dropbox.com/s/miybztfwfa2voau/LSZGS_student_countries.xls?dl=0
```

#### General Structure:

```
http://compbio.ch/simplemap/?locscale=___nnn___&imgw=___nnn___&mapheight=___nnn___&locfile=____URL____
```

##### Parameters to modify the plot:

* locfile= ...
    * table (see above) with the loc data
* locscale=5
    * factor to modify the size of the circle markers
    * a value of 0 (or a negative number) suppresses the marker
    * no circle markers will be displayed if none of the count values is >1
* imgw=794
    * width of the map, in pixels
* mapheight=480
    * height of map, in pixels
   

#### Example with parameters:

```
http://compbio.ch/simplemap/?locscale=20&imgw=1024&mapheight=512&locfile=https://www.dropbox.com/s/miybztfwfa2voau/LSZGS_student_countries.xls?dl=0
```
