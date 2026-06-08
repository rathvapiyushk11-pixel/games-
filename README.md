<head>
<meta charset="UTF-8">
<title>PK Gamer Battle</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<div id="login">
<h1>PK Gamer</h1>
<input type="email" placeholder="Enter Gmail">
<button onclick="startGame()">Login</button>
</div>

<div id="game" style="display:none;">
<h2>Score: <span id="score">0</span></h2>
<canvas id="canvas"></canvas>
</div>

<script src="game.js"></script>
</body>
</html>  
body{
margin:0;
background:black;
color:white;
text-align:center;
font-family:Arial;
}

canvas{
background:#222;
border:2px solid white;
}

function startGame(){
document.getElementById("login").style.display="none";
document.getElementById("game").style.display="block";
alert("Game Started!");
}
