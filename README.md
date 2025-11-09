<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Vysonic Designs — Graphic & Web Design</title>
  <meta name="description" content="Vysonic Designs — Logo, brand & website design. Contact via WhatsApp, email or social media." />
  <meta name="theme-color" content="#041028" />
  <style>
    /* =========================
       Vysonic Designs — Single Page (Static)
       Deep blue & black theme
       ========================= */
    :root{
      --bg:#05060a;
      --panel:#071229;
      --deep-blue:#061634; /* primary deep blue */
      --accent:#1e90ff;    /* bright accent for CTAs (blue) */
      --muted:#9fb0c8;
      --glass: rgba(255,255,255,0.03);
      --card: linear-gradient(180deg, rgba(255,255,255,0.02), transparent);
      --maxW:1100px;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      color-scheme: dark;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      background:
        radial-gradient(800px 400px at 10% 10%, rgba(30,48,80,0.35), transparent 12%),
        linear-gradient(180deg,var(--deep-blue),var(--bg));
      color:#e8f1fb;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
    }
    a{color:inherit}
    .container{max-width:var(--maxW);margin:36px auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:14px}
    .logo{
      width:68px;height:68px;border-radius:12px;
      background:linear-gradient(135deg,#063058,#02121a);
      display:flex;align-items:center;justify-content:center;font-weight:800;
      font-size:20px;color:var(--accent);box-shadow:0 6px 24px rgba(2,10,20,0.6);
    }
    .brand h1{margin:0;font-size:20px;letter-spacing:0.2px}
    .tag{font-size:13px;color:var(--muted);margin-top:2px}
    nav{display:flex;gap:14px}
    nav a{color:var(--muted);text-decoration:none;font-size:14px;padding:8px;border-radius:8px}
    nav a:hover{background:rgba(255,255,255,0.02);color:var(--accent)}
    /* Hero */
    .hero{
      display:grid;grid-template-columns:1fr 360px;gap:26px;align-items:center;margin-top:26px;
    }
    .card{
      background:var(--card);
      padding:28px;border-radius:14px;box-shadow:0 8px 40px rgba(2,6,20,0.6);
    }
    .hero h2{margin:0 0 12px 0;font-size:30px}
    .hero p{margin:0 0 18px;color:var(--muted)}
    .cta{display:flex;gap:12px;align-items:center}
    .btn{
      display:inline-block;padding:10px 14px;border-radius:10px;font-weight:700;
      text-decoration:none;color:#04111d;background:var(--accent);
      box-shadow:0 6px 18px rgba(30,144,255,0.14);
    }
    .btn.ghost{background:transparent;border:1px solid rgba(255,255,255,0.04);color:var(--muted)}
    /* Services */
    .services{display:flex;gap:12px;margin-top:18px}
    .service{flex:1;background:var(--glass);padding:12px;border-radius:10px;text-align:center}
    .service h3{margin:8px 0 0 0;font-size:14px}
    /* Right column contact */
    .side-contact .muted{color:var(--muted);font-size:13px}
    .socials{display:flex;gap:10px;flex-wrap:wrap;margin-top:10px}
    .socials a{font-size:13px;color:var(--muted);text-decoration:none;padding:6px 8px;border-radius:8px}
    .socials a:hover{color:var(--accent)}
    /* Portfolio */
    #portfolio{margin-top:26px}
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
    .thumb{
      height:140px;border-radius:10px;background:linear-gradient(135deg,#0b2340,#12253b);
      display:flex;align-items:center;justify-content:center;color:rgba(255,255,255,0.12);font-weight:800;
      box-shadow:inset 0 -20px 40px rgba(0,0,0,0.3);
    }
    /* Contact form area */
    form.contact{display:grid;gap:10px;margin-top:18px}
    input[type="text"], input[type="email"], textarea{
      width:100%;padding:12px;border-radius:10px;border:1px solid rgba(255,255,255,0.05);
      background:transparent;color:inherit;font-size:14px;
    }
    textarea{min-height:110px;resize:vertical}
    .note{font-size:13px;color:var(--muted)}
    /* Footer */
    footer{margin-top:30px;padding-top:18px;border-top:1px solid rgba(255,255,255,0.03);display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:12px}
    footer .small{color:var(--muted);font-size:13px}
    /* Responsive */
    @media (max-width:980px){
      .hero{grid-template-columns:1fr}
      .grid{grid-template-columns:repeat(2,1fr)}
    }
    @media (max-width:560px){
      .container{padding:16px;margin:12px}
      .grid{grid-template-columns:1fr}
      nav{display:none}
      header{align-items:flex-start;gap:8px}
      .logo{width:56px;height:56px}
      .hero h2{font-size:22px}
    }
  </style>
</head>
<body>
  <div class="container" role="document">
    <header>
      <div class="brand" aria-label="Vysonic Designs">
        <div class="logo" aria-hidden="true">VD</div>
        <div>
          <h1>Vysonic Designs</h1>
          <div class="tag">All sorts of graphic & website design</div>
        </div>
      </div>

      <nav aria-label="Main navigation">
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <!-- HERO -->
    <section class="hero" aria-labelledby="hero-title">
      <div class="card">
        <h2 id="hero-title">Beautiful design that helps your brand stand out.</h2>
        <p>Logos, brand identity, social assets, and responsive websites — crafted professionally and delivered quickly.</p>

        <div class="cta" role="region" aria-label="Primary actions">
          <a class="btn" href="https://wa.me/2347051798972?text=Hi%20Vysonic%20Designs,%20I%27d%20like%20to%20discuss%20a%20project" aria-label="Contact Vysonic Designs on WhatsApp">Contact on WhatsApp</a>
          <a class="btn ghost" href="mailto:vysonicdesigns@gmail.com" aria-label="Email Vysonic Designs">Email us</a>
        </div>

        <div class="services" aria-hidden="false">
          <div class="service">
            <div style="font-weight:700">Branding</div>
            <h3>Logos & identity</h3>
          </div>
          <div class="service">
            <div style="font-weight:700">Design</div>
            <h3>Social & print</h3>
          </div>
          <div class="service">
            <div style="font-weight:700">Web</div>
            <h3>Responsive sites</h3>
          </div>
        </div>
      </div>

      <aside class="card side-contact" aria-labelledby="contact-aside">
        <h3 id="contact-aside">Contact</h3>
        <div class="muted" style="color:var(--muted);margin-top:6px">
          <div><strong>Phone:</strong> <a href="https://wa.me/2347051798972" style="color:var(--accent);text-decoration:none">+234 705 179 8972</a> (WhatsApp)</div>
          <div style="margin-top:6px"><strong>Email:</strong> <a href="mailto:vysonicdesigns@gmail.com" style="color:var(--accent);text-decoration:none">vysonicdesigns@gmail.com</a></div>
        </div>

        <div style="margin-top:12px" class="note">Follow us</div>
        <div class="socials" aria-label="Social links">
          <a href="https://instagram.com/vysonic.2436.designs" target="_blank" rel="noopener">Instagram</a>
          <a href="https://www.tiktok.com/search?q=Vysonic%20Designs" target="_blank" rel="noopener">TikTok</a>
          <a href="https://www.pinterest.com/vysonicdesigns" target="_blank" rel="noopener">Pinterest</a>
          <a href="https://www.facebook.com/VysonicDesigns" target="_blank" rel="noopener">Facebook</a>
          <a href="https://www.youtube.com/results?search_query=Vysonic+Designs" target="_blank" rel="noopener">YouTube</a>
        </div>

        <div style="margin-top:12px;color:var(--muted);font-size:13px">IG: <a href="https://instagram.com/vysonic.2436.designs" style="color:var(--accent)">vysonic.2436.designs</a></div>
      </aside>
    </section>

    <!-- SERVICES & PORTFOLIO -->
    <section id="services" class="card" style="margin-top:26px">
      <h3 style="margin:0 0 8px 0">Services</h3>
      <p class="note">Typical projects we handle — custom quotes available.</p>

      <ul style="color:var(--muted);margin-top:12px;line-height:1.6">
        <li>Logo & brand identity</li>
        <li>Business stationery & print (flyers, posters)</li>
        <li>Social media graphics & ad creatives</li>
        <li>Responsive websites & landing pages</li>
        <li>Illustration & packaging design</li>
      </ul>

      <div id="portfolio" style="margin-top:18px">
        <h3 style="margin-bottom:10px">Portfolio</h3>
        <div class="grid" aria-hidden="false">
          <div class="thumb">Project A</div>
          <div class="thumb">Project B</div>
          <div class="thumb">Project C</div>
          <div class="thumb">Project D</div>
          <div class="thumb">Project E</div>
          <div class="thumb">Project F</div>
        </div>
        <p class="note" style="margin-top:10px">Replace thumbnails with images of your completed work. Each .thumb can contain an <code>&lt;img&gt;</code> instead of text.</p>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="card" style="margin-top:18px">
      <h3 style="margin:0 0 8px 0">Get a quote</h3>
      <p class="note">Send a short message — we’ll reply on WhatsApp.</p>

      <form class="contact" onsubmit="event.preventDefault(); submitForm();" aria-label="Quote form">
        <input id="name" type="text" placeholder="Your name" aria-label="Your name" />
        <input id="email" type="email" placeholder="Email (optional)" aria-label="Email (optional)" />
        <input id="subject" type="text" placeholder="Project (e.g. logo, website, social pack)" aria-label="Project brief" />
        <textarea id="details" placeholder="More details (optional)" aria-label="More details"></textarea>
        <div style="display:flex;gap:10px;align-items:center">
          <button type="button" class="btn" onclick="submitForm()" aria-label="Send message on WhatsApp">Send on WhatsApp</button>
          <div class="note" style="margin-left:auto">Or email: <a href="mailto:vysonicdesigns@gmail.com" style="color:var(--accent)">vysonicdesigns@gmail.com</a></div>
        </div>
      </form>
    </section>

    <!-- FOOTER -->
    <footer>
      <div class="small">© Vysonic Designs</div>
      <div class="small">Phone: <a href="https://wa.me/2347051798972" style="color:var(--accent);text-decoration:none">+234 705 179 8972</a> · Email: <a href="mailto:vysonicdesigns@gmail.com" style="color:var(--accent)">vysonicdesigns@gmail.com</a></div>
    </footer>
  </div>

  <script>
    // Static site helper to open WhatsApp with the user's message
    function submitForm() {
      const name = document.getElementById('name').value.trim();
      const email = document.getElementById('email').value.trim();
      const subject = document.getElementById('subject').value.trim();
      const details = document.getElementById('details').value.trim();

      let message = 'Hi Vysonic Designs, I need a quote for: ' + (subject || 'a project') + '.';
      if (name) message += '\\nName: ' + name;
      if (email) message += '\\nEmail: ' + email;
      if (details) message += '\\nDetails: ' + details;

      const url = 'https://wa.me/2347051798972?text=' + encodeURIComponent(message);
      window.open(url, '_blank');
    }
  </script>
</body>
</html>
