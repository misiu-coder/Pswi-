<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Technikum Samochodowe</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: #f2f2f2;
        }
        .logo {
            width: 100px;
            height: 50px;
            background-color: #ddd;
            display: flex;
            justify-content: center;
            align-items: center;
            font-weight: bold;
        }
        nav ul {
            list-style-type: none;
            display: flex;
            gap: 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: #333;
        }
        .main-content {
            display: flex;
            padding: 20px;
            gap: 20px;
        }
        .sidebar {
            width: 200px;
            background-color: #e9e9e9;
            padding: 10px;
        }
        .content {
            flex-grow: 1;
            background-color: #f9f9f9;
            padding: 20px;
        }
        .engine-image {
            width: 100%;
            height: 200px;
            background-color: #ccc;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 18px;
            color: #555;
        }
        footer {
            text-align: center;
            padding: 15px;
            background-color: #f2f2f2;
            font-size: 14px;
            color: #666;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Logo</div>
        <nav>
            <ul>
                <li><a href="#">Strona Główna</a></li>
                <li><a href="#">Galeria</a></li>
                <li><a href="#">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <h1>Technikum Samochodowe</h1>
        <div class="main-content">
            <aside class="sidebar">
                <p>Linki do podstron:</p>
                <ul>
                    <li><a href="#">Strona Główna</a></li>
                    <li><a href="#">Galeria</a></li>
                    <li><a href="#">Kontakt</a></li>
                </ul>
            </aside>
            <section class="content">
                <h2>Opis działania silnika hybrydowego</h2>
                <p>
                    Tutaj znajduje się szczegółowy opis działania silnika hybrydowego, w którym wyjaśnione są zasady działania, korzyści oraz innowacje technologiczne związane z tego typu jednostkami napędowymi.
                </p>
                <div class="engine-image">
                    Zdjęcie silnika
                </div>
            </section>
        </div>
    </div>

    <footer>
        Produkcja ZSP
    </footer>
</body>
</html>
