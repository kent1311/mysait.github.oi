# mysait.github.oi
rarararra
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Про спорт</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212; /* Темний фон */
            color: #e0e0e0; /* Світлий текст */
        }
        header {
            background: linear-gradient(45deg, #1f1f1f, #333333); /* Темний градієнт */
            color: #e0e0e0;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.6);
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            margin: 10px 0 0;
            font-size: 1.2em;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .card {
            background: #1e1e1e; /* Темна картка */
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.6);
            margin: 20px;
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
            width: 300px;
        }
        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.8);
        }
        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .card h2 {
            margin: 15px 0;
            font-size: 1.5em;
            color: #4caf50; /* Світло-зелений */
        }
        .card p {
            padding: 0 15px;
            font-size: 1em;
            color: #b0b0b0; /* Світло-сірий текст */
        }
        .card a {
            display: block;
            text-decoration: none;
            background: #4caf50; /* Світло-зелена кнопка */
            color: white;
            text-align: center;
            margin: 15px;
            padding: 10px 0;
            border-radius: 5px;
            transition: background 0.3s;
        }
        .card a:hover {
            background: #388e3c; /* Трохи темніший зелений */
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #1f1f1f; /* Темний футер */
            color: #e0e0e0;
            margin-top: 30px;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.6);
        }
        .footer-link {
            color: #4caf50; /* Світло-зелений текст для посилання */
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        .footer-link:hover {
            color: #388e3c; /* Темніший зелений при наведенні */
        }
        .footer-button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #4caf50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s;
        }
        .footer-button:hover {
            background-color: #388e3c;
        }
    </style>
</head>
<body>
    <header>
        <h1>Про спорт</h1>
        <p>Дізнайтеся більше про ваші улюблені види спорту</p>
    </header>

    <div class="container">
        <!-- Футбол -->
        <div class="card">
            <img src="photo_2025-01-27_21-31-08.jpg" alt="Футбол">
            <h2>Футбол</h2>
            <p>Дізнайте правила гри, цікаві факти та історію футболу.</p>
            <a href="football.html">Детальніше</a>
        </div>

        <!-- Хокей -->
        <div class="card">
            <img src="photo_2025-01-27_21-31-17.jpg" alt="Хокей">
            <h2>Хокей</h2>
            <p>Усе про хокей: правила гри, основні елементи та цікаві факти.</p>
            <a href="hockey.html">Детальніше</a>
        </div>

        <!-- Теніс -->
        <div class="card">
            <img src="photo_2025-01-27_21-31-25.jpg" alt="Теніс">
            <h2>Теніс</h2>
            <p>Ознайомтеся з основами тенісу, його історією та знаменитими гравцями.</p>
            <a href="tennis.html">Детальніше</a>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Про спорт. Усі права захищені.</p>
        <!-- Гіперпосилання на ваш сайт -->
        <a href="https://ваш-сайт.com" target="_blank" class="footer-link">Відвідати мій сайт</a>
        <!-- Кнопка-посилання -->
        <a href="https://ваш-сайт.com" target="_blank" class="footer-button">Перейти на мій сайт</a>
    </footer>
</body>
</html>
