<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>MISSION GET HOME - USFQ</title>
    <style>
        /* Estilo general */
        body {
            margin: 0;
            font-family: Cambria, serif;
            background: linear-gradient(120deg, #020024, #5c2d70, #00d4ff);
            color: white;
            overflow-x: hidden;
        }

        /* Encabezado */
        header {
            font-family: 'Press Start 2P', cursive;
            background: rgb(0, 0, 50);
            color: rgb(255, 255, 0);
            text-align: center;
            padding: 20px;
            text-shadow: 2px 2px 5px #000;
            font-size: 2.5rem;
        }

        /* Imagen principal */
        .hero {
            text-align: center;
            margin: 20px 0;
        }

        .hero img {
            width: 80%;
            border-radius: 10px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.6);
        }

        /* Menú lateral */
        .sidebar {
            position: fixed;
            top: 0;
            left: 0;
            height: 100%;
            width: 60px;
            background: rgba(99, 251, 226, 0.9);
            transition: width 0.3s;
            overflow: hidden;
        }

        .sidebar:hover {
            width: 250px;
        }

        .sidebar a {
            color: white;
            text-decoration: none;
            display: block;
            padding: 10px;
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
        }

        .sidebar a:hover {
            background: rgba(0, 0, 100, 0.8);
        }

        /* Contenido */
        .content {
            margin-left: 60px;
            text-align: center;
            margin: 20px;
        }

        h2 {
            font-family: 'Cambria', cursive;
            margin: 20px 0;
        }

        p {
            text-align: justify;
            line-height: 1.6;
        }

        /* Servicios */
        .services {
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .services div {
            background: rgba(255, 255, 255, 0.1);
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            width: 200px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .services div:hover {
            transform: translateY(-10px) scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.4);
        }

        /* Blog */
        .blog {
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .blog article {
            background: rgba(255, 255, 255, 0.1);
            margin: 10px;
            padding: 10px;
            border-radius: 10px;
            width: 200px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .blog article:hover {
            transform: translateY(-10px) scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.4);
        }

        .blog img {
            width: 100%;
            border-radius: 10px;
        }

        /* Lluvia de papeles */
        .confetti {
            position: fixed;
            top: -10%;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 999;
        }

        .confetti div {
            position: absolute;
            width: 10px;
            height: 10px;
            background: hsl(210, 70%, 80%);
            animation: fall 3s infinite ease-in-out;
        }

        @keyframes fall {
            0% {
                transform: translateY(-10%) rotate(0deg);
                opacity: 1;
            }
            100% {
                transform: translateY(110vh) rotate(720deg);
                opacity: 0;
            }
        
        }
        #lista1 {
                list-style-type: disc; /* Muestra viñetas tipo disco (círculos rellenos) */
                list-style-position: inside; /* Coloca las viñetas dentro del contenedor */
                text-align: left; /* Alinea el texto de la lista a la izquierda */
                margin-left: 0; /* Elimina el margen izquierdo predeterminado */
                padding-left: 20px; /* Ajusta el espacio del texto desde la viñeta */
                }

        #qhacemos {
        
                height: 145px;
                width: 185px;
                  }

        #qsomos {
        
        height: 145px;
        width: 185px;
          }
        
        #nuestroequipo {
               text-align: center;
                       }
        
        #controljuego {
        
        height: 145px;
        width: 185px;
          }
        
        #robot {
        
        height: 145px;
        width: 185px;
               }

    </style>
</head>
<body>

    <!-- Menú lateral -->
    <div class="sidebar">
        <a href="index.html">Página Principal</a>
        <a href="page2.html">Página Secundaria</a>
        <a href="page3.html">Página Tercera</a>
        <a href="floresgalacticas.html">¡SORPRESA</a>
    </div>

    <!-- Encabezado -->
    <header>MISSION GET HOME - USFQ</header>

    <!-- Imagen principal -->
    <div class="hero">
        <img src="img1.jpg" alt="Imagen Principal">
    </div>

    <!-- Contenido -->
    <section class="content">
        <h2>Tu Viaje Comienza Aquí</h2>
        <p><center>Explora aventuras y desafíos únicos en una experiencia diseñada para llevarte más allá de lo imaginable.</center></p>
    </section>

    <!-- Servicios -->
    <section class="content">
        <h2>¿Quiénes somos?</h2>
        <div class="services">
            <div>
                <h3>Somos</h3>
                <p>Estudiantes de la mejor carrera <b>Ingeniería en Ciencias de la Computación</b></p>
                <img src="qsomos.jpg" alt="qsomos" id="qsomos">
            </div>
            <div>
                <h3>¿Qué hacemos?</h3>
                <p>Creamos soluciones que parecen de otro mundo</p>
                <img src="qhacemos.jpeg" alt="qhacemos" id="qhacemos">
            </div>
        
            <div>
                <h3>Integrantes de este equipo</h3>
                <ol id="lista1">
                  <li>Daniela Pérez </li>
                  <li>Ariana Muñoz </li>
                  <li>Ani</li>
                  <li>Belén</li>
                  <li>Jesy</li>
                  <li>XXXXX</li>
                  <li>YYYYY</li>
                </ol>    
            </div>
        </div>
    </section>

    <h2 id="nuestroequipo">Nuestro Equipo &#128521;</h2>
    <img src="" alt="" id="">

    <!-- Blog -->
    <section class="content">
        <h2>Nuevo en el Blog</h2>
        <div class="blog">
            <article>
                <h3>Aventura Galáctica</h3>
                <img src="controljuego.jpg" alt="control" id="controljuego">
                <p>Descubre cómo vivir una aventura intergaláctica.</p>
                <p>AQUI LINK DEL JUEGO DE ANI</p>
            </article>
            <article>
                <h3>Top 5 Desafíos</h3>
                <img src="robot.jpg" alt="robot" id="robot">
                <p>Los desafíos más emocionantes para ti.</p>
            </article>
            <article>
                <h3>Nuestro Proyecto</h3>
                <p>Prepárate para ver proyectos llenos de innovación y creatividad</p>
                <p>AQUI VA LA IMAGEN DE NUESTRA CASA DE LEGO </p>
            </article>
        </div>
    </section>

    <!-- Lluvia de papeles -->
    <div class="confetti" id="confetti-container"></div>

    <script>
        // Lluvia de confeti
        const confettiContainer = document.getElementById('confetti-container');
        for (let i = 0; i < 100; i++) {
            const confetti = document.createElement('div');
            confetti.style.left = Math.random() * 100 + 'vw';
            confetti.style.backgroundColor = `hsl(${Math.random() * 360}, 70%, 80%)`;
            confetti.style.animationDuration = Math.random() * 3 + 2 + 's';
            confettiContainer.appendChild(confetti);
        }
    </script>
</body>
</html>
