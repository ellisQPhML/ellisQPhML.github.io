---
title: QPhML 2020 Registration
layout: default
---

<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSfFYZMO29bWFb4kmNaLIL6iZRs-JAWpUfrF-p9EbTsFB9XQEQ/formResponse?" target="hidden_iframe" onsubmit="submitted=true;">
  Name:<br>
  <input type="text" name="entry.838988348" id="entry.838988348"><br>
  Affiliation:<br>
  <input type="text" name="entry.488853232" id="entry.488853232"><br>
  Email address:<br>
  <input type="text" name="entry.907667145" id="entry.907667145"><br>
  <input type="submit" value="Submit">
</form>

<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>

<script src="assets/js/jquery.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gform').on('submit', function(e) {
  $('#gform *').fadeOut(2000);
  $('#gform').prepend('Your submission has been processed...');
  });
</script>
