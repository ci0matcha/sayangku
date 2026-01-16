# <!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Maaf Ya Sayang ❤️</title>

<style>
body {
  background: linear-gradient(to right, #ff9a9e, #fad0c4);
  text-align: center;
  font-family: Arial;
  padding-top: 80px;
}

h1 {
  color: white;
  font-size: 36px;
}

p {
  color: white;
  font-size: 20px;
  margin: 15px;
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

.heart {
  font-size: 50px;
  animation: float 2s infinite;
}

@keyframes float {
  0% { transform: translateY(0); }
  50% { transform: translateY(-20px); }
  100% { transform: translateY(0); }
}
</style>
</head>

<body>

<div class="heart">❤️</div>

<h1>Maaf Ya Sayangku 🥺</h1>

<p>Aku minta maaf karena tadi bikin kamu kesel...</p>
<p>Aku janji bakal jadi lebih baik dan lebih jaga perasaan kamu 💕</p>
<p>Aku sayang kamu lebih dari apapun 😘</p>

<button onclick="playMusic()">
Klik Kalau Kamu Udah Maafin Aku 💌
</button>

<audio id="lagu" loop>
  <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-2.mp3">
</audio>

<script>
function playMusic(){
  document.getElementById("lagu").play();
  alert("Makasih ya sayang 😭❤️ Aku janji gak ulangi lagi 😘");
}
</script>

</body>
</html>