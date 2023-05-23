# ayosimao.github.io
<html>
<head>
  <title>ahpoisbb</title>
  <style>
    body {
      background-color: #222;
      color: #fff;
      text-align: center;
      font-family: Arial, sans-serif;
    }

    .question {
      background-color: #800000;
      padding: 20px;
      margin-bottom: 20px;
    }

    .answers {
      display: flex;
      justify-content: center;
    }

    .answer {
      margin: 10px;
    }
  </style>
</head>
<body>
  <div class="question">
    <h2>!!!! PERGUNTA IMPORTANTE ANA !!!!</h2>
    <p>Fototeta?</p>
  </div>

  <div class="answers">
    <button onclick="exibirResposta('YESS CARALHOUUU ES GRANDE VALEU A PENA TAR UMA HORA NISTO')">Sim lindo :)</button>
    <button onclick="exibirResposta('só pelo esforço já valia mas tu é q sbs...(emoji meio ironicamente triste)')">Talvez Simão.</button>
    <button onclick="exibirResposta('tentou-se ya, encontrarei me em espera no wpp à espera da tua reação e ja n repito pedido de fototeta')">LOOOL NÃO BURRO</button>
  </div>

  <div id="respostaContainer"></div>

  <script>
    function exibirResposta(resposta) {
      var respostaContainer = document.getElementById("respostaContainer");
      respostaContainer.innerHTML = "<p class='answer'>" + resposta + "</p>";
    }
  </script>
</body>
</html>
