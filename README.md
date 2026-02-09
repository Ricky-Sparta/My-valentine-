# My-valentine-
index.html
style.css
script.js
<!DOCTYPE html>
<html>
<head>
  <title>Shanny ❤️</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<audio autoplay loop>
  <source src="song.mp3" type="audio/mpeg">
</audio>

<div class="card" id="card">
  <img src="her.jpg" class="photo">
  <h1>Shanny 💖</h1>
  <p>You make my world brighter every single day.</p>
  <h2>Will you be my Valentine? 🌹</h2>

  <button onclick="yesClick()">YES 💘</button>
  <button id="noBtn" onmouseover="moveButton()">NO 💔</button>

  <p class="from">From: Ragas 💘</p>

  <a href="https://wa.me/?text=I%20said%20YES%20to%20being%20your%20Valentine%20Ragas%20❤️" target="_blank">
    <button class="whatsapp">Reply on WhatsApp 💬</button>
  </a>
</div>

<div id="hearts"></div>
<div id="fireworks"></div>

<script src="script.js"></script>
</body>
</html>
