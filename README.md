# josue     

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Exercício de CSS</title>

  <style>
    /* Seletor por TAG */
    body {
      background-color: #e0f7fa; /* Cor de fundo alterada */
      font-family: Arial, sans-serif;
    }

    h1 {
      color: blue;
      text-align: center;
    }

    /* Seletor por CLASSE */
    .destaque {
      color: red;
      font-weight: bold;
    }

    .novo-produto {
      color: purple;
      font-style: italic;
    }

    /* Seletor por ID */
    #rodape {
      background-color: #222;
      color: #00ffcc; /* Cor do texto alterada */
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }

    /* Seletor por TAG */
    h2 {
      color: green;
    }
  </style>
</head>
<body>

  <h1>Loja Do Brawl</h1>
  <p>Confira alguns produtos E Tudo De Mintira:</p>

  <h2>jetpack Da JANET</h2>
  <p>Voe Super Rapido.</p>

  <h2 class="destaque">Arma Do Rico </h2>
  <p>As Bola Kika .</p>

  <h2>Chapeu Do Chester </h2>
  <p>Poderes Malucos.</p>

  <h2 class="novo-produto">Minegun Da Pam</h2>
  <p>Bala de borracha.</p>

  <div id="rodape">
    © 2025 Loja De Arma
  </div>

</body>  
</html>
