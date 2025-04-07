<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Saurav | AI & Web Services</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f5f5f5;
      color: #222;
    }
    header {
      background-color: #1a1a2e;
      padding: 1rem;
      color: white;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #0f3460;
    }
    nav a {
      color: white;
      padding: 1rem;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #533483;
    }
    .hero {
      background: linear-gradient(to right, #0f0c29, #302b63, #24243e);
      color: white;
      text-align: center;
      padding: 3rem 1rem;
    }
    .section {
      padding: 2rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    .service-card {
      background-color: white;
      margin: 1rem 0;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .pricing {
      display: flex;
      gap: 1rem;
      margin-top: 1rem;
    }
    .price-box {
      background-color: #eaeaea;
      padding: 1rem;
      border-radius: 6px;
      flex: 1;
      text-align: center;
    }
    button {
      padding: 0.7rem 1.5rem;
      background-color: #533483;
      color: white;
      border: none;
      border-radius: 5px;
      margin-top: 1rem;
      cursor: pointer;
    }
    button:hover {
      background-color: #372054;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #0f3460;
      color: white;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Welcome to Saurav's Web & AI Services</h1>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#services">Services</a>
  <a href="#about">About</a>
  <a href="#care">Customer Care</a>
</nav>

<div id="home" class="hero">
  <h2>Your One-Stop Solution for Website, App & AI Development</h2>
  <p>We provide top-class professional services to build your online business.</p>
</div>

<section id="services" class="section">
  <h2>Our Services</h2>

  <div class="service-card">
    <h3>Website Development</h3>
    <p>Custom business websites with beautiful UI/UX design and responsive layout.</p>
    <div class="pricing">
      <div class="price-box">
        <h4>Basic - ₹999</h4>
        <p>1 Page Static Website</p>
      </div>
      <div class="price-box">
        <h4>Medium - ₹1999</h4>
        <p>Multi-page Business Website</p>
      </div>
      <div class="price-box">
        <h4>Advance - ₹2999</h4>
        <p>Dynamic Website with Admin Panel</p>
      </div>
    </div>
    <button onclick="bookNow()">Book Now</button>
  </div>

  <div class="service-card">
    <h3>App Development</h3>
    <p>Custom Android/iOS mobile apps tailored to your business needs.</p>
    <div class="pricing">
      <div class="price-box">
        <h4>Basic - ₹1499</h4>
        <p>Single screen app (Static)</p>
      </div>
      <div class="price-box">
        <h4>Medium - ₹2999</h4>
        <p>Basic CRUD app</p>
      </div>
      <div class="price-box">
        <h4>Advance - ₹4999</h4>
        <p>Fully dynamic app with backend</p>
      </div>
    </div>
    <button onclick="bookNow()">Book Now</button>
  </div>

  <div class="service-card">
    <h3>AI Tools Development</h3>
    <p>Custom AI tools using OpenAI, ChatGPT API, and automation solutions.</p>
    <div class="pricing">
      <div class="price-box">
        <h4>Basic - ₹1999</h4>
        <p>Simple ChatBot</p>
      </div>
      <div class="price-box">
        <h4>Medium - ₹3999</h4>
        <p>Text generation or automation tools</p>
      </div>
      <div class="price-box">
        <h4>Advance - ₹7999</h4>
        <p>Full SaaS AI Product</p>
      </div>
    </div>
    <button onclick="bookNow()">Book Now</button>
  </div>

</section>

<section id="about" class="section">
  <h2>About Me</h2>
  <p>
    I'm Saurav Paswan, a passionate developer who helps businesses grow online. I specialize in website development, mobile apps, custom AI tools, and automation services. With over 3 years of experience and working on multiple successful projects, I offer reliable and affordable services that meet client expectations.
    <br/><br/>
    Contact Number: <strong>+91 7559347682</strong><br/>
    Email: <strong>sauravpaswann@gmail.com</strong><br/>
    I'm always available for support, discussion, or project planning. Let’s build something great together!
  </p>
</section>

<section id="care" class="section">
  <h2>Customer Support</h2>
  <p>Facing an issue or want to talk directly? Message me on WhatsApp.</p>
  <button onclick="window.open('https://wa.me/917559347682', '_blank')">Chat on WhatsApp</button>
</section>

<footer>
  &copy; 2025 Saurav's Web & AI Services | All Rights Reserved
</footer>

<script>
  function bookNow() {
    window.open("https://forms.gle/ZBsPo6Jr85MzrW8x9", "_blank");
  }
</script>

</body>
</html>
