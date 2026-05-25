<!DOCTYPE html>
<html lang="ar" dir="rtl">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>فرحتنا | فساتين الزفاف والجرتق السوداني</title>

<meta name="description" content="فرحتنا لفساتين الزفاف والجرتق السوداني - أحدث موديلات الزفاف السوداني الفاخر بتصاميم راقية وخدمة حجز سهلة عبر واتساب">

<meta name="keywords" content="فساتين زفاف, جرتق سوداني, عروس سودانية, فساتين عروس, زفاف سوداني">

<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700;800&display=swap" rel="stylesheet">

<link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
}

body{
font-family:'Cairo',sans-serif;
background:#fff7f8;
color:#333;
overflow-x:hidden;
}

/* HEADER */

header{
background:linear-gradient(135deg,#5b0014,#a00032,#d4004f);
padding:25px;
text-align:center;
color:white;
position:sticky;
top:0;
z-index:1000;
box-shadow:0 4px 15px rgba(0,0,0,0.2);
}

.logo{
font-size:48px;
font-weight:800;
margin-bottom:10px;
letter-spacing:1px;
}

.subtitle{
font-size:20px;
opacity:0.95;
}

/* NAVBAR */

nav{
margin-top:20px;
display:flex;
justify-content:center;
flex-wrap:wrap;
gap:15px;
}

nav a{
color:white;
text-decoration:none;
padding:10px 18px;
border-radius:30px;
transition:0.3s;
font-weight:bold;
}

nav a:hover{
background:white;
color:#8b002b;
}

/* HERO */

.hero{
height:92vh;
background:
linear-gradient(rgba(0,0,0,0.55),rgba(0,0,0,0.55)),
url('https://images.unsplash.com/photo-1525258946800-98cfd641d0de?q=80&w=1400')
center/cover no-repeat;

display:flex;
align-items:center;
justify-content:center;
text-align:center;
padding:20px;
}

.hero-content{
color:white;
max-width:900px;
animation:fadeUp 1.5s ease;
}

.hero-content h1{
font-size:70px;
margin-bottom:20px;
font-weight:800;
}

.hero-content p{
font-size:28px;
line-height:1.8;
margin-bottom:30px;
}

.hero-buttons{
display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;
}

.btn{
display:inline-block;
padding:15px 35px;
border-radius:40px;
text-decoration:none;
font-size:18px;
font-weight:bold;
transition:0.3s;
}

.btn-main{
background:#d4004f;
color:white;
}

.btn-main:hover{
background:white;
color:#8b002b;
transform:scale(1.05);
}

.btn-whatsapp{
background:#25D366;
color:white;
}

.btn-whatsapp:hover{
transform:scale(1.05);
}

/* STATS */

.stats{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:25px;
padding:70px 30px;
background:white;
}

.stat-box{
background:#fff;
padding:35px;
border-radius:20px;
text-align:center;
box-shadow:0 5px 15px rgba(0,0,0,0.08);
transition:0.3s;
}

.stat-box:hover{
transform:translateY(-8px);
}

.stat-box i{
font-size:45px;
color:#c40044;
margin-bottom:20px;
}

.stat-box h2{
font-size:40px;
color:#7a0019;
margin-bottom:10px;
}

/* SECTION */

.section{
padding:80px 30px;
}

.section-title{
text-align:center;
font-size:42px;
color:#7a0019;
margin-bottom:50px;
font-weight:800;
}

/* PRODUCTS */

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:35px;
}

.card{
background:white;
border-radius:25px;
overflow:hidden;
box-shadow:0 8px 25px rgba(0,0,0,0.08);
transition:0.4s;
position:relative;
}

.card:hover{
transform:translateY(-10px);
}

.card img{
width:100%;
height:400px;
object-fit:cover;
}

.badge{
position:absolute;
top:15px;
left:15px;
background:#d4004f;
color:white;
padding:8px 15px;
border-radius:30px;
font-size:14px;
font-weight:bold;
}

.card-content{
padding:25px;
text-align:center;
}

.card-content h3{
font-size:28px;
margin-bottom:15px;
color:#7a0019;
}

.price{
font-size:30px;
font-weight:bold;
color:#d4004f;
margin-bottom:20px;
}

.features{
list-style:none;
margin-bottom:25px;
line-height:2;
}

.features li{
font-size:17px;
}

/* GALLERY */

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:300px;
object-fit:cover;
border-radius:20px;
transition:0.4s;
}

.gallery img:hover{
transform:scale(1.05);
}

/* ABOUT */

.about{
background:white;
padding:50px;
border-radius:25px;
line-height:2.2;
font-size:22px;
text-align:center;
box-shadow:0 5px 20px rgba(0,0,0,0.08);
}

/* CLIENT LOGIN */

.login-box{
max-width:500px;
margin:auto;
background:white;
padding:40px;
border-radius:25px;
box-shadow:0 5px 20px rgba(0,0,0,0.08);
}

.login-box input{
width:100%;
padding:15px;
margin-bottom:20px;
border:1px solid #ddd;
border-radius:12px;
font-size:18px;
}

/* TESTIMONIALS */

.testimonials{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:30px;
}

.testimonial{
background:white;
padding:35px;
border-radius:25px;
box-shadow:0 5px 20px rgba(0,0,0,0.08);
line-height:2;
}

.testimonial h4{
color:#7a0019;
margin-top:15px;
}

/* FOOTER */

footer{
background:#5b0014;
color:white;
padding:60px 30px 30px;
margin-top:50px;
}

.footer-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:40px;
margin-bottom:30px;
}

.footer-box h3{
margin-bottom:20px;
font-size:24px;
}

.footer-box p,
.footer-box a{
line-height:2;
color:white;
text-decoration:none;
}

.socials{
display:flex;
gap:15px;
margin-top:20px;
}

.socials a{
width:45px;
height:45px;
background:white;
color:#7a0019;
display:flex;
align-items:center;
justify-content:center;
border-radius:50%;
font-size:20px;
transition:0.3s;
}

.socials a:hover{
transform:scale(1.1);
}

.copy{
text-align:center;
border-top:1px solid rgba(255,255,255,0.2);
padding-top:20px;
font-size:16px;
}

/* WHATSAPP FLOAT */

.whatsapp-float{
position:fixed;
bottom:25px;
left:25px;
width:65px;
height:65px;
background:#25D366;
color:white;
border-radius:50%;
display:flex;
justify-content:center;
align-items:center;
font-size:35px;
text-decoration:none;
z-index:999;
box-shadow:0 5px 15px rgba(0,0,0,0.3);
}

/* ANIMATION */

@keyframes fadeUp{
from{
opacity:0;
transform:translateY(50px);
}
to{
opacity:1;
transform:translateY(0);
}
}

/* MOBILE */

@media(max-width:768px){

.hero-content h1{
font-size:42px;
}

.hero-content p{
font-size:20px;
}

.section-title{
font-size:32px;
}

.logo{
font-size:35px;
}

}

</style>

</head>

<body>

<header>

<div class="logo">فرحتنا</div>

<div class="subtitle">
لفساتين الزفاف والجرتق السوداني
</div>

<nav>

<a href="#">الرئيسية</a>

<a href="#products">الفساتين</a>

<a href="#gallery">المعرض</a>

<a href="#about">من نحن</a>

<a href="#login">دخول العملاء</a>

<a href="#contact">تواصل معنا</a>

</nav>

</header>

<!-- HERO -->

<section class="hero">

<div class="hero-content">

<h1>أناقة العروس تبدأ من هنا</h1>

<p>
اكتشفي أحدث موديلات فساتين الزفاف والجرتق السوداني
بتصاميم ملكية وخامات فاخرة تمنحك إطلالة لا تُنسى
</p>

<div class="hero-buttons">

<a href="#products" class="btn btn-main">
تصفح الفساتين
</a>

<a href="https://wa.me/966500000000"
target="_blank"
class="btn btn-whatsapp">

<i class="fab fa-whatsapp"></i>
تواصل واتساب

</a>

</div>

</div>

</section>

<!-- STATS -->

<section class="stats">

<div class="stat-box">
<i class="fa-solid fa-gem"></i>
<h2>500+</h2>
<p>فستان فاخر</p>
</div>

<div class="stat-box">
<i class="fa-solid fa-heart"></i>
<h2>1200+</h2>
<p>عروس سعيدة</p>
</div>

<div class="stat-box">
<i class="fa-solid fa-star"></i>
<h2>5★</h2>
<p>تقييم العملاء</p>
</div>

<div class="stat-box">
<i class="fa-solid fa-truck"></i>
<h2>24H</h2>
<p>خدمة سريعة</p>
</div>

</section>

<!-- PRODUCTS -->

<section class="section" id="products">

<h2 class="section-title">
أحدث الفساتين
</h2>

<div class="products">

<div class="card">

<div class="badge">الأكثر طلباً</div>

<img src="https://images.unsplash.com/photo-1511285560929-80b456fea0bc?q=80&w=1200">

<div class="card-content">

<h3>فستان زفاف ملكي</h3>

<div class="price">3500 ريال</div>

<ul class="features">
<li>✔ تصميم فاخر</li>
<li>✔ خامة أوروبية</li>
<li>✔ تطريز يدوي</li>
</ul>

<a class="btn btn-whatsapp"
href="https://wa.me/966500000000"
target="_blank">

اطلب الآن

</a>

</div>

</div>

<div class="card">

<div class="badge">جديد</div>

<img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1?q=80&w=1200">

<div class="card-content">

<h3>جرتق سوداني فاخر</h3>

<div class="price">2800 ريال</div>

<ul class="features">
<li>✔ تصميم سوداني أصيل</li>
<li>✔ خامات فاخرة</li>
<li>✔ إكسسوارات متكاملة</li>
</ul>

<a class="btn btn-whatsapp"
href="https://wa.me/966500000000"
target="_blank">

اطلب الآن

</a>

</div>

</div>

<div class="card">

<div class="badge">حصري</div>

<img src="https://images.unsplash.com/photo-1594552072238-b8a33785b261?q=80&w=1200">

<div class="card-content">

<h3>فستان عروس ناعم</h3>

<div class="price">3200 ريال</div>

<ul class="features">
<li>✔ تصميم عصري</li>
<li>✔ راحة وأناقة</li>
<li>✔ متوفر بجميع المقاسات</li>
</ul>

<a class="btn btn-whatsapp"
href="https://wa.me/966500000000"
target="_blank">

اطلب الآن

</a>

</div>

</div>

</div>

</section>

<!-- GALLERY -->

<section class="section" id="gallery">

<h2 class="section-title">
معرض الصور
</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1525258946800-98cfd641d0de?q=80&w=1200">

<img src="https://images.unsplash.com/photo-1511285560929-80b456fea0bc?q=80&w=1200">

<img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1?q=80&w=1200">

<img src="https://images.unsplash.com/photo-1594552072238-b8a33785b261?q=80&w=1200">

</div>

</section>

<!-- ABOUT -->

<section class="section" id="about">

<div class="about">

<h2 class="section-title">
من نحن
</h2>

<p>

نحن في فرحتنا نسعى لتقديم أفخم فساتين الزفاف والجرتق السوداني
بتصاميم عالمية وخامات فاخرة تناسب كل عروس تبحث عن الأناقة والرقي.
نقدم تجربة تسوق مميزة وخدمة عملاء احترافية مع إمكانية الحجز والتواصل المباشر.

</p>

</div>

</section>

<!-- LOGIN -->

<section class="section" id="login">

<h2 class="section-title">
دخول العملاء
</h2>

<div class="login-box">

<input type="email" placeholder="البريد الإلكتروني">

<input type="password" placeholder="كلمة المرور">

<a href="#" class="btn btn-main" style="width:100%;text-align:center;">
تسجيل الدخول
</a>

</div>

</section>

<!-- TESTIMONIALS -->

<section class="section">

<h2 class="section-title">
آراء العملاء
</h2>

<div class="testimonials">

<div class="testimonial">

<p>
"الخدمة ممتازة والفساتين أفخم من الصور،
أنصح كل عروس بالتعامل مع فرحتنا."
</p>

<h4>— سارة محمد</h4>

</div>

<div class="testimonial">

<p>
"الجرتق السوداني كان راقي جدًا والتعامل احترافي وسريع."
</p>

<h4>— إيمان خالد</h4>

</div>

<div class="testimonial">

<p>
"أفضل متجر تعاملت معه من ناحية الجودة والذوق العالي."
</p>

<h4>— آلاء عثمان</h4>

</div>

</div>

</section>

<!-- CONTACT -->

<section class="section" id="contact">

<h2 class="section-title">
تواصل معنا
</h2>

<div style="text-align:center;">

<a class="btn btn-whatsapp"
href="https://wa.me/966500000000"
target="_blank">

<i class="fab fa-whatsapp"></i>
تواصل عبر واتساب

</a>

</div>

</section>

<!-- FOOTER -->

<footer>

<div class="footer-grid">

<div class="footer-box">

<h3>فرحتنا</h3>

<p>
فساتين الزفاف والجرتق السوداني بأحدث التصاميم العالمية.
</p>

</div>

<div class="footer-box">

<h3>روابط مهمة</h3>

<p><a href="#">الرئيسية</a></p>

<p><a href="#products">الفساتين</a></p>

<p><a href="#gallery">المعرض</a></p>

<p><a href="#contact">تواصل معنا</a></p>

</div>

<div class="footer-box">

<h3>تابعنا</h3>

<div class="socials">

<a href="#"><i class="fab fa-instagram"></i></a>

<a href="#"><i class="fab fa-tiktok"></i></a>

<a href="#"><i class="fab fa-snapchat"></i></a>

<a href="#"><i class="fab fa-facebook-f"></i></a>

</div>

</div>

</div>

<div class="copy">

جميع الحقوق محفوظة © فرحتنا 2026

</div>

</footer>

<!-- FLOATING WHATSAPP -->

<a href="https://wa.me/966500000000"
target="_blank"
class="whatsapp-float">

<i class="fab fa-whatsapp"></i>

</a>

</body>
</html>

© 2026 فرحتنا لفساتين الزفاف والجرتق السوداني
 
