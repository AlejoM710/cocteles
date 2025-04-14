<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Cocteles Granizados - Refresca tu día con los mejores cocteles granizados.">
  <title>Cocteles AMD</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f7f7;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      background-color: #ff5e5e;
      color: white;
    }

    .logo img {
      height: 60px;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 1.5rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      text-align: center;
      padding: 3rem 1rem;
      background-color: #ffe4e4;
    }

    .hero h1 {
      font-size: 2.5rem;
    }

    .cta-button {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.75rem 1.5rem;
      background-color: #ff5e5e;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }

    .cocteles {
      padding: 2rem;
      text-align: center;
    }

    .cocteles-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2rem;
    }

    .coctel {
      width: 250px;
      text-align: center;
      border: 1px solid #ddd;
      padding: 1rem;
      border-radius: 10px;
      background-color: #fff;
      box-shadow: 2px 2px 6px rgba(0, 0, 0, 0.1);
    }

    .coctel img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 8px;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <img src="logo.jpg" alt="Logo de Cocteles AMD">
    </div>
    <nav>
      <ul>
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Menú</a></li>
        <li><a href="#">Acerca de</a></li>
        <li><a href="#">Contacto</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="hero">
      <h1>Bienvenido a Cocteles AMD</h1>
      <p>¡La frescura que necesitas en cada sorbo!</p>
      <a href="#" class="cta-button">Descubre nuestros cocteles</a>
    </section>

    <section class="cocteles">
      <h2>Cocteles Granizados</h2>
      <div class="cocteles-list">
        <div class="coctel">
          <img src="c1.jpg" alt="Coctel Granizado de Frutas">
          <h3>Granizado Tropical</h3>
          <p>Un mix de frutas frescas con un toque de menta.</p>
        </div>
        <div class="coctel">
          <img src="c2.png" alt="Coctel Granizado de Limón">
          <h3>Limón Refrescante</h3>
          <p>El clásico sabor ácido y refrescante del limón, con un toque de fresa.</p>
        </div>
        <div class="coctel">
          <img src="c3.jpg" alt="Coctel Granizado de Mango">
          <h3>Mango Enfocado</h3>
          <p>Un delicioso granizado de mango, perfecto para el calor.</p>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Cocteles AMD. Todos los derechos reservados.</p>
  </footer>
</body>
</html>





