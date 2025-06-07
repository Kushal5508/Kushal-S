<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tanzenite Real Estate</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
    }
    body {
      background-color: #f8f9fa;
      color: #333;
      line-height: 1.6;
    }
    header {
      background-color: #e9ecef;
      padding: 1rem 2rem;
      text-align: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    header h1 {
      color: #2c3e50;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background-color: #dee2e6;
      padding: 0.5rem 0;
    }
    nav a {
      color: #2c3e50;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 2rem;
    }
    .hero {
      text-align: center;
      padding: 4rem 2rem;
      background-color: #f1f3f5;
    }
    .hero h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    .hero p {
      max-width: 600px;
      margin: auto;
    }
    .sites {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
      margin-top: 2rem;
    }
    .site-card {
      background: white;
      padding: 1rem;
      border: 1px solid #ced4da;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }
    footer {
      background-color: #dee2e6;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Tanzenite Real Estate</h1>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#sites">Sites</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home" class="hero">
    <h2>Welcome to Tanzenite</h2>
    <p>Your trusted partner in buying and selling premium plots with transparency and professionalism.</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>Tanzenite is a real estate company committed to helping individuals and families find the perfect piece of land. We specialize in verified plots and transparent transactions for both buyers and sellers.</p>
  </section>

  <section id="sites">
    <h2>Available Sites</h2>
    <div class="sites">
      <div class="site-card">
        <h3>Plot A - Bangalore</h3>
        <p>1200 sqft, near Electronic City. Price: ₹45 Lakhs</p>
      </div>
      <div class="site-card">
        <h3>Plot B - Mysore</h3>
        <p>1500 sqft, ring road facing. Price: ₹38 Lakhs</p>
      </div>
      <div class="site-card">
        <h3>Plot C - Hyderabad</h3>
        <p>2000 sqft, Gated community. Price: ₹65 Lakhs</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: contact@tanzenite.in</p>
    <p>Phone: +91 98765 43210</p>
    <p>Address: 123 Real Estate Lane, Bengaluru, India</p>
  </section>

  <footer>
    &copy; 2025 Tanzenite Real Estate. All rights reserved.
  </footer>
</body>
</html>
