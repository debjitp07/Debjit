<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Beautiful Neon Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: white;
        }

        header, footer {
            text-align: center;
            padding: 20px;
            background-color: #000;
        }

        h1, h2 {
            font-size: 2em;
            margin: 0;
            padding: 0;
            text-transform: uppercase;
            animation: neon 1.5s ease-in-out infinite alternate;
        }

        header h1, footer h2 {
            font-size: 3em;
            animation: neon 1.5s ease-in-out infinite alternate;
        }

        @keyframes neon {
            0% {
                text-shadow: 0 0 5px #ffffff, 0 0 10px #ff0099, 0 0 20px #ff0099, 0 0 40px #ff33cc, 0 0 80px #ff33cc;
            }
            100% {
                text-shadow: 0 0 5px #ff00ff, 0 0 10px #ff00ff, 0 0 20px #ff00ff, 0 0 40px #ff6600, 0 0 80px #ff6600;
            }
        }

        .neon-text {
            display: inline-block;
            animation: neon 1.5s ease-in-out infinite alternate;
        }

        .container {
            padding: 50px;
            text-align: center;
        }

        .section {
            padding: 20px;
            margin: 20px 0;
        }

        footer {
            background-color: #000;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .active {
            color: #ff00ff;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <header>
        <h1 class="neon-text">Welcome to My Beautiful Website</h1>
    </header>

    <div class="container">
        <div class="section">
            <h2 class="neon-text">Neighbour</h2>
            <p class="active">Always Active - Your neighbour is always with you!</p>
        </div>

        <div class="section">
            <h2 class="neon-text">Hometown</h2>
            <p class="active">Always Active - Your hometown is your soul!</p>
        </div>
    </div>

    <footer>
        <h2 class="neon-text">Thank You for Visiting!</h2>
    </footer>

</body>
</html>
