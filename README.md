<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ofertas Top do Dia</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f3f3f3;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #222;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      padding: 30px;
    }
    .card {
      background: #fff;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    .card:hover {
      transform: scale(1.02);
    }
    .card img {
      max-width: 100%;
      border-radius: 8px;
    }
    .card h3 {
      margin: 10px 0;
    }
    .button {
      display: inline-block;
      padding: 10px 16px;
      background-color: #ff5a00;
      color: #fff;
      text-decoration: none;
      border-radius: 6px;
      margin-top: 10px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>🔥 Ofertas Top do Dia</h1>
    <p>Promoções com links exclusivos – não perca!</p>
  </header>

  <div class="container">
    <div class="card">
      <img src="https://via.placeholder.com/300x200?text=Produto+1" alt="Produto 1">
      <h3>Produto Incrível 1</h3>
      <p>Descrição rápida e objetiva sobre o produto. Preço promocional!</p>
      <a class="button" href="https://seulinkdeafiliado.com/produto1" target="_blank">Ver Oferta</a>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/300x200?text=Produto+2" alt="Produto 2">
      <h3>Produto Incrível 2</h3>
      <p>Produto muito bem avaliado e com frete grátis. Aproveite!</p>
      <a class="button" href="https://seulinkdeafiliado.com/produto2" target="_blank">Ver Oferta</a>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/300x200?text=Produto+3" alt="Produto 3">
      <h3>Produto Incrível 3</h3>
      <p>Top vendas da Shopee. Ideal para o dia a dia e com super desconto.</p>
      <a class="button" href="https://seulinkdeafiliado.com/produto3" target="_blank">Ver Oferta</a>
    </div>
  </div>
</body>
</html>
