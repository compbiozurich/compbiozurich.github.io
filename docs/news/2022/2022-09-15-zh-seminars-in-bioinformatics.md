---
template: blog_post.html
title: Comprehensive network prediction for any fully sequence genome in STRING database
description: 'Zurich Seminars in Bioinformatics - Damian Szklarczyk'
date: 2022-09-15
authors:
  - '@mbaudis'
---

**Abstract** Every day new genomes are sequenced and existing genomes are re-sequenced and re-annotated. In the new version of STRING the user can submit any fully sequenced genome for complete network and functional annotation. To do so. will require only minimal input from the user in a form of the proteome in a FASTA format and, if known, a taxonomical clade of the given genome.<!--more--> 

Utilizing hierarchical orthology relationships from the eggNOG database precomputed for more than 1600 taxonomical clades the STRING algorithm chooses the most precise orthologous group for each protein and leverages all the data already included in the database for this group and its parent groups to predict both the functional neighbourhood and the functional annotation of each protein in the user input. The resulting dataset is explorable in the same manner as any other organism present in the STRING database: it’s sharable, with fully working user interface, extensive REST API access, a set of enrichment analysis tools and clustering methods, and simple flat-files available for download.  

* 12:15 UZH Irchel Y55-l-06/08 and ZOOM Call

---

<!-- Begin Mailchimp Signup Form -->
<link href="//cdn-images.mailchimp.com/embedcode/classic-071822.css" rel="stylesheet" type="text/css">
<style type="text/css">
</style>
<div id="mc_embed_signup">
    <form action="https://compbiozurich.us4.list-manage.com/subscribe/post?u=0141fde44f8e02ca53020666b&amp;id=3a49cab6bf&amp;f_id=003381e8f0" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
        <div id="mc_embed_signup_scroll">
        <h3>Subscribe to Zurich Seminars in Bioinformatics</h3>
<div class="mc-field-group">
  <label for="mce-EMAIL">Email Address</label>
  <input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL" required>
  <span id="mce-EMAIL-HELPERTEXT" class="helper_text"></span>
</div>
  <div id="mce-responses" class="clear foot">
    <div class="response" id="mce-error-response" style="display:none"></div>
    <div class="response" id="mce-success-response" style="display:none"></div>
  </div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_0141fde44f8e02ca53020666b_3a49cab6bf" tabindex="-1" value=""></div>
        <div class="optionalParent">
            <div class="clear foot">
                <input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button">
                <p class="brandingLogo"><a href="http://eepurl.com/h-TZ9D" title="Mailchimp - email marketing made easy and fun"><img src="https://eep.io/mc-cdn-images/template_images/branding_logo_text_dark_dtp.svg"></a></p>
            </div>
        </div>
    </div>
</form>
</div>
<script type='text/javascript' src='//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js'></script>
<script type='text/javascript'>
  (
    function($) {
      window.fnames = new Array();
      window.ftypes = new Array();
      fnames[0]='EMAIL';
      ftypes[0]='email';
      fnames[1]='FNAME';
      ftypes[1]='text';
      fnames[2]='LNAME';
      ftypes[2]='text';
      fnames[3]='ADDRESS';
      ftypes[3]='address';
      fnames[4]='PHONE';
      ftypes[4]='phone';
      fnames[5]='BIRTHDAY';
      ftypes[5]='birthday';
    }(jQuery)
  );
  var $mcj = jQuery.noConflict(true);
</script>
<!--End mc_embed_signup-->