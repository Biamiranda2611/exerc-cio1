<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galeria de Fotos</title>
    <style>
        .galeria {
            display: grid;
            grid-template-columns: repeat(3, 200px);
            grid-template-rows: repeat(4, 150px);
            gap: 15px 10px; /* gap: linha coluna */
        }

        .galeria img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <div class="galeria">
        <img src="https://via.placeholder.com/200x150" alt="Foto 1">
        <img src="https://via.placeholder.com/200x150" alt="Foto 2">
        <img src="https://via.placeholder.com/200x150" alt="Foto 3">
        <img src="https://via.placeholder.com/200x150" alt="Foto 4">
        <img src="https://via.placeholder.com/200x150" alt="Foto 5">
        <img src="https://via.placeholder.com/200x150" alt="Foto 6">
        <img src="https://via.placeholder.com/200x150" alt="Foto 7">
        <img src="https://via.placeholder.com/200x150" alt="Foto 8">
        <img src="https://via.placeholder.com/200x150" alt="Foto 9">
        <img src="https://via.placeholder.com/200x150" alt="Foto 10">
        <img src="https://via.placeholder.com/200x150" alt="Foto 11">
        <img src="https://via.placeholder.com/200x150" alt="Foto 12">
    </div>
</body>
</html>
