<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #1e1e1e;
            color: white;
            margin: 0;
            padding: 20px;
        }
        .container {
            background: #333;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.3);
            display: inline-block;
            max-width: 300px;
        }
        input {
            width: 90%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
        }
        button {
            background-color: #ffcc00;
            color: black;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #e6b800;
        }
    </style>
</head>
<body>
    <h1>Login</h1>
    <div class="container">
        <input type="text" id="username" placeholder="Usuário">
        <input type="password" id="password" placeholder="Senha">
        <button onclick="login()">Entrar</button>
    </div>

    <script>
        function login() {
            var user = document.getElementById("username").value;
            var pass = document.getElementById("password").value;
            
            if (user === "admin" && pass === "1234") {
                window.location.href = "musica.html";
            } else {
                alert("Usuário ou senha incorretos!");
            }
        }
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gêneros Musicais</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .category {
            font-size: 20px;
            font-weight: bold;
            margin-top: 20px;
            color: #2c3e50;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <h1>Lista de Gêneros Musicais</h1>
    
    <div class="category">Blues</div>
    <ul>
        <li>Acoustic Blues</li>
        <li>African Blues</li>
        <li>Blues Rock</li>
        <li>Chicago Blues</li>
        <li>Delta Blues</li>
        <li>Electric Blues</li>
        <li>Piano Blues</li>
        <li>Rhythm Blues</li>
        <li>Soul Blues</li>
        <li>Texas Blues</li>
    </ul>
    
    <div class="category">Clássico</div>
    <ul>
        <li>Baroque</li>
        <li>Chamber Music</li>
        <li>Classical Crossover</li>
        <li>Contemporary Classical</li>
        <li>Minimalism</li>
        <li>Opera</li>
        <li>Renaissance</li>
        <li>Romantic</li>
        <li>Sonata</li>
        <li>Symphonic</li>
    </ul>
    
    <div class="category">Country</div>
    <ul>
        <li>Alternative Country</li>
        <li>Bluegrass</li>
        <li>Classic Country</li>
        <li>Country Gospel</li>
        <li>Country Pop</li>
        <li>Country Rock</li>
        <li>Honky Tonk</li>
        <li>Outlaw Country</li>
        <li>Traditional Country</li>
        <li>Western Swing</li>
    </ul>
    
    <div class="category">Eletrônica</div>
    <ul>
        <li>Ambient</li>
        <li>Breakbeat</li>
        <li>Deep House</li>
        <li>Drum & Bass</li>
        <li>Electro House</li>
        <li>Hardstyle</li>
        <li>Minimal</li>
        <li>Techno</li>
        <li>Trance</li>
        <li>UK Garage</li>
    </ul>
</body>
</html>
