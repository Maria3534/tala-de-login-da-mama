# tala-de-login-da-mama
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site de Músicas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 20px;
        }

        .genre {
            background-color: white;
            border-radius: 5px;
            margin: 10px;
            width: 250px;
            padding: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .genre h3 {
            font-size: 18px;
            color: #333;
        }

        .genre ul {
            list-style: none;
            padding: 0;
        }

        .genre li {
            margin: 8px 0;
            color: #555;
        }
    </style>
</head>
<body>

<header>
    <h1>Site de Músicas</h1>
</header>

<nav>
    <a href="#blues">Blues</a>
    <a href="#country">Country</a>
    <a href="#funk">Funk</a>
    <a href="#hiphop">Hip-Hop</a>
    <a href="#jazz">Jazz</a>
    <a href="#pop">Pop</a>
    <a href="#rock">Rock</a>
    <a href="#samba">Samba</a>
    <a href="#soul">Soul</a>
    <a href="#world">World Music</a>
</nav>

<div class="container">

    <div class="genre" id="blues">
        <h3>Blues</h3>
        <ul>
            <li>The Thrill is Gone - B.B. King</li>
            <li>Pride and Joy - Stevie Ray Vaughan</li>
            <li>Crossroads - Robert Johnson</li>
        </ul>
    </div>

    <div class="genre" id="country">
        <h3>Country</h3>
        <ul>
            <li>Jolene - Dolly Parton</li>
            <li>Take Me Home, Country Roads - John Denver</li>
            <li>Ring of Fire - Johnny Cash</li>
        </ul>
    </div>

    <div class="genre" id="funk">
        <h3>Funk</h3>
        <ul>
            <li>Superstition - Stevie Wonder</li>
            <li>Get Up (I Feel Like Being A) Sex Machine - James Brown</li>
            <li>Give Up the Funk - Parliament</li>
        </ul>
    </div>

    <div class="genre" id="hiphop">
        <h3>Hip-Hop</h3>
        <ul>
            <li>Juicy - The Notorious B.I.G.</li>
            <li>Lose Yourself - Eminem</li>
            <li>Fight the Power - Public Enemy</li>
        </ul>
    </div>

    <div class="genre" id="jazz">
        <h3>Jazz</h3>
        <ul>
            <li>So What - Miles Davis</li>
            <li>Take Five - Dave Brubeck</li>
            <li>Feeling Good - Nina Simone</li>
        </ul>
    </div>

    <div class="genre" id="pop">
        <h3>Pop</h3>
        <ul>
            <li>Shape of You - Ed Sheeran</li>
            <li>Blinding Lights - The Weeknd</li>
            <li>Uptown Funk - Mark Ronson ft. Bruno Mars</li>
        </ul>
    </div>

    <div class="genre" id="rock">
        <h3>Rock</h3>
        <ul>
            <li>Bohemian Rhapsody - Queen</li>
            <li>Stairway to Heaven - Led Zeppelin</li>
            <li>Smells Like Teen Spirit - Nirvana</li>
        </ul>
    </div>

    <div class="genre" id="samba">
        <h3>Samba</h3>
        <ul>
            <li>Aquarela do Brasil - Ary Barroso</li>
            <li>Mas Que Nada - Jorge Ben Jor</li>
            <li>O Mundo é um Moinho - Cartola</li>
        </ul>
    </div>

    <div class="genre" id="soul">
        <h3>Soul</h3>
        <ul>
            <li>Respect - Aretha Franklin</li>
            <li>What's Going On - Marvin Gaye</li>
            <li>A Change Is Gonna Come - Sam Cooke</li>
        </ul>
    </div>

    <div class="genre" id="world">
        <h3>World Music</h3>
        <ul>
            <li>Pata Pata - Miriam Makeba</li>
            <li>Waka Waka - Shakira</li>
            <li>Desert Rose - Sting ft. Cheb Mami</li>
        </ul>
    </div>

</div>

</body>
</html>
