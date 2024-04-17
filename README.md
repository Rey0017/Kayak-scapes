```html
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kayak Scapes - Tours en Kayak</title>
    <style>
        /* Estilos CSS para la página */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            padding: 20px;
        }

        .intro {
            text-align: center;
        }

        .tours {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .tour {
            border: 1px solid #ccc;
            padding: 10px;
            border-radius: 5px;
            text-align: center;
        }

        .tour img {
            max-width: 100%;
            border-radius: 5px;
        }

        .contact {
            background-color: #f0f0f0;
            padding: 20px;
            border-radius: 5px;
        }

        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>

<body>
    <header>
        <h1>Kayak Scapes</h1>
        <p>Experiencias de tours en kayak inolvidables</p>
    </header>

    <section class="intro">
        <h2>Bienvenido a Kayak Scapes</h2>
        <p>Disfruta de aventuras únicas en kayak en las hermosas aguas de Cabarete. Ofrecemos tours guiados y experiencias personalizadas para todos los niveles.</p>
    </section>

    <section class="tours">
        <h2>Nuestros Tours</h2>
        <div class="tour">
            <img src="https://example.com/tour1.jpg" alt="Tour 1">
            <h3>Tour Aventura en Río</h3>
            <p>Explora los paisajes impresionantes de los ríos de Cabarete con nuestro tour de aventura en río. Duración: 3 horas.</p>
        </div>
        <div class="tour">
            <img src="https://example.com/tour2.jpg" alt="Tour 2">
            <h3>Tour al Atardecer</h3>
            <p>Disfruta de un tour relajante al atardecer mientras remas en las aguas tranquilas. Una experiencia inolvidable. Duración: 2 horas.</p>
        </div>
        <div class="tour">
            <img src="https://example.com/tour3.jpg" alt="Tour 3">
            <h3>Tour en Manglares</h3>
            <p>Descubre los manglares de Cabarete con nuestro tour especializado. Aprende sobre la biodiversidad local. Duración: 4 horas.</p>
        </div>
    </section>

    <section class="contact">
        <h2>Contáctanos</h2>
        <p>Ubicación: Cabarete Callejón de la Loma Calle 6</p>
        <p>Teléfono: +1 809-123-4567</p>
        <p>Email: info@kayakscapes.com</p>
    </section>

    <footer>
        <p>&copy; 2024 Kayak Scapes. Todos los derechos reservados.</p>
    </footer>
</body>

</html>
```

