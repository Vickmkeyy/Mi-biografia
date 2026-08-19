<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mi Biografía</title>
  <style>
    body { 
      background-color: #E0F2FE; 
      font-family: Arial, sans-serif; 
      max-width: 700px; 
      margin: 40px auto; 
      padding: 30px; 
      border-radius: 20px; 
      box-shadow: 0 0 30px rgba(1,3,0,0.2); 
    }
    h1 { 
      color: #0c0406; 
      text-align: center; 
      font-size: 36px; 
    }
    h2 { 
      color: #F43F5E; 
      border-bottom: 3px solid #3498db; 
      padding-bottom: 8px; 
    }
    img { 
      display: block; 
      margin: 20px auto; 
      border-radius: 50%; 
      border: 4px solid #3498db; 
      width: 200px; 
      height: 200px; 
      object-fit: cover; 
    }
    ul { 
      background-color: #F0F9FF; 
      padding: 20px 30px; 
      border-radius: 12px; 
      list-style: none; 
    }
    ul li { 
      padding: 8px 0; 
      border-bottom: 1px solid #bdc3c7; 
    }
    ul li:last-child { 
      border-bottom: none; 
    }
    a { 
      color: #F43F5E; 
      text-decoration: none; 
      font-weight: bold; 
    }
    a:hover { 
      text-decoration: underline; 
      color: #1E293B; 
    }

    /* Estilos de la sección de música */
    .musica-favorita {
      max-width: 800px;
      margin: 40px auto;
      padding: 24px;
    }
    .musica-favorita h2 {
      text-align: center;
      font-size: 1.8rem;
      color: #1a1a1a;
      margin-bottom: 24px;
    }
    .canciones-grid {
      display: flex;
      flex-direction: column;
      gap: 16px;
    }
    .cancion-card {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 16px 20px;
      background-color: #f9f9f9;
      border-radius: 8px;
      border: 1px solid #e0e0e0;
    }
    .cancion-info h3 {
      margin: 0;
      font-size: 1.1rem;
      color: #222;
    }
    .cancion-info p {
      margin: 4px 0 0 0;
      font-size: 0.9rem;
      color: #666;
    }
    .btn-youtube {
      display: inline-block;
      padding: 8px 16px;
      background-color: #FF0000;
      color: #ffffff;
      text-decoration: none;
      font-weight: 600;
      font-size: 0.85rem;
      border-radius: 4px;
      transition: background-color 0.2s ease;
    }
    .btn-youtube:hover {
      background-color: #cc0000;
    }
  </style>
</head>
<body>

  <h1>¡Hola! Somos Valentin Garro y Victoria Guayan</h1>
  <p>Esta es nuestra primera página web.</p>

  <h2>Sobre nosotros</h2>
  
  <h3>Valentin:
  <p><h5>Tengo 14, cumplo los 15 el 23/9, juego fútbol, con el celu, etc. Mis notas mehhhh.... pero bueno, esta es mi primera página web.</p>

  <h3>Victoria:
  <p><h5>Tengo 14 años, cumplo 15 el 5 de octubre del 2026, me gusta editar, dibujar, pasar tiempo con mis amigos, estar con mis gatos y comer.</p>

 <h2>Nuestros hobbies
  
  <h3>Valentin:
  <ul>
    <li>Jugar INK Games</li>
    <li>Jugar fútbol</li>
    <li>Hablar con Vicky Guayan</li>
  </li>

  <h3>Victoria:</h3>
  <ul>
    <li>Jugar con el celular</li>
    <li>Escribir historias</li>
    <li>Ver series</li>
  </ul>

  <h2>Nuestros Futuros</h2>

  <h3>Valentin:</h3>
  <button onclick="mostrarFuturoValentin()">🔮 Ver mi futuro</button>
  <p id="mensajeValentin"></p>
  <img src="https://img.magnific.com/fotos-premium/oficial-policia-latinoamericano_1243905-1032.jpg?semt=ais_hybrid&w=740&q=80" alt="Foto de policía" width="200">

  <h3>Victoria:</h3>
  <button onclick="mostrarFuturoVictoria()">🔮 Ver mi futuro</button>
  <p id="mensajeVictoria"></p>
  <img src="https://us.123rf.com/450wm/itchaznong/itchaznong2211/itchaznong221100760/193929955-abogada-mujer-de-negocios-que-trabaja-o-lee-un-contrato-de-acuerdo-en-el-lugar-de-trabajo-de-la.jpg?ver=6" alt="Foto de abogada" width="200">

  <p><strong>Mi Instagram:</strong> <a href="https://instagram.com/TU_USUARIO" target="_blank">@vickyg130_1</a></p>

  <section class="musica-favorita">
    <h2>Mi música favorita</h2>
    
    <div class="canciones-grid">
      <div class="cancion-card">
        <div class="cancion-info">
          <h3>Verte de cerca</h3>
          <p>De Airbag</p>
        </div>
        <a href="https://www.youtube.com/results?search_query=Verte+de+cerca+Airbag" target="_blank" rel="noopener noreferrer" class="btn-youtube">
          Ver en YouTube
        </a>
      </div>

      <div class="cancion-card">
        <div class="cancion-info">
          <h3>Me gustas tanto</h3>
          <p>De Miranda!</p>
        </div>
        <a href="https://www.youtube.com/results?search_query=Me+gustas+tanto+Miranda" target="_blank" rel="noopener noreferrer" class="btn-youtube">
          Ver en YouTube
        </a>
      </div>

      <div class="cancion-card">
        <div class="cancion-info">
          <h3>El Dios</h3>
          <p>De Kapo</p>
        </div>
        <a href="https://www.youtube.com/results?search_query=El+Dios+de+Kapo" target="_blank" rel="noopener noreferrer" class="btn-youtube">
          Ver en YouTube
        </a>
      </div>
    </div>
  </section>

  <button onclick="cambiarColor()">🎨 Cambiar color de fondo</button>

  <script>
    // Función para el botón de Valentin
    function mostrarFuturoValentin() { 
      const mensajes = [ 
        '👮 Seré un policía', 
        '🏠 Viviré en un departamento', 
        '👩‍❤️‍👨 Viviré con mi esposa' 
      ]; 
      const indice = Math.floor(Math.random() * mensajes.length); 
      document.getElementById('mensajeValentin').innerHTML = mensajes[indice]; 
    }

    // Función para el botón de Victoria
    function mostrarFuturoVictoria() { 
      const mensajes = [ 
        '⚖️ Seré abogada', 
        '👦 👧 Tendré dos hijos', 
        '🐱🦦 Tendré un gato y un hurón de mascota' 
      ]; 
      const indice = Math.floor(Math.random() * mensajes.length); 
      document.getElementById('mensajeVictoria').innerHTML = mensajes[indice]; 
    }

    // Función para cambiar el color de fondo de la página
    function cambiarColor() { 
      const colores = ['#ffedd5', '#e0f2fe', '#fce4ec', '#e8f5e9', '#f3e5f5']; 
      const indice = Math.floor(Math.random() * colores.length); 
      document.body.style.backgroundColor = colores[indice]; 
    }
  </script>

</body>
</html>
