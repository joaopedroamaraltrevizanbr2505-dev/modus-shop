<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MODUS - Loja de Roupas Roblox</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #121212;
      color: #fff;
    }

    header {
      background-color: #1f1f1f;
      padding: 20px;
      text-align: center;
      font-size: 2rem;
      font-weight: bold;
      letter-spacing: 2px;
    }

    main {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .product {
      background-color: #1e1e1e;
      border-radius: 12px;
      overflow: hidden;
      text-align: center;
      transition: transform 0.3s;
    }

    .product:hover {
      transform: scale(1.05);
    }

    .product img {
      width: 100%;
      display: block;
    }

    .product h2 {
      font-size: 1.2rem;
      margin: 10px 0 5px;
    }

    .product a {
      color: #00bfff;
      text-decoration: none;
      font-weight: bold;
      display: inline-block;
      margin-bottom: 10px;
    }

    footer {
      background-color: #1f1f1f;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>MODUS</header>

  <main>
    <div class="product">
      <img src="https://www.roblox.com/catalog/13622591782/ushanka-black-fur-shirt" alt="Ushanka Black Fur Shirt">
      <h2>Ushanka Black Fur Shirt</h2>
      <a href="https://www.roblox.com/catalog/13622591782/ushanka-black-fur-shirt" target="_blank">Comprar</a>
    </div>

    <div class="product">
      <img src="https://www.roblox.com/catalog/13329790319/Cute-baby-blue-shirt" alt="Cute Baby Blue Shirt">
      <h2>Cute Baby Blue Shirt</h2>
      <a href="https://www.roblox.com/catalog/13329790319/Cute-baby-blue-shirt" target="_blank">Comprar</a>
    </div>
  </main>

  <footer>
    Siga nosso Instagram: <a href="https://www.instagram.com/shop.modus/" target="_blank">@shop.modus</a>
  </footer>
</body>
</html>
