<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Acerca de mí</title>
  <style>
    /* ---------- Estilos generales ---------- */
    body {
      font-family: Arial, Helvetica, sans-serif;
      background: linear-gradient(135deg, #001F3F, #0074D9);
      color: white;
      text-align: center;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
    }

    header {
      background-color: rgba(0, 0, 0, 0.2);
      padding: 15px 0;
      font-size: 24px;
      font-weight: bold;
      letter-spacing: 1px;
      animation: fadeInDown 1.2s ease-in-out;
    }

    /* ---------- Animación CSS ---------- */
    @keyframes fadeInDown {
      from { transform: translateY(-40px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    .card {
      background: rgba(255, 255, 255, 0.15);
      border-radius: 15px;
      width: 80%;
      max-width: 400px;
      margin: 30px auto;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
      animation: slideUp 1.2s ease-in-out;
    }

    @keyframes slideUp {
      from { transform: translateY(60px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    img {
      width: 100px;
      border-radius: 50%;
      border: 3px solid white;
      margin-top: 10px;
      transition: transform 0.4s ease;
    }

    img:hover {
      transform: scale(1.1);
    }

    h2 {
      margin: 10px 0 5px 0;
    }

    p {
      font-size: 15px;
      line-height: 1.5;
      margin-bottom: 15px;
    }

    /* ---------- Formulario ---------- */
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin-top: 15px;
    }

    input, textarea {
      padding: 8px;
      border: none;
      border-radius: 5px;
      font-family: inherit;
    }

    button {
      background-color: #39CCCC;
      color: #001F3F;
      border: none;
      border-radius: 5px;
      padding: 10px;
      font-weight: bold;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #7FDBFF;
    }

    footer {
      margin-top: 20px;
      font-size: 13px;
      opacity: 0.8;
    }
  </style>
</head>
<body>
  <header>Acerca de mí</header>

  <div class="card">
    <img src="https://cdn-icons-png.flaticon.com/512/145/145867.png" alt="Perfil">
    <h2>Tiago González</h2>
    <p>Estudiante de Electrónica en la EPET N°14. Me interesa la programación, la automatización y el desarrollo de aplicaciones móviles que integren tecnología web con sistemas embebidos.</p>

    <h3>Formulario de Contacto</h3>
    <form>
      <input type="text" placeholder="Tu nombre" required>
      <input type="email" placeholder="Tu correo" required>
      <textarea rows="3" placeholder="Tu mensaje..." required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </div>

  <footer>© 2025 - Proyecto MIT App Inventor | Tiago G.</footer>
</body>
</html>
