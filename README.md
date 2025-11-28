<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Site-ul meu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f6f6f6;
            color: #333;
        }
        header {
            background: #1d70b8;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background: #0e4d7a;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 900px;
            margin: 40px auto;
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        footer {
            margin-top: 40px;
            background: #1d70b8;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bun venit pe site-ul meu!</h1>
        <p>Un site simplu, modern și rapid.</p>
    </header>

    <nav>
        <a href="#despre">Despre</a>
        <a href="#servicii">Servicii</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <h2 id="despre">Despre mine</h2>
        <p>Aici poți scrie câteva rânduri despre tine sau afacerea ta.</p>

        <h2 id="servicii">Servicii</h2>
        <ul>
            <li>Serviciu 1</li>
            <li>Serviciu 2</li>
            <li>Serviciu 3</li>
        </ul>

        <h2 id="contact">Contact</h2>
        <p>Email: exemplu@email.com</p>
    </div>

    <footer>
        <p>&copy; 2025 Site-ul meu. Toate drepturile rezervate.</p>
    </footer>
</body>
</html>
