
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
    color: black;
    background-color: rgb(119,136,153);
    clear: left;
    text-align: center;
}
body {
   background-color: #dddddd;
}
#table1, th, td {
    font-family: Helvetica;
    color: black;
    border-collapse: collapse;
}
th, td {
   padding: 15px;
   text-align: left;
}
tr:nth-child(even) {
   background-color: rgb(176,196,222);
}
tr:nth-child(odd) {
   background-color: rgb(202,225,255);
}

</style>

</head>
<body>

<header>
   <h2 style="font-family:Helvetica;">Inaugural Address Analysis</h2>
</header>

<p style="font-family:Helvetica;"> 
These tables summarize textual analysis
of selected presidential inaugural addresses. The 
Python scripts that support the analysis are part of the 
accompanying repository. 
</p>

<table id="table1" align="center"> <!-- style="color:black;" -->
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
</table>

</body>
