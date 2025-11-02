<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Bloom & Bliss — Wedding Decoration & Florist Design</title>
  <meta name="description" content="Bloom & Bliss: Luxury wedding decoration and bespoke florist design. We craft unforgettable ceremonies and receptions with floral art, lighting and styling." />
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Playfair+Display:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root{
      --peach:#FFD8C2;
      --deep:#2b2b2b;
      --muted:#6b6b6b;
      --accent:#FF8C6A;
      --card:#ffffff;
      --glass: rgba(255,255,255,0.7);
      font-family: 'Montserrat', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,#fff 0%,#fff7f3 100%);color:var(--deep);-webkit-font-smoothing:antialiased}
    header{display:flex;align-items:center;justify-content:space-between;padding:22px 6%;position:sticky;top:0;background:rgba(255,255,255,0.45);backdrop-filter:blur(6px);z-index:30}
    .logo{display:flex;gap:12px;align-items:center;font-weight:700}
    .logo .mark{width:44px;height:44px;border-radius:10px;background:linear-gradient(135deg,var(--accent),var(--peach));display:flex;align-items:center;justify-content:center;color:#fff;font-size:20px;font-weight:700}
    nav ul{list-style:none;display:flex;gap:18px;margin:0;padding:0}
    nav a{text-decoration:none;color:var(--deep);font-weight:600}
    .hero{display:grid;grid-template-columns:1fr 480px;gap:40px;padding:60px 6%;align-items:center}
    .hero-left h1{font-family:'Playfair Display',serif;font-size:42px;margin:0 0 12px}
    .hero-left p{color:var(--muted);line-height:1.6;margin:0 0 20px}
    .cta{display:flex;gap:12px}
    .btn{padding:12px 18px;border-radius:10px;border:0;cursor:pointer;font-weight:700}
    .btn-primary{background:linear-gradient(90deg,var(--accent),#ffbfa6);color:white}
    .btn-outline{background:transparent;border:2px solid rgba(43,43,43,0.08)}
    .hero-right{background:linear-gradient(180deg, rgba(255,255,255,0.9), rgba(255,255,255,0.6));padding:18px;border-radius:12px;box-shadow:0 10px 30px rgba(18,18,18,0.06)}
    .contact-card{display:flex;flex-direction:column;gap:10px}
    .contact-card h3{margin:0;font-size:18px}
    .contact-card a{color:var(--deep);text-decoration:none;font-weight:600}/* services */
.services{padding:40px 6%;display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:20px}
.service{background:var(--card);padding:20px;border-radius:12px;box-shadow:0 6px 18px rgba(43,43,43,0.05)}
.service h4{margin:8px 0}
.service p{color:var(--muted);font-size:14px}

/* portfolio */
.portfolio{padding:0 6% 40px}
.gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:12px}
.tile{position:relative;border-radius:10px;overflow:hidden}
.tile img{width:100%;height:220px;object-fit:cover;display:block;transition:transform .4s}
.tile:hover img{transform:scale(1.05)}
.tile .tag{position:absolute;left:12px;bottom:12px;background:var(--glass);padding:6px 10px;border-radius:8px;font-weight:600}

/* testimonials */
.testimonials{padding:30px 6%;background:linear-gradient(180deg,transparent,rgba(255,240,235,0.6));border-top:1px solid rgba(0,0,0,0.03)}
.testimonials .card{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 8px 24px rgba(43,43,43,0.05)}

/* footer */
footer{padding:30px 6%;display:flex;gap:24px;flex-wrap:wrap;align-items:flex-start}
.newsletter{flex:1;min-width:260px}
.socials{display:flex;gap:12px}

/* contact form */
form{display:grid;gap:8px}
input,textarea,select{padding:10px;border-radius:8px;border:1px solid #eee;font-size:14px}
textarea{min-height:120px;resize:vertical}

/* responsive */
@media (max-width:900px){
  .hero{grid-template-columns:1fr;gap:26px;padding:32px 6%}
  .hero-right{order:2}
}

  </style>
</head>
<body>
  <header>
    <div class="logo">
      <div class="mark">B&b</div>
      <div>
        <div style="font-size:16px">Bloom & Bliss</div>
        <div style="font-size:12px;color:var(--muted)">Wedding Decoration & Florist</div>
      </div>
    </div>
    <nav>
      <ul>
        <li><a href="#services">Services</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#testimonials">Testimonials</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>  <section class="hero">
    <div class="hero-left">
      <p style="color:var(--accent);font-weight:700;letter-spacing:1px">Bespoke • Elegant • Memorable</p>
      <h1>Create your dream wedding — floral & design services that tell your story</h1>
      <p>At Bloom & Bliss we specialise in luxury wedding styling, ceremony arches, reception centrepieces, and handcrafted bouquets. From intimate gatherings to grand celebrations — we bring emotion, texture and colour to every event.</p>
      <div class="cta">
        <button class="btn btn-primary" onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Book a consultation</button>
        <a href="#portfolio" class="btn btn-outline" style="display:inline-flex;align-items:center;gap:8px;padding:10px 14px;border-radius:10px">View portfolio</a>
      </div><div style="margin-top:22px;display:flex;gap:12px;flex-wrap:wrap">
    <div style="background:var(--card);padding:12px;border-radius:10px;box-shadow:0 6px 18px rgba(43,43,43,0.04);min-width:180px">
      <div style="font-size:12px;color:var(--muted)">Starting price</div>
      <div style="font-weight:700;font-size:18px">₹18,000</div>
    </div>
    <div style="background:var(--card);padding:12px;border-radius:10px;box-shadow:0 6px 18px rgba(43,43,43,0.04);min-width:180px">
      <div style="font-size:12px;color:var(--muted)">Service areas</div>
      <div style="font-weight:700;font-size:14px">Pune • Mumbai • Goa</div>
    </div>
  </div>
</div>

<aside class="hero-right">
  <div style="display:flex;justify-content:space-between;align-items:center">
    <div style="font-size:12px;color:var(--muted)">Quick contact</div>
    <div style="font-weight:700;color:var(--accent)">Open for bookings</div>
  </div>

  <div class="contact-card" style="margin-top:12px">
    <h3>Let's plan your day</h3>
    <a href="tel:+919876543210">📞 +91 98765 43210</a>
    <a href="mailto:hello@bloombliss.example">✉️ hello@bloombliss.example</a>
    <div style="font-size:13px;color:var(--muted);margin-top:6px">Or fill the short form to request a callback</div>

    <form id="quickForm" onsubmit="submitQuickForm(event)" style="margin-top:10px">
      <input type="text" id="qname" placeholder="Your name" required />
      <input type="tel" id="qphone" placeholder="Phone" required />
      <button class="btn btn-primary" type="submit">Request callback</button>
    </form>
  </div>

</aside>

  </section>  <section id="services" class="services">
    <div class="service">
      <h4>Ceremony Styling</h4>
      <p>Arches, aisle flowers, altar installations — custom to your theme and venue.
      </p>
    </div>
    <div class="service">
      <h4>Reception Design</h4>
      <p>Table centrepieces, lounge areas, stage styling and lighting to create a cohesive experience.</p>
    </div>
    <div class="service">
      <h4>Floristry & Bouquets</h4>
      <p>Bouquets, boutonnieres, corsages and hand-tied posies using seasonal blooms and premium foliage.</p>
    </div>
    <div class="service">
      <h4>Venue Dressing & Rentals</h4>
      <p>Furniture, drapes, props and floral backdrops. We manage sourcing and installation.</p>
    </div>
  </section>  <section id="portfolio" class="portfolio">
    <h2 style="font-family:'Playfair Display',serif;margin-bottom:14px">Portfolio</h2>
    <div class="gallery" aria-label="Gallery of past work">
      <figure class="tile"><img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Romantic arch with roses"><figcaption class="tag">Romantic Arch</figcaption></figure>
      <figure class="tile"><img src="https://images.unsplash.com/photo-1548199973-03cce0bbc87b?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Long reception table with centrepieces"><figcaption class="tag">Tablescape</figcaption></figure>
      <figure class="tile"><img src="https://images.unsplash.com/photo-1519710164239-da123dc03ef4?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Bridal bouquet"><figcaption class="tag">Bridal bouquet</figcaption></figure>
      <figure class="tile"><img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Floral chandelier"><figcaption class="tag">Installation</figcaption></figure>
    </div>
    <p style="color:var(--muted);margin-top:12px">Want to see more? We send a curated portfolio based on your venue and style — request a consultation.</p>
  </section>  <section id="testimonials" class="testimonials">
    <h3 style="margin-top:0">What couples say</h3>
    <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:12px">
      <div class="card">
        <p style="margin:0 0 8px">"Bloom & Bliss turned our venue into a dream — every detail was perfect. Guests couldn't stop talking about the flowers."</p>
        <div style="font-weight:700">— Priya & Rohit</div>
      </div>
      <div class="card">
        <p style="margin:0 0 8px">"Professional, creative and so calm on the day. The bouquet was stunning and lasted for weeks!"</p>
        <div style="font-weight:700">— Ananya</div>
      </div>
    </div>
  </section>  <section id="contact" style="padding:40px 6% 80px">
    <div style="display:grid;grid-template-columns:1fr 360px;gap:26px;align-items:start">
      <div>
        <h2 style="margin-top:0;font-family:'Playfair Display',serif">Book a consultation</h2>
        <p style="color:var(--muted)">Tell us briefly about your wedding date, venue, and style. We'll reply within 48 hours with availability and a tailored plan.</p><form id="contactForm" onsubmit="submitContactForm(event)">
      <input type="text" id="name" placeholder="Full name" required />
      <input type="email" id="email" placeholder="Email address" required />
      <input type="tel" id="phone" placeholder="Phone number" required />
      <select id="serviceType">
        <option>Full wedding styling</option>
        <option>Ceremony only</option>
        <option>Reception only</option>
        <option>Floristry (bouquets & boutonnieres)</option>
      </select>
      <textarea id="message" placeholder="Tell us about your date, venue and vision (optional)"></textarea>
      <button class="btn btn-primary" type="submit">Send request</button>
    </form>
  </div>

  <aside style="background:var(--card);padding:16px;border-radius:12px;box-shadow:0 10px 30px rgba(43,43,43,0.04)">
    <h4 style="margin-top:0">Visit / Follow</h4>
    <p style="margin:0 0 10px;color:var(--muted)">Studio: Koregaon Park, Pune</p>
    <div class="socials">
      <a href="#">Instagram</a>
      <a href="#">Facebook</a>
      <a href="#">Pinterest</a>
    </div>
    <hr style="margin:14px 0;border:none;border-top:1px solid #f0f0f0" />
    <div style="font-size:14px;color:var(--muted)">Hours: Mon–Sat 10:00 — 18:00</div>
  </aside>
</div>

  </section>  <footer>
    <div style="flex:1;min-width:220px">
      <div style="font-weight:700">Bloom & Bliss</div>
      <div style="color:var(--muted);font-size:13px">Wedding decoration • Floral design • Event styling</div>
    </div><div style="min-width:220px">
  <div style="font-weight:700">Contact</div>
  <div style="color:var(--muted);font-size:13px">hello@bloombliss.example • +91 98765 43210</div>
</div>

<div style="min-width:220px">
  <div style="font-weight:700">Quick links</div>
  <div style="color:var(--muted);font-size:13px"><a href="#portfolio">Portfolio</a> • <a href="#contact">Contact</a></div>
</div>

  </footer>  <script>
    function submitQuickForm(e){
      e.preventDefault();
      const name = document.getElementById('qname').value.trim();
      const phone = document.getElementById('qphone').value.trim();
      if(!name || !phone){alert('Please enter name and phone');return}
      alert('Thanks, ' + name + '! We will call you soon.');
      document.getElementById('quickForm').reset();
    }

    function submitContactForm(e){
      e.preventDefault();
      const name = document.getElementById('name').value.trim();
      const email = document.getElementById('email').value.trim();
      if(!name || !email){alert('Please provide your name and email');return}
      // This demo doesn't actually send email. Replace with your form backend.
      alert('Thanks ' + name + '! Your request has been received. We will email you shortly.');
      document.getElementById('contactForm').reset();
    }

    // Small accessibility enhancement: keyboard focus for tiles
    document.querySelectorAll('.tile').forEach(t => t.setAttribute('tabindex', '0'));
  </script></body>
</html>
