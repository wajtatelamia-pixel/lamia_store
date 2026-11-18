# lamia_store

<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LAMIA STORE</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:Arial,sans-serif;background:#faf7f4;color:#333}
header{background:#34251f;color:white;text-align:center;padding:25px}
header h1{letter-spacing:3px;font-size:30px}
header p{margin-top:8px;color:#e8c9a9}
nav{background:#fff;padding:15px;text-align:center}
nav a{color:#34251f;text-decoration:none;margin:12px;font-weight:bold}
.hero{text-align:center;padding:65px 15px;background:#eadbd0}
.hero h2{font-size:28px;margin-bottom:15px}
.hero p{margin-bottom:20px}
.btn{background:#34251f;color:white;padding:12px 25px;text-decoration:none;border-radius:5px}
.products{padding:35px 15px;text-align:center}
.products h2{margin-bottom:25px}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:15px;max-width:700px;margin:auto}
.product{background:white;padding:15px;border-radius:10px;box-shadow:0 2px 8px #ddd}
.product img{width:100%;height:130px;object-fit:cover;border-radius:7px}
.product h3{margin:12px 0}
.price{color:#9b6848;font-weight:bold;margin:10px}
.buy{display:inline-block;background:#34251f;color:white;padding:9px 15px;text-decoration:none;border-radius:5px}
footer{text-align:center;background:#34251f;color:white;padding:25px;margin-top:35px}
@media(min-width:600px){.grid{grid-template-columns:repeat(3,1fr)}}
</style>
</head>
<body>

<header>
<h1>LAMIA STORE</h1>
<p>Elegance • Beauty • Style</p>
</header>

<nav>
<a href="#home">الرئيسية</a>
<a href="#products">المنتجات</a>
<a href="#contact">اتصل بنا</a>
</nav>

<section class="hero" id="home">
<h2>مرحبا بكم في LAMIA STORE</h2>
<p>اكتشفي الأناقة والجمال مع تشكيلتنا المميزة</p>
<a href="#products" class="btn">تسوقي الآن</a>
</section>

<section class="products" id="products">
<h2>منتجاتنا</h2>
<div class="grid">

<div class="product">
<img src="hair-set.jpg" alt="Oil Repair Intensiv">
<h3>مجموعة العناية بالشعر Balea</h3>
<p class="price">149 DH</p>
<a class="buy" href="https://wa.me/212710476914text=بغيت نطلب مجموعة العناية بالشعر Balea" target="_blank">اطلبي الآن</a>

<h3>منتج الأول</h3>
<p class="price">99 DH</p>
<a class="buy" href="#contact">اطلبي الآن</a>
</div>

<div class="product">
<img src="https://placehold.co/300x200/e8d8ca/34251f?text=Product+2">
<h3>منتج الثاني</h3>
<p class="price">149 DH</p>
<a class="buy" href="#contact">اطلبي الآن</a>
</div>

<div class="product">
<img src="https://placehold.co/300x200/e8d8ca/34251f?text=Product+3">
<h3>منتج الثالث</h3>
<p class="price">199 DH</p>
<a class="buy" href="#contact">اطلبي الآن</a>
</div>

</div>
</section>

<footer id="contact">
<h3>LAMIA STORE</h3>
<p><a href="https://wa.me/0710476914" target="_blank" style="color: #d2b48c; text-decoration: underline;">تواصل معنا عبر واتساب للطلب</a></p>

<p>© 2026 LAMIA STORE</p>
</footer>

</body>
</html>

