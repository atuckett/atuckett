<html>
<body>

<canvas id="myCanvas" width="250" height="1000" style="border:1px solid #d3d3d3;">
Your browser does not support the HTML canvas tag.</canvas>

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");

// Create gradient
var grd = ctx.createRadialGradient(75,50,5,90,60,100);
grd.addColorStop(0,"purple");
grd.addColorStop(1,"black");

// Fill with gradient
ctx.fillStyle = grd;
ctx.fillRect(0,0,250,200);
</script>

</body>
</html>


