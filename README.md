<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meine kostenlose Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 1rem;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            padding: 2rem;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Willkommen auf meiner kostenlosen Website</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">Über uns</a>
        <a href="#contact">Kontakt</a>
    </nav>
    <div class="container">
        <section id="home">
            <h2>Home</h2>
            <p>Dies ist meine Startseite. Willkommen!</p>
        </section>
        <section id="about">
            <h2>Über uns</h2>
            <p>Hier findest du Informationen über mich und mein Projekt.</p>
        </section>
        <section id="contact">
            <h2>Kontakt</h2>
            <p>Du kannst mich per E-Mail unter <a href="mailto:beispiel@domain.com">beispiel@domain.com</a> erreichen.</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Meine kostenlose Website</p>
    </footer>
</body>
</html>
