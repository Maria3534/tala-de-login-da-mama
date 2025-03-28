# tala-de-login-da-mazinha

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Todos os Gêneros Musicais</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>🎵 Todos os Gêneros Musicais 🎶</h1>
    </header>

    <main>
        <section class="genre">
            <h2>Funk</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/4/4d/Funk_Music.jpg" alt="Funk Music">
            <audio controls>
                <source src="musica-funk.mp3" type="audio/mpeg">
            </audio>
        </section>

        <section class="genre">
            <h2>Jazz</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/Jazz_Band.jpg" alt="Jazz Music">
            <audio controls>
                <source src="musica-jazz.mp3" type="audio/mpeg">
            </audio>
        </section>

        <section class="genre">
            <h2>Rock</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/9/98/Rock_Band.jpg" alt="Rock Music">
            <audio controls>
                <source src="musica-rock.mp3" type="audio/mpeg">
            </audio>
        </section>

        <section class="genre">
            <h2>Pop</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/3/3d/Pop_Music.jpg" alt="Pop Music">
            <audio controls>
                <source src="musica-pop.mp3" type="audio/mpeg">
            </audio>
        </section>

        <section class="genre">
            <h2>Hip-Hop</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/8/83/Hip_Hop.jpg" alt="Hip-Hop Music">
            <audio controls>
                <source src="musica-hiphop.mp3" type="audio/mpeg">
            </audio>
        </section>

        <section class="genre">
            <h2>Clássica</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a8/Classical_Music.jpg" alt="Classical Music">
            <audio controls>
                <source src="musica-classica.mp3" type="audio/mpeg">
            </audio>
        </section>

        <section class="genre">
            <h2>Reggae</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/1/1f/Reggae_Music.jpg" alt="Reggae Music">
            <audio controls>
                <source src="musica-reggae.mp3" type="audio/mpeg">
            </audio>
        </section>

        <section class="genre">
            <h2>Eletrônica</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/0/0b/Electronic_Music.jpg" alt="Electronic Music">
            <audio controls>
                <source src="musica-eletronica.mp3" type="audio/mpeg">
            </audio>
        </section>
    </main>

    <footer>
        <p>© 2025 Todos os Gêneros Musicais</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #121212;
    color: white;
    margin: 0;
}

header {
    background-color: #1db954;
    padding: 20px;
    font-size: 24px;
    font-weight: bold;
}

.genre {
    background: #1e1e1e;
    margin: 20px auto;
    padding: 15px;
    border-radius: 10px;
    width: 80%;
    max-width: 400px;
}

.genre img {
    width: 100%;
    border-radius: 10px;
}

footer {
    background-color: #1db954;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
