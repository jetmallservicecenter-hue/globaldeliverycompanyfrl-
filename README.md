<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Global Delivery Company | Fast & Reliable Logistics</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #f5f7fa;
      color: #333;
    }
    header {
      background: #0b3c5d;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    nav {
      background: #06283d;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      background: linear-gradient(rgba(11,60,93,0.8), rgba(11,60,93,0.8)), url('https://images.unsplash.com/photo-1601584115197-04ecc0da31d7');
      background-size: cover;
      background-position: center;
      color: #fff;
      padding: 80px 20px;
      text-align: center;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.1rem;
      margin-bottom: 20px;
    }
    .hero button {
      padding: 15px 30px;
      font-size: 1rem;
      background: #ff9800;
      border: none;
      cursor: pointer;
      border-radius: 5px;
    }
    .hero button:hover {
      background: #e68900;
    }
    section {
      padding: 50px 20px;
      max-width: 1100px;
      margin: auto;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .card h3 {
      margin-top: 0;
      color: #0b3c5d;
    }
    .booking-form {
      background: #fff;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      max-width: 700px;
      margin: auto;
    }
    .booking-form h2 {
      text-align: center;
      color: #0b3c5d;
    }
    .booking-form label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }
    .booking-form input,
    .booking-form select,
    .booking-form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    .booking-form button {
      margin-top: 20px;
      width: 100%;
      padding: 15px;
      font-size: 1rem;
      background: #0b3c5d;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .booking-form button:hover {
      background: #06283d;
    }
    footer {
      background: #06283d;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
    }
  </style>
</head>
<body><header>
  <h1>Global Delivery Company</h1>
  <p>Worldwide Shipping • Fast • Secure • Reliable</p>
</header><nav>
  <a href="#services">Services</a>
  <a href="#booking">Book Delivery</a>
  <a href="#track">Track Order</a>
  <a href="#about">About Us</a>
  <a href="#contact">Contact</a>
</nav><div class="hero">
  <h2>Your Package, Delivered Anywhere</h2>
  <p>We handle local and international deliveries with speed and care.</p>
  <button onclick="document.getElementById('booking').scrollIntoView({behavior:'smooth'})">Book Now</button>
</div><section id="services">
  <h2>Our Services</h2>
  <div class="services">
    <div class="card">
      <h3>Local Delivery</h3>
      <p>Same-day and next-day delivery within cities and states.</p>
    </div>
    <div class="card">
      <h3>International Shipping</h3>
      <p>Secure global delivery to over 200 countries worldwide.</p>
    </div>
    <div class="card">
      <h3>Express Courier</h3>
      <p>Fast-track delivery for urgent and high-value items.</p>
    </div>
    <div class="card">
      <h3>Business Logistics</h3>
      <p>Custom logistics solutions for companies and online stores.</p>
    </div>
  </div>
</section><section id="booking">
  <div class="booking-form">
    <h2>Book a Delivery</h2>
    <form action="mailto:globaldeliverycompany542@gmail.com" method="post" enctype="text/plain">
      <label>Sender Name</label>
      <input type="text" name="Sender Name" placeholder="Your full name" required /><label>Sender Phone / WhatsApp</label>
  <input type="tel" name="Sender Phone" placeholder="Phone or WhatsApp number" required />

  <label>Pickup Address</label>
  <textarea name="Pickup Address" placeholder="Pickup location" required></textarea>

  <label>Delivery Address</label>
  <textarea name="Delivery Address" placeholder="Delivery location" required></textarea>

  <label>Package Type</label>
  <select name="Package Type" required>
    <option value="">Select package type</option>
    <option>Documents</option>
    <option>Electronics</option>
    <option>Clothing</option>
    <option>Food Items</option>
    <option>Other</option>
  </select>

  <label>Delivery Option</label>
  <select name="Delivery Speed" required>
    <option value="">Select delivery speed</option>
    <option>Standard</option>
    <option>Express</option>
  </select>

  <button type="submit">Submit Booking</button>
</form>
<p style="text-align:center; font-size:0.9rem; margin-top:10px;">After submission, our team will contact you immediately.</p>

  </div>
</section><section id="track">
  <div class="booking-form">
    <h2>Track Your Delivery</h2>
    <p style="text-align:center">Enter your tracking number to check delivery status.</p>
    <input type="text" placeholder="e.g. GDC-123456" />
    <button style="margin-top:15px">Check Status</button>
    <p style="text-align:center; font-size:0.85rem; margin-top:10px;">Tracking updates will be confirmed by our support team.</p>
  </div>
</section><section id="about">
  <h2>About Global Delivery Company</h2>
  <p>
    Global Delivery Company is a trusted logistics and courier service provider dedicated to
    fast, safe, and affordable deliveries. We serve individuals and businesses with modern
    delivery solutions tailored to your needs.
  </p>
</section><section id="contact">
  <h2>Contact Us</h2>
  <p>Email: globaldeliverycompany542@gmail.com</p>
  <p>Phone: +234 XXX XXX XXXX</p>
  <p>Office Hours: Monday – Saturday, 8am – 6pm</p>
</section><footer>
  <p>© 2026 Global Delivery Company. All Rights Reserved.</p>
</footer></body>
</html>
