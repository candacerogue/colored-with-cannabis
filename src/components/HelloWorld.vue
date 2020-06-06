<template>
  <div class="hello">
    <h2>all your tech resources in one place 
      for black-owned and ally cannabis businesses
    </h2>
    <div class="email-signup">
      <!-- Begin Mailchimp Signup Form -->
    <link href="//cdn-images.mailchimp.com/embedcode/classic-10_7.css" rel="stylesheet" type="text/css">
    <div id="mc_embed_signup">
    <form action="https://candacerogue.us14.list-manage.com/subscribe/post?u=ffd9760471781939a950401fd&amp;id=52ca0d5707" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
        <div id="mc_embed_signup_scroll">
      <h2>Subscribe</h2>
    <div class="indicates-required"><span class="asterisk">*</span> indicates required</div>
    <div class="mc-field-group">
      <label for="mce-EMAIL">Email Address  <span class="asterisk">*</span>
    </label>
      <input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL">
    </div>
    <div class="mc-field-group">
      <label for="mce-FNAME">First Name </label>
      <input type="text" value="" name="FNAME" class="" id="mce-FNAME">
    </div>
    <div class="mc-field-group">
      <label for="mce-LNAME">Last Name </label>
      <input type="text" value="" name="LNAME" class="" id="mce-LNAME">
    </div>
      <div id="mce-responses" class="clear">
        <div class="response" id="mce-error-response" style="display:none"></div>
        <div class="response" id="mce-success-response" style="display:none"></div>
      </div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
        <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_ffd9760471781939a950401fd_52ca0d5707" tabindex="-1" value=""></div>
        <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
        </div>
    </form>
    </div>
    <!--End mc_embed_signup-->
    <p>Candace Rogue LLC</p>
    </div>
  </div>
</template>
<script type='text/javascript' src='//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js'></script><script type='text/javascript'>(function($) {window.fnames = new Array(); window.ftypes = new Array();fnames[0]='EMAIL';ftypes[0]='email';fnames[1]='FNAME';ftypes[1]='text';fnames[2]='LNAME';ftypes[2]='text';}(jQuery));var $mcj = jQuery.noConflict(true);</script>
<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.hello {
  /* display: flex; */
  justify-items: center;
  max-width: 525px;
  position: absolute;
  left: 30%;
  order: 2;
}

.email-signup {
  width: 100%;
  height: 500px;
  background-image: url(../assets/Content-Border.svg);
  background-repeat: no-repeat;
  background-position: center top;
  background-size: 500px 500px;
}

#mc_embed_signup{
  background: #000000;
  color: white; 
  clear:left; 
  font:14px Helvetica,Arial,sans-serif;  
  width:300px;
  height: 300px;
  margin: 0 auto;
}


input#mc-embedded-subscribe {
    background-color: red;
}
      /* Add your own Mailchimp form style overrides in your site stylesheet or in this style block.
        We recommend moving this block and the preceding CSS link to the HEAD of your HTML file. */

h2 {
  text-transform: uppercase;
  color: red;
}

p {
  color: white;
  margin-top: 100px;
}
</style>
