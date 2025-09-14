# carlossNascimento.github.io
pagina de extensão do chrome
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="popup.css" />
    <title>Chrome extensão</title>
  </head>
  <body>
    <div id="main">
      <img src="../assets/logo.svg" alt="Logo" width="40" />
      <h1>Ola, clique no button abaixo!</h1>
      <button id="actionBtn">Click me</button>
    </div>
    <script src="popup.js"></script>
  </body>
</html>
document.getElementById('actionBtn').addEventListener('click', () => {
  alert('Parabens!');
});
