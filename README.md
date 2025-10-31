<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portafolio - Agustina Chacón</title>

  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #fff;
      color: #333;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }

    header {
      background-color: #f8d7da;
      color: #333;
      text-align: center;
      padding: 40px 20px;
      border-bottom: 3px solid #f3b6c4;
    }

    /* 🌸 Foto de perfil */
    .foto-perfil {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #f3b6c4;
      display: block;
      margin: 0 auto 15px auto;
      box-shadow: 0 0 8px #f3b6c4;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
      color: #444;
    }

    header h2 {
      font-weight: 400;
      margin: 5px 0 10px;
      color: #666;
    }

    section {
      padding: 40px 10%;
    }

    h3 {
      color: #e07a9a;
      border-bottom: 2px solid #f3b6c4;
      padding-bottom: 5px;
      margin-bottom: 15px;
    }

    p, li {
      font-size: 1em;
    }

    .info, .contacto {
      background-color: #fceef0;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 20px;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li {
      background: #fdf0f2;
      padding: 8px 12px;
      border-radius: 8px;
      margin: 6px 0;
    }

    a {
      color: #e07a9a;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    footer {
      background-color: #f8d7da;
      text-align: center;
      padding: 15px;
      color: #444;
      font-size: 14px;
      border-top: 3px solid #f3b6c4;
    }

    .redes a {
      margin: 0 10px;
      color: #e07a9a;
      font-weight: bold;
    }

    .redes a:hover {
      text-decoration: underline;
    }

    @media (max-width: 768px) {
      section {
        padding: 25px 8%;
      }
    }
  </style>
</head>

<body>

  <header>
    <img src="foto.jpg" alt="Foto de Agustina Chacón" class="foto-perfil">
    <h1>Agustina Chacón</h1>
    <h2>Estudiante de Programación — Mendoza, Argentina</h2>
    <p>📧 <a href="mailto:mariaagustinachacon0@gmail.com">mariaagustinachacon0@gmail.com</a> | 📞 2622561486</p>
  </header>

  <section id="sobre-mi">
    <h3>Sobre mí</h3>
    <p>Me apasiona el mundo de la tecnología y cómo puede transformar nuestra vida diaria. Me interesa aprender sobre desarrollo web, programación y nuevas herramientas digitales. Disfruto crear proyectos que resuelvan problemas reales y seguir creciendo en este campo en constante evolución.</p>
  </section>

  <section id="educacion">
    <h3>Educación</h3>
    <ul>
      <li>Escuela Primaria: Profesor Dionisio Chaca (2008–2014)</li>
      <li>Escuela Secundaria: Domingo Faustino Sarmiento (2015–2019)</li>
      <li>Estudiante de Programación (en curso)</li>
    </ul>
  </section>

  <section id="proyectos">
    <h3>Proyectos</h3>
    <ul>
      <li><b>Proyecto 1:</b> Página web con HTML y CSS — Sitio estático responsivo</li>
      <li><b>Proyecto 2:</b> Aplicación de tareas con JavaScript — Funcionalidad CRUD en el navegador</li>
      <li><b>Proyecto 3:</b> Blog personal con diseño responsive — Diseño adaptable y navegación</li>
    </ul>
  </section>

  <section id="experiencia">
    <h3>Experiencia laboral</h3>
    <ul>
      <li><b>Panadería Medialuna (2023–2024):</b> Atención al cliente, manejo de redes sociales.</li>
      <li><b>Gomería Gómez (Enero–Mayo 2024):</b> Atención al cliente, community manager.</li>
      <li><b>Galpón de Nueces Mendoza (Dic 2024–May 2025):</b> Empaquetamiento y selección.</li>
      <li><b>AURA Indumentaria (Mayo–Actualidad):</b> Venta de ropa, redes y creación de contenido.</li>
      <li><b>Call Center AP Conection (Agosto 2025):</b> Ventas de portabilidad numérica y fibra óptica.</li>
    </ul>
  </section>

  <section id="habilidades">
    <h3>Habilidades</h3>
    <ul>
      <li>Python</li>
      <li>JavaScript</li>
      <li>HTML & CSS</li>
      <li>Git / GitHub</li>
      <li>MySQL (básico)</li>
      <li>Visual Studio Code</li>
      <li>Microsoft Office</li>
      <li>Google Workspace</li>
      <li>Canva</li>
      <li>Meta Business Suite / Ads</li>
    </ul>
  </section>

  <section id="contacto">
    <h3>Contacto</h3>
    <p><b>País / Provincia:</b> Argentina, Mendoza (CP 5560)</p>
    <p><b>Email:</b> <a href="mailto:mariaagustinachacon0@gmail.com">mariaagustinachacon0@gmail.com</a></p>
    <p><b>Teléfono:</b> 2622561486</p>
  </section>

  <footer>
    <div class="redes">
      <a href="https://github.com/AgustinaChacon" target="_blank">GitHub</a> |
      <a href="https://www.linkedin.com/in/agustina-reyes-a396602b5" target="_blank">LinkedIn</a> |
      <a href="https://www.instagram.com/agustina_chacon" target="_blank">Instagram</a> |
      <a href="https://www.facebook.com/share/173K1s87S8/" target="_blank">Facebook</a>
    </div>
    <p>© 2025 Agustina Chacón — Portafolio Web</p>
  </footer>

</body>
</html>
