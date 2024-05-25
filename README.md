<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mis Enlaces😍</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            background-color: #000; /* Fondo negro */
        }
        .container {
            text-align: center;
        }
        h1 {
            color: #87CEEB; /* Azul cielo */
            font-size: 1.5em; /* Tamaño del texto reducido */
            margin-bottom: 20px; /* Espacio inferior */
        }
        .link {
            display: block;
            width: 80%; /* Ocupa el 80% del ancho de la pantalla */
            margin: 10px auto; /* Centra los enlaces */
            padding: 10px 20px;
            text-decoration: none;
            color: white; /* Texto blanco */
            background: linear-gradient(to left, #ff69b4, #007bff); /* Degradado de azul a rosa */
            border-radius: 5px;
            overflow: hidden;
            white-space: nowrap;
            font-size: 1.2em; /* Tamaño de fuente reducido */
        }
        .link:hover {
            background: linear-gradient(to left, #ff69b4, #0056b3); /* Degradado de azul oscuro a rosa en hover */
        }
        .link span {
            display: inline-block;
            position: relative;
            animation: slide-left 2s infinite;
        }
        @keyframes slide-left {
            0% {
                left: 0;
            }
            50% {
                left: -50px;
            }
            100% {
                left: 0;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Mis Enlaces😍</h1>
        <a href="https://www.instagram.com/t_shirts_nice_new/" class="link"><span>Instagram 📸</span></a>
        <a href="https://www.lolapay.com/tshirtsnice" class="link"><span>Tienda 🛒</span></a>
        <a href="https://www.whatsapp.com/catalog/5212482406909/" class="link"><span>Whats App 📨</span></a>
        <a href="https://www.facebook.com/tshirtsnice" class="link"><span>Facebook 🤳</span></a>
    </div>
</body>
</html>
