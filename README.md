# ELI<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cyber Console - Sistema Intervenido</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <div class="console-header">
      <span class="header-text">CYBER-CONSOLE v1.0.0</span>
      <span class="header-time" id="time"></span>
    </div>
    
    <div class="console-content">
      <h1 class="texto-hacker">SISTEMA INTERVENIDO: CÓDIGO DE ELIMINACIÓN TOTAL ACTIVADO</h1>
      
      <div class="console-lines">
        <div class="line">
          <span class="prompt">$</span>
          <span class="command">sudo rm -rf /system/*</span>
        </div>
        <div class="line">
          <span class="prompt">$</span>
          <span class="command">Acceso concedido... █████████░</span>
        </div>
        <div class="line">
          <span class="prompt">$</span>
          <span class="command">Eliminando archivos críticos...</span>
        </div>
        <div class="line typing">
          <span class="prompt">$</span>
          <span class="command" id="typing-text"></span>
        </div>
      </div>
    </div>

    <div class="console-footer">
      <button class="btn-activate" onclick="activateSystem()">ACTIVAR SISTEMA</button>
      <button class="btn-reset" onclick="resetSystem()">REINICIAR</button>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <style>
    /* Aquí pegas el código CSS que escribiste */
    body { background-color: black; }
    .texto-hacker {
      color: #00ff00;
      font-family: monospace;
      animation: vibrar 0.2s infinite;
    }
    @keyframes vibrar {
      0% { transform: translate(0); }
      50% { transform: translate(3px, -3px); }
      100% { transform: translate(0); }
    }
  </style>
</head>
<body>
  <h1 class="texto-hacker">SISTEMA INTERVENIDO: CÓDIGO DE ELIMINACIÓN TOTAL ACTIVADO</h1>
</body>
</html>
