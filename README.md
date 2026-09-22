# royal-cuts-
Royal Cuts Barbershop website
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Royal Cuts | Premium Barbershop</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  scroll-behavior:smooth;
}

body{
  font-family:Arial, sans-serif;
  background:#080808;
  color:#fff;
  line-height:1.6;
}

header{
  position:fixed;
  top:0;
  width:100%;
  z-index:1000;
  background:rgba(0,0,0,.92);
  border-bottom:1px solid #333;
  padding:18px 6%;
  display:flex;
  justify-content:space-between;
  align-items:center;
}

.logo{
  color:#d4af37;
  font-size:24px;
  font-weight:bold;
  letter-spacing:2px;
}

nav a{
  color:white;
  text-decoration:none;
  margin-left:18px;
  font-size:14px;
}

nav a:hover{
  color:#d4af37;
}

.hero{
  min-height:100vh;
  padding:150px 7% 80px;
  display:flex;
  align-items:center;
  text-align:center;
  justify-content:center;
  background:
  linear-gradient(rgba(0,0,0,.68),rgba(0,0,0,.85)),
  url("https://images.unsplash.com/photo-1622288432450-277d0fef5ed6?auto=format&fit=crop&w=1200&q=80");
  background-size:cover;
  background-position:center;
}

.hero-content{
  max-width:750px;
}

.tag{
  color:#d4af37;
  letter-spacing:3px;
  font-size:13px;
  font-weight:bold;
  margin-bottom:15px;
}

h1{
  font-size:52px;
  line-height:1.1;
  margin-bottom:20px;
}

.gold{
  color:#d4af37;
}

.hero p{
  font-size:18px;
  color:#ddd;
  margin-bottom:30px;
}

.btn{
  display:inline-block;
  padding:15px 28px;
  margin:6px;
  border-radius:4px;
  text-decoration:none;
  font-weight:bold;
  transition:.3s;
}

.primary{
  background:#d4af37;
  color:#000;
}

.secondary{
  border:1px solid #d4af37;
  color:#d4af37;
}

.btn:hover{
  transform:translateY(-3px);
}

section{
  padding:80px 7%;
}

.section-title{
  text-align:center;
  font-size:34px;
  margin-bottom:45px;
}

.section-title span{
  color:#d4af37;
}

.services{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:20px;
  max-width:1100px;
  margin:auto;
}

.card{
  background:#111;
  border:1px solid #292929;
  padding:28px 22px;
  border-radius:10px;
  text-align:center;
  transition:.3s;
}

.card:hover{
  transform:translateY(-7px);
  border-color:#d4af37;
}

.card h3{
  margin-bottom:10px;
  color:#fff;
}

.card p{
  color:#aaa;
  font-size:14px;
}

.price{
  color:#d4af37;
  font-size:23px;
  font-weight:bold;
  margin-top:15px;
}

.about{
  background:#0e0e0e;
}

.about-box{
  max-width:850px;
  margin:auto;
  text-align:center;
}

.about-box p{
  color:#bbb;
  font-size:17px;
}

.gallery{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:12px;
  max-width:1100px;
  margin:auto;
}

.gallery img{
  width:100%;
  height:230px;
  object-fit:cover;
  border-radius:8px;
}

.info{
  max-width:850px;
  margin:auto;
  text-align:center;
}

.info p{
  margin:12px 0;
  color:#ccc;
}

.whatsapp{
  position:fixed;
  right:20px;
  bottom:20px;
  z-index:999;
  background:#25d366;
  color:white;
  width:58px;
  height:58px;
  border-radius:50%;
  display:flex;
  justify-content:center;
  align-items:center;
  text-decoration:none;
  font-size:27px;
  box-shadow:0 5px 20px rgba(0,0,0,.5);
}

footer{
  text-align:center;
  padding:30px;
  background:#050505;
  color:#777;
  font-size:13px;
}

@media(max-width:700px){

  nav{
    display:none;
  }

  h1{
    font-size:40px;
  }

  .hero p{
    font-size:16px;
  }

  section{
    padding:65px 5%;
  }

  .gallery{
    grid-template-columns:1fr;
  }

  .gallery img{
    height:240px;
  }

  .section-title{
    font-size:29px;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">ROYAL CUTS</div>

  <nav>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <div class="hero-content">

    <div class="tag">PREMIUM MEN'S GROOMING</div>

    <h1>
      Look Sharp.<br>
      <span class="gold">Feel Royal.</span>
    </h1>

    <p>
      Premium haircuts, beard grooming and modern men's styling.
      A fictional demo website created for presentation.
    </p>

    <a class="btn primary" href="#contact">
      BOOK APPOINTMENT
    </a>

    <a class="btn secondary" href="#services">
      VIEW SERVICES
    </a>

  </div>
</section>

<section id="services">

  <h2 class="section-title">
    Our <span>Services</span>
  </h2>

  <div class="services">

    <div class="card">
      <h3>Classic Haircut</h3>
      <p>Clean, sharp and professionally finished.</p>
      <div class="price">₦5,000</div>
    </div>

    <div class="card">
      <h3>Beard Grooming</h3>
      <p>Professional beard shaping and finishing.</p>
      <div class="price">₦3,000</div>
    </div>

    <div class="card">
      <h3>Hair + Beard</h3>
      <p>A complete haircut and beard transformation.</p>
      <div class="price">₦7,000</div>
    </div>

    <div class="card">
      <h3>Premium Package</h3>
      <p>Haircut, beard, styling and premium finishing.</p>
      <div class="price">₦10,000</div>
    </div>

  </div>
</section>

<section class="about" id="about">

  <h2 class="section-title">
    About <span>Royal Cuts</span>
  </h2>

  <div class="about-box">

    <p>
      Royal Cuts is a fictional premium Lagos barbershop created
      as a website demonstration. The concept focuses on quality
      grooming, attention to detail and a modern customer experience.
    </p>

  </div>
</section>

<section id="gallery">

  <h2 class="section-title">
    Style <span>Gallery</span>
  </h2>

  <div class="gallery">

    <img src="https://images.unsplash.com/photo-1503951914875-452162b0f3f1?auto=format&fit=crop&w=800&q=80">

    <img src="https://images.unsplash.com/photo-1621605815971-fbc98d665033?auto=format&fit=crop&w=800&q=80">

    <img src="https://images.unsplash.com/photo-1622287162716-f311baa1a2b8?auto=format&fit=crop&w=800&q=80">

  </div>

</section>

<section id="contact">

  <h2 class="section-title">
    Visit <span>Royal Cuts</span>
  </h2>

  <div class="info">

    <p>📍 Ikeja, Lagos, Nigeria</p>

    <p>📞 +234 800 000 0000</p>

    <p>🕐 Monday – Saturday: 9:00 AM – 8:00 PM</p>

    <br>

    <a class="btn primary"
       href="https://wa.me/2348000000000">
       CHAT ON WHATSAPP
    </a>

  </div>

</section>

<a class="whatsapp"
   href="https://wa.me/2348000000000"
   aria-label="WhatsApp">
   ☎
</a>

<footer>
  © 2026 Royal Cuts — Demo Website
</footer>

</body>
</html>
