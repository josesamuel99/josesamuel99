<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Império Digital Premium</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #0f0f0f;
      color: #fff;
    }

    header {
      background: linear-gradient(90deg, #000, #1a1a1a);
      padding: 30px 20px;
      text-align: center;
      animation: fadeInDown 1.2s ease-out;
    }

    header h1 {
      font-size: 2rem;
      color: #ffd700;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1rem;
      color: #e0e0e0;
    }

    .section {
      padding: 30px 20px;
      max-width: 900px;
      margin: auto;
    }

    .section h2 {
      color: #ffd700;
      font-size: 1.6rem;
      margin-bottom: 20px;
    }

    .section p {
      font-size: 1.1rem;
      line-height: 1.6;
    }

    .destaques {
      display: flex;
      flex-direction: column;
      gap: 20px;
      margin-top: 20px;
    }

    .destaque-item {
      background: #1b1b1b;
      border-left: 5px solid #ffd700;
      padding: 15px;
      border-radius: 10px;
      font-size: 1.1rem;
    }

    .garantia-box {
      display: flex;
      justify-content: center;
      margin: 40px 0;
    }

    .highlight-animation {
      font-size: 1rem;
      font-weight: 700;
      color: #fffbe8;
      position: relative;
      padding: 14px 28px;
      border-radius: 12px;
      background: linear-gradient(90deg, #1b1b1b, #2a2a2a);
      box-shadow: 0 0 25px rgba(255, 215, 0, 0.4);
      text-align: center;
      overflow: hidden;
      border: 1px solid #ffd70070;
    }

    .highlight-animation::after {
      content: "";
      position: absolute;
      top: 0;
      left: -75%;
      width: 50%;
      height: 100%;
      background: linear-gradient(120deg, transparent, #ffd70080, transparent);
      animation: shine 2.5s infinite;
    }

    @keyframes shine {
      0% {
        left: -75%;
      }
      50% {
        left: 100%;
      }
      100% {
        left: 100%;
      }
    }

    .comentarios {
      margin-top: 40px;
    }

    .comentario {
      background-color: #1c1c1c;
      padding: 15px;
      border-radius: 10px;
      margin-bottom: 15px;
      display: flex;
      gap: 10px;
      align-items: center;
    }

    .comentario img {
      border-radius: 50%;
      width: 50px;
      height: 50px;
    }

    .comentario-content {
      color: #ccc;
    }

    .bancos {
      margin-top: 40px;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }

    .bancos img {
      height: 35px;
      filter: brightness(1.2);
    }

    .btn-comprar {
      display: block;
      margin: 40px auto;
      background: #ffd700;
      color: #000;
      padding: 15px 30px;
      font-size: 1.2rem;
      font-weight: bold;
      border-radius: 50px;
      border: none;
      cursor: pointer;
      box-shadow: 0 0 15px #ffd700aa;
      transition: transform 0.2s ease;
      text-decoration: none;
      text-align: center;
      width: fit-content;
    }

    .btn-comprar:hover {
      transform: scale(1.05);
    }

    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <header>
    <h1> Bem-vindo ao Império Digital Premium</h1>
    <p>Transforme seu tempo livre em lucro com o pacote mais completo do Brasil</p>
  </header>

  <div class="section">
    <h2> O que você vai receber?</h2>
    <div class="destaques">
      <div class="destaque-item"> +300 eBooks PLR para revenda com direitos</div>
      <div class="destaque-item"> Página de vendas profissional pronta para você usar</div>
      <div class="destaque-item"> Marca Premium com capa e identidade visual inclusa</div>
    </div>

    <div class="garantia-box">
      <div class="highlight-animation"> Compra 100% segura com garantia</div>
    </div>

    <div class="comentarios">
      <h2> Depoimentos reais</h2>
      <div class="comentario">
        <img
          src="https://randomuser.me/api/portraits/men/32.jpg"
          alt="cliente"
        />
        <div class="comentario-content">
          <strong>Lucas R.</strong><br />
          Já comecei a revender os ebooks, vale muito a pena!
        </div>
      </div>
      <div class="comentario">
        <img
          src="https://randomuser.me/api/portraits/women/45.jpg"
          alt="cliente"
        />
        <div class="comentario-content">
          <strong>Ana C.</strong><br />
          Produto top! Tudo pronto, é só divulgar. Amei!
        </div>
      </div>
    </div>

    <div class="bancos">
      <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/Pix_logo.svg" alt="Pix" />
      <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/Visa.svg" alt="Visa" />
      <img
        src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Mastercard-logo.png"
        alt="Mastercard"
      />
      <img
        src="https://upload.wikimedia.org/wikipedia/commons/4/4e/PicPay_Logo_2021.svg"
        alt="PicPay"
      />
      <img
        src="https://upload.wikimedia.org/wikipedia/commons/b/bb/Nubank_logo_2021.svg"
        alt="Nubank"
      />
    </div>

    <a
      class="btn-comprar"
      href="https://pay.cakto.com.br/8Kqb8Kt?fbclid=PAQ0xDSwKzvu5leHRuA2FlbQIxMAABp1N4n8TOIsvIJu0fPdzQC5un5R9p7OsdHnyGDSZWiOO64ABPp3XDdoQmP-i__aem_miztkj1e-Yyg6o6OAAs4dA"
      target="_blank"
      > QUERO COMPRAR AGORA</a
    >
  </div>
</body>
</html>
