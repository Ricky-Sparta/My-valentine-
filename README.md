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

<script src="script.js"></script>
</body>
</html>body {
  background: linear-gradient(to right, pink, red);
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: Arial, sans-serif;
}

.card {
  background: white;
  padding: 25px;
  border-radius: 20px;
  text-align: center;
  box-shadow: 0 0 20px rgba(0,0,0,0.3);
}

.photo {
  width: 150px;
  border-radius: 50%;
  margin-bottom: 10px;
}

.from {
  margin-top: 10px;
  font-weight: bold;
  color: hotpink;
}

button {
  padding: 12px 20px;
  margin: 8px;
  border: none;
  border-radius: 20px;
  font-size: 16px;
  cursor: pointer;
}

button:first-child {
  background-color: hotpink;
  color: white;
}

#noBtn {
  background-color: gray;
  color: white;
}

.whatsapp {
  background-color: #25D366;
  color: white;
}function yesClick() {
  document.getElementById("card").innerHTML = `
    <h1 style="color:hotpink;">Yay Shanny!!! 💖</h1>
    <p>You just made me the happiest person alive 🥰</p>
    <h2>Happy Valentine’s Day 🌹</h2>
    <p>I love you so much 😘</p>
    <p>— From Ragas 💘</p>
  `;
}

function moveButton() {
  const noBtn = document.getElementById("noBtn");
  const x = Math.random() * (window.innerWidth - noBtn.clientWidth);
  const y = Math.random() * (window.innerHeight - noBtn.clientHeight);

  noBtn.style.position = "absolute";
  noBtn.style.left = x + "px";
  noBtn.style.top = y + "px";
}

https://github.com/user-attachments/assets/779aa6f9-075c-4446-8930-ae086ec71ff0

