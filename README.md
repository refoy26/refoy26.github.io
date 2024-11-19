<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Luxury Refurbished Furniture</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Open+Sans:wght@400;600&family=Lora:wght@700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <header>
    <nav>
      <div class="logo">Refurbished Luxury</div>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="products.html">Products</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
    <div class="hero">
      <h1>Transform Your Home with High-Quality Refurbished Furniture</h1>
      <p>Eco-friendly, stylish, and affordable. Redefine your space today.</p>
      <a href="products.html" class="btn">Shop Now</a>
    </div>
  </header>

  <section class="services">
    <h2>Our Promise</h2>
    <div class="service-cards">
      <div class="card">
        <h3>Eco-Friendly</h3>
        <p>We take pride in reducing waste by restoring beautiful furniture.</p>
      </div>
      <div class="card">
        <h3>High-Quality Craftsmanship</h3>
        <p>Every piece is hand-restored to look and feel brand new.</p>
      </div>
      <div class="card">
        <h3>Affordable Luxury</h3>
        <p>Get luxury without the high price tag. Quality shouldn't be expensive.</p>
      </div>
    </div>
  </section>

  <footer>
    <div class="footer-content">
      <p>&copy; 2024 Refurbished Luxury Furniture | All Rights Reserved</p>
    </div>
  </footer>
</body>
</html>
/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Global Styles */
body {
  font-family: 'Open Sans', sans-serif;
  background: linear-gradient(45deg, #66ccff, #ff99cc, #ffcc00, #ff6666); /* Multi-color gradient background */
  color: #fff;
  line-height: 1.6;
  transition: all 0.3s ease-in-out;
}

/* Logo & Navigation */
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent navbar */
  position: fixed;
  width: 100%;
  top: 0;
  z-index: 10;
}

.logo {
  font-family: 'Playfair Display', serif;
  font-size: 36px;
  color: #fff;
  text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.3);
}

nav ul {
  display: flex;
  list-style: none;
}

nav ul li {
  margin-left: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #ffffff;
  font-size: 18px;
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: 1px;
  transition: color 0.3s ease;
}

nav ul li a:hover {
  color: #ffcc00;
}

/* Hero Section */
.hero {
  text-align: center;
  padding: 150px 20px;
  background: linear-gradient(45deg, rgba(0, 128, 255, 0.7), rgba(0, 0, 128, 0.7)), url('https://via.placeholder.com/1500x800') no-repeat center center/cover;
  background-size: cover;
  color: #ffffff;
  animation: backgroundShift 8s ease-in-out infinite;
}

.hero h1 {
  font-family: 'Playfair Display', serif;
  font-size: 56px;
  color: #fff;
  text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.4);
  animation: colorShift 3s infinite alternate;
}

.hero p {
  font-size: 20px;
  margin-top: 20px;
  animation: colorShift 3s infinite alternate;
}

.hero .btn {
  padding: 15px 30px;
  background-color: #ff99cc;
  color: #fff;
  font-size: 18px;
  text-decoration: none;
  border-radius: 5px;
  margin-top: 30px;
  transition: background-color 0.3s ease, transform 0.3s ease;
}

.hero .btn:hover {
  background-color: #ff3366;
  transform: scale(1.1);
}

/* Services Section */
.services {
  text-align: center;
  padding: 100px 20px;
  background-color: #f2f2f2;
}

.services h2 {
  font-family: 'Playfair Display', serif;
  font-size: 40px;
  color: #333;
  margin-bottom: 50px;
}

.service-cards {
  display: flex;
  justify-content: space-around;
  gap: 20px;
}

.card {
  background: #ffffff;
  padding: 25px;
  border-radius: 10px;
  width: 30%;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
  transform: translateY(-10px);
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
}

.card h3 {
  font-family: 'Lora', serif;
  font-size: 26px;
  color: #ff6666;
  margin-bottom: 15px;
}

.card p {
  font-size: 18px;
  color: #333;
}

/* Footer */
footer {
  background-color: #003366;
  color: #fff;
  padding: 30px;
  text-align: center;
}

footer p {
  font-size: 16px;
  margin-top: 20px;
}

/* Text Color Shifting Animation */
@keyframes colorShift {
  0% {
    color: #ff0000;
  }
  25% {
    color: #ffcc00;
  }
  50% {
    color: #00cc66;
  }
  75% {
    color: #ff66cc;
  }
  100% {
    color: #ff0066;
  }
}

/* Background Shifting Animation */
@keyframes backgroundShift {
  0% {
    background: linear-gradient(45deg, #ffcc99, #66ccff, #ff9966);
  }
  25% {
    background: linear-gradient(45deg, #66ccff, #ffcc99, #ff6666);
  }
  50% {
    background: linear-gradient(45deg, #ff9966, #ffcc99, #66ccff);
  }
  75% {
    background: linear-gradient(45deg, #ff6666, #ff9966, #ffcc99);
  }
  100% {
    background: linear-gradient(45deg, #66ccff, #ff6666, #ffcc99);
  }
}
background: linear-gradient(45deg, #66ccff, #ff99cc, #ffcc00, #ff6666);
@keyframes backgroundShift {
  0% { background: linear-gradient(45deg, #ffcc99, #66ccff, #ff9966); }
  50% { background: linear-gradient(45deg, #ff9966, #ffcc99, #66ccff); }
}
@keyframes colorShift {
  0% { color: #ff0000; }
  25% { color: #ffcc00; }
  50% { color: #00cc66; }
  75% { color: #ff66cc; }
  100% { color: #ff0066; }
}
.hero .btn:hover {
  background-color: #ff3366;
  transform: scale(1.1);
}

.card:hover {
  transform: translateY(-10px);
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
}
position: fixed;
width: 100%;
top: 0;
z-index: 10;
