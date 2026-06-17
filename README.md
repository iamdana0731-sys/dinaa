<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Dina Salad Court</title>

<link rel="icon" type="image/png" href="https://i.pinimg.com/736x/cd/40/a0/cd40a05cbeacbcd3476cd3c4e3b42823.jpg">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&family=Playfair+Display:wght@700&family=Lobster&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
}

html{
scroll-behavior:smooth;
}

body{
font-family:'Poppins',sans-serif;
background:#f7fff7;
color:#333;
}

/* HEADER */

header{
position:fixed;
top:0;
width:100%;
z-index:1000;
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
background:linear-gradient(135deg,#0d5c2b,#4caf50,#a5d6a7);
box-shadow:0 3px 15px rgba(0,0,0,0.15);
}

.logo{
font-family:'Lobster',cursive;
font-size:38px;
color:white;
}

nav a{
text-decoration:none;
color:white;
font-weight:600;
margin-left:25px;
transition:.3s;
}

nav a:hover{
color:#e8f5e9;
}

/* PAGE */

.page{
min-height:100vh;
padding:120px 8% 80px;
}

.section-title{
font-family:'Playfair Display',serif;
font-size:50px;
text-align:center;
margin-bottom:40px;
background:linear-gradient(135deg,#0d5c2b,#66bb6a);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

/* HOME */

.home{
display:flex;
align-items:center;
gap:50px;
flex-wrap:wrap;
}

.home-image{
flex:1;
}

.home-image img{
width:100%;
border-radius:25px;
box-shadow:0 10px 25px rgba(0,0,0,0.15);
border:5px solid #c8e6c9;
}

.home-content{
flex:1;
}

.home-content h1{
font-family:'Playfair Display',serif;
font-size:65px;
margin-bottom:20px;
background:linear-gradient(135deg,#0d5c2b,#4caf50);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

.home-content p{
text-align:justify;
line-height:2;
font-size:17px;
}

/* CARDS */

.card{
background:white;
padding:40px;
border-radius:25px;
box-shadow:0 5px 20px rgba(0,0,0,0.08);
}

/* CONTACT */

form{
max-width:800px;
margin:auto;
}

label{
display:block;
margin-bottom:8px;
margin-top:15px;
font-weight:600;
color:#2e7d32;
}

input, textarea{
width:100%;
padding:15px;
border:2px solid #c8e6c9;
border-radius:12px;
font-size:16px;
}

textarea{
height:180px;
resize:none;
}

button{
margin-top:20px;
padding:15px 35px;
border:none;
border-radius:12px;
font-size:16px;
font-weight:600;
color:white;
cursor:pointer;
background:linear-gradient(135deg,#0d5c2b,#4caf50);
}

button:hover{
opacity:.9;
}

/* FOOTER */

footer{
text-align:center;
padding:25px;
background:linear-gradient(135deg,#0d5c2b,#4caf50,#81c784);
color:white;
}

</style>

</head>

<body>

<header>

<div class="logo">Dina Salad Court</div>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>

</header>

<!-- HOME -->

<section id="home" class="page">

<div class="home">

<div class="home-image">
<img src="https://i.pinimg.com/1200x/8b/e6/92/8be69288e0dfeb2e4269ca076fed716f.jpg" alt="Dina Salad Court">
</div>

<div class="home-content">

<h1>Dina Salad Court</h1>

<p>
Dina Salad Court merupakan usaha kuliner sehat yang menghadirkan berbagai pilihan makanan berbahan dasar sayuran segar dan buah-buahan berkualitas. Menu yang tersedia meliputi salad sayur, salad buah, sandwich sehat, rice bowl, jus alami, smoothies, serta aneka hidangan sehat lainnya yang cocok untuk mendukung gaya hidup modern. Setiap bahan dipilih dengan cermat untuk menjaga kualitas, kesegaran, dan kandungan nutrisinya. Dengan mengutamakan cita rasa, kebersihan, dan kesehatan, Dina Salad Court berkomitmen menghadirkan pengalaman menikmati makanan sehat yang lezat, bergizi, dan menyenangkan bagi seluruh pelanggan.
</p>

</div>

</div>

</section>

<!-- ABOUT -->

<section id="about" class="page">

<h2 class="section-title">About Us</h2>

<div class="card">

<p style="text-align:justify; line-height:2;">
Dina Salad Court adalah website profil perusahaan yang bergerak di bidang makanan sehat dan olahan sayuran segar. Website ini dibuat untuk memperkenalkan berbagai produk yang tersedia, memberikan informasi mengenai kualitas bahan yang digunakan, serta menunjukkan komitmen perusahaan dalam mendukung pola hidup sehat masyarakat. Dengan desain modern bernuansa hijau, website ini mencerminkan kesegaran, kesehatan, dan kepedulian terhadap konsumsi pangan bergizi.
</p>

<br>

<p style="text-align:justify; line-height:2;">
Melalui website ini, pengunjung dapat mengenal lebih dekat layanan dan produk yang ditawarkan, menghubungi perusahaan melalui formulir kontak, serta memperoleh informasi mengenai visi Dina Salad Court dalam menyediakan makanan sehat yang lezat dan berkualitas tinggi.
</p>

</div>

</section>

<!-- CONTACT -->

<section id="contact" class="page">

<h2 class="section-title">Contact Us</h2>

<div class="card">

<form>

<label>Email</label> <input type="email" placeholder="Masukkan email Anda" required>

<label>Pesan</label>

<textarea placeholder="Tulis pesan Anda di sini..." required></textarea>

<button type="submit">Kirim Pesan</button>

</form>

</div>

</section>

<footer>
© 2026 Dina Salad Court | Fresh • Healthy • Green Lifestyle
</footer>

</body>
</html>
