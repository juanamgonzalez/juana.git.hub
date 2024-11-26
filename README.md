<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Página web dedicada a la saga de películas Crepúsculo. Conoce los personajes, trama y las películas de esta exitosa franquicia basada en los libros de Stephenie Meyer.">
    <meta name="author" content="Tu Nombre">
    <title>Saga Crepúsculo - Página Oficial</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>CREPÚSCULO</h1>
            <p>La Saga que Cautivó al Mundo</p>
        </div>
        <nav>
            <ul>
                <li><a href="#peliculas">Películas</a></li>
                <li><a href="#personajes">Personajes</a></li>
                <li><a href="#libros">Libros</a></li>
                <li><a href="#galeria">Galería</a></li>
            </ul>
        </nav>
    </header>

    <section id="peliculas">
        <h2>Las Películas</h2>
        <p>La saga "Crepúsculo" está basada en los libros de Stephenie Meyer. Las cinco películas que conforman la serie son:</p>
        <ul>
            <li>Crepúsculo (2008)</li>
            <li>La Saga Crepúsculo: Luna Nueva (2009)</li>
            <li>La Saga Crepúsculo: Eclipse (2010)</li>
            <li>La Saga Crepúsculo: Amanecer – Parte 1 (2011)</li>
            <li>La Saga Crepúsculo: Amanecer – Parte 2 (2012)</li>
        </ul>
        <p>Cada película sigue las aventuras de Bella Swan, un ser humano que se enamora de un vampiro llamado Edward Cullen, mientras enfrenta desafíos sobrenaturales.</p>
    </section>

    <section id="personajes">
        <h2>Personajes Principales</h2>
        <div class="personaje">
            <h3>Bella Swan</h3>
            <p>Interpretada por Kristen Stewart, Bella es una joven que se muda a Forks y se enamora de Edward Cullen, un vampiro. Bella es conocida por su valentía y determinación.</p>
        </div>
        <div class="personaje">
            <h3>Edward Cullen</h3>
            <p>Interpretado por Robert Pattinson, Edward es un vampiro con más de 100 años de edad. A pesar de su naturaleza, se enamora de Bella y lucha por protegerla.</p>
        </div>
        <div class="personaje">
            <h3>Jacob Black</h3>
            <p>Interpretado por Taylor Lautner, Jacob es un amigo cercano de Bella, que eventualmente descubre su propia identidad como licántropo. Él forma un triángulo amoroso con Bella y Edward.</p>
        </div>
    </section>

    <section id="libros">
        <h2>Los Libros</h2>
        <p>La saga de "Crepúsculo" comenzó como una serie de libros escritos por Stephenie Meyer. Los libros que conforman la saga son:</p>
        <ul>
            <li>Crepúsculo</li>
            <li>Luna Nueva</li>
            <li>Eclipse</li>
            <li>Amanecer</li>
        </ul>
        <p>Los libros fueron adaptados al cine con un gran éxito en taquilla, y la saga cuenta con una base de seguidores muy fiel.</p>
    </section>

    <section id="galeria">
        <h2>Galería de Imágenes</h2>
        <p>Disfruta de las icónicas portadas de las películas:</p>
        <div class="imagenes">
            <img src="crepùsculo.jpg" alt="Crepúsculo">
            <img src="luna nueva.jpg" alt="Luna Nueva">
            <img src="eclipce.jpg" alt="Eclipse">
            <img src="amanecer p1.jpg" alt="Eclipse">
            <img src="amanecer p2.jpg" alt="Eclipse">
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Crepúsculo Fans | Todos los derechos reservados</p>
    </footer>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
}

header {
    background-color: #2c3e50;
    color: #fff;
    padding: 20px;
    text-align: center;
}

header .logo h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

header nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}

header nav ul li {
    display: inline;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1.2rem;
}

header nav ul li a:hover {
    text-decoration: underline;
}

section {
    padding: 40px;
    max-width: 1200px;
    margin: 0 auto;
}

section h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

section p {
    font-size: 1.1rem;
    line-height: 1.6;
    margin-bottom: 20px;
}

ul {
    margin-left: 20px;
}

#personajes .personaje {
    margin-bottom: 20px;
}

#personajes h3 {
    font-size: 1.6rem;
    margin-bottom: 10px;
}

#galeria .imagenes {
    display: flex;
    gap: 20px;
    justify-content: center;
}

#galeria img {
    width: 300px;
    height: auto;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

footer {
    background-color: #2c3e50;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

footer p {
    font-size: 1rem;
}
