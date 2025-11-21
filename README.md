# salgadohumberto588-pilau.sername.github.io
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">

    <!-- SEO BÁSICO -->
    <title>ROACH RAIDS - Videojuego Oficial | Acción Pixel Art</title>
    <meta name="description" content="ROACH RAIDS es un videojuego de acción pixel art donde un estudiante lucha contra chinches mutantes creadas por leche radioactiva CONASUPO.">
    <meta name="keywords" content="videojuego, pixel art, acción, chinches mutantes, México, indie game, estudiante, conasupo">
    <meta name="author" content="Kaiju Studios">
    <meta name="robots" content="index, follow">

    <!-- HACE QUE GOOGLE MUESTRE BIEN LA PÁGINA EN CELULAR -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- URL CANÓNICA (IMPORTANTE PARA GOOGLE) -->
    <link rel="canonical" href="https://tudominio.com/">

    <!-- SEGURIDAD (solo funciona si subes la página a tu hosting HTTPS) -->
    <meta http-equiv="Content-Security-Policy" content="default-src 'self' https://fonts.googleapis.com; style-src 'self' 'unsafe-inline' https://fonts.googleapis.com; font-src https://fonts.gstatic.com; img-src 'self' data:;">

    <!-- Fuente pixel art -->
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">

    <style>
        body {
            margin: 0;
            font-family: "Press Start 2P", monospace;
            background: #0a0a0f url('fondo_pixelart.jpg') center/cover fixed no-repeat;
            color: white;
            text-align: center;
            overflow-x: hidden;
        }

        body::after {
            content: "";
            position: fixed;
            top: 0; left: 0;
            width: 100%; height: 100%;
            pointer-events: none;
            background: repeating-linear-gradient(
                rgba(255,255,255,0.02),
                rgba(255,255,255,0.02) 2px,
                rgba(0,0,0,0.05) 4px
            );
            mix-blend-mode: overlay;
        }

        header {
            padding: 80px 20px;
            background-color: rgba(0,0,0,0.4);
            text-shadow: 3px 3px 0 #b80000;
        }

        h1 {
            font-size: 2.6rem;
        }

        .descripcion {
            max-width: 800px;
            margin: auto;
            font-size: 0.9rem;
            line-height: 1.8;
            text-shadow: 2px 2px 0 #000;
            background: rgba(0,0,0,0.5);
            padding: 20px;
            border-radius: 10px;
            border: 3px solid #ff3131;
        }

        .seccion {
            margin-top: 60px;
        }

        .btn {
            display: inline-block;
            margin-top: 40px;
            padding: 18px 35px;
            font-size: 0.9rem;
            background: #ff3131;
            border: 4px solid white;
            border-radius: 6px;
            box-shadow: 0 0 15px #ff3131, inset 0 0 10px #000;
            color: white;
            text-decoration: none;
            transition: 0.2s;
        }

        .btn:hover {
            background: #ff5050;
            transform: scale(1.1);
            box-shadow: 0 0 25px #ff5050;
        }

        .caracteristicas {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            max-width: 900px;
            margin: 40px auto;
        }

        .card {
            background: rgba(0,0,0,0.55);
            padding: 20px;
            border: 3px solid #ff3131;
            border-radius: 10px;
            text-shadow: 2px 2px 0 #000;
        }

        footer {
            margin-top: 60px;
            padding: 30px;
            font-size: 0.7rem;
            color: #aaa;
        }
    </style>
</head>

<body>

<header>
    <h1>ROACH RAIDS</h1>
    <p>¡Sobrevive. Aplasta. Extermina.</p>
</header>

<section class="seccion">
    <div class="descripcion">
        <p>
            En un México alterno, un lote ilegal de <b>leche radioactiva CONASUPO</b>
            ha mutado a las chinches convirtiéndolas en criaturas feroces y sedientas
            de sangre.
        </p>
        <p>
            Tú eres <b>El Estudiante</b>, un joven de ingeniería que debe sobrevivir usando
            herramientas caseras, combate urbano y pura desesperación.
        </p>
        <p>
            ¿Podrás detener la plaga antes de que devore toda la ciudad?
        </p>
    </div>
</section>

<section class="seccion">
    <h2>CARACTERÍSTICAS DEL JUEGO</h2>

    <div class="caracteristicas">
        <div class="card">🪳 Enemigos: chinches mutantes con ácido</div>
        <div class="card">🎮 Pixel Art al estilo 16-bits</div>
        <div class="card">🧪 Jefes nacidos de radiación</div>
        <div class="card">🏫 Un estudiante como héroe improvisado</div>
        <div class="card">🔧 Armas caseras y mejoras raras</div>
        <div class="card">🔥 Acción rápida y humor negro</div>
    </div>
</section>

<a class="btn" href="#">BETA DISPONIBLE (PRÓXIMAMENTE)</a>

<footer>
    ROACH RAIDS © 2025 — Derechos reservados por Kaiju Studios
</footer>

</body>
</html>
