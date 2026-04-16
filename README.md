# V-R-Fruit
abou V R Fruit
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>V R Fruits</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f4fff4;
    }

    header {
      background: #2e7d32;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background: #388e3c;
      display: flex;
      justify-content: center;
      padding: 10px;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      padding: 60px 20px;
      text-align: center;
      background: linear-gradient(#c8e6c9, #e8f5e9);
    }

    .hero h1 {
      font-size: 42px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
      margin-bottom: 20px;
    }

    .btn {
      background: #2e7d32;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      text-decoration: none;
    }

    .btn:hover {
      background: #1b5e20;
    }

    .products {
      padding: 40px 20px;
      text-align: center;
    }

    .products h2 {
      margin-bottom: 20px;
    }

    .product-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    .product {
      background: white;
      margin: 15px;
      padding: 15px;
      width: 220px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .product img {
      width: 100%;
      border-radius: 10px;
    }

    footer {
      background: #2e7d32;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>

<body>

<header>
  <h1>V R Fruits</h1>
  <p>Fresh & Organic Fruits</p>
</header>

<nav>
  <a href="#">Home</a>
  <a href="#">Products</a>
  <a href="#">Contact</a>
</nav>

<section class="hero">
  <h1>Welcome to V R Fruits 🍎</h1>
  <p>We deliver fresh fruits directly to your home.</p>
  <a href="tel:+911234567890" class="btn">Call Now</a>
</section>

<section class="products">
  <h2>Our Fruits</h2>

  <div class="product-container">

    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Apple">
      <h3>Apple</h3>
      <p>Fresh & juicy apples</p>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Banana">
      <h3>Banana</h3>
      <p>Healthy and energetic</p>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Orange">
      <h3>Orange</h3>
      <p>Rich in Vitamin C</p>
    </div>

  </div>
</section>

<footer>
  <p>© 2026 V R Fruits | All Rights Reserved</p>
</footer>

</body>
</html>
