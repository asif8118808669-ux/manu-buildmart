<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8" />  
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>  
<title>Manu Buildmart</title>  
  
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet">  
  
<style>  
*{margin:0;padding:0;box-sizing:border-box}  
body{  
  font-family:'Montserrat',sans-serif;  
  background:#0b0b0b;  
  color:#fff;  
  overflow-x:hidden;  
}  
  
/* HEADER */  
header{  
  position:fixed;  
  top:0;left:0;  
  width:100%;  
  padding:20px 60px;  
  display:flex;  
  justify-content:space-between;  
  align-items:center;  
  z-index:1000;  
  background:rgba(0,0,0,.6);  
  backdrop-filter:blur(10px);  
}  
.logo{  
  font-size:26px;  
  letter-spacing:3px;  
  font-weight:600;  
}  
nav a{  
  color:#fff;  
  margin-left:30px;  
  text-decoration:none;  
  font-size:14px;  
}  
  
/* HERO */  
.hero{  
  height:100vh;  
  display:flex;  
  align-items:center;  
  padding:120px 60px 60px;  
}  
.hero-text{  
  max-width:520px;  
}  
.hero-text h1{  
  font-size:56px;  
  line-height:1.1;  
}  
.hero-text p{  
  margin-top:20px;  
  opacity:.8;  
}  
.hero-media{  
  position:absolute;  
  right:60px;  
  top:50%;  
  transform:translateY(-50%);  
  width:45%;  
  height:65%;  
  border-radius:20px;  
  background:linear-gradient(135deg,#1a1a1a,#000);  
  overflow:hidden;  
}  
  
/* ABOUT */  
section{  
  padding:120px 60px;  
}  
.about{  
  display:flex;  
  justify-content:space-between;  
  gap:60px;  
}  
.about h2{  
  font-size:42px;  
}  
.stats{  
  display:flex;  
  gap:60px;  
}  
.stat h3{  
  font-size:36px;  
}  
.stat span{  
  font-size:12px;  
  opacity:.7;  
}  
  
/* MEDIA GRID */  
.media-grid{  
  display:grid;  
  grid-template-columns:repeat(3,1fr);  
  gap:30px;  
}  
.media-box{  
  height:260px;  
  border-radius:18px;  
  background:#111;  
}  
  
/* PROJECTS */  
.projects{  
  display:grid;  
  grid-template-columns:repeat(3,1fr);  
  gap:30px;  
}  
.project{  
  padding:30px;  
  background:#111;  
  border-radius:18px;  
}  
.project h3{  
  margin-top:20px;  
}  
  
/* FOOTER */  
footer{  
  padding:60px;  
  text-align:center;  
  opacity:.6;  
}  
  
@media(max-width:900px){  
  .hero{flex-direction:column}  
  .hero-media{position:relative;width:100%;height:300px;right:auto;top:auto;transform:none;margin-top:40px}  
  .about{flex-direction:column}  
  .media-grid,.projects{grid-template-columns:1fr}  
}  
</style>  
</head>  
  
<body>  
  
<header>  
  <div class="logo">MANU BUILDMART</div>  
  <nav>  
    <a href="#about">About</a>  
    <a href="#projects">Projects</a>  
    <a href="#contact">Contact</a>  
  </nav>  
</header>  
  
<div class="hero">  
  <div class="hero-text">  
    <h1>Luxury Real Estate<br>Crafted Since 2007</h1>  
    <p>Jaipur-based premium real estate developer delivering architectural excellence.</p>  
  </div>  
  <div class="hero-media">  
    <!-- Add image or video later -->  
  </div>  
</div>  
  
<section id="about" class="about">  
  <div>  
    <h2>About Manu Buildmart</h2>  
    <p style="margin-top:20px;opacity:.8">  
      Established in 2007, Manu Buildmart is a Jaipur-based real estate company focused on premium residential developments inspired by global luxury standards.  
    </p>  
  </div>  
  
  <div class="stats">  
    <div class="stat">  
      <h3>2007</h3>  
      <span>Established</span>  
    </div>  
    <div class="stat">  
      <h3>15+</h3>  
      <span>Projects</span>  
    </div>  
    <div class="stat">  
      <h3>1000+</h3>  
      <span>Happy Clients</span>  
    </div>  
  </div>  
</section>  
  
<section>  
  <h2 style="margin-bottom:40px">Media Showcase</h2>  
  <div class="media-grid">  
    <div class="media-box"></div>  
    <div class="media-box"></div>  
    <div class="media-box"></div>  
  </div>  
</section>  
  
<section id="projects">  
  <h2 style="margin-bottom:40px">Ongoing Projects</h2>  
  <div class="projects">  
    <div class="project">  
      <h3>Upcoming Luxury Residences</h3>  
      <p style="opacity:.7;margin-top:10px">Details coming soon</p>  
    </div>  
    <div class="project">  
      <h3>Premium Villas</h3>  
      <p style="opacity:.7;margin-top:10px">Launching shortly</p>  
    </div>  
    <div class="project">  
      <h3>Signature Development</h3>  
      <p style="opacity:.7;margin-top:10px">Under planning</p>  
    </div>  
  </div>  
</section>  
  
<footer id="contact">  
  <p>Manu Buildmart · Jaipur · +91 9XXXXXXXXX</p>  
</footer>  
  
</body>  
</html>  
