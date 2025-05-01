<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Criptoseve - E-books em PDF</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
    }

    header {
      background-color: #1a1a1a;
      color: white;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
    }

    nav {
      text-align: center;
      background: #333;
      padding: 10px;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .ebooks {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .ebook {
      background: white;
      border: 1px solid #ddd;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
    }

    .ebook h3 {
      margin: 10px 0;
    }

    .ebook a {
      display: inline-block;
      margin-top: 10px;
      background: #1a1a1a;
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
    }

    .purchase-buttons {
      margin-top: 15px;
    }

    .purchase-buttons a {
      display: inline-block;
      margin: 5px;
      padding: 10px 15px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }

    .pix {
      background-color: #00b894;
      color: white;
    }

    .cartao {
      background-color: #0984e3;
      color: white;
    }

    .contact {
      background: #eee;
      padding: 30px;
      text-align: center;
      border-radius: 10px;
    }

    footer {
      background-color: #1a1a1a;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Criptoseve</h1>
    <p>Seus e-books em PDF sobre criptomoedas, investimentos e mais.</p>
  </header>

  <nav>
    <a href="#ebooks">E-books</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="ebooks">
    <h2>Nossos E-books</h2>
    <div class="ebooks">
      <div class="ebook">
        <h3>Guia do Bitcoin</h3>
        <p>Aprenda os fundamentos da maior criptomoeda do mundo.</p>
        <div class="purchase-buttons">
          <a href="#" class="pix">Comprar via Pix</a>
          <a href="#" class="cartao">Comprar com Cartão</a>
        </div>
      </div>
      <div class="ebook">
        <h3>Investindo em Criptos</h3>
        <p>Dicas e estratégias para iniciantes.</p>
        <div class="purchase-buttons">
          <a href="#" class="pix">Comprar via Pix</a>
          <a href="#" class="cartao">Comprar com Cartão</a>
        </div>
      </div>
      <div class="ebook">
        <h3>Web3 e o Futuro</h3>
        <p>Descubra o impacto da Web3 no mundo dos investimentos.</p>
        <div class="purchase-buttons">
          <a href="#" class="pix">Comprar via Pix</a>
          <a href="#" class="cartao">Comprar com Cartão</a>
        </div>
      </div>
    </div>
  </section>

  <section id="contato" class="contact">
    <h2>Entre em Contato</h2>
    <p>WhatsApp: <strong>(54) 99114-1875</strong></p>
    <p>Email: <strong>pontesdudu690@gmail.com</strong></p>
  </section>

  <footer>
    <p>&copy; 2025 Criptoseve. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
