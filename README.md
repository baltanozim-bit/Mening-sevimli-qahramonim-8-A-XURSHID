# Mening-sevimli-qahramonim-8-A-XURSHID
<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<title>SHOKH AKE | FX TRADER PRO</title>

<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600;800&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Montserrat',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:radial-gradient(circle at top,#0b1220,#02040a);
    color:#fff;
}

/* ===== HERO ===== */
header{
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:90px 10%;
    gap:60px;
}

.tag{
    display:inline-block;
    background:linear-gradient(90deg,#00ffcc,#00e5ff);
    color:#000;
    padding:10px 26px;
    border-radius:40px;
    font-weight:800;
    letter-spacing:1px;
    margin-bottom:25px;
    box-shadow:0 0 25px rgba(0,255,204,.8);
}

.hero-text h1{
    font-size:76px;
    font-weight:800;
    background:linear-gradient(90deg,gold,#00ffcc);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
    animation:glow 2.5s infinite alternate;
}

@keyframes glow{
    from{filter:drop-shadow(0 0 10px gold);}
    to{filter:drop-shadow(0 0 25px #00ffcc);}
}

.hero-text h2{
    font-size:28px;
    color:#00ffcc;
    margin:20px 0;
}

.hero-text p{
    max-width:650px;
    line-height:1.9;
    opacity:.92;
}

.hero-img img{
    width:420px;
    border-radius:40px;
    box-shadow:
        0 0 40px rgba(0,255,204,.6),
        0 0 80px rgba(255,215,0,.6);
}

/* ===== SECTIONS ===== */
section{
    padding:120px 10%;
}

.section-title{
    text-align:center;
    font-size:48px;
    margin-bottom:90px;
    background:linear-gradient(90deg,gold,#00ffcc);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

/* ===== STATS ===== */
.stats{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:45px;
}

.stat{
    background:rgba(255,255,255,.07);
    padding:50px;
    border-radius:35px;
    text-align:center;
    transition:.4s;
}

.stat:hover{
    transform:translateY(-15px) scale(1.03);
    background:rgba(255,255,255,.14);
}

.stat h3{
    font-size:42px;
    color:#00ffcc;
}

.stat p{
    margin-top:12px;
    opacity:.85;
}

/* ===== DASHBOARD ===== */
.dashboard{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:45px;
}

.panel{
    background:rgba(255,255,255,.06);
    padding:45px;
    border-radius:35px;
    border:1px solid rgba(0,255,204,.25);
}

.panel h3{
    color:gold;
    margin-bottom:15px;
}

/* ===== LIVE CHART ===== */
.chart-box{
    border-radius:35px;
    overflow:hidden;
    box-shadow:0 0 60px rgba(0,255,204,.5);
}

/* ===== TIMELINE ===== */
.timeline{
    max-width:900px;
    margin:auto;
}

.step{
    border-left:4px solid #00ffcc;
    padding-left:30px;
    margin-bottom:45px;
}

.step span{
    color:gold;
    font-weight:800;
}

/* ===== GALLERY ===== */
.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:35px;
}

.gallery img{
    width:100%;
    border-radius:30px;
    transition:.4s;
}

.gallery img:hover{
    transform:scale(1.1);
}

/* ===== FOOTER ===== */
footer{
    text-align:center;
    padding:45px;
    background:#01030a;
    opacity:.9;
}

/* ===== RESPONSIVE ===== */
@media(max-width:900px){
    header{
        flex-direction:column;
        text-align:center;
    }
    .hero-img img{
        width:320px;
    }
}
</style>
</head>
<body>

<header>
<div class="hero-text">
    <div class="tag">ELITE FX TRADER</div>
    <h1>SHOKH AKE</h1>
    <h2>Forex • Crypto • Risk Manager</h2>
    <p>
        SHOKH AKE — professional FX treyder va AKE FX asoschisi.
        Bozor psixologiyasi, texnik va fundamental tahlil asosida
        barqaror va nazoratli treyding olib boradi.
    </p>
</div>

<div class="hero-img">
    <img src="Без названия.jpg">
</div>
</header>

<section>
<h2 class="section-title">Trading Statistikasi</h2>
<div class="stats">
    <div class="stat"><h3>6+ yil</h3><p>Tajriba</p></div>
    <div class="stat"><h3>78%</h3><p>Win Rate</p></div>
    <div class="stat"><h3>1:3</h3><p>Risk / Reward</p></div>
    <div class="stat"><h3>100+</h3><p>Mijozlar</p></div>
</div>
</section>

<section>
<h2 class="section-title">FX Dashboard</h2>
<div class="dashboard">
    <div class="panel">
        <h3>Asosiy bozorlar</h3>
        <p>EUR/USD, GBP/USD, XAU/USD, BTC, NASDAQ</p>
    </div>
    <div class="panel">
        <h3>Strategiya</h3>
        <p>Price Action + Liquidity + News Filter</p>
    </div>
    <div class="panel">
        <h3>Risk qoidasi</h3>
        <p>1 treyd = max 1–2% kapital</p>
    </div>
</div>
</section>

<section>
<h2 class="section-title">Live Market Chart</h2>
<div class="chart-box">
<iframe src="https://s.tradingview.com/widgetembed/?symbol=FX:EURUSD&interval=60&theme=dark&style=1"
width="100%" height="500" frameborder="0"></iframe>
</div>
</section>

<section>
<h2 class="section-title">Faoliyat yo‘li</h2>
<div class="timeline">
    <div class="step"><span>2018</span> — Forex bilan tanishuv</div>
    <div class="step"><span>2020</span> — Real hisoblar</div>
    <div class="step"><span>2021</span> — AKE FX tashkil etildi</div>
    <div class="step"><span>2024</span> — Pro treyder</div>
    <div class="step"><span>2026</span> — Elite FX brend</div>
</div>
</section>

<section>
<h2 class="section-title">Galeriyasi</h2>
<div class="gallery">
    <img src="Без названия (1).jpg">
    <img src="Без названия (2).jpg">
    <img src="Без названия (3).jpg">
    <img src="Без названия (4).jpg">
</div>
</section>

<footer>
<p>© 2026 AKE FX | SHOKH AKE — ELITE FX TRADER</p>
</footer>

</body>
</html>
