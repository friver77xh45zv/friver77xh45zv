<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sneakers de Lujo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
        }
        header {
            background-color: #000;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        .sneaker {
            border: 1px solid #ddd;
            padding: 20px;
            margin: 10px;
            background-color: #fff;
        }
        .sneaker img {
            width: 100%;
            height: auto;
        }
        .footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Sneakers de Lujo</h1>
    <p>Los mejores sneakers de alta gama para los amantes de la moda</p>
</header>

<nav>
    <a href="#home">Inicio</a>
    <a href="#about">Nosotros</a>
    <a href="#products">Productos</a>
    <a href="#contact">Contacto</a>
</nav>

<div class="container" id="home">
    <h2>Bienvenido a Sneakers de Lujo</h2>
    <p>Descubre nuestra colección exclusiva de sneakers de alta gama. Cada par está cuidadosamente seleccionado para garantizar la mejor calidad y estilo.</p>
</div>

<div class="container" id="about">
    <h2>Nosotros</h2>
    <p>Somos una tienda digital dedicada a ofrecer sneakers de lujo a los entusiastas de la moda. Nuestra misión es proporcionar productos de alta calidad y un excelente servicio al cliente.</p>
</div>

<div class="container" id="products">
    <h2>Productos</h2>
    <div class="sneaker">
        <img src="sneaker1.jpg" alt="Sneaker 1">
        <h3>Sneaker 1</h3>
        <p>Descripción del Sneaker 1. Precio: $300</p>
    </div>
    <div class="sneaker">
        <img src="sneaker2.jpg" alt="Sneaker 2">
        <h3>Sneaker 2</h3>
        <p>Descripción del Sneaker 2. Precio: $350</p>
    </div>
    <!-- Añade más productos según sea necesario -->
</div>

<div class="container" id="contact">
    <h2>Contacto</h2>
    <p>Para consultas y pedidos, contáctanos en <a href="mailto:contacto@sneakersdelujo.com">contacto@sneakersdelujo.com</a> o llámanos al +123 456 7890.</p>
</div>

<div class="footer">
    <p>&copy; 2024 Sneakers de Lujo. Todos los derechos reservados.</p>
</div>

</body>
</html>
