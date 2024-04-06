<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=Edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Coffee Shops Tia Rosa</title>

    <!-- Google Fontes-->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
      rel="stylesheet"
    />

    <!--Estilos-->
    <link rel="stylesheet" href="css/styles.css" />
  </head>
  <body>
    <div id="about-container">
      <div id="brand">
        <img src="img/Cafeteria.jpeg" alt="COFFEE SHOPS TIA ROSA" />
        <h1>Coffee Shops Tia Rosa</h1>
      </div>
      <p id="exclusive">Uma xícara de motivação</p>
      <h2>Venha saborear um delicioso Coffee da tia Rosa</h2>
      <p id="date">10/04/2024 Delivery 100% GRATUITO</p>
      <p id="description">Café na sua porta, sabor no seu coração.</p>
      <h4>Bem-vindo ao nosso cardápio!</h4>

      <div id="users-container">
        <div class="user-card">
          <img
            src="img/Cafe ameriacano.jpg"
            alt=" Uma bebida mais suave, feita diluindo o café expresso com água quente"
          />
          <p class="user-name">CAFÉ AMERICANO</p>
          <p class="user-role">
            Uma bebida mais suave, feita diluindo o café expresso com água
            quente
          </p>
        </div>
        <div class="user-card">
          <img
            src="img/Cafe descafeinado.jpg"
            alt=" O café descafeinado é uma ótima escolha"
          />
          <p class="user-name">CAFÉ DESCAFEINADO</p>
          <p class="user-role">O café descafeinado é uma ótima escolha</p>
        </div>
        <div class="user-card">
          <img
            src="img/Cafe latte.jpg"
            alt=" Uma combinação de café expresso e leite vaporizado"
          />
          <p class="user-name">CAFÉ LATTE</p>
          <p class="user-role">
            Uma combinação de café expresso e leite vaporizado
          </p>
        </div>
      </div>
    </div>

    <div id="form-container">
      <div id="form-inner">
        <h3>Cadastre-se</h3>
        <p>Não perca tempo, faça seu pedido através do nosso site</p>
        <form id="register-form">
          <div id="name-container">
            <input type="text" name="name" id="name" placeholder="Nome" />
            <input
              type="text"
              name="lastname"
              id="lastname"
              placeholder="Sobrenome"
            />
          </div>
          <input
            type="email"
            name="email"
            id="email"
            placeholder="Digitar seu e-mail"
          />
          <input type="submit" value="Pedidos" />
        </form>

        <div id="benefits">
          <h4>Aqui você encontrará</h4>
          <ul>
            <li>Diversos sabores especiais</li>
            <li>Atendimento personalizado</li>
            <li>Entrega rápida na sua porta</li>
          </ul>
        </div>
      </div>
    </div>
  </body>
</html>
