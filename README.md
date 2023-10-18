
<!DOCTYPE html>
<html>
<head>
    <title>Meu Site com Imagens</title>
</head>
<body>
    <h1>Bem-vindo ao Meu Site</h1>
    <p>Aqui estão algumas imagens:</p>
    <img src="caminho_para_imagem1.jpg" alt="Imagem 1">
    <img src="caminho_para_imagem2.jpg" alt="Imagem 2">
    <img src="caminho_para_imagem3.jpg" alt="Imagem 3">
</body>
</html>
[18/10 17:51] Larih: <!DOCTYPE html>
<html>
<head>
  <title>Localização</title>
  <script>
    function obterLocalizacao() {
      if (navigator.geolocation) {
        navigator.geolocation.getCurrentPosition(mostrarLocalizacao);
      } else {
        alert("Geolocalização não é suportada pelo seu navegador.");
      }
    
  </script>
</head>
<body>
  <h1>Localização</h1>
  <button onclick="obterLocalizacao()">Obter Localização</button>
  <div id="localizacao"></div>
</body>
</html>
