<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EspilotZone - Normativa Drones</title>
  <link rel="stylesheet" href="styles.css">
  <script src="https://unpkg.com/lucide@latest"></script>
</head>
<body>
  <header>
    <nav>
      <div class="logo">EspilotZone</div>
      <ul>
        <li><a href="index.html">Inicio</a></li>
        <li><a href="normativa.html">Normativa</a></li>
        <li><a href="zonas-vuelo.html">Zonas de Vuelo</a></li>
        <li><a href="zonas-protegidas.html">Zonas Protegidas</a></li>
        <li><a href="faq.html">FAQ</a></li>
        <li><a href="contacto.html">Contacto</a></li>
      </ul>
    </nav>
  </header>  <main>
    <!-- Contenido específico de cada sección -->
    <section class="hero fade-in">
      <h1>Bienvenido a EspilotZone</h1>
      <p>Tu guía clara y actualizada sobre normativa de drones en España.</p>
    </section>
  </main>  <footer>
    <p>&copy; 2025 EspilotZone. Información basada en fuentes oficiales: MITECO, ENAIRE, AESA.</p>
    <div class="social-icons">
      <i data-lucide="mail"></i>
      <i data-lucide="map"></i>
      <a href="https://drones.enaire.es/" target="_blank">Mapa ENAIRE</a>
    </div>
  </footer>  <script>
    lucide.createIcons();
  </script></body>
</html>

/* Estilo profesional para EspilotZone */

/* Variables de color */ :root { --gris-oscuro: #2f2f2f; --gris-claro: #f4f4f4; --azul-claro: #4A90E2; --blanco: #ffffff; }

body { font-family: 'Open Sans', sans-serif; margin: 0; padding: 0; background-color: var(--gris-claro); color: var(--gris-oscuro); }

header { background-color: var(--blanco); border-bottom: 1px solid #ddd; padding: 1rem 2rem; display: flex; justify-content: space-between; align-items: center; position: sticky; top: 0; z-index: 1000; }

.logo { font-size: 1.5rem; font-weight: bold; color: var(--azul-claro); }

nav ul { list-style: none; display: flex; gap: 1rem; margin: 0; padding: 0; }

nav ul li a { text-decoration: none; color: var(--gris-oscuro); font-weight: 600; transition: color 0.3s; }

nav ul li a:hover { color: var(--azul-claro); }

main { padding: 2rem; }

section.hero { text-align: center; padding: 4rem 2rem; background-color: var(--blanco); border-radius: 12px; box-shadow: 0 2px 8px rgba(0,0,0,0.05); }

section.hero h1 { font-size: 2.5rem; margin-bottom: 1rem; }

section.hero p { font-size: 1.2rem; color: #555; }

footer { text-align: center; padding: 2rem; background-color: var(--blanco); border-top: 1px solid #ddd; margin-top: 2rem; }

footer .social-icons { margin-top: 1rem; display: flex; justify-content: center; align-items: center; gap: 1rem; color: var(--azul-claro); }

.fade-in { opacity: 0; transform: translateY(20px); animation: fadeInUp 1s ease-out forwards; }

@keyframes fadeInUp { to { opacity: 1; transform: translateY(0); } }

