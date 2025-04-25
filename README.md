# quevepc
sss-ppp
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Quevepec | Pesca y Naturaleza</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f2f9f8; color: #333; }
    header { background-color: #007B8A; color: white; padding: 20px; text-align: center; }
    nav { background-color: #005F6A; display: flex; justify-content: center; gap: 20px; padding: 10px; }
    nav a { color: white; text-decoration: none; font-weight: bold; }
    section { padding: 40px 20px; }
    .hero { background: url('https://source.unsplash.com/featured/?fishing') no-repeat center/cover; color: white; padding: 100px 20px; text-align: center; }
    .hero h1 { font-size: 3em; margin-bottom: 10px; }
    .productos, .portafolio { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .card { background: white; padding: 15px; border-radius: 10px; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }
    footer { background-color: #007B8A; color: white; text-align: center; padding: 20px; margin-top: 40px; }
    img { width: 100%; border-radius: 8px; }
    form input, form textarea { width: 100%; margin: 10px 0; padding: 10px; border: 1px solid #ccc; border-radius: 5px; }
    form button { background-color: #007B8A; color: white; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer; }
  </style>
</head>
<body>
  <header>
    <h1>Quevepec</h1>
    <p>Pasión por la pesca y la naturaleza</p>
  </header>
  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#nosotros">Sobre Nosotros</a>
    <a href="#tienda">Tienda</a>
    <a href="#portafolio">Portafolio</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section class="hero" id="inicio">
    <h1>Bienvenido a Quevepec</h1>
    <p>Explora nuestra tienda y únete a la comunidad de pesca</p>
  </section>

  <section id="nosotros">
    <h2>Sobre Nosotros</h2>
    <p>En Quevepec nos dedicamos a ofrecer productos de pesca de alta calidad, inspirados en la naturaleza y diseñados para apasionados como tú.</p>
  </section>

  <section id="tienda">
    <h2>Tienda</h2>
    <div class="productos">
      <div class="card">
        <img src="https://source.unsplash.com/featured/?fishing-rod" alt="Caña de pesca">
        <h3>Caña Queve X200</h3>
        <p>Caña ultra resistente para pesca en río o mar.</p>
        <p><strong>$79.99</strong></p>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/featured/?fishing-gear" alt="Accesorios de pesca">
        <h3>Kit de accesorios Pro</h3>
        <p>Todo lo que necesitas en un solo kit.</p>
        <p><strong>$49.99</strong></p>
      </div>
    </div>
  </section>

  <section id="portafolio">
    <h2>Portafolio</h2>
    <div class="portafolio">
      <div class="card">
        <img src="https://source.unsplash.com/featured/?fishing,river" alt="Pesca en río">
        <p>Expedición Río Amazonas 2024</p>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/featured/?fishing,boat" alt="Pesca en bote">
        <p>Campeonato Nacional de Pesca</p>
      </div>
    </div>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <form>
      <input type="text" placeholder="Tu nombre" required>
      <input type="email" placeholder="Tu correo" required>
      <textarea placeholder="Tu mensaje" rows="5" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Quevepec. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
