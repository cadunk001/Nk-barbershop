# Nk-barbershop
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NK Barbershop - Serviços</title>
  <style>
    body {
      background: #1C1C1C;
      color: #FFFFFF;
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
    }
    .services-section {
      padding: 50px;
      text-align: center;
    }
    .services-section h1 {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 3em;
      color: #FF2E2E;
    }
    .services-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .service-card {
      background: #2A2A2A;
      border-radius: 10px;
      padding: 20px;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .service-card:hover {
      transform: scale(1.05);
      box-shadow: 0 0 10px #FF2E2E;
    }
    .service-card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 10px;
    }
    .service-card h3 {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 1.8em;
      margin: 10px 0;
    }
    .service-card p {
      font-size: 1em;
      color: #BBBBBB;
    }
    .service-card .price {
      color: #FF2E2E;
      font-weight: bold;
      font-size: 1.2em;
    }
    .service-card a {
      display: inline-block;
      background: #FF2E2E;
      color: #FFFFFF;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      margin-top: 10px;
      transition: background 0.3s;
    }
    .service-card a:hover {
      background: #D91C1C;
    }
  </style>
</head>
<body>
  <section class="services-section">
    <h1>🎙️ NA NK, SEU ESTILO GANHA VIDA 🎙️</h1>
    <p>Escolha seu corte, agende no WhatsApp e saia com a confiança lá em cima!</p>
    <div class="services-grid">
      <div class="service-card">
        <img src="https://i.imgur.com/2DocMoZ.jpg" alt="Degradê Navalhado">
        <h3>Degradê Navalhado</h3>
        <p class="price">R$ 30,00</p>
        <p>Precisão na navalha, estilo no visual.</p>
        <a href="https://wa.me/SEU_NUMERO?text=Oi,%20quero%20agendar%20um%20Degradê%20Navalhado">Agendar Agora</a>
      </div>
      <div class="service-card">
        <img src="https://i.imgur.com/qddJ0HS.jpg" alt="Corte Social">
        <h3>Corte Social</h3>
        <p class="price">R$ 25,00</p>
        <p>Clássico, limpo e pronto pra qualquer rolê.</p>
        <a href="https://wa.me/SEU_NUMERO?text=Oi,%20quero%20agendar%20um%20Corte%20Social">Agendar Agora</a>
      </div>
      <!-- Adicione os outros serviços aqui -->
      <div class="service-card">
        <img src="https://via.placeholder.com/150" alt="Sobrancelha">
        <h3>Sobrancelha</h3>
        <p class="price">R$ 10,00</p>
        <p>Acabamento perfeito pro seu olhar.</p>
        <a href="https://wa.me/SEU_NUMERO?text=Oi,%20quero%20agendar%20uma%20Sobrancelha">Agendar Agora</a>
      </div>
      <div class="service-card">
        <img src="https://via.placeholder.com/150" alt="Pezinho">
        <h3>Pezinho</h3>
        <p class="price">R$ 10,00</p>
        <p>Detalhe que faz toda a diferença.</p>
        <a href="https://wa.me/SEU_NUMERO?text=Oi,%20quero%20agendar%20um%20Pezinho">Agendar Agora</a>
      </div>
      <div class="service-card">
        <img src="https://via.placeholder.com/150" alt="Corte Tesoura">
        <h3>Corte Tesoura</h3>
        <p class="price">R$ 35,00</p>
        <p>Elegância e técnica em cada tesourada.</p>
        <a href="https://wa.me/SEU_NUMERO?text=Oi,%20quero%20agendar%20um%20Corte%20Tesoura">Agendar Agora</a>
      </div>
      <div class="service-card">
        <img src="https://via.placeholder.com/150" alt="Limpeza de Pele">
        <h3>Limpeza de Pele</h3>
        <p class="price">R$ 25,00</p>
        <p>Rosto renovado, vibe impecável.</p>
        <a href="https://wa.me/SEU_NUMERO?text=Oi,%20quero%20agendar%20uma%20Limpeza%20de%20Pele">Agendar Agora</a>
      </div>
    </div>
  </section>
</body>
</html>
