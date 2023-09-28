<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="estilo.css">
    <title>Elementos Visuais</title>
</head>
<body>
    <figure class="elemento-visual">
        <img src="download (2).jpg" alt="Descrição da imagem">
        <figcaption>terra</figcaption>
    </figure>
</body>
</html>
body, figure, img {
    margin: 0;
    padding: 0;
    border: none;
}


.elemento-visual {
    width: 300px;
    border: 2px solid #ccc;
    padding: 20px;
    background-color: #f0f0f0;
    text-align: center;
    margin: 20px auto;
}

.elemento-visual img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 0 auto;
}

.elemento-visual figcaption {
    font-size: 1.2em;
    margin-top: 10px;
    color: #333;
}

body {
    background-image: url('download.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
}
