
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>For Mawi ♡</title>
<style>
*{box-sizing:border-box}
body{
 margin:0;padding:20px;color:#704158;
 font-family:"Trebuchet MS",sans-serif;
 background:linear-gradient(135deg,#fff3f7,#f7d3e2,#fff8f5);
}
main{max-width:850px;margin:auto}
.card{
 background:#fffbfccc;padding:25px;margin:18px 0;
 border:1px solid #e8b4c8;border-radius:24px;
 box-shadow:0 8px 25px #b9587d15;
}
.hero{text-align:center;padding:40px 20px}
h1,h2{font-family:Georgia,serif;font-weight:normal;color:#b9587d}
h1{font-size:clamp(42px,9vw,70px);margin:10px 0}
h2{font-size:27px;margin-top:0}
p{line-height:1.8}
.pill{
 display:inline-block;background:#fff0f5;color:#b9587d;
 border-radius:30px;padding:9px 14px;margin:4px
}
.message{
 background:#fff0f5;border:1px dashed #e6a8bf;
 padding:20px;border-radius:18px;line-height:1.9
}
.gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}
figure{margin:0;background:#fff0f5;padding:7px;border-radius:15px}
figure img{width:100%;height:280px;object-fit:cover;border-radius:10px}
figcaption{text-align:center;padding:10px 2px;color:#b9587d;font-size:13px}
.likes{display:grid;grid-template-columns:repeat(4,1fr);gap:10px}
.like{text-align:center;background:#fff0f5;padding:18px 5px;border-radius:15px}
.emoji{display:block;font-size:28px;margin-bottom:8px}
.dates{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.date{background:#fff0f5;padding:16px;border-radius:15px;line-height:1.7}
.date strong{display:block;color:#b9587d}
button{
 background:#b9587d;color:white;border:0;border-radius:30px;
 padding:13px 20px;font-size:16px;cursor:pointer
}
#secret{display:none;background:#fff0f5;padding:18px;border-radius:15px;margin-top:15px;line-height:1.8}
footer{text-align:center;padding:25px;color:#a36b82}
@media(max-width:600px){
 .gallery{grid-template-columns:1fr}
 figure img{height:auto;max-height:500px;object-fit:contain}
 .likes{grid-template-columns:repeat(2,1fr)}
 .dates{grid-template-columns:1fr}
 .card{padding:20px}
}
</style>
</head>
<body>
<main>
<header class="card hero">
 <div style="font-size:35px">🎀</div>
 <h1>For Mawi ♡</h1>
 <p>A tiny corner of the internet, made just for you.</p>
 <span class="pill">Marwa ♡</span>
 <span class="pill">Mawi 🎀</span>
 <span class="pill">Mommy 😋</span>
</header>

<section class="card">
 <h2>A little message for you 💌</h2>
 <div class="message">Idk haha , I know we're not dating yet but this is smth cute for you and you will be mine soon ahem 😋</div>
</section>

<section class="card">
 <h2>Little memories 📸</h2>
 <div class="gallery">
  <figure>
   <img src="mawi-photo-1.jpg" alt="Mawi photo 1">
   <figcaption>a little moment ♡</figcaption>
  </figure>
  <figure>
   <img src="mawi-photo-2.jpg" alt="Mawi photo 2">
   <figcaption>pretty memories 🌷</figcaption>
  </figure>
  <figure>
   <img src="mawi-photo-3.jpg" alt="Mawi photo 3">
   <figcaption>one for the memories ✨</figcaption>
  </figure>
 </div>
</section>

<section class="card">
 <h2>Things you like 🌷</h2>
 <div class="likes">
  <div class="like"><span class="emoji">👯‍♀️</span>Her friends</div>
  <div class="like"><span class="emoji">💗</span>Me</div>
  <div class="like"><span class="emoji">🐱</span>Cats</div>
  <div class="like"><span class="emoji">💄</span>Makeup</div>
 </div>
</section>

<section class="card">
 <h2>Our little timeline ✨</h2>
 <div class="dates">
  <div class="date"><strong>🎂 07 March 2010</strong>Marwa's birthday</div>
  <div class="date"><strong>💬 23 September 2026</strong>Our first interaction</div>
 </div>
</section>

<section class="card" style="text-align:center">
 <h2>A tiny surprise? 🐾</h2>
 <p>Every cute page needs a little secret.</p>
 <button onclick="document.getElementById('secret').style.display=document.getElementById('secret').style.display==='block'?'none':'block'">Open your surprise ♡</button>
 <div id="secret">🐱🎀 A tiny reminder that someone thought you deserved a cute little website today. Stay adorable, Mawi. 😋💕</div>
</section>

<footer>made with a little blush and a lot of ♡<br>for Mawi · Marwa 🎀</footer>
</main>
<script>
const symbols=["♡","♥","✧","🎀"];
setInterval(()=>{
 const heart=document.createElement("span");
 heart.textContent=symbols[Math.floor(Math.random()*symbols.length)];
 heart.style.cssText="position:fixed;bottom:-30px;left:"+Math.random()*100+"vw;color:#b9587d99;pointer-events:none;animation:floatUp 7s linear forwards";
 heart.style.fontSize=(16+Math.random()*15)+"px";
 document.body.appendChild(heart);
 setTimeout(()=>heart.remove(),7000);
},800);
const style=document.createElement("style");
style.textContent="@keyframes floatUp{to{transform:translateY(-110vh) rotate(25deg);opacity:0}}";
document.head.appendChild(style);
</script>
</body>
</html>
