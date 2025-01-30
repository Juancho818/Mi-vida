# Mi-vida
Para la niña que más amo 
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carta de San Valentín</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: pink;
            font-family: Arial, sans-serif;
        }

        .heart {
            position: relative;
            width: 100px;
            height: 100px;
            background-color: red;
            transform: rotate(-45deg);
            margin-top: 50px;
            cursor: pointer;
            transition: transform 0.3s ease-in-out;
        }

        .heart::before,
        .heart::after {
            content: "";
            position: absolute;
            width: 100px;
            height: 100px;
            background-color: red;
            border-radius: 50%;
        }

        .heart::before {
            top: -50px;
            left: 0;
        }

        .heart::after {
            left: 50px;
            top: 0;
        }

        .heart:hover {
            transform: rotate(-45deg) scale(1.1);
        }
    </style>
</head>
<body>

    <div class="heart" onclick="mostrarMensaje()"></div>

    <script>
        function mostrarMensaje() {
            alert("Mi vida, eres lo mejor que me ha pasado en la vida, te amo muchísimo y espero que estemos juntos por muchísimo más tiempo, te amo.\n\n¿Quieres ser mi San Valentín?");
        }
    </script>

</body>
</html>
