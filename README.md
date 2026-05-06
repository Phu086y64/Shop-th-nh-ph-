<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>THANHPHU SHOP</title>

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Arial}

/* ❌ XOÁ ẢNH → ✅ NỀN MỚI */
body{
    background:#000;
    background-image:radial-gradient(circle at 20% 20%,rgba(0,255,255,0.15),transparent),
                     radial-gradient(circle at 80% 80%,rgba(255,0,255,0.15),transparent);
    min-height:100vh;
    color:#fff;
    text-align:center;
}

.title{
    font-size:32px;
    margin:20px;
    animation:rainbow 6s linear infinite;
}

.container{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:20px;
}

.box{
    width:260px;
    padding:20px;
    border-radius:15px;
    background:rgba(0,0,0,0.6);
    border:1px solid rgba(255,255,255,0.2);
    transition:0.3s;
    box-shadow:0 0 15px #0ff;
}

.box:hover{
    transform:scale(1.05);
    box-shadow:0 0 30px #0ff;
}

.price{
    margin:6px 0;
    font-weight:bold;
    background:linear-gradient(90deg,#fff,#0ff,#fff);
    background-size:200%;
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
    animation:shine 2s linear infinite;
}

.links a{
    display:inline-block;
    margin:10px;
    padding:12px 18px;
    border-radius:10px;
    background:rgba(0,0,0,0.7);
    color:#fff;
    text-decoration:none;
    transition:0.3s;
}

.links a:hover{
    background:#0ff;
    color:#000;
    box-shadow:0 0 20px #0ff;
}

.footer{
    margin-top:30px;
    font-size:16px;
}

.admin{
    font-weight:bold;
    background:linear-gradient(90deg, red, yellow, cyan, lime, red);
    background-size:300%;
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
    animation:adminRun 4s linear infinite;
}

.thanks{
    color:#ff66cc;
    animation:blink 1.5s infinite;
}

@keyframes rainbow{
    0%{color:red}
    25%{color:yellow}
    50%{color:cyan}
    75%{color:lime}
    100%{color:red}
}

@keyframes shine{
    0%{background-position:0%}
    100%{background-position:200%}
}

@keyframes adminRun{
    0%{background-position:0%}
    100%{background-position:300%}
}

@keyframes blink{
    0%,100%{opacity:1}
    50%{opacity:0.5}
}
</style>
</head>

<body>

<h1 class="title">💎 THANHPHU SHOP 💎</h1>

<div class="container">

<div class="box">
<h2>🔥 DRIP NOOROT </h2>
<div class="price">1 DAY: 40K</div>
<div class="price">7 DAY: 90K</div>
<div class="price">15 DAY: 120K</div>
<div class="price">30 DAY: 170K</div>
</div>

<div class="box">
<h2>⚡ PATO XANH</h2>
<div class="price">1 DAY: 30K</div>
<div class="price">7 DAY: 70K</div>
<div class="price">15 DAY: 100K</div>
<div class="price">30 DAY: 150K</div>
</div>

<div class="box">
<h2>🔥 PATO VIP</h2>
<div class="price">1 DAY: 40K</div>
<div class="price">7 DAY: 90K</div>
<div class="price">15 DAY: 120K</div>
<div class="price">30 DAY: 160K</div>
</div>

<div class="box">
<h2>⚡ Fluorite tây</h2>
<div class="price">1 DAY: 90K</div>
<div class="price">7 DAY: 220K</div>
<div class="price">30 DAY: 380K</div>
</div>

</div>

<div class="links">
<a href="https://t.me/thanhphu9994744" target="_blank">📲 Telegram</a>
<a href="https://zalo.me/0337894501" target="_blank">💬 Zalo</a>
<a href="https://www.facebook.com/share/14bGtqGgYHk/" target="_blank">📘 Facebook</a>
</div>

<div class="footer">
👑 <span class="admin">ADMIN: THANHPHU</span><br>
💖 <span class="thanks">Cảm ơn bạn đã ủng hộ!</span>
</div>

</body>
</html>
