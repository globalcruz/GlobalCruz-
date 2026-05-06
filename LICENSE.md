<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Global Cruz</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background: #0a0a0a; color: #fff; }
    header { display: flex; justify-content: space-between; align-items: center; padding: 20px; background: #000; }
    header h1 { margin: 0; font-size: 24px; }
    nav a { margin: 0 10px; color: #fff; text-decoration: none; }
    .hero { text-align: center; padding: 80px 20px; background: linear-gradient(to right, #000, #111); }
    .hero h2 { font-size: 40px; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; padding: 40px; }
    .product { background: #111; padding: 20px; border-radius: 10px; text-align: center; }
    .product img { width: 100%; border-radius: 10px; }
    .product button { margin-top: 10px; padding: 10px; background: #fff; border: none; cursor: pointer; }
    footer { text-align: center; padding: 20px; background: #000; }
  </style>
</head>
<body><header>
  <h1>Global Cruz</h1>
  <nav>
    <a href="#">Início</a>
    <a href="#produtos">Produtos</a>
    <a href="#contato">Contato</a>
  </nav>
</header><section class="hero">
  <h2>Bem-vindo à Global Cruz</h2>
  <p>Estilo, atitude e identidade em cada peça.</p>
</section><section id="produtos" class="products">
  <div class="product">
    <img src="https://via.placeholder.com/300" alt="Camiseta">
    <h3>Camiseta Street</h3>
    <p>R$ 89,90</p>
    <button onclick="addToCart('Camiseta Street')">Comprar</button>
  </div>
  <div class="product">
    <img src="https://via.placeholder.com/300" alt="Moletom">
    <h3>Moletom Premium</h3>
    <p>R$ 199,90</p>
    <button onclick="addToCart('Moletom Premium')">Comprar</button>
  </div>
  <div class="product">
    <img src="https://via.placeholder.com/300" alt="Boné">
    <h3>Boné Cruz</h3>
    <p>R$ 59,90</p>
    <button onclick="addToCart('Boné Cruz')">Comprar</button>
  </div>
</section><section id="contato" style="padding:40px; text-align:center;">
  <h2>Contato</h2>
  <p>Email: contato@globalcruzworld.com</p>
  <p>Instagram: @globalcruzz</p>
</section><footer>
  <p>© 2026 Global Cruz - Todos os direitos reservados</p>
</footer><script>
  function addToCart(product) {
    alert(product + ' adicionado ao carrinho!');
  }
</script></body>
</html>
