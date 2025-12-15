<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Birthday Surprise 💖</title>

<style>
body{
 margin:0;
 height:100vh;
 display:flex;
 justify-content:center;
 align-items:center;
 background:linear-gradient(135deg,#ff9a9e,#fad0c4,#fbc2eb);
 font-family:'Comic Sans MS',cursive;
 text-align:center;
 overflow:hidden;
}
.box{
 background:white;
 padding:25px;
 border-radius:25px;
 box-shadow:0 15px 30px rgba(0,0,0,0.2);
 max-width:360px;
}
h1{color:#ff4081;}
p{color:#444;font-size:16px;}
button{
 padding:12px 25px;
 border:none;
 border-radius:25px;
 background:#ff4081;
 color:white;
 font-size:16px;
 margin-top:15px;
 cursor:pointer;
}
.balloon{
 position:absolute;
 bottom:-100px;
 font-size:30px;
 animation:float 6s linear infinite;
}
@keyframes float{
 0%{transform:translateY(0);}
 100%{transform:translateY(-120vh);}
}
.cake{font-size:80px;}
.knife{font-size:45px;cursor:pointer;}
</style>
</head>

<body>

<div class="box" id="content">
 <h1>🎁 Ready for Surprise?</h1>
 <p>Ek chhota sa gift 💖</p>
 <button onclick="start()">Start 🎶</button>
</div>

<audio id="music" loop>
 <source src="song.mp3" type="audio/mp3">
</audio>

<script>
function start(){
 document.getElementById("music").play();
 document.getElementById("content").innerHTML = `
 <h1>🎈 Balloons Time 🎈</h1>
 <p>Smile please 😊</p>
 <button onclick="balloons()">Next 🎂</button>`;
}

function balloons(){
 for(let i=0;i<20;i++){
  let b=document.createElement("div");
  b.className="balloon";
  b.innerHTML="🎈";
  b.style.left=Math.random()*100+"vw";
  document.body.appendChild(b);
  setTimeout(()=>b.remove(),6000);
 }
 document.getElementById("content").innerHTML = `
 <h1>🎂 Cake Time 🎂</h1>
 <div class="cake">🍰 <span class="knife" onclick="cutCake()">🔪</span></div>
 <p>Knife par click karo</p>`;
}

function cutCake(){
 document.getElementById("content").innerHTML = `
 <h1>🎉 Happy Birthday 🎉</h1>
 <p>
 💖 Chunnuuu 😸🎀<br>
 💖 Cuttie Billiii 💖<br>
 💖 Myyy Babuu 🧸<br>
 💖 My Payriii Bachiiiii 🌸<br><br>
 <strong>I love you chunnnuuuuu forever ❤️♾️</strong>
 </p>`;
}
</script>

</body>
</html><!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Birthday Surprise 💖</title>

<style>
body{
 margin:0;
 height:100vh;
 display:flex;
 justify-content:center;
 align-items:center;
 background:linear-gradient(135deg,#ff9a9e,#fad0c4,#fbc2eb);
 font-family:'Comic Sans MS',cursive;
 text-align:center;
 overflow:hidden;
}
.box{
 background:white;
 padding:25px;
 border-radius:25px;
 box-shadow:0 15px 30px rgba(0,0,0,0.2);
 max-width:360px;
}
h1{color:#ff4081;}
p{color:#444;font-size:16px;}
button{
 padding:12px 25px;
 border:none;
 border-radius:25px;
 background:#ff4081;
 color:white;
 font-size:16px;
 margin-top:15px;
 cursor:pointer;
}
.balloon{
 position:absolute;
 bottom:-100px;
 font-size:30px;
 animation:float 6s linear infinite;
}
@keyframes float{
 0%{transform:translateY(0);}
 100%{transform:translateY(-120vh);}
}
.cake{font-size:80px;}
.knife{font-size:45px;cursor:pointer;}
</style>
</head>

<body>

<div class="box" id="content">
 <h1>🎁 Ready for Surprise?</h1>
 <p>Ek chhota sa gift 💖</p>
 <button onclick="start()">Start 🎶</button>
</div>

<audio id="music" loop>
 <source src="song.mp3" type="audio/mp3">
</audio>

<script>
function start(){
 document.getElementById("music").play();
 document.getElementById("content").innerHTML = `
 <h1>🎈 Balloons Time 🎈</h1>
 <p>Smile please 😊</p>
 <button onclick="balloons()">Next 🎂</button>`;
}

function balloons(){
 for(let i=0;i<20;i++){
  let b=document.createElement("div");
  b.className="balloon";
  b.innerHTML="🎈";
  b.style.left=Math.random()*100+"vw";
  document.body.appendChild(b);
  setTimeout(()=>b.remove(),6000);
 }
 document.getElementById("content").innerHTML = `
 <h1>🎂 Cake Time 🎂</h1>
 <div class="cake">🍰 <span class="knife" onclick="cutCake()">🔪</span></div>
 <p>Knife par click karo</p>`;
}

function cutCake(){
 document.getElementById("content").innerHTML = `
 <h1>🎉 Happy Birthday 🎉</h1>
 <p>
 💖 Chunnuuu 😸🎀<br>
 💖 Cuttie Billiii 💖<br>
 💖 Myyy Babuu 🧸<br>
 💖 My Payriii Bachiiiii 🌸<br><br>
 <strong>I love you chunnnuuuuu forever ❤️♾️</strong>
 </p>`;
}
</script>

</body>
</html>
