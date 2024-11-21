-<link rel="shortcut icon" href="https://cdn3.emoji.gg/emojis/16037-haunterspin.gif"/>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Syfers hahagames</title>
    <style>
        body {
            margin: 0;
            padding: 0;
        }
        .container {
            display: flex;
            flex-direction: column;
            height: 100vh;
            width: 100vw;
        }
        .menu {
            position: absolute;
            top: 0;
            left: 0;
            width: 100vw;
            height: 20px;
            background-color: #000;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .menu button {
            margin-left: 20px;
            padding: 5px;
            font-size: 20px;
        }
        .game-area {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100vw;
            height: 100vh;
            overflow: hidden;
        }
        .game-iframe {
            width: 100vw;
            height: 100vh;
            border: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="menu">
                <a href="Syfer-Menu.html">Home</a>
        </nav>
        </div>
        <div class="game-area">
            <iframe class="game-iframe" src="https://www.hahagames.com/"></iframe>
        </div>
    </div>
    <script>
        document.getElementById('menuButton').addEventListener('click', function() {
            document.querySelector('.menu').classList.toggle('active');
        });
    </script>
</body>
</html>
