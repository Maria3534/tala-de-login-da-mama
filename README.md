# tala-de-login-da-mazinha

<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estilos Musicais</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Estilos Musicais</h1>
    </header>

    <div class="container">
        <div class="genre">
            <img src="sertanejo.jpg" alt="Sertanejo">
            <h2>Sertanejo</h2>
            <p>O Sertanejo é um dos estilos mais populares no Brasil, com raízes na música caipira.</p>
        </div>

        <div class="genre">
            <img src="funk.jpg" alt="Funk">
            <h2>Funk</h2>
            <p>O Funk brasileiro surgiu nas favelas do Rio de Janeiro e tem batidas animadas e letras variadas.</p>
        </div>

        <div class="genre">
            <img src="mpb.jpg" alt="MPB">
            <h2>MPB</h2>
            <p>Música Popular Brasileira, um estilo que mistura ritmos regionais e letras poéticas.</p>
        body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 20px;
}

h1 {
    margin: 0;
}

.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 20px;
}

.genre {
    background: white;
    margin: 15px;
    padding: 15px;
    width: 300px;
    border-radius: 8px;
    text-align: center;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}

.genre img {
    width: 100%;
    border-radius: 8px;
}

.genre h2 {
    margin: 10px 0;
    font-size: 20px;
}

.genre p {
    color: #555;
}
