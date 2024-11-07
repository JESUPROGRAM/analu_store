# analu_store
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Analu Store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Encabezado -->
    <header>
        <h1>Analu Store</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#catalogo">Catálogo</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <!-- Sección de inicio -->
    <section id="inicio">
        <h2>Bienvenidos a Analu Store</h2>
        <p>Encuentra productos de maquillaje de alta calidad. Realza tu belleza con nuestra exclusiva colección.</p>
    </section>

    <!-- Sección de productos -->
    <section id="productos">
        <h2>Productos de Maquillaje Destacados</h2>
        <div class="product">
            <h3>Labial Mate Color Vino</h3>
            <p>Duradero y de alta pigmentación. Precio: $25,000 COP</p>
        </div>
        <div class="product">
            <h3>Paleta de Sombras Naturales</h3>
            <p>10 tonos perfectos para cualquier ocasión. Precio: $60,000 COP</p>
        </div>
        <div class="product">
            <h3>Base de Maquillaje Líquida</h3>
            <p>Acabado natural para todo tipo de piel. Precio: $45,000 COP</p>
        </div>
        <div class="product">
            <h3>Rímel Volumen Extremo</h3>
            <p>Pestañas más largas y definidas. Precio: $30,000 COP</p>
        </div>
    </section>

    <!-- Sección de catálogo -->
    <section id="catalogo">
        <h2>Catálogo Completo</h2>
        <p>Explora nuestra colección de maquillaje: bases, sombras, labiales, brochas y más.</p>
    </section>

    <!-- Sección de contacto -->
    <section id="contacto">
        <h2>Contacto</h2>
        <p>¿Tienes dudas o deseas asesoría sobre nuestros productos? ¡Escríbenos!</p>
        <form action="#" method="POST">
            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" required>
            <br>
            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea>
            <br>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <!-- Pie de página -->
    <footer>
        <p>© 2024 Analu Store. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
