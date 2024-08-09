<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fabiana Melian Depilaciones y Perfumes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2313168;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: #fff;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: #000;
        }
        section {
            padding: 20px;
            margin: 10px;
        }
        .services, .products, .gallery {
            display: flex;
            flex-wrap: wrap;
        }
        .service, .product, .gallery-item {
            flex: 1 1 200px;
            background-color: #fff;
            margin: 10px;
            padding: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .product img, .gallery-item img {
            max-width: 100%;
            height: auto;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Fabiana Melian Depilaciones y Perfumes</h1>
    </header>
    <nav>
        <a href="#peluqueria">Peluquería</a>
        <a href="#perfumeria">Perfumería</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section id="peluqueria">
        <h2>Servicios de Peluquería</h2>
        <div class="services">
            <div class="service">
                <h3>Corte de Cabello</h3>
                <p>$260 damas y caballeros.</p>
            </div>
            <div class="service">
                <h3>Tintas</h3>
                <p>$200 solo aplicacion brushing y planchita total $520.</p>
            </div>
            <div class="service">
                <h3>Planchitas</h3>
                <p>$250.</p>
            </div>
            <div class="service">
                <h3>Depilaciones</h3>
                <p>Cejas y bozo $200,Ceja solo $150, depilacion completa $1500 .</p>
            </div>
            <div class="service">
                <h3>Brushing</h3>
                <p>$250.</p>
            </div>
        </div>
        <h3>Galería de Trabajos</h3>
        <div class="gallery">
            <div class="gallery-item">
                <img src="images/depilacion.jpg" alt="Trabajo de peluquería 1">
            </div>
            <div class="gallery-item">
                <img src="images/clienta-seca-cabello-peluqueria_23-2150771297.jpg" alt="Trabajo de peluquería 2">
            </div>
            <!-- Agrega más imágenes según sea necesario -->
        </div>
    </section>
    <section id="perfumeria">
        <h2>Perfumería</h2>
        <div class="products">
            <div class="product">
                <img src="images/perfumes1.jpg" alt="Perfume 1">
                <h3>Perfume 1</h3>
                <p>Precio: $350</p>
            </div>
        </div>
        <div>
            <h3>Oferta Especial</h3>
            <p>3 perfumes por $1000</p>
            <img src="images/3x1000.jpg" alt="Oferta 3x1000">
        </div>
        <h3>Galería de Perfumes</h3>
        <div class="gallery">
            <div class="gallery-item">
                <img src="images/moments victori.jpg" alt="Perfume 1">
            </div>
            <div class="gallery-item">
                <img src="images/pack.jpg" alt="Perfume 2">
            </div>
            <!-- Agrega más imágenes según sea necesario -->
        </div>
    </section>
    <section id="contacto">
        <h2>Contacto</h2>
        <p>Teléfono: 099938655</p>
        <p>Dirección: Colón 854</p>
        <form>
            <label for="name">Nombre:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="email">Correo Electrónico:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="message">Mensaje:</label><br>
            <textarea id="message" name="message"></textarea><br>
            <input type="submit" value="Enviar">
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Fabiana Melian Depilaciones y Perfumes. Todos los derechos reservados.</p>
    </footer>
</body>
