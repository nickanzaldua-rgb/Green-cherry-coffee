# Green-cherry-coffee<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title> Green Cherry Coffee</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #faf8f4;
      color: #3b2e2a;
    }

    header {
      background-color: #3b2e2a;
      color: #f5e8d0;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-family: 'Georgia', serif;
      letter-spacing: 2px;
      font-size: 1.8em;
    }

    nav a {
      color: #f5e8d0;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 500;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      background-image: url('https://images.unsplash.com/photo-1510626176961-4b37d0c9b11b?auto=format&fit=crop&w=1600&q=80');
      background-size: cover;
      background-position: center;
      color: #fff;
      text-align: center;
      padding: 160px 20px;
    }

    .hero h2 {
      font-size: 3em;
      background: rgba(0,0,0,0.6);
      display: inline-block;
      padding: 15px 30px;
      border-radius: 5px;
    }

    .section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: 0 auto;
    }

    .section h3 {
      text-align: center;
      font-size: 2em;
      margin-bottom: 20px;
    }

    .coffee-item {
      display: flex;
      align-items: center;
      justify-content: space-between;
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      margin-bottom: 20px;
    }

    .coffee-item img {
      width: 200px;
      border-radius: 10px;
      margin-right: 20px;
    }

    .coffee-info {
      flex: 1;
    }

    .coffee-info h4 {
      margin: 0;
      font-size: 1.4em;
    }

    .price {
      font-weight: bold;
      color: #7c4a2d;
      font-size: 1.2em;
    }

    button {
      background: #7c4a2d;
      color: #fff;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    button:hover {
      background: #5a3521;
    }

    footer {
      background: #3b2e2a;
      color: #f5e8d0;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Ember Roast Coffee</h1>
    <nav>
      <a href="#coffee">Our Coffee</a>
      <a href="#about">About</a>
      <a href="#shop">Shop</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h2>Fresh. Bold. Roasted with Passion.</h2>
  </div>

  <section id="coffee" class="section">
    <h3>Our Coffee</h3>
    <div class="coffee-item">
      <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93?auto=format&fit=crop&w=800&q=80" alt="House Blend Coffee">
      <div class="coffee-info">
        <h4>Signature House Roast</h4>
        <p>Rich aroma, smooth chocolate undertones, and a nutty finish. Roasted fresh weekly.</p>
        <p class="price">$20 / lb</p>
        <button>Order Now</button>
      </div>
    </div>

    <div class="coffee-item">
      <img src="https://images.unsplash.com/photo-1554118811-1e0d58224f24?auto=format&fit=crop&w=800&q=80" alt="Dark Roast">
      <div class="coffee-info">
        <h4>Dark Ember Roast</h4>
        <p>Smoky, full-bodied, and bold—crafted for those who love an intense, lingering flavor.</p>
        <p class="price">$20 / lb</p>
        <button>Order Now</button>
      </div>
    </div>
  </section>

  <section id="about" class="section">
    <h3>About Us</h3>
    <p>At Ember Roast Coffee, we believe great coffee starts with great care—from sourcing ethically grown beans to roasting each batch by hand in small quantities. Our mission is simple: deliver coffee that ignites your mornings and inspires your moments.</p>
  </section>

  <section id="shop" class="section">
    <h3>Shop Online</h3>
    <p>Coming soon! We’re perfecting our online ordering system. For now, reach out below to order your favorite roast directly.</p>
  </section>

  <section id="contact" class="section">
    <h3>Contact Us</h3>
    <p>Email: <a href="mailto:orders@emberroast.com">orders@emberroast.com</a></p>
    <p>Follow us on Instagram: <a href="#">@EmberRoastCoffee</a></p>
  </section>

  <footer>
    &copy; 2025 Ember Roast Coffee — Roasted with heart in Texas.
  </footer>
</body>
</html>
