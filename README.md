[index.html.html](https://github.com/user-attachments/files/22962424/index.html.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sweet Pack</title>
    <style>
        /* --- ESTILOS GENERALES --- */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffeef4;
            color: #5a2a3e;
        }

        /* --- ENCABEZADO / BANNER --- */
        header {
            background-image: url('banner rosa.jpeg'); /*  banner rosa.jepg */
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            height: 500px; /* alto del banner */
            color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
        }

        header::before {
            /* capa semitransparente para resaltar texto */
            content: "";
            position: absolute;
            top: 0; left: 0; right: 0; bottom: 0;
            background-color: rgba(255, 105, 180, 0.3);
        }

        header h1, header p {
            position: relative; /* mantiene el texto arriba del fondo */
            z-index: 1;
        }

        header h1 {
            font-size: 10rem;
            font-weight: 700;
            margin: 0;
            color: #fff;
        }

        header p {
            font-size: 1.2rem;
            margin-top: 10px;
            color: #fff;
        }

        /* --- NAVEGACIÓN --- */
        nav {
            background-color: #f8cadd;
            text-align: center;
            padding: 10px 0;
        }

        nav a {
            color: #5a2a3e;
            text-decoration: none;
            margin: 0 20px;
            font-weight: 600;
        }

        nav a:hover {
            color: #fff;
        }

        /* --- SECCIÓN PRINCIPAL --- */
        section {
            padding: 50px;
            text-align: center;
        }

        .btn {
            display: inline-block;
            background-color: #ff7ba3;
            color: white;
            padding: 12px 25px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s;
        }

        .btn:hover {
            background-color: #e65f8d;
        }

        /* --- PIE DE PÁGINA --- */
        footer {
            background-color: #f8cadd;
            text-align: center;
            padding: 15px;
            color: #5a2a3e;
        }
    </style>
</head>
<body>

    <!-- 🔹 BANNER -->
    <header>
        <h1>Sweet Pack</h1>
        <p>Diseño de Empaque de Dulces</p>
        <p style="font-style: italic; font-size: 32px; color:#FFD700; font-weight: bold; text-align: center;">
  Creatividad que endulza
</p>

    </header>

    <!-- 🔹 MENÚ DE NAVEGACIÓN -->
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#galeria">Galería</a>
        <a href="#acerca">Acerca</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <!-- 🔹 CONTENIDO PRINCIPAL -->
    <section id="inicio">
        <h2>Bienvenido a Sweet Pack, un nuevo estilo de dulzura</h2>
        <p>Diseñamos empaques que enamoran a primera vista y endulzan cada experiencia.
            En Sweet Pack creemos que cada detalle cuenta. Nuestro propósito es ofrecer productos que no solo cumplan su función, sino que también inspiren y sorprendan a quienes los usan. Combinamos creatividad, innovación y compromiso con la calidad para brindarte soluciones únicas y experiencias memorables.
Explora nuestro catálogo, descubre nuestras novedades y déjate guiar por un espacio pensado para quienes valoran el diseño, la originalidad y la excelencia. Estamos aquí para acompañarte en cada elección y hacer que cada experiencia con nosotros sea especial. 🍬✨</p>
        <a href="#galeria" class="btn">Ver Diseños</a>
    </section>

    <section id="galeria">
        <h2>Galería de Empaques para Dulces</h2>
        <!-- Ejemplo de dónde poner tus imágenes -->
        <img src="bites.jpeg" alt="Dulce 1" width="250">
        <img src="chocolateII.jpeg" alt="Dulce 2" width="250">
        <img src="papassss.jpeg" alt="Dulce 3" width="250">
        <img src="Xile_Chile.jpeg" alt="Dulce 4" width="250">
        <img src="botellas jugo.jpeg" alt="Dulce 5" width="250">
        <img src="emaque principal.jpeg" alt="Dulce 6" width="250">
        <img src="Dessert Delivery.jpeg" alt="Dulce 7" width="250">
        <img src="barritas.jpeg" alt="Dulce 8" width="250">
        <img src="envase rojo.jpeg" alt="Dulce 9" width="250">
        <img src="vaso verde.jpeg" alt="Dulce 10" width="250">
    </section>

    <section id="acerca">
        <h2>Sobre Nosotros</h2>
        <p>Sweet Pack nació para combinar creatividad, color y sabor en cada diseño de empaque.
           Creemos que cada producto tiene el poder de crear momentos especiales. Desde nuestros inicios, nos hemos dedicado a combinar diseño, calidad y creatividad para ofrecer experiencias únicas a nuestros clientes. Cada detalle, desde la selección de materiales hasta la presentación final, refleja nuestro compromiso con la excelencia.

Nuestra misión es brindar productos que inspiren y sorprendan, siempre con un enfoque en la satisfacción y confianza de quienes nos eligen. Aspiramos a ser una marca reconocida por la innovación y la atención al cliente, creando vínculos duraderos y significativos.

Guiados por valores como la calidad, la creatividad, la pasión y la transparencia, trabajamos cada día para superar expectativas y convertir cada interacción en una experiencia memorable. 
<p>En Sweet Pack, cada detalle cuenta, porque entendemos que los pequeños momentos son los que dejan una gran impresión. Por eso nos esforzamos en cuidar cada aspecto de nuestros productos, desde el empaque hasta la experiencia de uso, asegurando que cada interacción con nuestra marca sea memorable. Queremos que quienes nos eligen sientan pasión, alegría y confianza en cada elección, convirtiendo cada dulce en un recuerdo único que se comparte y se disfruta.</p>
        </p>
    </section>

    <section id="contacto">
        <h2>Nuestras redes sociales</h2>
<p>Instagram:@SweetPackMx</p>
<p>Tik Tok:@SweetPackOficial</p>
<p>Facebook:@SweetPackStore</p>

        <h2>Contáctanos</h2>
        <p>Correo: contacto@sweetpack.com </p>

        <a href="#inicio" class="btn">Volver arriba</a>
    </section>

    <!-- 🔹 PIE DE PÁGINA -->
    <footer>
        <p>© 2025 Sweet Pack | Todos los derechos reservados</p>
    </footer>

</body>
</html>
