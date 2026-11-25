
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Hadiah Kecil Untukmu 💗</title>
<style>
*{box-sizing:border-box}
body{
 margin:0;min-height:100vh;display:flex;align-items:center;
 justify-content:center;overflow:hidden;
 font-family:Arial,sans-serif;
 background:linear-gradient(135deg,#ffe6f0,#f8d9ff,#fff1dc);
 color:#a34d79;text-align:center
}
canvas{position:fixed;inset:0;width:100%;height:100%;pointer-events:none}
.card{
 position:relative;z-index:2;width:90%;max-width:400px;
 padding:30px 20px;border-radius:28px;
 background:#ffffffdf;box-shadow:0 10px 40px #c77ba344
}
h1{color:#d64d91;font-size:27px}
p{line-height:1.6}
.gift{border:0;background:none;cursor:pointer;position:relative;
 width:180px;height:175px;animation:bob 1.5s infinite}
.box{position:absolute;bottom:15px;left:25px;width:130px;height:100px;
 background:#f47eae;border-radius:8px}
.box:after{content:"";position:absolute;left:52px;width:26px;height:100%;background:#ffe5a7}
.lid{position:absolute;bottom:110px;left:15px;width:150px;height:30px;
 background:#e85c99;border-radius:7px;transition:.7s}
.lid:after{content:"";position:absolute;left:62px;width:26px;height:100%;background:#ffe5a7}
.gift.open .lid{transform:translateY(-45px) rotate(-25deg)}
.gift.open{animation:none}
#message{display:none;animation:fade 1s}
#message.show{display:block}
#message h2{color:#dc5595;font-size:28px}
@keyframes bob{50%{transform:translateY(-10px)}}
@keyframes fade{from{opacity:0;transform:translateY(15px)}to{opacity:1;transform:none}}
button.replay{border:0;background:#e96b9f;color:white;padding:12px 20px;
 border-radius:30px;margin-top:12px;cursor:pointer}
</style>
</head>
<body>
<canvas id="fireworks"></canvas>
<div class="card">
 <div id="intro">
  <h1>Haiii, ada hadiah kecil! 💗</h1>
  <p>Terima kasih sudah meluangkan waktu untuk mengisi kuesionerku.</p>
  <p>Tekan kadonya untuk membuka kejutan! 🎁</p>
 </div>
 <button class="gift" id="gift" aria-label="Buka kado">
  <div class="box"></div><div class="lid"></div>
 </button>
 <div id="message">
  <h2>Kamu cantik! 💗</h2>
  <p>Makasiih yaaa udah ngisi!</p>
  <p>Semoga harimu menyenangkan dan selalu dipenuhi kebahagiaan! 🌷</p>
  <p>You're amazing! ✨</p>
  <button class="replay" onclick="celebrate()">Lihat kembang api lagi 🎆</button>
 </div>
</div>
<script>
const canvas=document.getElementById('fireworks');
const ctx=canvas.getContext('2d');
let w,h,particles=[];
function resize(){w=canvas.width=innerWidth;h=canvas.height=innerHeight}
resize();window.addEventListener('resize',resize);
function burst(x,y){
 const colors=['#ff69b4','#ffd166','#b68cff','#ffffff','#ff987e','#77d9ce'];
 for(let i=0;i<90;i++){
  let a=Math.random()*Math.PI*2,s=1+Math.random()*5;
  particles.push({x,y,vx:Math.cos(a)*s,vy:Math.sin(a)*s,
  life:90,color:colors[Math.floor(Math.random()*colors.length)]});
 }
}
function animate(){
 ctx.clearRect(0,0,w,h);
 particles=particles.filter(p=>p.life>0);
 particles.forEach(p=>{
  p.x+=p.vx;p.y+=p.vy;p.vy+=.035;p.life--;
  ctx.globalAlpha=p.life/90;ctx.fillStyle=p.color;
  ctx.beginPath();ctx.arc(p.x,p.y,2.5,0,Math.PI*2);ctx.fill();
 });
 ctx.globalAlpha=1;
 if(particles.length)requestAnimationFrame(animate);
}
function celebrate(){
 for(let i=0;i<7;i++){
  setTimeout(()=>{
   burst(Math.random()*w,Math.random()*h*.65);
   animate();
  },i*350);
 }
}
document.getElementById('gift').addEventListener('click',()=>{
 document.getElementById('gift').classList.add('open');
 document.getElementById('intro').style.display='none';
 document.getElementById('message').classList.add('show');
 celebrate();
});
</script>
</body>
</html>
