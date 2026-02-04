# canva-with-rafay<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Canva with Rafay | Graphics Designer</title>
  <meta name="description" content="Professional Canva graphics designer specializing in social media posts, logos, flyers, banners, and branding. Based in Vehari, Pakistan." />
  <meta name="theme-color" content="#7b2ff7" />
  <!-- Google Fonts (optional) -->
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet" />
  <style>
    :root{
      --bg:#f4f6f9;
      --text:#222;
      --accent-1:#7b2ff7;
      --accent-2:#f107a3;
      --card:#ffffff;
      --radius:12px;
      --shadow: 0 10px 25px rgba(0,0,0,0.08);
      --container-max:1100px;
      --gap:20px;
      --fs-h1:2rem; /* scalable with rem */
    }

    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: "Inter", "Segoe UI", system-ui, -apple-system, "Helvetica Neue", Arial;
      background:var(--bg);
      color:var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.5;
      font-size:16px;
    }

    header{
      background:linear-gradient(135deg,var(--accent-1),var(--accent-2));
      color:#fff;
      padding:4.5rem 1.25rem;
      text-align:center;
    }
    header .wrap{max-width:var(--container-max);margin:0 auto;padding:0 1rem}
    header h1{font-size:clamp(1.5rem,3vw,2.6rem);margin-bottom:.5rem;letter-spacing:-.5px}
    header p{font-size:clamp(.95rem,1.4vw,1.125rem);opacity:.95;margin-bottom:1.25rem}
    .btn{
      display:inline-block;
      background:#fff;
      color:var(--accent-1);
      padding:.6rem 1.25rem;
      border-radius:999px;
      text-decoration:none;
      font-weight:700;
      box-shadow:0 6px 18px rgba(123,47,247,0.12);
    }
    .btn:focus{outline:3px solid rgba(123,47,247,0.18);outline-offset:3px}

    main{max-width:var(--container-max);margin:0 auto;padding:2.5rem 1rem}
    h2{color:var(--accent-1);text-align:center;margin:0 0 1.25rem 0;font-size:1.5rem}

    .about p{max-width:62ch;margin:0 auto;text-align:center;font-size:1rem;color:rgba(0,0,0,0.82)}

    .grid{
      display:grid;
      gap:var(--gap);
      grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    }

    .card{
      background:var(--card);
      padding:1.25rem;
      border-radius:var(--radius);
      box-shadow:var(--shadow);
      text-align:center;
      transition:transform .22s ease,box-shadow .22s ease;
    }
    .card:hover{transform:translateY(-6px)}
    .card:focus-within{outline:3px solid rgba(17,17,17,0.04);outline-offset:3px}

    .portfolio img{width:100%;height:auto;border-radius:10px;display:block}

    .pricing .price{
      font-size:1.75rem;color:var(--accent-2);margin:.6rem 0;font-weight:700
    }

    .contact{ text-align:center }

    footer{
      background:#0e0e0e;color:#fff;text-align:center;padding:1.25rem;margin-top:2.5rem;font-size:.95rem;
    }

    /* Accessibility: visible focus for keyboard users */
    a:focus{outline:3px solid rgba(123,47,247,0.18);outline-offset:3px}
    button:focus{outline:3px solid rgba(123,47,247,0.18);outline-offset:3px}

    /* Responsive tweaks */
    @media (max-width:640px){
      header{padding:3rem 1rem}
      main{padding:1.5rem 1rem}
    }
  </style>

  <!-- Structured data for SEO (LocalBusiness/person) -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Rafay",
    "jobTitle": "Graphics Designer",
    "worksFor": "Canva with Rafay",
    "email": "mailto:canvadesigner123458@gmail.com",
    "telephone": "+92-327-6251828",
    "address": {
      "@type": "PostalAddress",
      "addressLocality": "Vehari",
      "addressCountry": "PK"
    },
    "url": ""
  }
  </script>
</head>
<body>
  <header>
    <div class="wrap">
      <h1>Canva with Rafay</h1>
      <p>Professional Graphics Designer — social posts, logos, flyers, banners & branding</p>
      <a class="btn" href="#contact" aria-label="Contact Rafay">Contact Me</a>
    </div>
  </header>

  <main>
    <section class="about" aria-labelledby="about-heading">
      <h2 id="about-heading">About Me</h2>
      <p>
        I'm a creative Canva graphics designer helping brands stand out with eye-catching visuals.
        I specialize in social media assets, logos, posters, banners and complete branding packages.
      </p>
    </section>

    <section aria-labelledby="services-heading" style="margin-top:2.5rem">
      <h2 id="services-heading">My Services</h2>
      <div class="grid">
        <div class="card">Social Media Post Design</div>
        <div class="card">Logo Design</div>
        <div class="card">Flyer & Poster Design</div>
        <div class="card">Business Card Design</div>
        <div class="card">YouTube Thumbnail</div>
        <div class="card">Facebook & Instagram Ads</div>
      </div>
    </section>

    <section aria-labelledby="portfolio-heading" style="margin-top:2.5rem">
      <h2 id="portfolio-heading">Portfolio</h2>
      <div class="grid portfolio" aria-live="polite">
        <div class="card"><img src="https://via.placeholder.com/600x400?text=Design+1" alt="Portfolio design 1 — sample social post" loading="lazy"></div>
        <div class="card"><img src="https://via.placeholder.com/600x400?text=Design+2" alt="Portfolio design 2 — sample logo" loading="lazy"></div>
        <div class="card"><img src="https://via.placeholder.com/600x400?text=Design+3" alt="Portfolio design 3 — sample flyer" loading="lazy"></div>
        <div class="card"><img src="https://via.placeholder.com/600x400?text=Design+4" alt="Portfolio design 4 — sample banner" loading="lazy"></div>
        <div class="card"><img src="https://via.placeholder.com/600x400?text=Design+5" alt="Portfolio design 5 — sample poster" loading="lazy"></div>
        <div class="card"><img src="https://via.placeholder.com/600x400?text=Design+6" alt="Portfolio design 6 — sample thumbnail" loading="lazy"></div>
      </div>
    </section>

    <section aria-labelledby="pricing-heading" style="margin-top:2.5rem">
      <h2 id="pricing-heading">Pricing</h2>
      <div class="grid pricing">
        <div class="card">
          <h3>Basic</h3>
          <p class="price">$10</p>
          <p>1 Design</p>
        </div>
        <div class="card">
          <h3>Standard</h3>
          <p class="price">$25</p>
          <p>5 Designs</p>
        </div>
        <div class="card">
          <h3>Premium</h3>
          <p class="price">$50</p>
          <p>10 Designs</p>
        </div>
      </div>
    </section>

    <section id="contact" class="contact" aria-labelledby="contact-heading" style="margin-top:2.5rem">
      <h2 id="contact-heading">Contact Me</h2>
      <p>📞 <a href="tel:+923276251828">+92 327 6251828</a> — <a href="https://wa.me/923276251828" target="_blank" rel="noopener noreferrer">WhatsApp</a></p>
      <p>📧 <a href="mailto:canvadesigner123458@gmail.com">canvadesigner123458@gmail.com</a></p>
      <p>📍 Vehari, Pakistan</p>

      <!-- Optional: simple contact form (uncomment and set up backend or Netlify Forms) -->
      <!--
      <form method="POST" action="/.netlify/functions/contact" style="max-width:560px;margin:1rem auto;display:grid;gap:10px">
        <input name="name" placeholder="Your name" required />
        <input type="email" name="email" placeholder="Email" required />
        <textarea name="message" rows="5" placeholder="Message" required></textarea>
        <button type="submit" class="btn">Send Message</button>
      </form>
      -->
    </section>
  </main>

  <footer>
    © 2026 Canva with Rafay | All Rights Reserved
  </footer>
</body>
</html>
