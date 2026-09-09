# Ms-mobile-repairing-and-accessories-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>MS Mobile Repairing & Accessories</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
    scroll-behavior:smooth;
}

body{
    background:#f5f7fb;
    color:#222;
}

/* HEADER */
header{
    background:#111827;
    color:white;
    padding:15px 7%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
    z-index:1000;
}

.logo{
    font-size:24px;
    font-weight:bold;
}

.logo span{
    color:#22c55e;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    font-size:15px;
}

nav a:hover{
    color:#22c55e;
}

/* HERO */
.hero{
    min-height:90vh;
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:60px 7%;
    background:linear-gradient(135deg,#111827,#1f2937);
    color:white;
}

.hero-text{
    max-width:600px;
}

.hero h1{
    font-size:48px;
    margin-bottom:20px;
}

.hero h1 span{
    color:#22c55e;
}

.hero p{
    font-size:18px;
    line-height:1.7;
    color:#d1d5db;
    margin-bottom:30px;
}

.buttons a{
    display:inline-block;
    padding:13px 22px;
    border-radius:8px;
    text-decoration:none;
    font-weight:bold;
    margin-right:10px;
}

.call{
    background:#22c55e;
    color:white;
}

.whatsapp{
    background:#25D366;
    color:white;
}

.phone{
    font-size:130px;
}

/* SECTION */
section{
    padding:70px 7%;
}

.section-title{
    text-align:center;
    margin-bottom:40px;
}

.section-title h2{
    font-size:35px;
    margin-bottom:10px;
}

.section-title p{
    color:#666;
}

/* SERVICES */
.cards{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:25px;
}

.card{
    background:white;
    padding:30px 20px;
    text-align:center;
    border-radius:15px;
    box-shadow:0 5px 20px rgba(0,0,0,.08);
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.icon{
    font-size:45px;
    margin-bottom:15px;
}

.card h3{
    margin-bottom:10px;
}

.card p{
    color:#666;
    line-height:1.6;
}

/* ACCESSORIES */
.accessories{
    background:#eef2f7;
}

.product{
    background:white;
    border-radius:15px;
    padding:25px;
    text-align:center;
    box-shadow:0 5px 15px rgba(0,0,0,.07);
}

.product .product-icon{
    font-size:60px;
    margin-bottom:15px;
}

.product h3{
    margin-bottom:8px;
}

.product p{
    color:#666;
}

/* WHY US */
.why{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:20px;
}

.why-box{
    background:#111827;
    color:white;
    padding:25px;
    border-radius:12px;
    text-align:center;
}

.why-box h3{
    margin:10px 0;
    color:#22c55e;
}

.why-box p{
    color:#d1d5db;
    font-size:14px;
}

/* ABOUT */
.about{
    display:flex;
    align-items:center;
    gap:50px;
}

.about-text{
    flex:1;
}

.about-text h2{
    font-size:35px;
    margin-bottom:15px;
}

.about-text p{
    color:#666;
    line-height:1.8;
    margin-bottom:15px;
}

.about-box{
    flex:1;
    background:#111827;
    color:white;
    padding:45px;
    border-radius:20px;
    text-align:center;
}

.about-box .big-icon{
    font-size:90px;
}

/* CONTACT */
.contact{
    background:#111827;
    color:white;
}

.contact-container{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:30px;
}

.contact-info{
    line-height:2;
}

.contact-info h3{
    color:#22c55e;
    margin-bottom:15px;
}

.contact-buttons a{
    display:inline-block;
    margin-top:15px;
    padding:13px 20px;
    border-radius:8px;
    text-decoration:none;
    color:white;
    margin-right:8px;
}

.map{
    background:#1f2937;
    padding:40px;
    border-radius:15px;
    text-align:center;
}

.map a{
    display:inline-block;
    margin-top:15px;
    background:#22c55e;
    padding:12px 20px;
    border-radius:8px;
    color:white;
    text-decoration:none;
}

/* FOOTER */
footer{
    background:#080c14;
    color:#aaa;
    text-align:center;
    padding:25px;
}

footer strong{
    color:#22c55e;
}

/* MOBILE */
@media(max-width:800px){

    header{
        padding:15px 5%;
    }

    nav{
        display:none;
    }

    .hero{
        text-align:center;
        flex-direction:column;
        padding:70px 5%;
    }

    .hero h1{
        font-size:36px;
    }

    .phone{
        font-size:90px;
        margin-top:40px;
    }

    .cards{
        grid-template-columns:1fr;
    }

    .why{
        grid-template-columns:1fr 1fr;
    }

    .about{
        flex-direction:column;
    }

    .contact-container{
        grid-template-columns:1fr;
    }
}

@media(max-width:450px){

    .why{
        grid-template-columns:1fr;
    }

    .hero h1{
        font-size:31px;
    }

    .buttons a{
        margin-bottom:10px;
    }
}
</style>
</head>

<body>

<!-- HEADER -->

<header>

<div class="logo">
MS <span>Mobile</span>
</div>

<nav>
<a href="#home">Home</a>
<a href="#services">Services</a>
<a href="#accessories">Accessories</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>

</header>


<!-- HERO -->

<section class="hero" id="home">

<div class="hero-text">

<h1>
MS Mobile<br>
<span>Repairing & Accessories</span>
</h1>

<p>
Your trusted place for mobile repairing,
spare parts and quality mobile accessories.
Fast service, genuine parts and affordable prices.
</p>

<div class="buttons">

<a class="call" href="tel:+919561261968">
📞 Call Now
</a>

<a class="whatsapp"
href="https://wa.me/919561261968"
target="_blank">
💬 WhatsApp
</a>

</div>

</div>

<div class="phone">
📱
</div>

</section>


<!-- SERVICES -->

<section id="services">

<div class="section-title">

<h2>Our Repairing Services</h2>

<p>Professional mobile repairing services</p>

</div>

<div class="cards">

<div class="card">
<div class="icon">📱</div>
<h3>Display Repair</h3>
<p>Broken or damaged mobile display replacement.</p>
</div>

<div class="card">
<div class="icon">🔋</div>
<h3>Battery Replacement</h3>
<p>Battery replacement for different mobile models.</p>
</div>

<div class="card">
<div class="icon">🔌</div>
<h3>Charging Repair</h3>
<p>Charging port and charging-related problems.</p>
</div>

<div class="card">
<div class="icon">🔊</div>
<h3>Speaker Repair</h3>
<p>Speaker and microphone problem solutions.</p>
</div>

<div class="card">
<div class="icon">📷</div>
<h3>Camera Repair</h3>
<p>Camera glass and camera-related repairs.</p>
</div>

<div class="card">
<div class="icon">⚙️</div>
<h3>Software Repair</h3>
<p>Software problems, updates and troubleshooting.</p>
</div>

</div>

</section>


<!-- ACCESSORIES -->

<section class="accessories" id="accessories">

<div class="section-title">

<h2>Mobile Accessories</h2>

<p>Quality accessories at affordable prices</p>

</div>

<div class="cards">

<div class="product">
<div class="product-icon">🎧</div>
<h3>Earphones</h3>
<p>Wired & wireless earphones</p>
</div>

<div class="product">
<div class="product-icon">🔌</div>
<h3>Chargers</h3>
<p>Fast chargers & charging cables</p>
</div>

<div class="product">
<div class="product-icon">🛡️</div>
<h3>Tempered Glass</h3>
<p>Protection for your mobile display</p>
</div>

<div class="product">
<div class="product-icon">📱</div>
<h3>Mobile Covers</h3>
<p>Stylish covers for different models</p>
</div>

<div class="product">
<div class="product-icon">🔋</div>
<h3>Power Banks</h3>
<p>Portable charging solutions</p>
</div>

<div class="product">
<div class="product-icon">🎮</div>
<h3>Mobile Gadgets</h3>
<p>Useful gadgets and accessories</p>
</div>

</div>

</section>


<!-- WHY US -->

<section>

<div class="section-title">

<h2>Why Choose Us?</h2>

<p>Trusted service for your mobile</p>

</div>

<div class="why">

<div class="why-box">
<div>🔧</div>
<h3>Expert Repair</h3>
<p>Experienced repair service.</p>
</div>

<div class="why-box">
<div>💰</div>
<h3>Affordable Price</h3>
<p>Reasonable service charges.</p>
</div>

<div class="why-box">
<div>⚡</div>
<h3>Fast Service</h3>
<p>Quick and reliable service.</p>
</div>

<div class="why-box">
<div>⭐</div>
<h3>Quality</h3>
<p>Quality parts and accessories.</p>
</div>

</div>

</section>


<!-- ABOUT -->

<section id="about">

<div class="about">

<div class="about-text">

<h2>About MS Mobile</h2>

<p>
MS Mobile Repairing & Accessories is your local destination
for mobile repairing and mobile accessories.
</p>

<p>
We provide reliable mobile repair services along with
useful and stylish mobile accessories at reasonable prices.
</p>

</div>

<div class="about-box">

<div class="big-icon">📱</div>

<h2>MS MOBILE</h2>

<p>Repair • Accessories • Service</p>

</div>

</div>

</section>


<!-- CONTACT -->

<section class="contact" id="contact">

<div class="section-title">

<h2>Contact Us</h2>

<p style="color:#ccc;">
Visit our shop or contact us today
</p>

</div>

<div class="contact-container">

<div class="contact-info">

<h3>MS Mobile Repairing & Accessories</h3>

<p>📞 Phone: +91 95612 61968</p>

<p>💬 WhatsApp: +91 95612 61968</p>

<p>📍 Address: Your Shop Address Here</p>

<div class="contact-buttons">

<a class="call" href="tel:+919561261968">
📞 Call Now
</a>

<a class="whatsapp"
href="https://wa.me/919561261968"
target="_blank">
💬 WhatsApp
</a>

</div>

</div>


<div class="map">

<h2>📍 Find Our Shop</h2>

<p style="margin-top:10px;color:#ccc;">
Click below to open Google Maps
</p>

<a href="https://www.google.com/maps"
target="_blank">
Open Google Maps
</a>

</div>

</div>

</section>


<!-- FOOTER -->

<footer>

<p>
© 2026 <strong>MS Mobile Repairing & Accessories</strong>
</p>

<p style="margin-top:8px;">
All Rights Reserved.
</p>

</footer>

</body>
</html>
