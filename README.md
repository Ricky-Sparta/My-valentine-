

https://github.com/user-attachments/assets/2bac9b8b-abac-49bb-8c8d-9becea9d62f5

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
function yesClick() {
  document.getElementById("card").innerHTML = `
    <h1 style="color:hotpink;">Yay Shanny!!! 💖</h1>
    <p>You just made me the happiest person alive 🥰</p>
    <h2>Happy Valentine’s Day 🌹</h2>
    <p>I love you so much 😘</p>
    <p>— From Ragas 💘</p>
  `;
  fireworks();
}

function moveButton() {
  const noBtn = document.getElementById("noBtn");
  const x = Math.random() * (window.innerWidth - noBtn.clientWidth);
  const y = Math.random() * (window.innerHeight - noBtn.clientHeight);

  noBtn.style.position = "absolute";
  noBtn.style.left = x + "px";
  noBtn.style.top = y + "px";
}

// Floating hearts
setInterval(() => {
  const heart = document.createElement("div");
  heart.className = "heart";
  heart.innerHTML = "💖";
  heart.style.left = Math.random() * window.innerWidth + "px";
  heart.style.bottom = "0px";
  document.body.appendChild(heart);

  setTimeout(() => heart.remove(), 5000);
}, 300);

// Fireworks
function fireworks() {
  setInterval(() => {
    const firework = document.createElement("div");
    firework.className = "firework";
    firework.innerHTML = "🎆";
    firework.style.left = Math.random() * window.innerWidth + "px";
    firework.style.top = Math.random() * window.innerHeight + "px";
    document.body.appendChild(firework);

    setTimeout(() => firework.remove(), 1000);
  }, 400);
}function yesClick() {
  document.getElementById("card").innerHTML = `
    <h1 style="color:hotpink;">Yay Shanny!!! 💖</h1>
    <p>You just made me the happiest person alive 🥰</p>
    <h2>Happy Valentine’s Day 🌹</h2>
    <p>I love you so much 😘</p>
    <p>— From Ragas 💘</p>
  `;
  fireworks();
}

function moveButton() {
  const noBtn = document.getElementById("noBtn");
  const x = Math.random() * (window.innerWidth - noBtn.clientWidth);
  const y = Math.random() * (window.innerHeight - noBtn.clientHeight);

  noBtn.style.position = "absolute";
  noBtn.style.left = x + "px";
  noBtn.style.top = y + "px";
}

// Floating hearts
setInterval(() => {
  const heart = document.createElement("div");
  heart.className = "heart";
  heart.innerHTML = "💖";
  heart.style.left = Math.random() * window.innerWidth + "px";
  heart.style.bottom = "0px";
  document.body.appendChild(heart);

  setTimeout(() => heart.remove(), 5000);
}, 300);

// Fireworks
function fireworks() {
  setInterval(() => {
    const firework = document.createElement("div");
    firework.className = "firework";
    firework.innerHTML = "🎆";
    firework.style.left = Math.random() * window.innerWidth + "px";
    firework.style.top = Math.random() * window.innerHeight + "px";
    document.body.appendChild(firework);

    setTimeout(() => firework.remove(), 1000);
  }, 400);
}
