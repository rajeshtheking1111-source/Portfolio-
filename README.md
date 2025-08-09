<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>ACT Fiber Net — Chennai | Unlimited Fiber Broadband</title>
  <style>
    :root{--accent:#1066d1;--bg:#f7f9fc;--card:#ffffff;--text:#111827}
    *{box-sizing:border-box}
    body{margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;background:var(--bg);color:var(--text);line-height:1.4}
    header{background:linear-gradient(180deg,var(--card),var(--bg));padding:28px 16px;display:flex;align-items:center;justify-content:space-between;gap:12px}
    .brand{display:flex;flex-direction:column}
    .brand h1{margin:0;font-size:20px}
    .brand p{margin:4px 0 0;font-size:13px;color:#444}
    .cta{display:flex;gap:8px;align-items:center}
    .button{background:var(--accent);color:#fff;padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:600}
    main{max-width:900px;margin:22px auto;padding:0 16px}
    .hero{display:grid;grid-template-columns:1fr;gap:18px;align-items:center}
    .card{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(16,102,209,0.06)}
    h2{margin:0 0 8px;font-size:20px}
    p.lead{margin:0 0 12px;color:#334155}
    .features{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:12px;margin-top:12px}
    .feature{padding:12px;border-radius:10px;border:1px solid #eef2f7;background:linear-gradient(180deg,#fff,#fbfdff)}
    footer{max-width:900px;margin:18px auto 40px;padding:0 16px;color:#445; font-size:14px}
    .contact-row{display:flex;flex-wrap:wrap;gap:12px}
    .small{font-size:13px;color:#556}
    @media(min-width:720px){
      .hero{grid-template-columns:1fr 360px}
      .brand h1{font-size:22px}
    }
    /* simple form styles */
    form input, form textarea{width:100%;padding:10px;margin-top:8px;border:1px solid #e6eef8;border-radius:8px;font-size:14px}
    form button{margin-top:10px}
  </style>
</head>
<body>

<header>
  <div class="brand">
    <h1>ACT Fiber Net — Chennai</h1>
    <p>Unlimited Fiber Broadband • Fast install • Local support</p>
  </div>

  <div class="cta">
    <a class="button" href="tel:9600643059">Call Now: 9600643059</a>
    <a class="button" href="#contact" style="background:#0ea5a4">Get Quote</a>
  </div>
</header>

<main>
  <section class="hero">
    <div class="card">
      <h2>Fast, Unlimited Fiber Internet — Chennai</h2>
      <p class="lead">Reliable high-speed fiber plans for home & small business. Easy installation, 24/7 local support, and no hidden charges.</p>

      <div class="features">
        <div class="feature">
          <strong>Unlimited Data</strong><div class="small">No FUP for most plans</div>
        </div>
        <div class="feature">
          <strong>High Speeds</strong><div class="small">Up to 1 Gbps plans available</div>
        </div>
        <div class="feature">
          <strong>Fast Install</strong><div class="small">Schedule within days</div>
        </div>
        <div class="feature">
          <strong>Local Support</strong><div class="small">Chennai-based team</div>
        </div>
      </div>

      <p style="margin-top:14px">Want best price for your address? Click <a href="#contact">Get Quote</a> or call <a href="tel:9600643059">9600643059</a>.</p>
    </div>

    <aside class="card">
      <h2>Get a Free Quote</h2>
      <form id="leadForm" action="mailto:info@example.com" method="post" enctype="text/plain" onsubmit="setTimeout(()=>alert('This will open your email client. Or use the call button.'),100)">
        <label class="small">Name</label>
        <input type="text" name="Name" placeholder="Your name" required>
        <label class="small">Phone</label>
        <input type="tel" name="Phone" placeholder="9600xxxxxx" required>
        <label class="small">Address / Area</label>
        <input type="text" name="Address" placeholder="Eg: Velachery, Chennai" required>
        <label class="small">Message</label>
        <textarea name="Message" rows="3" placeholder="Any preferences (plan, speed)"></textarea>
        <button class="button" type="submit">Send Request</button>
      </form>

      <div style="margin-top:12px;font-size:13px;color:#475569">
        Or call: <a href="tel:9600643059">9600643059</a><br>
        Email: <a href="mailto:info@example.com">info@example.com</a>
      </div>
    </aside>
  </section>
</main>

<footer>
  <div class="card" id="contact">
    <strong>ACT Fiber Net — Chennai</strong>
    <div class="contact-row" style="margin-top:8px">
      <div>Phone: <a href="tel:9600643059">9600643059</a></div>
      <div style="margin-left:auto" class="small">© <span id="year"></span> ACT Fiber Net — All rights reserved</div>
    </div>
  </div>
</footer>

<script>
  document.getElementById('year').textContent = new Date().getFullYear();
</script>

</body>
</html>
