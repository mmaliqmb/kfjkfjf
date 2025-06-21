# <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lümea Skincare</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fffdfb;
      color: #2a2a2a;
    }

    header {
      background-color: #f2f2f2;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3em;
      margin: 0;
      color: #2d6cdf;
      letter-spacing: 1px;
    }

    header p {
      font-size: 1.2em;
      color: #555;
    }

    nav {
      background-color: #ffffff;
      border-bottom: 1px solid #eee;
      padding: 10px 20px;
      display: flex;
      justify-content: center;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #2d6cdf;
      font-weight: 500;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 60px 20px;
      max-width: 800px;
      margin: auto;
      text-align: center;
    }

    .button {
      display: inline-block;
      padding: 12px 24px;
      margin-top: 20px;
      background-color: #2d6cdf;
      color: #fff;
      text-decoration: none;
      border-radius: 6px;
      font-size: 16px;
    }

    footer {
      background-color: #f8f8f8;
      text-align: center;
      padding: 20px;
      font-size: 14px;
      color: #999;
    }

    .highlight {
      font-weight: bold;
      color: #2d6cdf;
    }
  </style>
</head>
<body>

  <header>
    <h1>Lümea Skincare</h1>
    <p>Natural. Radiant. SPF-protected beauty, every day.</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Lümea</h2>
    <p>
      Lümea is a UK-based skincare brand created for everyday glow. Our mission is to deliver <span class="highlight">simple, clean, and protective skincare</span> for all skin tones – powered by nature and backed by science.
    </p>
  </section>

  <section id="products">
    <h2>Our Products</h2>
    <p>Launching soon: Lip Balm with SPF 30 • Body Butter • Mini Glow Kits</p>
    <a href="#" class="button">Join Waitlist</a>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Questions? Partnerships? Email us at <a href="mailto:hello@lumeaskin.co.uk">hello@lumeaskin.co.uk</a></p>
  </section>

  <footer>
    &copy; 2025 Lümea Skincare. All rights reserved.
  </footer>

</body>
</html>
