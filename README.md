<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>San Valentín</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: #ffe6e6;
        }
        h1 {
            color: #d6336c;
            font-size: 24px;
            margin-bottom: 50px;
        }
        .heart {
            position: relative;
            width: 100px;
            height: 100px;
            background-color: red;
            transform: rotate(-45deg);
            margin: 50px auto 0 auto;
            animation: latido 1s infinite;
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
        @keyframes latido {
            0%, 100% { transform: scale(1) rotate(-45deg); }
            50% { transform: scale(1.2) rotate(-45deg); }
        }
    </style>
</head>
<body>
    <h1>Cristina Isabel, ¿quieres ser mi San Valentín? ❤️</h1>
    <div class="heart"></div>
</body>
</html>
