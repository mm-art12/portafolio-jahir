<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PORTAFOLIO  - JAHIR</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #343a40;
        }
        header {
            background-color: #212529;
            color: white;
            padding: 1.5rem 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #343a40;
            padding: 1rem 0;
        }
        nav a {
            color: white;
            margin: 0 1.5rem;
            text-decoration: none;
            font-size: 1.1rem;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #007bff;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        section {
            margin-bottom: 3rem;
        }
        h2 {
            color: #212529;
            border-bottom: 3px solid #007bff;
            display: inline-block;
            padding-bottom: 0.5rem;
        }
        .about {
            text-align: center;
        }
        .about p {
            font-size: 1.2rem;
            line-height: 1.8;
            margin: 1rem 0;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
        }
        .project {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .project:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2);
        }
        .project img {
            width: 100%;
            height: auto;
        }
        .project-content {
            padding: 1.5rem;
        }
        .project-content h3 {
            margin: 0 0 1rem;
            color: #007bff;
        }
        .project-content p {
            margin: 0;
            line-height: 1.6;
        }
        footer {
            text-align: center;
            padding: 2rem 0;
            background-color: #212529;
            color: white;
            font-size: 0.9rem;
        }
        footer a {
            color: #007bff;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>PORTAFOLIO </h1>
        <p>Por jahir</p>
    </header>
    <nav>
        <a href="#sobre-mi">Sobre mí</a>
        <a href="#proyectos">Proyectos</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <div class="container">
        <section id="sobre-mi" class="about">
            <h2>Sobre mí</h2>
            <p>Soy un desarrollador que le gusta ofrecer su servicios y ayudar a los user.</p>
        </section>
        <section id="proyectos">
            <h2>Proyectos</h2>
            <div class="projects">
                <div class="project">
                    <img src="https://www.minecraft.net/content/dam/minecraftnet/games/minecraft/key-art/Carousel_Pixel-Squared_Cyber-Ninjas_800x450.jpg" alt="Proyecto 1">
                    <div class="project-content">
                        <h3>Creacion de servidores de minecraft</h3>
                        <p>Un desarrollador de servidor de minecraft 5 años de experiencias.</p>
                    </div>
                </div>
                <div class="project">
                    <img src="https://i.imgur.com/znlX7YC.png" alt="Proyecto 2">
                    <div class="project-content">
                        <h3>Creador de bot</h3>
                        <p>Desarrollador bot de discord puedes contactarme en mi correo</p>
                    </div>
                </div>
                <div class="project">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQCGXSizgKdSWGLqF7UyyaL_dNOUC5C-mCcQw&s" alt="Proyecto 3">
                    <div class="project-content">
                        <h3>Plataforma </h3>
                        <p>Implementación de una tienda en línea con carrito de compras y pasarela de pagos segura.</p>
                    </div>
                </div>
            </div>
        </section>
        <section id="contacto">
            <h2>Contacto</h2>
            <p>¿Interesado en colaborar? Contáctame por correo electrónico en <a href="gmail:pokebox18@gmail.com">pokebox@gmail.com</a> o en mis redes sociales.</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024-2025 E. JAHIR. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
