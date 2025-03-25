<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>𝕸𝖎𝖑𝖎𝖔𝖓á𝖗𝖎𝖔</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #2c3e50;
            color: white;
            text-align: center;
        }

        header {
            background: #34495e;
            padding: 30px 0;
            font-size: 2.5em;
            letter-spacing: 3px;
        }

        .container {
            max-width: 1200px;
            margin: 50px auto;
            padding: 20px;
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
        }

        .image-box {
            position: relative;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }

        .image-box img {
            width: 100%;
            height: auto;
            transition: transform 0.3s ease;
        }

        .image-box img:hover {
            transform: scale(1.1);
        }

        .image-box .overlay {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.4);
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .image-box:hover .overlay {
            opacity: 1;
        }

        .image-box .text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 1.5em;
            font-weight: bold;
            color: #ecf0f1;
            text-shadow: 0 0 10px rgba(0, 0, 0, 0.7);
        }

        footer {
            background: #34495e;
            padding: 15px;
            font-size: 1.2em;
        }
    </style>
</head>
<body>

<header>
    𝕸𝖎𝖑𝖎𝖔𝖓á𝖗𝖎𝖔 💰
</header>

<div class="container">
    <div class="image-box">
        <img src="https://example.com/imagem1.jpg" alt="Imagem de dinheiro">
        <div class="overlay">
            <div class="text">Investimentos</div>
        </div>
    </div>

    <div class="image-box">
        <img src="https://example.com/imagem2.jpg" alt="Imagem de riqueza">
        <div class="overlay">
            <div class="text">Riqueza</div>
        </div>
    </div>

    <div class="image-box">
        <img src="https://example.com/imagem3.jpg" alt="Imagem de moedas">
        <div class="overlay">
            <div class="text">Finanças Pessoais</div>
        </div>
    </div>
</div>

<footer>
    © 2025 𝕸𝖎𝖑𝖎𝖔𝖓á𝖗𝖎𝖔 - Todos os direitos reservados.
</footer>

</body>
</html>
