<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>PK Gamer</title>

<style>
body{
    margin:0;
    background:black;
    color:white;
    text-align:center;
    font-family:Arial;
}

button{
    padding:10px 20px;
    font-size:18px;
}

#game{
    display:none;
}
</style>

</head>
<body>

<div id="login">
    <h1>PK Gamer</h1>

    <input type="email" id="gmail" placeholder="Enter Gmail">
    <br><br>

    <button onclick="startGame()">Login</button>
</div>

<div id="game">
    <h1>🎮 Welcome To PK Gamer</h1>
    <h2>Game Started!</h2>
</div>

<script>
function startGame(){

    document.getElementById("login").style.display="none";

    document.getElementById("game").style.display="block";
}
</script>

</body>
</html>
