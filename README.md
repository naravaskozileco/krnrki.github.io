<!DOCTYPE html>
<html lang="sl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Narava skozi lečo</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: rgb(247,240,224);
            color: #000;
        }
        header {
            background-color: rgb(102,149,45);
            color: #000;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background-color: rgb(102,149,45);
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 10px 0;
        }
        nav a {
            color: #000;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background-image: url('https://source.unsplash.com/1600x400/?nature,forest');
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: rgb(247,240,224);
            text-shadow: 2px 2px 5px #000;
            font-size: 2rem;
            font-weight: bold;
        }
        section {
            padding: 50px 20px;
            max-width: 800px;
            margin: auto;
        }
        .contact form {
            display: flex;
            flex-direction: column;
            gap: 15px;
            max-width: 600px;
            margin: auto;
            background-color: rgba(102,149,45,0.1);
            padding: 20px;
            border-radius: 10px;
        }
        .contact input, .contact textarea {
            padding: 10px;
            font-size: 1rem;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .contact button {
            padding: 10px;
            font-size: 1rem;
            background-color: rgb(102,149,45);
            color: #000;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact button:hover {
            background-color: rgba(102,149,45,0.8);
        }
        footer {
            background-color: rgb(102,149,45);
            color: #000;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Narava skozi lečo</h1>
    </header>

    <nav>
        <a href="#o-nas">O nas</a>
        <a href="#kontakt">Kontakt</a>
    </nav>

    <div class="hero">
        Ujemi lepoto narave
    </div>

    <section id="o-nas">
        <h2>O nas</h2>
        <p>Smo strastni fotografi narave, ki želimo deliti čarobnost gora, gozdov in divjih živali. Naša misija je približati naravo vsem, ki želijo raziskovati in uživati v njeni lepoti skozi objektiv.</p>
    </section>

    <section id="kontakt" class="contact">
        <h2>Kontakt</h2>
        <form action="https://formsubmit.co/hribar.tilen00@gmail.com" method="POST">
            <!-- Pošiljanje na tvoj email -->
            <input type="hidden" name="_next" value="https://tvoja-stran.si/hvala.html">
            <input type="hidden" name="_captcha" value="false">
            
            <input type="text" name="ime" placeholder="Vaše ime" required>
            <input type="email" name="email" placeholder="Vaš email" required>
            <textarea name="sporocilo" rows="5" placeholder="Vaše sporočilo" required></textarea>
            <button type="submit">Pošlji</button>
        </form>
    </section>

    <footer>
        &copy; 2026 Narava skozi lečo. Vse pravice pridržane.
    </footer>
</body>
</html>
