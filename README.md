<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Wooltek - Tienda de Auriculares</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f8f9fa;
    }
    header {
      background: #111;
      color: white;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }
    header img {
      height: 50px;
    }
    nav {
      display: flex;
      align-items: center;
      gap: 20px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #00bfff;
    }
    .telefono {
      font-size: 14px;
      margin-left: 20px;
      color: #00bfff;
      font-weight: bold;
    }
    .hero {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(to right, #111, #333);
      color: white;
    }
    .hero h2 {
      font-size: 36px;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 18px;
    }
    .productos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px;
    }
    .card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      padding: 20px;
      text-align: center;
    }
    .card img {
      width: 100%;
      max-height: 200px;
      object-fit: contain;
      border-radius: 10px;
    }
    .card h3 {
      margin: 10px 0;
    }
    .card p {
      font-size: 14px;
      color: #555;
    }
    .precio {
      font-size: 18px;
      font-weight: bold;
      margin: 10px 0;
      color: #00bfff;
    }
    .btn {
      display: inline-block;
      background: #00bfff;
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      transition: 0.3s;
    }
    .btn:hover {
      background: #008ccc;
    }
    .opiniones {
      background: #eee;
      padding: 40px;
      text-align: center;
    }
    .opiniones h2 {
      margin-bottom: 20px;
    }
    .opiniones p {
      font-style: italic;
      color: #333;
    }
    .contacto {
      padding: 40px;
      text-align: center;
    }
    .contacto form {
      max-width: 500px;
      margin: auto;
    }
    .contacto input, .contacto textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 20px;
    }
    footer a {
      color: #00bfff;
      margin: 0 10px;
      text-decoration: none;
    }
    footer .telefono {
      display: block;
      margin-top: 10px;
      font-weight: bold;
      color: #00bfff;
    }

    /* BOTÓN WHATSAPP */
    .whatsapp-float {
      position: fixed;
      width: 60px;
      height: 60px;
      bottom: 20px;
      right: 20px;
      background-color: #25d366;
      color: #FFF;
      border-radius: 50%;
      text-align: center;
      font-size: 30px;
      box-shadow: 2px 2px 5px rgba(0,0,0,0.3);
      z-index: 100;
      display: flex;
      justify-content: center;
      align-items: center;
      transition: 0.3s;
    }
    .whatsapp-float:hover {
      background-color: #20b955;
    }
  </style>
</head>
<body>

  <header>
    <img src="db804394-0044-4e11-90e1-5e4b89609a50.jpg" alt="Logo Wooltek">
    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#productos">Productos</a>
      <a href="#opiniones">Opiniones</a>
      <a href="#contacto">Contacto</a>
      <span class="telefono">📞 +54 381 216-0221</span>
    </nav>
  </header>

  <section class="hero" id="inicio">
    <h2>Los mejores auriculares al mejor precio</h2>
    <p>Calidad de sonido superior y diseños modernos</p>
    <a href="#productos" class="btn">Ver catálogo</a>
  </section>

  <section class="productos" id="productos">
    <div class="card">
      <img src="" alt="Auricular 1">
      <h3>Auriculares A6S suono</h3>
      <p>Sonido profundo y envolvente, ideal para música.</p>
      <div class="precio">$26.700</div>
      <a href="#" class="btn">Comprar</a>
    </div>
    <div class="card">
      <img src="https://i.imgur.com/9eJLZae.png" alt="Auricular 2">
      <h3>Wireless X</h3>
      <p>Inalámbricos, batería de larga duración.</p>
      <div class="precio">$79.99</div>
      <a href="#" class="btn">Comprar</a>
    </div>
    <div class="card">
      <img src="https://i.imgur.com/j7DQ5Yx.png" alt="Auricular 3">
      <h3>Gaming Headset</h3>
      <p>Micrófono incorporado, ideal para gamers.</p>
      <div class="precio">$59.99</div>
      <a href="#" class="btn">Comprar</a>
    </div>
  </section>

  <section class="opiniones" id="opiniones">
    <h2>Opiniones de Clientes</h2>
    <p>"Excelente calidad de sonido, los mejores que he comprado." – Emiliano Figueroa.</p>
    <p>"Muy cómodos y la batería dura mucho, recomendados." – Martina Acosta.</p>
    <p>"El headset gamer es increíble, se escucha todo perfecto." – Fagioli.</p>
  </section>

  <section class="contacto" id="contacto">
    <h2>Contáctanos</h2>
    <p>También puedes llamarnos al 📞 <strong>+54 381 216-0221</strong></p>
    <form>
      <input type="text" placeholder="Tu nombre" required>
      <input type="email" placeholder="Tu correo" required>
      <textarea rows="5" placeholder="Tu mensaje"></textarea>
      <button type="submit" class="btn">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Wooltek - Todos los derechos reservados</p>
    <p>Síguenos en:
      <a href="#">Facebook</a> |
      <a href="#">Instagram</a> |
      <a href="#">Twitter</a>
    </p>
    <span class="telefono">📞 +54 381 216-0221</span>
  </footer>

  <!-- BOTÓN WHATSAPP -->
  <a href="https://wa.me/543812160221" class="whatsapp-float" target="_blank">
    💬
  </a>

</body>
</html>
