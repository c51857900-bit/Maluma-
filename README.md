<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maluma Project Mobile</title>
    <style>
        body { font-family: sans-serif; background: #121212; color: white; margin: 0; padding: 20px; }
        .gallery { display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; }
        .card { background: #1e1e1e; border-radius: 10px; padding: 10px; text-align: center; }
        img { width: 100%; border-radius: 8px; margin-bottom: 5px; }
        .code-box { background: #000; padding: 15px; border-radius: 5px; overflow-x: auto; font-family: monospace; font-size: 12px; color: #0f0; margin-top: 20px; }
        h2 { border-bottom: 2px solid #ff4081; padding-bottom: 5px; }
    </style>
</head>
<body>
    <h2>Galería de Imágenes</h2>
    <div class="gallery">
        <div class="card"><img src="imagenes/maluma1.jpg" alt="Maluma 1"><p>Maluma 1</p></div>
        <div class="card"><img src="imagenes/maluma2.jpg" alt="Maluma 2"><p>Maluma 2</p></div>
        <div class="card"><img src="imagenes/maluma3.jpg" alt="Maluma 3"><p>Maluma 3</p></div>
        <div class="card"><img src="imagenes/maluma4.jpg" alt="Maluma 4"><p>Maluma 4</p></div>
    </div>

    <h2>Estructura del Proyecto</h2>
    <div class="code-box">
        Paquete: pe.edu.uns.maluma<br>
        Clase Principal: Maluma.java<br>
        UI: jFMalumaBeibi.class
    </div>
</body>
</html>


