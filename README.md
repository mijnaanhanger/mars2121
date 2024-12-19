<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mijn Blog</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Welkom op mijn Blog</h1>
        <p>Dit is mijn persoonlijke blog waar ik mijn gedachten en ervaringen deel.</p>
    </section>

    <section id="blog">
        <h2>Mijn Blogposts</h2>
        <article>
            <h3>Blogpost 1: Mijn Eerste Avontuur</h3>
            <img src="foto1.jpg" alt="Foto van avontuur 1">
            <p>Dit is een tekst over mijn eerste avontuur...</p>
        </article>

        <article>
            <h3>Blogpost 2: Reizen naar de Bergen</h3>
            <img src="foto2.jpg" alt="Foto van de bergen">
            <p>Een verhaal over mijn reis naar de bergen...</p>
        </article>
    </section>

    <section id="contact">
        <h2>Contactgegevens</h2>
        <p>Je kunt me bereiken via de volgende gegevens:</p>
        <ul>
            <li>Email: mijnemail@example.com</li>
            <li>Telefoon: 123-456-7890</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 Mijn Blog</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>



body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px;
}

h1, h2, h3 {
    color: #333;
}

article {
    background-color: white;
    padding: 15px;
    margin-bottom: 20px;
    border-radius: 5px;
}

article img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}

ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    padding: 5px 0;
}



// Hier kun je JavaScript toevoegen voor interactie, bijvoorbeeld een knop voor de blog die meer posts laadt.
console.log('Website geladen');


    {%- endif -%}
  </body>
</html>
