<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Jonathan">
    <meta name="description" content="lista de documentos">
    <title>Página de exemplo estrutura básica</title>

    <style>
        html,
        body {
            height: 100%;
            padding: 0;
            margin: 0;
        }

        body {
            background-color: red;
            background-image: linear-gradient(70deg, red 50%, blue, black, white, orange 60%), url(/imagens/css3.png);
            background-size: auto, 100% 100%;
        }


        #radius1 {
            background: orange;
            width: 200px;
            height: 200px;
            margin: 50px auto;

            border-radius: 50px 100px / 100px 50px;

            box-shadow: 30px 0 10px -20px red, 10px 10px 0 black, -5px -5px 0 10px blue;

        }

        h1 {
            color: white;
            font-family: sans-serif;
            font-size: 50px;
            text-align: center;
            text-shadow: -1px 1px 0 #5d5d5d, -2px 2px 0 #727272,
                -3px 3px 0 #868686, -4px 4px 0 #a3a3a3;
        }
    </style>

</head>

<body>

    <h1>CSS efeitos</h1>
    <div id="radius1"></div>

</body>

</html>
