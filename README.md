<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Soporte Informático Remoto & Programación Inicial</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Poppins', sans-serif; background: #f0f2f5; color: #333; line-height: 1.6; }

    /* Navbar */
    nav { position: fixed; top: 0; left: 0; width: 100%; background: #0d47a1; color: white; padding: 15px 30px; display: flex; justify-content: space-between; align-items: center; z-index: 1000; }
    nav h1 { font-size: 1.2em; }
    nav ul { list-style: none; display: flex; }
    nav ul li { margin-left: 20px; }
    nav ul li a { color: white; text-decoration: none; font-weight: 600; transition: color 0.3s; }
    nav ul li a:hover { color: #90caf9; }

    /* Hero */
    header { height: 100vh; background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://source.unsplash.com/1600x900/?technology,workspace') no-repeat center center/cover; color: white; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; padding: 0 20px; }
    header h2 { font-size: 3em; margin-bottom: 20px; }
    header p { font-size: 1.2em; margin-bottom: 30px; }
    header a { background: #43a047; padding: 15px 30px; border-radius: 30px; color: white; text-decoration: none; font-weight: bold; transition: background 0.3s; }
    header a:hover { background: #66bb6a; }

    /* Sections */
    section { padding: 80px 20px; max-width: 1100px; margin: auto; }
    h2 { text-align: center; font-size: 2.2em; margin-bottom: 40px; color: #0d47a1; }

    /* Services */
    .services { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px; }
    .service-card { background: white; padding: 30px; border-radius: 15px; box-shadow: 0 4px 15px rgba(0,0,0,0.1); text-align: center; transition: transform 0.3s; }
    .service-card:hover { transform: translateY(-10px); }
    .service-card i { font-size: 40px; color: #0d47a1; margin-bottom: 15px; }
    .service-card h3 { margin-bottom: 10px; color: #333; }

    /* About */
    .about { background: white; padding: 40px; border-radius: 15px; box-shadow: 0 4px 15px rgba(0,0,0,0.1); text-align: center; }

    /* Contact */
    .contact { background: #0d47a1; color: white; border-radius: 15px; padding: 40px; text-align: center; }
    .contact a { display: inline-block; margin-top: 20px; background: #43a047; padding: 12px 25px; border-radius: 30px; color: white; text-decoration: none; font-weight: bold; transition: background 0.3s; }
    .contact a:hover { background: #66bb6a; }

    footer { text-align: center; padding: 20px; background: #0d47a1; color: white; margin-top: 40px; }

    /* Animations */
    [data-animate] { opacity: 0; transform: translateY(30px); transition: all 0.6s ease-out; }
    [data-animate].visible { opacity: 1; transform: translateY(0); }
  </style>
</head>
<body>

  <nav>
    <h1>Erick Saavedra</h1>
    <ul>
      <li><a href="#servicios">Servicios</a></li>
      <li><a href="#sobre-mi">Sobre mí</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>

  <header>
    <h2>Soporte Informático Remoto & Programación Inicial</h2>
    <p>Soluciones rápidas, confiables y desde casa.</p>
    <a href="https://wa.me/5491153448911" target="_blank">📲 Contactame por WhatsApp</a>
  </header>

  <section id="servicios" data-animate>
    <h2>Servicios</h2>
    <div class="services">
      <div class="service-card">
        <i>🖥️</i>
        <h3>Soporte Técnico Remoto</h3>
        <p>Instalación Windows, limpieza de virus, instalación Office, respaldo de datos.</p>
        <p><strong>Desde ARS 10.000</strong></p>
      </div>
      <div class="service-card">
        <i>⚙️</i>
        <h3>Mantenimiento Mensual</h3>
        <p>Planes de soporte remoto preventivo y correctivo.</p>
        <p><strong>Particulares: ARS 8.000/mes</strong></p>
        <p><strong>Negocios: ARS 20.000/mes</strong></p>
      </div>
      <div class="service-card">
        <i>📚</i>
        <h3>Clases Online</h3>
        <p>Word, Excel, Zoom, homebanking y más.</p>
        <p><strong>ARS 3.500 por clase o 4 por ARS 12.000</strong></p>
      </div>
      <div class="service-card">
        <i>💻</i>
        <h3>Programación y Automatización</h3>
        <p>Scripts, páginas web simples, automatización en Excel.</p>
        <p><strong>Desde ARS 15.000</strong></p>
      </div>
    </div>
  </section>

  <section id="sobre-mi" data-animate>
    <h2>Sobre mí</h2>
    <div class="about">
      <p>Soy <strong>Erick Saavedra</strong>, técnico en informática con más de 10 años de experiencia y estudiante de la Tecnicatura en Programación. Me destaco por <strong>seriedad, compromiso y confianza</strong>. Mi objetivo es que cada cliente tenga un servicio confiable, sin preocupaciones y con acompañamiento real.</p>
    </div>
  </section>

  <section id="contacto" data-animate>
    <h2>Contacto</h2>
    <div class="contact">
      <p>📧 Email: <a href="mailto:erick.soporte@gmail.com" style="color:white;">erick.soporte@gmail.com</a></p>
      <p>🕒 Horarios: Lunes a Sábado – 9:00 a 20:00</p>
      <a href="https://wa.me/5491153448911" target="_blank">Escribime por WhatsApp</a>
    </div>
  </section>

  <footer>
    <p>© 2025 Erick Saavedra - Soporte Informático & Programación</p>
  </footer>

  <script>
    // Animación al hacer scroll
    const items = document.querySelectorAll('[data-animate]');
    const onScroll = () => {
      items.forEach(item => {
        const rect = item.getBoundingClientRect();
        if (rect.top < window.innerHeight - 100) {
          item.classList.add('visible');
        }
      });
    };
    window.addEventListener('scroll', onScroll);
    onScroll();
  </script>

</body>
</html>
