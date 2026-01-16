<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Maaf fajriku sayang❤️</title>

<style>
body {
  background: linear-gradient(to right, pink, lightcoral);
  text-align: center;
  font-family: Arial;
  padding-top: 80px;
}

h1 {
  color: white;
  font-size: 35px;
}

p {
  color: white;
  font-size: 20px;
}

button {
  background: white;
  color: hotpink;
  border: none;
  padding: 14px 25px;
  font-size: 18px;
  border-radius: 30px;
  cursor: pointer;
}

button:hover {
  background: hotpink;
  color: white;
}
</style>
</head>

<body>

<!-- EDIT DI SINI -->
<h1>Maaf fajriku Sayangku 🥺❤️</h1>

<p>Maaf ya karena tadi bikin ki marah...</p>
<p>tidak pamit pas mau berangkat kerja, tidak kiss ki juga huhu</p>
<p>janji besok2 tidak kuulangmi, love u! 💕</p>
<!-- SAMPAI SINI -->

<button onclick="playMusic()">
Klik Kalau Kamu Udah Maafin Aku 💌
</button>

<audio id="lagu" loop>
  <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-2.mp3">
</audio>

<script>
function playMusic(){
  document.getElementById("lagu").play();

  // EDIT DI SINI
  alert("Makasih ya sayang ❤️ Aku janji berubah 😘");
}
</script>

</body>
</html>