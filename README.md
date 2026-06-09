# agro-tudo<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Primeiro Site</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            color: #333;
            text-align: center;
            padding: 50px;
        }
        h1 {
            color: #007bff;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <h1>Bem-vindo ao meu primeiro site!</h1>
    <p>Este site foi criado usando HTML, CSS e JavaScript.</p>
    
    <button onclick="cliqueAqui()">Clique em mim!</button>

    <script>
        function cliqueAqui() {
            alert("Incrível! Você interagiu com o site.");
        }
    </script>

</body>
</html>
