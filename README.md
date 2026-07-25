<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sunan Store</title>

<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Cairo,sans-serif;
}

body{
background:#f7f8fc;
}

header{
background:#0B3D91;
padding:15px 60px;
display:flex;
justify-content:space-between;
align-items:center;
color:white;
}

.logo{
font-size:30px;
font-weight:bold;
}

nav a{
color:white;
text-decoration:none;
margin:15px;
}

.hero{

height:500px;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;

background:linear-gradient(120deg,#0B3D91,#1565C0);

color:white;

}

.hero h1{

font-size:55px;

}

.hero p{

margin-top:15px;
font-size:22px;

}

.btn{

margin-top:30px;

padding:15px 40px;

background:#FFC107;

border-radius:50px;

text-decoration:none;

color:black;

font-weight:bold;

}

.products{

padding:60px;

}

.title{

font-size:35px;

margin-bottom:30px;

}

.grid{

display:grid;

grid-template-columns:repeat(auto-fit,minmax(250px,1fr));

gap:25px;

}

.card{

background:white;

padding:20px;

border-radius:15px;

box-shadow:0 5px 20px rgba(0,0,0,.1);

text-align:center;

}

.card img{

width:200px;

}

.price{

font-size:22px;

color:#0B3D91;

font-weight:bold;

margin:15px;

}

.buy{

display:inline-block;

padding:12px 30px;

background:#0B3D91;

color:white;

text-decoration:none;

border-radius:30px;

}

footer{

background:#0B3D91;

color:white;

padding:30px;

text-align:center;

margin-top:50px;

}

</style>

</head>

<body>

<header>

<div class="logo">Sunan Store</div>

<nav>

<a href="#">الرئيسية</a>

<a href="#">الهواتف</a>

<a href="#">السماعات</a>

<a href="#">العروض</a>

<a href="#">تواصل معنا</a>

</nav>

</header>

<section class="hero">

<h1>مرحباً بك في Sunan Store</h1>

<p>كل ما تحتاجه من الهواتف والإلكترونيات الأصلية</p>

<a class="btn" href="#">تسوق الآن</a>

</section>

<section class="products">

<h2 class="title">أحدث المنتجات</h2>

<div class="grid">

<div class="card">

<img src="iphone.png">

<h3>iPhone 16 Pro Max</h3>

<div class="price">$999</div>

<a class="buy" href="#">شراء</a>

</div>

<div class="card">

<img src="liberty5.png">

<h3>Soundcore Liberty 5</h3>

<div class="price">$129</div>

<a class="buy" href="#">شراء</a>

</div>

<div class="card">

<img src="anker.png">

<h3>Anker Charger 30W</h3>

<div class="price">$25</div>

<a class="buy" href="#">شراء</a>

</div>

</div>

</section>

<footer>

© 2026 Sunan Store

</footer>

</body>
</html>
