<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Indra Estate — Real Estate</title>
  <meta name="description" content="Indra Estate — Real Estate, Farmhouses, Plots. Contact: +91-9310113616" />
  <style>
    :root{--accent:#b8860b;--dark:#111;--muted:#666}
    *{box-sizing:border-box}
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;margin:0;color:var(--dark);line-height:1.5}
    header{background:linear-gradient(90deg,rgba(184,134,11,.08),transparent);padding:28px 16px}
    .container{max-width:960px;margin:0 auto;padding:16px}
    nav{display:flex;justify-content:space-between;align-items:center;gap:12px}
    .brand{font-weight:700;font-size:20px;color:var(--accent)}
    .hero{display:grid;grid-template-columns:1fr;gap:18px;align-items:center;padding:28px 0}
    h1{margin:.2rem 0;font-size:28px}
    p.lead{color:var(--muted);margin:0 0 12px}
    .cta{display:inline-block;background:var(--accent);color:white;padding:10px 16px;border-radius:8px;text-decoration:none}
    .cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px;margin:20px 0}
    .card{padding:14px;border-radius:10px;border:1px solid #eee;background:#fff;box-shadow:0 6px 18px rgba(0,0,0,.03)}
    footer{border-top:1px solid #eee;padding:18px 0;margin-top:22px;color:var(--muted)}
    .contact{display:flex;flex-direction:column;gap:8px}
    @media(min-width:700px){ .hero{grid-template-columns:1fr 360px} h1{font-size:34px} }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <nav>
        <div class="brand">Indra Estate</div>
        <div class="navlinks" aria-hidden="true">Gurgaon • Sohna • Madhya Pradesh</div>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div>
        <h1>We build luxury homes & plots — Indra Estate</h1>
        <p class="lead">Modern farmhouses, plotted developments and trustworthy construction services. Trusted in Gurgaon, Sohna & Madhya Pradesh.</p>
        <a class="cta" href="#contact">Get in touch</a>
        <div class="cards" aria-hidden="false">
          <div class="card"><strong>Plots & Land</strong><div style="color:var(--muted)">Buy/sell and development support</div></div>
          <div class="card"><strong>Farmhouses</strong><div style="color:var(--muted)">Luxury and fully-serviced designs</div></div>
          <div class="card"><strong>Construction</strong><div style="color:var(--muted)">Project planning to handover</div></div>
        </div>
      </div>

      <aside style="padding:18px;border-radius:10px;border:1px solid #f0e6d0;background:#fff8e6">
        <strong>Contact</strong>
        <div class="contact">
          <div>Phone: <a href="tel:+919310113616">+91-9310113616</a></div>
          <div>Email: <a href="mailto:indraestateofindia@gmail.com">indraestateofindia@gmail.com</a></div>
          <div>Location: Gurgaon | Sohna | Madhya Pradesh</div>
        </div>
      </aside>
    </section>

    <section>
      <h2>Why choose us</h2>
      <ul>
        <li>Transparent pricing & clear documentation</li>
        <li>Experienced local team for approvals & construction</li>
        <li>Post-sale support and site visits</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Send a message</h2>
      <form onsubmit="alert('Thanks — form would be sent to email in production.'); return false;">
        <div style="display:grid;gap:8px;max-width:520px">
          <input name="name" placeholder="Your name" style="padding:10px;border:1px solid #ddd;border-radius:6px" required>
          <input name="email" placeholder="Your email" style="padding:10px;border:1px solid #ddd;border-radius:6px" required>
          <textarea name="msg" placeholder="Message" rows="4" style="padding:10px;border:1px solid #ddd;border-radius:6px" required></textarea>
          <button class="cta" type="submit" style="border:none">Send message</button>
        </div>
      </form>
    </section>

    <footer>
      <div>© <span id="year"></span> Indra Estate — Real Estate • Phone: <a href="tel:+919310113616">+91-9310113616</a></div>
    </footer>
  </main>

  <script>document.getElementById('year').textContent=new Date().getFullYear();</script>
</body>
</html><img width="1024" height="1024" alt="1000044638" src="https://github.com/user-attachments/assets/538bc11b-b870-4faa-be03-8192f35d5308" />
