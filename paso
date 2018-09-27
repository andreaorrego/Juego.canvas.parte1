# Juego.canvas.parte1
Como crear un juego 2D con CANVAS
Para empezar, necesitamos  crear la estructura básica de la página. Eso lo hacemos utilizando HTML y el elemento  <canvas>.
En un editor de texto escribe el siguiente código y guardalo omo quieras.
  
  <!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title>Gamedev Canvas Workshop</title>
    <style>
    	* { padding: 0; margin: 0; }
    	canvas { background: #eee; display: block; margin: 0 auto; }
    </style>
</head>
<body>
<canvas id="myCanvas" width="400" height="300"></canvas>
<script>
	// JavaScript code goes here
</script>
</body>
</html>
 
En el script pon el siguiente código:

var canvas = document.getElementById("myCanvas");
var ctx = canvas.getContext("2d");

Ejemplo para dibujar un cuadrado.
Pon el siguiente código debajo del anterior

ctx.beginPath();
ctx.rect(50, 20, 70, 50);
ctx.fillStyle = "#FF0000";
ctx.fill();
ctx.closePath();

Circulo 
Pon el siguiente código debajo del anterior

ctx.beginPath();
ctx.arc(300, 120, 40, 0, math.PI*2, false);
ctx.fillStyle = "red";
ctx.fill();
ctx.closePath();

Trazo
Pon el siguiente código debajo del anterior

ctx.beginPath();
ctx.rect(120, 70, 50, 100);
ctx.strokeStyle = "rgba(0, 240, 0, 0.5)";
ctx.stroke();
ctx.closePath();

Compara tu código

<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title>Gamedev Canvas Workshop</title>
    <style>
    	* { padding: 0; margin: 0; }
    	canvas { background: #eee; display: block; margin: 0 auto; }
    </style>
</head>
<body>
<canvas id="myCanvas" width="400" height="300"></canvas>
<script>
	var canvas = document.getElementById("myCanvas");
	var ctx = canvas.getContext("2d");
	ctx.beginPath();
	ctx.rect(50, 20, 70, 40);
	ctx.fillStyle = "#7B68EE";
	ctx.fill();
	ctx.closePath();
	ctx.beginPath();
	ctx.arc(300, 120, 40, 0, Math.PI*2, false);
	ctx.fillStyle = "red";
	ctx.fill();
	ctx.closePath();
	ctx.beginPath();
	ctx.rect(120, 70, 50, 100);
	ctx.strokeStyle = "rgba(0, 240, 0, 0.5)";
	ctx.stroke();
	ctx.closePath();
</script>
</body>
</html>
