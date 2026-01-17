<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mój Sklep</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
    }
    header {
      background: #111827;
      color: white;
      padding: 24px 16px 12px;
      text-align: center;
    }

    .logo {
      font-size: 28px;
      font-weight: bold;
      margin-bottom: 12px;
    }

    nav {
      background: #1f2933;
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 48px;
      padding: 12px 0;
    }

    nav a {
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-decoration: none;
    }

    nav img {
      height: 48px;
      object-fit: contain;
    }

    nav a:hover {
      opacity: 0.8;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 24px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 24px;
    }

    .product {
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.08);
      padding: 16px;
      display: flex;
      flex-direction: column;
    }

    .product img {
      width: 100%;
      border-radius: 8px;
      object-fit: cover;
    }

    .product h3 {
      margin: 12px 0 8px;
    }

    .price {
      font-weight: bold;
      margin-bottom: 12px;
    }

    button {
      margin-top: auto;
      padding: 10px;
      border: none;
      border-radius: 8px;
      background: #2563eb;
      color: white;
      cursor: pointer;
      font-size: 14px;
    }

    button:hover {
      background: #1d4ed8;
    }

    footer {
      text-align: center;
      padding: 16px;
      background: #e5e7eb;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">LOGO SKLEPU</div>
  </header>

  <nav>
    <a href="#">
      <img src="mini-gt.jpeg" alt="Mini GT" />
    </a>
    <a href="#">
      <img src="hot-wheels.jpeg" alt="Hot Wheels" />
    </a>
    <a href="#">Koszyk</a>
  </nav>

  <main class="container">
    <h2>Nasze produkty</h2>

    <section class="products">
      <div class="product">
        <img src="https://via.placeholder.com/300x200" alt="Produkt 1" />
        <h3>Produkt 1</h3>
        <p class="price">99,99 zł</p>
        <button>Dodaj do koszyka</button>
      </div>

      <div class="product">
        <img src="https://via.placeholder.com/300x200" alt="Produkt 2" />
        <h3>Produkt 2</h3>
        <p class="price">149,99 zł</p>
        <button>Dodaj do koszyka</button>
      </div>

      <div class="product">
        <img src="https://via.placeholder.com/300x200" alt="Produkt 3" />
        <h3>Produkt 3</h3>
        <p class="price">79,99 zł</p>
        <button>Dodaj do koszyka</button>
      </div>
    </section>
  </main>

  <footer>
    © 2026 Mój Sklep. Wszelkie prawa zastrzeżone.
  </footer>
</body>
</html>
