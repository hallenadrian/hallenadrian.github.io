<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vali Spaidar</title>
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1a242f;
            color: #ecf0f1;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }

        header {
            text-align: center;
            margin-bottom: 2rem;
            margin-top: 0.5rem;
        }

        header img {
            width: 500px;
            height: auto;
            margin-bottom: 1rem; /* Adaugă un spațiu între logo și titlu */
        }

        header h1 {
            font-size: 2.5rem;
            margin: 0;
            color: #ecf0f1;
        }

        header p {
            font-size: 1rem;
            color: #bdc3c7;
        }

        .main {
            display: flex;
            justify-content: center;
            align-items: flex-start;
            gap: 2rem;
            max-width: 1200px;
            width: 90%;
            flex-wrap: wrap;
        }

        .container {
            background: #36454F;
            padding: 1.5rem;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            max-width: 620px;
            width: 100%;
            text-align: center;
        }

        .container h2 {
            font-size: 1.4rem;
            margin-bottom: 1rem;
            color: #ffffff;
        }

        .container p {
            font-size: 1rem;
            margin-bottom: 0;
            line-height: 1.4;
            color: #ffffff;
        }

        .btn {
            display: inline-block;
            padding: 0.75rem 1.5rem;
            font-size: 1rem;
            color: white;
            background-color: #1a242f;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s, transform 0.3s;
            margin-top: 1rem;
            margin-right: 1rem;
        }

        .btn:hover {
            background-color: #000000;
            transform: scale(1.05);
        }

        .image-column {
            max-width: 500px;
            width: 100%;
            text-align: center;
        }

        .image-column img {
            width: 400px;
            height: 400px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            object-fit: cover;
        }

        .image-column p {
            font-size: 1rem;
            color: #ffffff;
            margin-top: 1rem;
            font-weight: bold;
        }

        footer {
            margin-top: 2rem;
            font-size: 0.8rem;
            color: #bdc3c7;
        }

        .support-container {
            background: #36454F;
            padding: 1.5rem;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            max-width: 620px;
            width: 100%;
            text-align: center;
            margin-top: 2rem;
        }

        .support-container h2 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: #ffffff;
        }

        .support-container p {
            font-size: 1rem;
            color: #ffffff;
            margin-bottom: 1rem;
        }

    </style>
</head>
<body>
    <header>
        <img src="https://i.imgur.com/Sr6X4Pk.png" alt="Logo"> <!-- Adaugă link-ul către logo aici -->
        <h1>botu cu cea mai lungă fază</h1>
    </header>
    <div class="main">
        <div class="image-column">
            <img src="https://i.imgur.com/3A7Gte9.png" alt="Vali Spaidar">
            <p>Primul bot interlop din România</p>
        </div>
        <div class="container">
            <h2>Cine este Vali Spaidăr?</h2>
            <p>Hai so keres merundo!</p>
            <p>Te-ai saturat sa dormi linistit fara sa iti ceara cineva banii?</p>
            <p>Vrei sa ti se ia neamu in sabie si mama ta sa fie luata-n ciocan?</p>
            <p>Stai linistit varule, Vali Spider e aici pentru tine!</p>
            <p>Daca te plictisesti sau esti cu brigada, doar zi cuvantu si varu tau iti canta cea mai bengoasa dedicatie care rupe globu pamantesc!</p>
            <p>Hai avelo baftalo si has mo car! Va pupa jos varu!</p>
            <p>Cu !help, ai acolo toate calitatiile și talentele mele, totul pt suma modica bineinteles (nu se include tva si camata in pret)</p>
            <p>Acum cu mine in viata ta mortii tai nu o sa mai doarma linistiti, o sa primesti cele mai dulci mesaje dimineata iar nevasta ta o sa fie mai in siguranta ca niciodata, temerer moro chavel.</p>
            <div style="display: flex; justify-content: center;">
                <a href="https://discord.com/oauth2/authorize?client_id=1234567890&scope=bot&permissions=8" class="btn">Add to Discord</a>
                <a href="https://discord.gg/d7yTmARHcc" class="btn">Join our Discord Server</a>
            </div>
        </div>
        <div class="support-container">
            <h2>Support the Creator</h2>
            <p>Vali Spaidăr este oferit gratuit. Fără abonamente sau alte plan-uri. Tot ce inseamna "profit", o sa intre tot in mentinerea bot-ului sau alte feature-uri pe viitor. Pentru feature-uri private disponibile doar la dvs. pe server, ma puteti contacta pe discord : hxllen</p>
            <a href="https://ko-fi.com/hxllen" class="btn">Support the Project</a>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Vali Spaidăr | built with love by hxllen</p>
    </footer>
</body>
</html>
