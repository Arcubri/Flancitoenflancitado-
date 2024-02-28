# Flancitoenflancitado-
Para mí bebe
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Propuesta de Matrimonio</title>
<style>
  body {
    font-family: Arial, sans-serif;
    text-align: center;
  }
  .container {
    margin-top: 50px;
  }
  .ring {
    width: 150px;
  }
  .cat {
    width: 200px;
    position: relative;
  }
  .black-cat {
    left: 50%;
    transform: translateX(-50%);
  }
  .white-cat {
    display: none;
    position: absolute;
    top: 70px;
    left: 50%;
    transform: translateX(-50%);
  }
</style>
</head>
<body>
<div class="container">
  <img src="https://i.imgur.com/rW7EhiA.png" alt="Cat with wedding ring" class="cat black-cat">
  <img src="https://i.imgur.com/XcSllY2.png" alt="Cat hugging" class="cat white-cat">
  <img src="https://i.imgur.com/gawUEbo.png" alt="Wedding ring" class="ring" id="ring">
  <div id="proposal">
    <p>¿Te casarías conmigo?</p>
    <button onclick="acceptProposal()">Aceptar</button>
  </div>
  <div id="response" style="display: none;">
    <p>¡Te amo mi flancito enflancitado!</p>
  </div>
</div>

<script>
  function acceptProposal() {
    document.getElementById("proposal").style.display = "none";
    document.getElementById("response").style.display = "block";
    document.querySelector(".black-cat").style.display = "none";
    document.querySelector(".white-cat").style.display = "block";
    document.getElementById("ring").style.display = "none";
  }
</script>
</body>
</html>
