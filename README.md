<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jonah's Schüler-Treff</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        .category {
            margin-bottom: 30px;
        }
        .category h2 {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
        }
        footer {
            background-color: #333;
            color: white;
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
        <h1>Willkommen zu Jonah's Schüler-Treff!</h1>
        <p>Wo Schüler sich online treffen und quatschen können</p>
    </header>

    <nav>
        <a href="#chat">Chat-Räume</a>
        <a href="#games">Spiele</a>
        <a href="#study">Lernen</a>
        <a href="#contact">Kontakt</a>
    </nav>

    <div class="container">
        <div id="chat" class="category">
            <h2>Chat-Räume</h2>
            <p>Hier kannst du dich mit anderen Schülern in verschiedenen Themenräumen austauschen.</p>
            <!-- Platz für zukünftige Funktionen wie Chat-Links -->
        </div>

        <div id="games" class="category">
            <h2>Spiele</h2>
            <p>Mach eine Pause und spiele mit deinen Freunden coole Online-Spiele.</p>
            <!-- Platz für zukünftige Funktionen wie Spiel-Links -->
        </div>

        <div id="study" class="category">
            <h2>Lernen</h2>
            <p>Teile Lernmaterialien und hilf dir gegenseitig bei Hausaufgaben und Prüfungen.</p>
            <!-- Platz für Lerninhalte -->
        </div>
    </div>

    <footer>
        <p>Kontakt: jonah@example.com | &copy; 2024 Jonah's Schüler-Treff</p>
    </footer>
</body>
</html>
