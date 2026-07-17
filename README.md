<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>AJ Effectx | AJ Effectx</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="d:\fonts\fonts\NagoyaDEMO-Regular.otf" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{

background:#080808;
color:white;
overflow-x:hidden;

}

body::before{

content:"";
position:fixed;
width:600px;
height:600px;
background:#ff003c25;
border-radius:50%;
filter:blur(150px);
top:-250px;
left:-150px;
z-index:-1;

}

body::after{

content:"";
position:fixed;
width:500px;
height:500px;
background:#0066ff22;
border-radius:50%;
filter:blur(160px);
bottom:-200px;
right:-150px;
z-index:-1;

}

nav{

position:fixed;
top:0;
width:100%;
padding:22px 8%;
display:flex;
justify-content:space-between;
align-items:center;
backdrop-filter:blur(20px);
background:#11111180;
border-bottom:1px solid rgba(255,255,255,.05);
z-index:1000;

}

.logo{

font-size:30px;
font-weight:700;
letter-spacing:2px;

}

.logo span{

color:#ff003c;

}

nav ul{

display:flex;
gap:35px;
list-style:none;

}

nav a{

color:white;
text-decoration:none;
transition:.3s;

}

nav a:hover{

color:#ff003c;

}

.hero{

height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:0 10%;

}

.hero h1{

font-size:70px;
font-weight:800;

}

.hero span{

color:#ff003c;

}

.hero p{

margin-top:20px;
font-size:20px;
opacity:.8;

}

.btn{

display:inline-block;
margin-top:35px;
padding:15px 35px;
background:#ff003c;
color:white;
text-decoration:none;
border-radius:50px;
transition:.3s;

}

.btn:hover{

transform:translateY(-5px);

}

section{

padding:100px 8%;

}

.title{

font-size:45px;
margin-bottom:50px;

}

.services{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:25px;

}

.card{

background:#131313;
padding:40px;
border-radius:20px;
transition:.4s;
border:1px solid rgba(255,255,255,.05);

}

.card:hover{

transform:translateY(-10px);
border-color:#ff003c;

}

.card i{

font-size:45px;
color:#ff003c;
margin-bottom:20px;

}

.gallery{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:20px;

}

.gallery img{

width:100%;
height:380px;
object-fit:cover;
border-radius:15px;
transition:.4s;

}

.gallery img:hover{

transform:scale(1.10);

}

.about{

display:grid;
grid-template-columns:1fr 1fr;
gap:60px;
align-items:center;

}

.about img{

width:100%;
border-radius:20px;

}

.about h3{

font-size:40px;

}

.about p{

margin-top:20px;
line-height:1.8;
opacity:.8;

}

.contact{

text-align:center;

}

.contact i{

font-size:25px;
color:#ff003c;
margin-right:10px;

}

footer{

padding:30px;
text-align:center;
opacity:.6;

}

@media(max-width:900px){

.hero h1{

font-size:45px;

}

.about{

grid-template-columns:1fr;

}

nav ul{

display:none;

}

}

</style>

</head>

<body>

<nav>

<div class="logo">
AJ <span>Effectx</span>
</div>

<ul>

<li><a href="#">Home</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#portfolio">Portfolio</a></li>
<li><a href="#about">About</a></li>
<li><a href="#contact">Contact</a></li>

</ul>

</nav>

<section class="hero">

<div>

<h1>A J <span>E F F E C T X</span></h1>

<p>
Automotive Posters • Photo Manipulation • Branding • Social Media Designs • Video editing • Motion graphics</p>

<a href="#portfolio" class="btn">View Portfolio</a>

</div>

</section>

<section id="services">

<h2 class="title">Services</h2>

<div class="services">

<div class="card">

<i class="fa-solid fa-car"></i>

<h3>Automotive Posters</h3>

<p>Premium car posters with cinematic editing and professional lighting.</p>

</div>

<div class="card">

<i class="fa-solid fa-image"></i>

<h3>Photo Editing</h3>

<p>Luxury retouching, manipulation and premium quality enhancements.</p>

</div>

<div class="card">

<i class="fa-solid fa-pen-ruler"></i>

<h3>Brand Design</h3>

<p>Creative logos, social media branding and visual identity.</p>

<h4>Video Editing</h4>

<p>Instagram reels, car videos, marriage reels</p>

</div>

</div>

</section>

<section id="portfolio">

<h2 class="title">Featured Work</h2>

<div class="gallery">

<img src="d:\colorgradingfinalout\bmwm3.jpg">

<img src="d:\colorgradingfinalout\gtr.jpg">

<img src="d:\colorgradingfinalout\redbull1 (1 of 1).jpg">

<img src="d:\colorgradingfinalout\911.jpg">

<img src="d:\colorgradingfinalout\Muffinbakes6.jpg">

<img src="d:\colorgradingfinalout\muffinbakes4.jpg">

<img src="d:\colorgradingfinalout\muffinbakes.jpg">

<img src="d:\colorgradingfinalout\manna chapathi.jpg">

</div>

</section>

<section id="about">

<div class="about">

<img src="d:\colorgradingfinalout\ajeffectxlogo.png">

<div>

<h3>About AJ Effectx</h3>

<p>

AJ Effectx is a creative design brand specializing in automotive poster design, video editing, motion graphics, premium photo manipulation, branding, and social media content. Every project is crafted with cinematic quality, attention to detail, and a modern visual style to help clients stand out.

</p>

</div>

</div>

</section>

<section id="contact">

<div class="contact">

<h2 class="title">Let's Work Together</h2>

<p>

<i class="fa-brands fa-instagram"></i>

@_aj_.effectx._

</p>

<br>

<p>

<i class="fa-solid fa-envelope"></i>

ajeffectx01@gmail.com

</p>

<br>

<a href="#" class="btn">Contact Me</a>

</div>

</section>

<footer>

© 2026 AJ Effectx. All Rights Reserved.

</footer>

</body>
</html>
