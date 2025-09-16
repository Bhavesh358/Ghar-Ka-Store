# Ghar-Ka-Store
Food's, vegitables, grocery 
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ghar Ka Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #2e7d32;
      color: white;
      padding: 15px;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background: #388e3c;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      padding: 20px;
    }
    .category {
      margin-bottom: 40px;
    }
    .category h2 {
      border-bottom: 2px solid #ccc;
      padding-bottom: 10px;
      color: #2e7d32;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .product {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
    }
    .product h3 {
      margin: 10px 0 5px;
    }
    .price {
      font-weight: bold;
      color: #388e3c;
    }
    .order-btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background: #25d366;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }
    footer {
      background: #2e7d32;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>
<body>  <header>
    <h1>🏠 Ghar Ka Store</h1>
    <p>Roz ka saman, seedha aapke ghar tak!</p>
  </header>  <nav>
    <a href="#sabzi">Sabzi</a>
    <a href="#fruits">Fruits</a>
    <a href="#grocery">Grocery</a>
    <a href="#dairy">Dairy</a>
  </nav>  <div class="container">
    <section id="sabzi" class="category">
      <h2>🥦 Sabzi</h2>
      <div class="products">
        <div class="product">
          <img src="https://images.unsplash.com/photo-1567306226416-28f0efdc88ce" alt="Tomato">
          <h3>Tomato</h3>
          <p class="price">₹40 / kg</p>
          <a class="order-btn" href="https://wa.me/918055638377?text=I%20want%20to%20order%20Tomato">Order on WhatsApp</a>
        </div>
        <div class="product">
          <img src="https://images.unsplash.com/photo-1572441710534-680c9949fdf8" alt="Potato">
          <h3>Potato</h3>
          <p class="price">₹30 / kg</p>
          <a class="order-btn" href="https://wa.me/918055638377?text=I%20want%20to%20order%20Potato">Order on WhatsApp</a>
        </div>
      </div>
    </section><section id="fruits" class="category">
  <h2>🍎 Fruits</h2>
  <div class="products">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1567306301408-9b74779a11af" alt="Apple">
      <h3>Apple</h3>
      <p class="price">₹120 / kg</p>
      <a class="order-btn" href="https://wa.me/918055638377?text=I%20want%20to%20order%20Apple">Order on WhatsApp</a>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1574226516831-e1dff420e43e" alt="Banana">
      <h3>Banana</h3>
      <p class="price">₹60 / dozen</p>
      <a class="order-btn" href="https://wa.me/918055638377?text=I%

