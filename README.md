# PC2
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ofertas Educativas</title>
</head>
<body>
    <h1>Bienvenido a VentPeru</h1>
    <h2>VENT PERÚ</h2>
    <h3>Acerca de</h3>
    <p>Nosotros</p>
    <h3>Contactanos</h3>
    <p>¿Preguntas o comentarios? ¡Estamos aqui para ayudarte!</p>
    <p>Contáctanos y te responderemos rápidamente.</p>
    <p>Información de contacto:</p>
    <ul>
        <li>Correo Electrónico: info@ventperu.com</li>
        <li>Teléfono: +51 123 456 789</li>
    </ul>

    <h3>Ofertas Educativas</h3>
    <ul id="ofertas">
        <!-- Las ofertas se cargarán dinámicamente aquí -->
    </ul>

    <script>
        const ofertas = [
            "Curso de Matemática",
            "Curso de Inglés",
            "Curso de Comunicaciones"
        ];

        const listaOfertas = document.getElementById("ofertas");

        ofertas.forEach(offer => {
            const listItem = document.createElement("li");
            listItem.textContent = offer;
            listaOfertas.appendChild(listItem);
        });
    </script>
</body>
</html>
