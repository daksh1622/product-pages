<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Product Landing Page</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="header">
    <nav class="navbar">
      <div class="logo">BrandLogo</div>
      <ul class="nav-links">
        <li><a href="#features">Features</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <div class="hero">
      <h1>Discover Our Amazing Product</h1>
      <p>Transform your life with our innovative solutions!</p>
      <a href="#features" class="btn">Learn More</a>
    </div>
  </header>

  <main>
    <section id="features" class="features">
      <h2>Key Features</h2>
      <div class="feature-item">
        <h3>Feature One</h3>
        <p>Brief description of the first feature.</p>
      </div>
      <div class="feature-item">
        <h3>Feature Two</h3>
        <p>Brief description of the second feature.</p>
      </div>
      <div class="feature-item">
        <h3>Feature Three</h3>
        <p>Brief description of the third feature.</p>
      </div>
    </section>

    <section id="about" class="about">
      <h2>About Us</h2>
      <p>We are a company dedicated to creating innovative products that make a difference.</p>
    </section>
  </main>

  <footer id="contact" class="footer">
    <h2>Contact Us</h2>
    <p>Email: info@brand.com</p>
    <p>Phone: +123 456 7890</p>
    <p>&copy; 2024 BrandLogo. All Rights Reserved.</p>
  </footer>
</body>
</html>

CSS Code

/* styles.css */

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
}

.header {
  background: #007bff;
  color: #fff;
  padding: 20px 0;
  text-align: center;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.logo {
  font-size: 1.5em;
  font-weight: bold;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 15px;
}

.nav-links li {
  display: inline;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
}

.hero {
  padding: 50px 20px;
}

.hero h1 {
  font-size: 2.5em;
  margin: 20px 0;
}

.hero p {
  font-size: 1.2em;
  margin-bottom: 20px;
}

.btn {
  background: #fff;
  color: #007bff;
  padding: 10px 20px;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
}

.btn:hover {
  background: #0056b3;
  color: #fff;
}

.features, .about, .footer {
  text-align: center;
  padding: 50px 20px;
}

.feature-item {
  margin: 20px 0;
}

.footer {
  background: #333;
  color: #fff;
}
