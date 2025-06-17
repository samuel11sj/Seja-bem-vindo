<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Boas-vindas</title>
</head>
<body>
  <h2>Digite seu nome:</h2>
  <input type="text" id="nomeInput" placeholder="Seu nome">
  <button onclick="mostrarMensagem()">Enviar</button>

  <p id="mensagem"></p>

  <script>
    function mostrarMensagem() {
      const nome = document.getElementById("nomeInput").value;
      const mensagem = "Bem vindo " + nome;
      document.getElementById("mensagem").textContent = mensagem;
    }
  </script>
</body>
</html>
