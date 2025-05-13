# eu-te-amo-meu-momo
<!DOCTYPE html>
<html>
<head>
  <title>Surpresa</title>
  <style>
    body {
      text-align: center;
      padding-top: 100px;
      font-family: Arial;
      background-color: #fff0f5;
    }
    button {
      font-size: 20px;
      padding: 10px 20px;
      border-radius: 12px;
      border: none;
      background-color: #ff69b4;
      color: white;
      cursor: pointer;
    }
    #mensagem {
      margin-top: 30px;
      font-size: 24px;
      color: red;
      display: none;
    }
  </style>
</head>
<body>

  <h2>Tenho algo pra te dizer...</h2>
  <button onclick="mostrarMensagem()">Clique aqui</button>
  <div id="mensagem">Eu te amo</div>

  <script>
    function mostrarMensagem() {
      document.getElementById("mensagem").style.display = "block";
    }
  </script>

</body>
</html>
