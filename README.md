<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>John Edmund A. Gabiana | Civil Engineer</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<style>

:root{
--primary:#00b4ff;
--dark:#0a0f1c;
--card:#141b2d;
--light:#f5f7fa;
--gray:#94a3b8;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Inter',sans-serif;
scroll-behavior:smooth;
}

body{
background:var(--dark);
color:white;
}

.container{
width:90%;
max-width:1400px;
margin:auto;
}

header{
position:fixed;
width:100%;
background:rgba(10,15,28,.95);
backdrop-filter:blur(10px);
z-index:1000;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 0;
}

.logo{
font-size:1.4rem;
font-weight:800;
color:var(--primary);
}

nav ul{
display:flex;
gap:30px;
list-style:none;
}

nav a{
text-decoration:none;
color:white;
font-weight:500;
}

.hero{
height:100vh;
display:flex;
align-items:center;
}

.hero-content{
max-width:800px;
}

.hero h1{
font-size:5rem;
font-weight:800;
line-height:1;
}

.hero h2{
color:var(--primary);
margin:20px 0;
font-size:1.8rem;
}

.hero p{
color:var(--gray);
font-size:1.1rem;
margin-bottom:40px;
max-width:650px;
}

.btn{
display:inline-block;
padding:14px 30px;
background:var(--primary);
color:black;
font-weight:700;
text-decoration:none;
border-radius:8px;
}

section{
padding:120px 0;
}

.section-title{
font-size:3rem;
margin-bottom:60px;
text-align:center;
}

.about-grid{
display:grid;
grid-template-columns:1fr 2fr;
gap:60px;
align-items:center;
}

.profile-box{
height:350px;
background:var(--card);
border-radius:20px;
}

.about-text{
color:var(--gray);
font-size:1.1rem;
line-height:1.8;
}

.skills{
display:flex;
flex-wrap:wrap;
gap:15px;
margin-top:30px;
}

.skill{
padding:10px 20px;
background:var(--card);
border-radius:30px;
}

.project-card{
background:var(--card);
border-radius:20px;
overflow:hidden;
margin-bottom:50px;
}

.project-image{
height:500px;
background:url('oil-sampling-bottle.jpg') center/cover;
}

.project-content{
padding:40px;
}

.project-content h3{
font-size:2rem;
margin-bottom:15px;
}

.project-content p{
color:var(--gray);
line-height:1.8;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(350px,1fr));
gap:25px;
}

.gallery-item{
background:var(--card);
border-radius:15px;
overflow:hidden;
}

.gallery-img{
height:250px;
background:#202b44;
}

.gallery-content{
padding:25px;
}

.gallery-content h4{
margin-bottom:10px;
}

.gallery-content p{
color:var(--gray);
}

.stats{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:25px;
margin-top:60px;
}

.stat{
background:var(--card);
padding:30px;
text-align:center;
border-radius:15px;
}

.stat h3{
font-size:2rem;
color:var(--primary);
}

.contact{
text-align:center;
}

.contact p{
color:var(--gray);
margin-bottom:30px;
}

footer{
padding:40px;
text-align:center;
border-top:1px solid #1e293b;
color:var(--gray);
}

@media(max-width:768px){

.hero h1{
font-size:3rem;
}

.about-grid{
grid-template-columns:1fr;
}

.stats{
grid-template-columns:1fr 1fr;
}

nav ul{
display:none;
}

}

</style>
</head>

<body>

<header>
<div class="container">
<nav>

<div class="logo">
JD ENGINEERING
</div>

<ul>
<li><a href="#about">About</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#portfolio">CAD Portfolio</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>
</div>
</header>

<section class="hero">

<div class="container">

<div class="hero-content">

<h1>Product Design Engineer</h1>

<h2>CAD Design • Product Development • Prototyping</h2>

<p>
Designing innovative industrial products through CAD modeling,
engineering analysis, rapid prototyping, and manufacturing-ready
solutions.
</p>

<a href="#projects" class="btn">
View Projects
</a>

</div>

</div>

</section>

<section id="about">

<div class="container">

<h2 class="section-title">About Me</h2>

<div class="about-grid">

<div class="profile-box">
<!-- Profile image here -->
</div>

<div>

<p class="about-text">

I specialize in product design engineering with expertise in CAD
modeling, industrial design, plastic product development, and
manufacturing optimization. My workflow covers concept generation,
3D modeling, prototyping, testing, and production documentation.

</p>

<div class="skills">

<div class="skill">SolidWorks</div>
<div class="skill">Fusion 360</div>
<div class="skill">AutoCAD</div>
<div class="skill">3D Rendering</div>
<div class="skill">DFM</div>
<div class="skill">Injection Molding</div>
<div class="skill">Rapid Prototyping</div>
<div class="skill">Product Development</div>

</div>

</div>

</div>

</div>

</section>

<section id="projects">

<div class="container">

<h2 class="section-title">Featured Project</h2>

<div class="project-card">

<div class="project-image">
<!-- Replace with oil bottle render -->
</div>

<div class="project-content">

<h3>Oil Sampling Bottle Design</h3>

<p>

Designed a 100 ml industrial oil sampling bottle for lubricant
analysis applications. The project included CAD modeling,
ergonomic cap redesign, manufacturing optimization, dimensional
verification, and photorealistic rendering for production review.

</p>

<br>

<p>

Deliverables:
• Production-ready CAD Model
• Technical Drawings
• Mold-Friendly Geometry
• Product Visualization
• Engineering Documentation

</p>

</div>

</div>

</div>

</section>

<section id="portfolio">

<div class="container">

<h2 class="section-title">CAD Portfolio</h2>

<div class="gallery">

<div class="gallery-item">
<div class="gallery-img"></div>
<div class="gallery-content">
<h4>Industrial Container</h4>
<p>Injection molded packaging design.</p>
</div>
</div>

<div class="gallery-item">
<div class="gallery-img"></div>
<div class="gallery-content">
<h4>Mechanical Assembly</h4>
<p>Precision engineered assembly system.</p>
</div>
</div>

<div class="gallery-item">
<div class="gallery-img"></div>
<div class="gallery-content">
<h4>Custom Enclosure</h4>
<p>Electronics housing development.</p>
</div>
</div>

<div class="gallery-item">
<div class="gallery-img"></div>
<div class="gallery-content">
<h4>Consumer Product</h4>
<p>Product concept through production.</p>
</div>
</div>

</div>

<div class="stats">

<div class="stat">
<h3>50+</h3>
<p>CAD Models</p>
</div>

<div class="stat">
<h3>20+</h3>
<p>Projects</p>
</div>

<div class="stat">
<h3>5+</h3>
<p>Years Design</p>
</div>

<div class="stat">
<h3>100%</h3>
<p>Manufacturable</p>
</div>

</div>

</div>

</section>      

<section id="contact">

<div class="container">

<div class="contact">

<h2 class="section-title">Let's Build Something</h2>

<p>
Available for product design, CAD modeling,
engineering consulting, and prototype development.
</p>

<a href="mailto:your@email.com" class="btn">
Contact Me
</a>

</div>

</div>

</section>

<footer>

© 2026 John Dragneel | Civil Engineer

</footer>

</body>
</html>
