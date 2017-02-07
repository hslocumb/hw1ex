
<!DOCTYPE html>  <!-- Use w3schools for reference and prototyping, if you'd like -->

<html>
<head>
<style>
div.container {
    width: 100%;
    border: 1px solid gray;
}
header, footer {
    padding: 1em;
    color: rgb(0,255,0);
    background-color: rgb(255,0,255);
    clear: left;
    text-align: center;
}
body {
  background-color: rgb(255,255,0);
    color: rgb(0,255,0)
}
#table1, th, td {
    font-family: Comic Sans;
    color: rgb(155,48,255);
    border-collapse: collapse;
}
th, td {
  padding: 15px;
  text-align: left;
}
tr:nth-child(even) {
  background-color: rgb(41,36,33);
}
tr:nth-child(odd) {
  background-color: rgb(255,0,0);
}


</style>

</head>

<body>

<script type="text/javascript">
  function blink() {
    var blinks = document.getElementsByTagName('blink');
    for (var i = blinks.length - 1; i >= 0; i--) {
      var s = blinks[i];
      s.style.visibility = (s.style.visibility === 'visible') ? 'hidden' : 'visible';
    }
    window.setTimeout(blink, 500);
  }
  if (document.addEventListener) document.addEventListener("DOMContentLoaded", blink, false);
  else if (window.addEventListener) window.addEventListener("load", blink, false);
  else if (window.attachEvent) window.attachEvent("onload", blink);
  else window.onload = blink;
</script>

<script type="text/javascript">
  function blink1() {
    var blinks = document.getElementsByTagName('p');
    for (var i = blinks.length - 1; i >= 0; i--) {
      var s = blinks[i];
      s.style.visibility = (s.style.visibility === 'visible') ? 'hidden' : 'visible';
    }
    window.setTimeout(blink1, 100);
  }
  if (document.addEventListener) document.addEventListener("DOMContentLoaded", blink1, false);
  else if (window.addEventListener) window.addEventListener("load", blink1, false);
  else if (window.attachEvent) window.attachEvent("onload", blink1);
  else window.onload = blink1;
</script>

<script type="text/javascript">
  function blink2() {
    var blinks = document.getElementsByTagName('tr');
    for (var i = blinks.length - 1; i >= 0; i--) {
      var s = blinks[i];
      s.style.visibility = (s.style.visibility === 'visible') ? 'hidden' : 'visible';
    }
    window.setTimeout(blink2, 300);
  }
  if (document.addEventListener) document.addEventListener("DOMContentLoaded", blink2, false);
  else if (window.addEventListener) window.addEventListener("load", blink2, false);
  else if (window.attachEvent) window.attachEvent("onload", blink2);
  else window.onload = blink2;
</script>

<blink><header>
  <h2 style="font-family:Helvetica;">Inaugural Address Analysis</h2>
</header></blink>

<p style="font-family:Helvetica;"> </p>
<p>
These tables summarize textual analysis
of selected presidential inaugural addresses. The 
Python scripts that support the analysis are part of the 
accompanying repository. 
</p>


<blink><table id="table1" align="center"> <!-- style="color:black;" -->
<tr>
   <td>President</td>
   <td>Years</td>
   <td>Relative Terribility on 1-10 scale</td>
</tr>
<tr>
   <td>Donald Trump</td>
   <td>2017-hopefully soon</td>
   <td>69*420*infinity</td>
</tr>
<tr>
   <td>Barack Obama</td>
   <td>2009-2017</td>
   <td>1</td>
</tr>
<tr>
   <td>George W. Bush</td>
   <td>2005-2009</td>
   <td>9</td>
</tr>
</table></blink>

</body>
