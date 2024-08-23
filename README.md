<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aires Nuevos NQN</title>
    <style>
        /* Estilos Generales */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        
        header {
            background-color: #ff0000;
            padding: 10px 20px;
            display: flex;
            align-items: center;
            position: relative;
            flex-direction: column; /* Alinea los elementos en columna */
        }
        
        .header-content {
            display: flex;
            align-items: center; /* Alinea los elementos verticalmente */
            justify-content: center; /* Centra los elementos horizontalmente */
            text-align: center;
            width: 100%;
        }
        
        #logo {
            height: 70px;
            margin-right: 15px; /* Espacio entre logo y texto */
        }
        
        h1 {
            font-size: 2.0em;
            color: #000000;
            margin: 0;
            padding: 0;
        }
        
        h2 {
            font-size: 1.0em;
            color: #a5a5a5;
            margin: 0;
        }
        
        nav {
            background-color: #ff0000;
            padding: 10px;
            text-align: center;
            display: flex;
            justify-content: center;
            position: relative;
        }
        
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            overflow-x: auto;
        }
        
        nav ul li {
            margin: 0 15px;
        }
        
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.2em;
        }
        
        .menu-right {
            position: absolute;
            right: 20px;
            top: 10px; /* Movido hacia arriba */
        }
        
        .promo-video-container {
            width: 100%;
            height: 150px; /* Ajustado para hacer más fino */
            overflow: hidden;
            margin-bottom: 10px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .promo-video {
            width: 100%;
            height: 100%;
            object-fit: cover; /* Ajusta la imagen/video para que cubra el contenedor */
        }

        /* Estilos de Noticias */
        #titulares {
            background-color: #fff;
            padding: 20px;
            margin: 20px;
            display: flex;
        }
        
        #titulares h2 {
            color: #333;
            margin-bottom: 20px;
        }

        .noticia-principal {
            width: 65%; /* Ocupa el 65% del espacio */
            margin-right: 20px;
            display: flex;
            flex-direction: column;
            border-bottom: 2px solid #ccc;
            padding-bottom: 15px;
        }
        
        .noticia-principal img {
            width: 100%;
            margin-bottom: 15px;
        }
        
        .noticia-principal h3 {
            font-size: 2.4em;
            color: #333;
            margin-bottom: 10px;
        }
        
        .noticia-principal h4 {
            font-size: 1.4em;
            color: #777;
            margin-bottom: 10px;
        }
        
        .noticia-principal p {
            font-size: 1.2em;
            color: #666;
        }

        .noticias-column {
            width: 35%; /* Ocupa el 35% del espacio */
            display: flex;
            flex-direction: column;
            gap: 20px;
        }
        
        .noticia {
            display: flex;
            border-bottom: 2px solid #ccc;
            padding-bottom: 15px;
        }
        
        .noticia img {
            width: 40%;
            margin-right: 15px;
        }
        
        .noticia h3 {
            font-size: 1.8em;
            color: #333;
            margin-bottom: 10px;
        }
        
        .noticia h4 {
            font-size: 1.2em;
            color: #777;
            margin-bottom: 10px;
        }
        
        .noticia p {
            font-size: 1em;
            color: #666;
        }

        /* Estilos de Publicidad */
        .ads-container {
            display: flex;
            justify-content: center;
            margin: 20px 0;
        }
        
        .ad {
            width: 300px; /* Aumentar el ancho de los bloques de publicidad */
            height: 200px; /* Aumentar el alto para mantener proporción */
            background-color: #ddd;
            margin: 0 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2em;
            color: #333;
        }

        video {
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <img src="c:\Users\Yamil Jara\OneDrive\Imágenes\Escritorio\airesnuevosNEUQUEN\logo final .png" id="logo">
            <div>
                <h1>airesnuevosNQN</h1>
                <h2>"El nuevo NEUQUÉN en noticias"</h2>
            </div>
        </div>
        <div class="menu-right">
            <button style="background-color: #C0C0C0; padding: 10px 20px; font-size: 1.1em; border: none; cursor: pointer;">Escuchar radio en vivo</button>
        </div>
    </header>
    
    <nav>
        <ul>
            <li><a href="#">Regionales</a></li>
            <li><a href="#">Provinciales</a></li>
            <li><a href="#">Nacionales</a></li>
            <li><a href="#">Internacionales</a></li>
            <li><a href="#">Deporte</a></li>
            <li><a href="#">Cultura</a></li>
            <li><a href="#">Política</a></li>
            <li><a href="#">Espectáculos</a></li>
        </ul>
    </nav>
    
    <!-- Publicidad -->
    <div class="promo-video-container">
        <video class="promo-video" autoplay muted loop>
            <source src="c:\Users\Yamil Jara\OneDrive\Imágenes\Escritorio\airesnuevosNEUQUEN\publicidad gestión rioseco.mp4" type="video/mp4">
        </video>
    </div>
    
    <div class="ads-container">
        <div class="ad">
            <video autoplay muted loop>
                <source src="c:\Users\Yamil Jara\OneDrive\Imágenes\Escritorio\airesnuevosNEUQUEN\cerrro publi.mp4" type="video/mp4">
            </video>
        </div>
        <div class="ad">
            <video autoplay muted loop>
                <source src="c:\Users\Yamil Jara\OneDrive\Imágenes\Escritorio\airesnuevosNEUQUEN\publi 3.mp4" type="video/mp4">
            </video>
        </div>
        <div class="ad">
            <video autoplay muted loop>
                <source src="c:\Users\Yamil Jara\OneDrive\Imágenes\Escritorio\airesnuevosNEUQUEN\publicidad planetG.mp4" type="video/mp4">
            </video>
        </div>
    </div>
    
    <main>
        <section id="titulares">
            <h2>Titulares</h2>
            
            <!-- Noticia Principal -->
            <div class="noticia-principal">
                <img src="c:\Users\Yamil Jara\OneDrive\Imágenes\Escritorio\airesnuevosNEUQUEN\pagina de noticias\imagenes de noticias\conflicto docente .png" alt="Imagen de la noticia">
                <div>
                    <h3>Los docentes siguen en lucha tras días de conflicto con el gobierno de Rolando Figueroa</h3>
                    <h4>La historia se repite, y los docentes son atacados por los gobiernos provinciales una vez más</h4>
                    <p>Breve descripción de la noticia que da un adelanto sobre el contenido principal del artículo.</p>
                </div>
            </div>

            <!-- Columna de Noticias Secundarias -->
            <div class="noticias-column">
                <div class="noticia">
                    <img src="c:\Users\Yamil Jara\OneDrive\Imágenes\Escritorio\airesnuevosNEUQUEN\pagina de noticias\Captura de pantalla 2024-08-21 012400.png" alt="Imagen de la noticia">
                    <div>
                        <h3>Más vacunas y el factor Delta</h3>
                        <h4>Subtítulo de la noticia</h4>
                        <p>Breve descripción de la noticia que da un adelanto sobre el contenido principal del artículo.</p>
                    </div>
                </div>

                <div class="noticia">
                    <img src="c:\Users\Yamil Jara\OneDrive\Imágenes\Escritorio\airesnuevosNEUQUEN\pagina de noticias\Captura de pantalla 2024-08-21 012400.png" alt="Imagen de la noticia">
                    <div>
                        <h3>Elecciones 2023: el panorama se aclara</h3>
                        <h4>Subtítulo de la noticia</h4>
                        <p>Breve descripción de la noticia que da un adelanto sobre el contenido principal del artículo.</p>
                    </div>
                </div>

                <div class="noticia">
                    <img src="c:\Users\Yamil Jara\OneDrive\Imágenes\Escritorio\airesnuevosNEUQUEN\pagina de noticias\Captura de pantalla 2024-08-21 012400.png" alt="Imagen de la noticia">
                    <div>
                        <h3>El impacto de la inflación en los hogares</h3>
                        <h4>Subtítulo de la noticia</h4>
                        <p>Breve descripción de la noticia que da un adelanto sobre el contenido principal del artículo.</p>
                    </div>
                </div>

                <div class="noticia">
                    <img src="c:\Users\Yamil Jara\OneDrive\Imágenes\Escritorio\airesnuevosNEUQUEN\pagina de noticias\Captura de pantalla 2024-08-21 012400.png" alt="Imagen de la noticia">
                    <div>
                        <h3>Cómo preparar tu hogar para el invierno</h3>
                        <h4>Subtítulo de la noticia</h4>
                        <p>Breve descripción de la noticia que da un adelanto sobre el contenido principal del artículo.</p>
                    </div>
                </div>
            </div>
        </section>
    </main>
</body>
</html>
