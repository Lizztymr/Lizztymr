<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Papelería Los Papus</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: url('my.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #333;
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
        }

        header {
            background: rgba(255, 255, 255, 0.95);
            padding: 10px;
            width: 100%;
            position: fixed;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        header nav {
            display: flex;
            justify-content: center;
            align-items: center;
        }

        header nav button {
            background: #6a1b9a;
            color: white;
            border: none;
            padding: 10px 20px;
            margin: 0 5px;
            cursor: pointer;
            border-radius: 20px;
            transition: background 0.3s ease;
            font-size: 14px;
            text-transform: uppercase;
        }

        header nav button:hover {
            background: #4a148c;
        }

        .content {
            background-color: rgba(255, 255, 255, 0.95);
            padding: 30px;
            border-radius: 20px;
            margin: 20px 0;
            width: 80%;
            color: #333;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-top: 100px;
        }

        table {
            border-collapse: collapse;
            width: 100%;
            margin: 20px 0;
            border-radius: 10px;
            overflow: hidden;
        }

        th, td {
            border: 1px solid #ddd;
            text-align: left;
            padding: 12px;
            background: rgba(255, 255, 255, 0.8);
        }

        th {
            background-color: #6a1b9a;
            color: white;
        }

        .form-container {
            background: #fff;
            padding: 20px;
            border-radius: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 400px;
            margin: 20px auto; /* Centra el contenedor en el contenedor padre */
        }

        h2 {
            margin-top: 0;
            font-size: 24px;
            color: #444;
            text-align: center;
        }

        label {
            display: block;
            margin-bottom: 8px;
            color: #555;
            font-weight: bold;
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 10px;
        }

        button {
            background: #6a1b9a;
            color: #fff;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 20px;
            width: 100%;
            transition: background 0.3s ease;
            font-size: 16px;
        }

        button:hover {
            background: #4a148c;
        }

        img {
            border-radius: 10px;
        }

        .section-title {
            font-size: 28px;
            color: #444;
            margin-bottom: 20px;
            text-align: center;
        }

        .section-content {
            margin-bottom: 40px;
        }

        .center {
            text-align: center;
        }

        .highlight {
            background: #6a1b9a;
            color: white;
            padding: 5px 10px;
            border-radius: 10px;
        }

        /* Estilos para el contenedor de cookies */
        .cookie-container {
            background: rgba(0, 0, 0, 0.8);
            color: #fff;
            padding: 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 1000;
        }

        .cookie-container button {
            background: #6a1b9a;
            border: none;
            padding: 10px 20px;
            border-radius: 20px;
            margin: 0 5px;
            cursor: pointer;
            transition: background 0.3s ease;
            font-size: 14px;
        }

        .cookie-container button:hover {
            background: #4a148c;
        }

        .cookie-container a {
            color: #6a1b9a;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <button onclick="scrollToSection('mision')">Misión</button>
            <button onclick="scrollToSection('vision')">Visión</button>
            <button onclick="scrollToSection('valores')">Valores</button>
            <button onclick="scrollToSection('productos')">Productos</button>
            <button onclick="scrollToSection('registro')">Registro</button>
            <button onclick="scrollToSection('contacto')">Contacto</button>
        </nav>
    </header>

    <div class="content center">
        <h1 class="section-title">Los Maynards</h1>
        <img src="perro.jpg" width="500" alt="maynards">
        <h3 class="highlight">¡OFERTAS HASTA EL 30% DE DESCUENTO!</h3>
        <div id="mision" class="section-content">
            <h4 class="section-title">Misión</h4>
            <p>Nuestra misión es ofrecer una amplia variedad de productos de papelería de alta calidad y a precios accesibles, promoviendo la creatividad y la educación en nuestra comunidad. Nos esforzamos por brindar un excelente servicio al cliente, garantizando que cada visitante encuentre justo lo que necesita para sus proyectos personales, escolares y profesionales.</p>
        </div>
        <div id="vision" class="section-content">
            <h4 class="section-title">Visión</h4>
            <p>Nuestra visión es ser la papelería líder en la región, reconocida por nuestra calidad, variedad y servicio excepcional. Aspiramos a ser un punto de referencia en el sector, innovando constantemente y adaptándonos a las necesidades cambiantes de nuestros clientes. Queremos ser un lugar donde las ideas cobren vida y se fomenten los valores de la creatividad y el aprendizaje continuo.</p>
        </div>
        <div id="valores" class="section-content">
            <h4 class="section-title">Valores</h4>
            <p>Calidad: Nos comprometemos a ofrecer productos de la más alta calidad para satisfacer las expectativas de nuestros clientes.
                Servicio al Cliente: Valoramos a nuestros clientes y nos esforzamos por brindarles una atención personalizada y amigable.
                Integridad: Actuamos con honestidad y transparencia en todas nuestras operaciones.
                Innovación: Promovemos la creatividad y la innovación en nuestros productos y servicios.
                Compromiso con la Comunidad: Apoyamos el desarrollo educativo y cultural de nuestra comunidad, participando activamente en iniciativas locales.</p>
        </div>
        <h4 class="highlight">DATO CURIOSO:</h4>
        <p>Las papelerías como tiendas especializadas en la venta de artículos de papelería y material de oficina han existido por mucho tiempo, y su origen no se puede atribuir a un único creador. Sin embargo, es posible decir que la idea de establecimientos especializados en la venta de suministros de escritura y papelería surge históricamente junto con el desarrollo de la imprenta y la creciente necesidad de materiales de escritura y papelería. En diferentes épocas y lugares, personas emprendedoras han establecido tiendas que ofrecen estos productos, adaptándose a las necesidades cambiantes de la sociedad. Por lo tanto, no hay un único "creador" de las papelerías en el sentido moderno, sino más bien una evolución orgánica de este tipo de establecimientos a lo largo del tiempo.</p>
        <div id="productos" class="section-content">
            <h3 class="section-title">PRODUCTOS A LA VENTA</h3>
            <table>
                <tr>
                    <th>Producto</th>
                    <th>Descripción</th>
                    <th>Precio</th>
                    <th>Imagen</th>
                </tr>
                <tr>
                    <td>CUADERNO</td>
                    <td>100 Hojas de papel bond, cualquier rayado</td>
                    <td>$30</td>
                    <td><img src="cuadernos.jpg" alt="Cuaderno" width="100"></td>
                </tr>
                <tr>
                    <td>LAPICES DE COLORES</td>
                    <td>Estuche de 12 o 24 lápices de colores</td>
                    <td>$70 y $130</td>
                    <td><img src="colores.jpg" alt="Lápices de Colores" width="100"></td>
                </tr>
                <tr>
                    <td>LAPICES Y BOLIGRAFOS</td>
                    <td>De todos los tipos y colores</td>
                    <td>$5 c/u</td>
                    <td><img src="bolis.jpg" alt="Lápices y Bolígrafos" width="100"></td>
                </tr>
                <tr>
                    <td>MARACADORES</td>
                    <td>De todos los tipos y colores</td>
                    <td>$50</td>
                    <td><img src="marcadore.jpg" alt="Marcadores" width="100"></td>
                </tr>
                <tr>
                    <td>HOJAS BLANCAS O DE COLORES</td>
                    <td>Carta, oficio, tamaño A4</td>
                    <td>$1 c/u</td>
                    <td><img src="hojas.jpg" alt="Hojas" width="100"></td>
                </tr>
            </table>
        </div>
        <div id="registro" class="form-container">
            <h2>REGISTRATE</h2>
            <form id="registrationForm">
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre" name="nombre" required>
                
                <label for="apellidos">Apellidos:</label>
                <input type="text" id="apellidos" name="apellidos" required>
                
                <label for="usuario">Usuario:</label>
                <input type="text" id="usuario" name="usuario" required>
                
                <label for="contraseña">Contraseña:</label>
                <input type="password" id="contraseña" name="contraseña" required>
                
                <button type="submit">Enviar</button>
            </form>
        </div>
        <div id="contacto" class="form-container">
            <h2>Contacto</h2>
            <form id="contactForm">
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre" name="nombre" required>
                
                <label for="correo">Correo:</label>
                <input type="email" id="correo" name="correo" required>
                
                <label for="mensaje">Mensaje:</label>
                <textarea id="mensaje" name="mensaje" rows="4" required></textarea>
                
                <button type="submit">Enviar</button>
            </form>
        </div>
    </div>

    <!-- Contenedor de cookies -->
    <div id="cookieContainer" class="cookie-container">
        <p>Este sitio utiliza cookies para mejorar su experiencia. <a href="privacidad.html" target="_blank">Leer más</a></p>
        <div>
            <button id="acceptCookies">Aceptar</button>
            <button id="denyCookies">Denegar</button>
        </div>
    </div>

    <script>
        function scrollToSection(sectionId) {
            document.getElementById(sectionId).scrollIntoView({ behavior: 'smooth' });
        }

        document.getElementById('registrationForm').addEventListener('submit', function(event) {
            event.preventDefault();

            const nombre = document.getElementById('nombre').value;
            const apellidos = document.getElementById('apellidos').value;
            const usuario = document.getElementById('usuario').value;
            const contraseña = document.getElementById('contraseña').value;

            const user = {
                nombre: nombre,
                apellidos: apellidos,
                usuario: usuario,
                contraseña: contraseña
            };

            localStorage.setItem('user', JSON.stringify(user));

            alert('Registro exitoso');
            document.getElementById('registrationForm').reset();
        });

        document.getElementById('contactForm').addEventListener('submit', function(event) {
            event.preventDefault();

            alert('Mensaje enviado');
            document.getElementById('contactForm').reset();
        });

        // Manejo de cookies
        document.getElementById('acceptCookies').addEventListener('click', function() {
            localStorage.setItem('cookiesAccepted', 'true');
            document.getElementById('cookieContainer').style.display = 'none';
        });

        document.getElementById('denyCookies').addEventListener('click', function() {
            localStorage.setItem('cookiesAccepted', 'false');
            document.getElementById('cookieContainer').style.display = 'none';
        });

        window.addEventListener('load', function() {
            if (localStorage.getItem('cookiesAccepted') !== null) {
                document.getElementById('cookieContainer').style.display = 'none';
            }
        });
    </script>
</body>
</html>
