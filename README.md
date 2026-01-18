<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Aqua Force | Window Cleaning Mallow</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    :root{--gold:#d4af37;--black:#111;--white:#fff;--grey:#f8f8f8;--max:600px}
    *{margin:0;padding:0;box-sizing:border-box;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif}
    body{background:var(--white);color:var(--black);line-height:1.55}
    img{max-width:100%;display:block}
    a{color:inherit;text-decoration:none}
    .section{padding:3rem 1rem;max-width:var(--max);margin:auto}
    .center{text-align:center}
    nav{display:flex;justify-content:space-between;align-items:center;padding:1rem}
    .logo{font-weight:700;font-size:1.2rem;color:var(--gold)}
    .nav-links{display:flex;gap:1rem;list-style:none;font-size:.9rem}
    .btn-gold{background:var(--gold);color:var(--white);padding:.6rem 1.2rem;border:none;border-radius:4px;font-weight:600;display:inline-block}
    .hero{background:var(--grey)}
    h1{font-size:2rem;margin-bottom:.5rem}
    .cards{display:grid;gap:1rem;margin-top:1.5rem}
    .card{background:var(--grey);padding:1.25rem;border-radius:6px}
    .testi{background:var(--grey)}
    blockquote{font-style:italic;margin:.8rem 0}
    cite{display:block;margin-top:.5rem;font-style:normal;font-weight:600;color:var(--gold)}
    input,textarea{width:100%;padding:.6rem;margin:.4rem 0;border:1px solid #ccc;border-radius:4px}
    footer{background:var(--black);color:var(--white);text-align:center;font-size:.8rem;padding:2rem 1rem}
    @media(max-width:500px){.nav-links{gap:.6rem;font-size:.8rem}}
  </style>
</head>
<body>

<nav>
  <div class="logo">Aqua Force</div>
  <ul class="nav-links">
    <li><a href="#home">Home</a></li><li><a href="#services">Services</a></li><li><a href="#about">About</a></li><li><a href="#gallery">Gallery</a></li><li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<section id="home" class="hero section center">
  <h1>Crystal-clear windows every time</h1>
  <p>Professional window & gutter cleaning in Mallow. Fully insured, reliable service.</p>
  <a href="#contact" class="btn-gold">Book your clean</a>
</section>

<section id="services" class="section">
  <h2 class="center">What we do</h2>
  <div class="cards">
    <div class="card"><h3>Window Cleaning</h3><p>€4-€7 per pane · Interior & exterior<br>+20 % if inside required</p></div>
    <div class="card"><h3>Gutter Cleaning</h3><p>From €80 typical semi-D<br>Debris removed, flow tested</p></div>
    <div class="card"><h3>Fascia & Soffit</h3><p>Restore uPVC to bright white<br>Quote on site</p></div>
  </div>
</section>

<section id="testimonials" class="testi section">
  <h2 class="center">What neighbours say</h2>
  <blockquote>“Great job on my windows—no streaks at all.” <cite>Jamie Sheehan, Mallow</cite></blockquote>
  <blockquote>“Punctual, polite and the gutters work perfectly now.” <cite>Mary O’Connell, Mallow</cite></blockquote>
  <blockquote>“Fair price and brilliant finish.” <cite>Patrick O’Sullivan, Mallow</cite></blockquote>
</section>

<section id="about" class="section">
  <h2>About Aqua Force</h2>
  <p>Aqua Force began in 2024 as a way for me to earn money while managing my Leaving Cert study schedule. Window cleaning fitted perfectly: early mornings and weekends left the rest of the day free for revision. I quickly discovered I enjoyed the work and that neighbours in Mallow appreciated reliable, high-standard service.</p>
  <p><strong>Owner:</strong> Abdul Hamdi — I’ve cleaned hundreds of windows across Mallow and take real pride in a streak-free finish.</p>
  <p><strong>Area:</strong> Mallow business district & surrounding residential estates.</p>
</section>

<section id="gallery" class="section center">
  <h2>Before & After</h2>
  <div style="margin-top:1.5rem;display:grid;gap:1.5rem">
    <div><img src="https://i.imgur.com/8k04Gkb.jpg" alt="Dirty"><img src="https://i.imgur.com/7ZL2gF1.jpg" alt="Clean" style="margin-top:.5rem"><small>Residential windows — Mallow estate</small></div>
    <div><img src="https://i.imgur.com/9cY0cXd.jpg" alt="Clogged gutter"><img src="https://i.imgur.com/2FJl4nP.jpg" alt="Clean gutter" style="margin-top:.5rem"><small>Gutter clearance — Blackthorn Drive</small></div>
  </div>
</section>

<section id="contact" class="section">
  <h2 class="center">Get a Free Quote</h2>
  <div style="max-width:480px;margin:auto">
    <p class="center"><strong>Phone:</strong> <a href="tel:+353894925326">089 492 5326</a><br><strong>Email:</strong> <a href="mailto:aquaforcemallow@gmail.com">aquaforcemallow@gmail.com</a></p>
    <form action="https://formspree.io/f/your-form-id" method="POST" style="margin-top:1.5rem">
      <input name="name" placeholder="Your name" required>
      <input name="phone" placeholder="Phone number" required>
      <input name="email" placeholder="Email address" required>
      <textarea name="message" placeholder="Tell us about your windows/gutters" rows="4" required></textarea>
      <button type="submit" class="btn-gold" style="width:100%">Send quote request</button>
    </form>
  </div>
</section>

<footer>© 2024 Aqua Force · Mallow, Co. Cork<br>089 492 5326 · aquaforcemallow@gmail.com</footer>
</body>
</html>
