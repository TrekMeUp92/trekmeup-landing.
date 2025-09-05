# trekmeup-landing.
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Track Me Up - Simone Roselli</title>
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Arial', sans-serif;
    }

    body {
      color: #fff;
      background: #000;
      scroll-behavior: smooth;
    }

    section {
      padding: 80px 20px;
      text-align: center;
    }

    h1, h2, h3 {
      margin-bottom: 20px;
    }

    p {
      margin-bottom: 15px;
      font-size: 1.1em;
      line-height: 1.5em;
    }

    .btn {
      display: inline-block;
      margin: 10px;
      padding: 12px 25px;
      border-radius: 25px;
      background: #ff6600;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      background: #e65500;
    }

    /* Hero */
    .hero {
      height: 100vh;
      background: url('mountain.jpg') center/cover no-repeat;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-shadow: 0 2px 5px rgba(0,0,0,0.7);
      padding: 20px;
      text-align: center;
    }

    .hero img {
      max-width: 200px;
      margin-bottom: 20px;
    }

    .hero h1 {
      font-size: 1.8em;
    }

    /* About */
    .about {
      background: #111;
    }

    /* Services */
    .services {
      background: #1a1a1a;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .service {
      padding: 20px;
      border: 1px solid #333;
      border-radius: 15px;
      background: #222;
    }

    .service h3 {
      margin-top: 10px;
    }

    /* Certifications */
    .certs {
      background: #111;
    }

    .certs img {
      height: 70px;
      margin: 10px;
      max-width: 100%;
    }

    /* Contacts */
    .contacts {
      background: #ff6600;
      color: #fff;
    }

    .contacts a {
      display: block;
      margin: 10px 0;
      color: #fff;
      text-decoration: none;
      font-size: 1.1em;
    }

    .contacts a:hover {
      text-decoration: underline;
    }

    .qr {
      margin-top: 20px;
    }

    .qr img {
      width: 140px;
      max-width: 80%;
    }

    /* Footer */
    footer {
      background: #000;
      padding: 15px;
      font-size: 0.9em;
      text-align: center;
      color: #888;
    }

    /* Responsive tweaks */
    @media (max-width: 768px) {
      .hero h1 {
        font-size: 1.4em;
      }

      .btn {
        padding: 10px 20px;
        font-size: 0.9em;
      }

      section {
        padding: 60px 15px;
      }

      .certs img {
        height: 60px;
      }
    }

    @media (max-width: 480px) {
      .hero img {
        max-width: 150px;
      }

      .hero h1 {
        font-size: 1.2em;
      }

      p {
        font-size: 1em;
      }

      .contacts a {
        font-size: 1em;
      }

      .qr img {
        width: 120px;
      }
    }
  </style>
</head>
<body>

  <!-- HERO -->
  <section class="hero">
    <img src="logo.png" alt="Track Me Up Logo" />
    <h1>Il viaggio è appena iniziato…<br><small><em>The journey has just begun…</em></small></h1>
    <a href="#contacts" class="btn">Contattami / Contact me</a>
    <a href="https://instagram.com/simone.r.92" class="btn" target="_blank">Seguimi / Follow me</a>
  </section>

  <!-- ABOUT -->
  <section class="about" id="about">
    <h2>Chi Sono / About</h2>
    <p>🇮🇹 Mi chiamo <strong>Simone Roselli</strong>, Guida E-Bike e futuro Accompagnatore di Media Montagna.<br>
       🇬🇧 I’m <strong>Simone Roselli</strong>, E-Bike Guide and future Mountain Leader.</p>
  </section>

  <!-- SERVICES -->
  <section class="services" id="services">
    <div class="service">
      🚵‍♂️ <h3>Escursioni in E-Bike<br><small>E-Bike Tours</small></h3>
    </div>
    <div class="service">
      🥾 <h3>Trekking e Outdoor<br><small>Hiking & Outdoor</small></h3>
    </div>
    <div class="service">
      🌍 <h3>Esperienze su misura<br><small>Tailored Adventures</small></h3>
    </div>
  </section>

  <!-- CERTIFICATIONS -->
  <section class="certs" id="certs">
    <h2>Certificazioni / Certifications</h2>
    <p>🇮🇹 Formazione certificata per garantire esperienze sicure e professionali.<br>
       🇬🇧 Certified training to ensure safe and professional experiences.</p>
    <div>
      <img src="logo_guide_alpine.png" alt="Guide Alpine Lombardia" />
      <img src="logo_seib.png" alt="SEIB" />
      <img src="logo_uimla.png" alt="UIMLA" />
    </div>
  </section>

  <!-- CONTACTS -->
  <section class="contacts" id="contacts">
    <h2>Contatti / Contacts</h2>
    <a href="mailto:simoneroselli92@gmail.com">📧 simoneroselli92@gmail.com</a>
    <a href="https://instagram.com/simone.r.92" target="_blank">📷 Instagram: @simone.r.92</a>
    <a href="https://t.me/TrekMeUp" target="_blank">💬 Telegram: @TrekMeUp</a>
    <div class="qr">
      <img src="qrcode.png" alt="QR Code" />
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    © 2025 Track Me Up – Tutti i diritti riservati / All rights reserved
  </footer>

</body>
</html>
