<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Legion Trick - Radio</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #0d0d0d;
      font-family: 'Segoe UI', sans-serif;
      color: #f5c518;
      text-align: center;
    }

    header {
      padding: 40px 20px;
      animation: fadeIn 2s ease-out;
    }

    h1 {
      font-size: 3.5em;
      margin: 0;
      letter-spacing: 2px;
    }

    p.subtitle {
      font-size: 1.2em;
      color: #cccccc;
      margin-top: 10px;
    }

    main {
      margin-top: 40px;
      animation: fadeIn 3s ease-in;
    }

    audio {
      width: 80%;
      max-width: 600px;
      margin: 20px auto;
      display: block;
    }

    footer {
      margin-top: 50px;
      font-size: 0.9em;
      color: #777;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-10px); }
      to   { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <header>
    <h1>LEGION TRICK</h1>
    <p class="subtitle">Transmitiendo el lado oculto del conocimiento...</p>
  </header>

  <main>
    <h2>🔊 Emisora en vivo</h2>
    
    <!-- 🔁 CAMBIA ESTE LINK CUANDO NGROK CAMBIE -->
    <audio controls autoplay>
      <source src="https://70fbd5b7673e.ngrok-free.app/radio" type="audio/mpeg">
      Tu navegador no soporta audio HTML5.
    </audio>
    
    <p>Comparte esta página con tus amigos para que escuchen la señal secreta. 📡</p>
  </main>

  <footer>
    <p>© 2025 Legion Trick. Proyecto de David Haney.</p>
  </footer>

</body>
</html>
