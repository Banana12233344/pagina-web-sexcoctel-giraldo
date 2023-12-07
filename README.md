<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SEXCOCTEL</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Estilos adicionales */
        /* ... (se agregan los estilos proporcionados anteriormente) ... */
    </style>
</head>
<body>

    <!-- Cabecera o header -->
    <header class="main-header">
        <div class="logo-container">
            <img src="SEXCOCTEL.jpg" alt="Logo de la empresa" style="width: 150px; height: auto;">
            <h1>SEXCOCTEL</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#presentacion">Presentación</a></li>
                <li><a href="#mision-vision">Misión y Visión</a></li>
                <li><a href="#informacion">Información de Contacto</a></li>
                <li><a href="#galeria">Galería</a></li>
                <li><a href="#video">Video</a></li>
                <li><a href="#autor">Autor</a></li>
            </ul>
        </nav>
    </header>

    <!-- Cuerpo de la página -->
    <main>
        <section id="presentacion">
            <h2>Presentación de la Empresa</h2>
            <p>Sexcoctel es una empresa innovadora que se destaca en el competitivo mercado de bebidas gracias a su enfoque único en la creación y comercialización de una amplia gama de cócteles premium. Su enfoque en el diseño de empaques atractivos, presentaciones visuales cautivadoras y un servicio al cliente excepcional ha contribuido a consolidar la lealtad de sus clientes.</p>
        </section>
        <section id="mision-vision">
            <h2>Misión</h2>
            <p>Ofrecer a nuestros clientes una experiencia de cóctel única y emocionante que los haga sentir sexys y sofisticados. Utilizamos solo los ingredientes más frescos y de alta calidad para crear cócteles que deleiten los sentidos y satisfagan el paladar.</p>
        </section>
        <section id="vision">
            <h2>Visión</h2>
            <p>Ser la marca líder en el mercado de cócteles sexys, reconocida por su innovación, calidad y excelencia en el servicio al cliente.</p>
        </section>
        <section id="valores">
            <h2>Valores</h2>
            <p>Pasión por la calidad, la creatividad y la innovación. Compromiso con la satisfacción del cliente y la excelencia en el servicio. Responsabilidad social y ambiental.</p>
        </section>

        <!-- Galería de Fotos (Carousel de Bootstrap) -->
        <section id="galeria">
            <h2>Galería de Fotos</h2>
            <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="imagen1.webp" class="d-block w-100" alt="Imagen 1">
                    </div>
                    <div class="carousel-item">
                        <img src="imagen2.jpg" class="d-block w-100" alt="Imagen 2">
                    </div>
                    <!-- Agregar más imágenes según sea necesario -->
                </div>
                <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="sr-only">Next</span>
                </a>
            </div>
        </section>

        <!-- Video -->
        <section id="video">
            <h2>Video</h2>
            <div class="video-container">
                <!-- Inserta el reproductor de video aquí -->
                <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
            </div>
        </section>
    </main>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

