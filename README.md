# Marwa-s-safeplace
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Mawi ❤️</title>
<style>
* {
  box-sizing: border-box;
}
body {
  margin: 0;
  min-height: 100vh;
  font-family: Georgia, serif;
  color: #fff0f5;
  text-align: center;
  background: linear-gradient(145deg, #190914, #55152e, #210c20);
  padding: 25px 15px;
}
.card {
  max-width: 480px;
  margin: 20px auto;
  padding: 28px 22px;
  border: 1px solid #f5a4c3;
  border-radius: 25px;
  background: rgba(255,255,255,0.07);
  box-shadow: 0 0 30px #e7548050;
}
h1 {
  color: #ffb6d0;
  font-size: 2.4em;
}
h2 {
  color: #ffd4e3;
}
p {
  line-height: 1.8;
  font-size: 17px;
}
.heart {
  font-size: 55px;
  animation: beat 1s infinite alternate;
}
@keyframes beat {
  to { transform: scale(1.15); }
}
button {
  background: #f16b9c;
  border: none;
  border-radius: 25px;
  color: white;
  padding: 13px 22px;
  margin: 10px;
  font-size: 16px;
  cursor: pointer;
}
button:hover {
  background: #ff8db5;
}
#secret {
  display: none;
  margin-top: 20px;
  padding: 15px;
  border-radius: 15px;
  background: #6c2546;
}
.small {
  font-size: 13px;
  color: #ffc5d9;
}
</style>
</head>
<body>

<div class="card">
  <div class="heart">❤️</div>
  <h1>For My Mawi</h1>
  <h2>Marwa 😍👠</h2>

  <p>
    To the prettiest girl in my world,<br>
    this little website is just for you.
  </p>

  <p>
    You're not just my girlfriend.<br>
    You're my favorite person,<br>
    my happiness, and my special girl.
  </p>

  <button onclick="showLove()">Open your surprise 💌</button>

  <div id="secret">
    <h2>I love you, Marwa ❤️</h2>
    <p>
      No matter how many people I meet,<br>
      you'll always have your own special place
      in my heart.
    </p>
    <p>Forever your Anes 🫶🏻</p>
  </div>
</div>

<div class="card">
  <h2>Things that remind me of you 🎀</h2>
  <p>🐱 Cats</p>
  <p>💄 Makeup</p>
  <p>👭 Your friends</p>
  <p>❤️ And me, of course 😭</p>
</div>

<div class="card">
  <h2>Our Special Date 💞</h2>
  <p>23 September</p>
  <p>A date that means something special to us.</p>

  <h2>Your Birthday 🎂</h2>
  <p>7 March 2010</p>
</div>

<div class="card">
  <h2>One last thing, Mawi...</h2>
  <p>
    If I could choose again,<br>
    I'd still choose you.<br>
    Every time. ❤️
  </p>
  <p>Made with love by Anes 💌</p>
</div>

<script>
function showLove() {
  const secret = document.getElementById("secret");
  secret.style.display =
    secret.style.display === "block" ? "none" : "block";
}
</script>

</body>
</html>
