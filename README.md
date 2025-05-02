<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AvisaFácil - Lembretes que funcionam</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #ffffff;
      color: #333;
    }
    header {
      background-color: #4A90E2;
      padding: 20px;
      text-align: center;
      color: white;
    }
    header h1 {
      margin: 0;
      font-size: 28px;
    }
    header button {
      background-color: #7ED957;
      color: #000;
      padding: 10px 20px;
      font-weight: bold;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      margin-top: 10px;
    }
    .section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
      text-align: center;
    }
    .steps, .benefits {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }
    .step, .benefit {
      background-color: #f5f5f5;
      border-radius: 10px;
      padding: 20px;
    }
    .testimonial {
      font-style: italic;
      margin: 10px 0;
    }
    form input[type="email"] {
      padding: 10px;
      width: 60%;
      max-width: 300px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    form button {
      background-color: #4A90E2;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 5px;
      margin-left: 10px;
      cursor: pointer;
    }
    footer {
      background-color: #eee;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }
    a {
      color: #4A90E2;
      text-decoration: none;
      margin: 0 10px;
    }
  </style>
</head>
<body>

  <header>
    <h1>AvisaFácil</h1>
    <p>Lembretes que funcionam. Por WhatsApp, SMS ou e-mail.</p>
    <button>Comece grátis</button>
  </header>

  <section class="section">
    <h2>Como funciona</h2>
    <div class="steps">
      <div class="step"><strong>1.</strong> Crie seu lembrete</div>
      <div class="step"><strong>2.</strong> Escolha o canal: WhatsApp, SMS ou e-mail</div>
      <div class="step"><strong>3.</strong> Receba na hora certa</div>
    </div>
  </section>

  <section class="section">
    <h2>Por que usar o AvisaFácil?</h2>
    <div class="benefits">
      <div class="benefit">Funciona mesmo sem instalar nada</div>
      <div class="benefit">Envio direto para canais que você usa</div>
      <div class="benefit">Plano grátis disponível</div>
    </div>
  </section>

  <section class="section">
    <h2>Depoimentos</h2>
    <p class="testimonial">"Salvou minha vida! Nunca mais esqueci de tomar meu remédio." – Ana C.</p>
    <p class="testimonial">"Uso para lembrar reuniões com clientes. Muito útil." – Marcos L.</p>
  </section>

  <section class="section">
    <h2>Teste grátis agora</h2>
    <form>
      <input type="email" placeholder="Seu e-mail" required />
      <button type="submit">Quero testar</button>
    </form>
  </section>

  <footer>
    <p>
      <a href="#">Termos de Uso</a> |
      <a href="#">Contato</a>
    </p>
    <p>&copy; 2025 AvisaFácil</p>
  </footer>

</body>
</html>
