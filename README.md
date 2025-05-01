<!DOCTYPE html>
<html lang="es">
<head>
  <link rel="apple-touch-icon" sizes="180x180" href="logo.png">
  <link rel="icon" type="image/png" sizes="32x32" href="logo.png">
  <link rel="icon" type="image/png" sizes="16x16" href="logo.png">
  <meta name="theme-color" content="#000000">
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
  <meta name="mobile-web-app-capable" content="yes">
  <meta name="application-name" content="Jhoandersontattoo">
  <meta name="apple-mobile-web-app-title" content="Jhoandersontattoo">
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(270deg, #111, #222, #333, #222, #111);
      background-size: 1000% 1000%;
      animation: colorFlow 20s ease infinite;
      color: #f5f5f5;
    }
    header {
      background-color: #000;
      padding: 1rem;
      text-align: center;
      border-bottom: 2px solid #ff6600;
    }
    header img {
      max-width: 300px;
      height: auto;
      animation: bounceLogo 3s infinite ease-in-out;
    }
    nav {
      flex-wrap: wrap;
      background: #111;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
      border-bottom: 1px solid #333;
    }
    nav a {
      color: #ff6600;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #fff;
    }
    section {
      max-width: 100%;
      box-sizing: border-box;
      padding: 2rem;
    }
    .form-group {
      margin-bottom: 1rem;
    }
    label, input, textarea, select {
      box-sizing: border-box;
      display: block;
      width: 100%;
      margin-top: 0.5rem;
    }
    button {
      background: #ff6600;
      color: white;
      padding: 0.75rem;
      border: none;
      cursor: pointer;
    }
    footer {
      background: #000;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  
    a[href*='facebook'] {
      animation: pulse 1.5s infinite;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.05); }
      100% { transform: scale(1); }
    }
  
    @keyframes colorFlow {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
  
    @keyframes bounceLogo {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-10px);
      }
    }
  </style>
  </head>
<body>
  <header>
    <img src="logo.png" alt="Jhoandersontattoo Store Logo">
  </header>

  <nav>
    <a href="#sobre">Sobre Nosotros</a>
    <a href="#galeria">Galería</a>
    <a href="#cita">Agenda</a>
    <a href="#cotizacion">Cotización</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="sobre">
    <h2>Sobre Nosotros</h2>
    <p>Bienvenidos a Jhoandersontattoo Store, tu estudio de tatuajes en . Especialistas en estilos realistas, oscuros y personalizados.</p>
  </section>

  <section id="galeria">
  <h2>Galería</h2>
  <video width="100%" controls>
    <source src="WhatsApp Video 2025-05-01 at 16.05.01 (1).mp4" type="video/mp4">
    Tu navegador no soporta el video.
  </video>
  <p style="margin-top: 1rem; text-align: center;">
    <a href="https://www.instagram.com/jhoandersontattoo" target="_blank" style="display:inline-block;padding:10px 20px;background:#e1306c;color:#fff;border-radius:5px;text-decoration:none;transition:background 0.3s ease; animation: pulse 1.5s infinite;">Ver más fotos en Instagram</a>
  </p>
</section>

  <section id="cita">
    <h2>Agenda tu Cita</h2>
    <form>
      <div class="form-group">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required>
      </div>
      <div class="form-group">
        <label for="email">Correo electrónico o WhatsApp:</label>
        <input type="text" id="email" name="email" required>
      </div>
      <div class="form-group">
        <label for="fecha">Fecha deseada:</label>
        <input type="date" id="fecha" name="fecha">
      </div>
      <div class="form-group">
        <label for="descripcion">Descripción del tatuaje:</label>
        <textarea id="descripcion" name="descripcion" rows="4"></textarea>
      </div>
      <button type="submit">Agendar</button>
    </form>
  </section>

  <section id="cotizacion">
  <div style="background: #ff6600; color: white; padding: 1rem; border-radius: 5px; margin-bottom: 2rem; text-align: center; font-weight: bold;">
    IMPORTANTE: Para finalizar cualquier cotización, debes escribirnos directamente por <a href="https://wa.me/32456319092" style="color: #fff; text-decoration: underline;">WhatsApp</a>.
  </div>
  <h2>Solicita una Cotización</h2>
  <form action="mailto:jhoanfreitez@gmail.com" method="post" enctype="text/plain">
    <div class="form-group">
      <label for="zona">Parte del cuerpo:</label>
      <input type="text" id="zona" name="zona">
    </div>
    <div class="form-group">
      <label for="tamano">Tamaño aproximado (cm):</label>
      <input type="text" id="tamano" name="tamano">
    </div>
    <div class="form-group">
      <label for="estilo">Estilo deseado:</label>
      <select id="estilo" name="estilo">
        <option value="realismo">Realismo</option>
        <option value="blackwork">Blackwork</option>
        <option value="tradicional">Tradicional</option>
        <option value="personalizado">Personalizado</option>
      </select>
    </div>
    <div class="form-group">
      <label for="presupuesto">Rango de precio estimado:</label>
      <select id="presupuesto" name="presupuesto">
        <option value="50-100">€50 - €100</option>
        <option value="100-200">€100 - €200</option>
        <option value="200-400">€200 - €400</option>
        <option value="400+">Más de €400</option>
      </select>
    </div>
    <button type="submit">Solicitar Cotización</button>
  </form>
</section>

  <br><a href="https://www.facebook.com/jhoanderson.freitez?mibextid=wwXIf" target="_blank" style="display:inline-block;padding:10px 20px;background:#1877f2;color:#fff;border-radius:5px;text-decoration:none;transition:background 0.3s ease;">Síguenos en Facebook</a><br><a href="https://www.instagram.com/jhoandersontattoo" target="_blank" style="display:inline-block;padding:10px 20px;background:#e1306c;color:#fff;border-radius:5px;text-decoration:none;transition:background 0.3s ease; animation: pulse 1.5s infinite;">Síguenos en Instagram</a></p>
  <br><a href="https://wa.me/32456319092" target="_blank" style="display:inline-block;padding:10px 20px;background:#25D366;color:#fff;border-radius:5px;text-decoration:none;transition:background 0.3s ease; animation: pulse 1.5s infinite;">Contáctanos por WhatsApp</a>

    <p>&copy; 2025 Jhoandersontattoo Store. Todos los derechos reservados.</p>
  </footer>
<section id="contacto">
  <h2>Información de Contacto</h2>
  <ul style="list-style: none; padding: 0;">
    <li style="margin-bottom: 1rem;">
      <strong>Correo Electrónico:</strong><br>
      <a href="mailto:jhoanfreitez@gmail.com" style="color: #ff6600;">jhoanfreitez@gmail.com</a>
    </li>
    <li style="margin-bottom: 1rem;">
      <strong>WhatsApp:</strong><br>
      <a href="https://wa.me/32456319092" target="_blank" style="color: #25D366;">+32 456 31 90 92</a>
    </li>
    <li style="margin-bottom: 1rem;">
      <strong>Instagram:</strong><br>
      <a href="https://www.instagram.com/jhoandersontattoo" target="_blank" style="color: #e1306c;">@jhoandersontattoo</a>
    </li>
    <li style="margin-bottom: 1rem;">
      <strong>Facebook:</strong><br>
      <a href="https://www.facebook.com/jhoanderson.freitez?mibextid=wwXIf" target="_blank" style="color: #1877f2;">Jhoanderson Freitez</a>
    </li>
  </ul>
</section>

</body>
</html>
