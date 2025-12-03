<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tienda de Ropa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f5f5f5;
        }
        header {
            background: #000;
            color: #fff;
            padding: 20px;
            text-align: center;
            font-size: 28px;
            font-weight: bold;
        }
        .contenedor {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .producto {
            background: #fff;
            border-radius: 12px;
            padding: 15px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        .producto img {
            width: 100%;
            height: 260px;
            object-fit: cover;
            border-radius: 10px;
        }
        .producto h3 {
            margin: 10px 0 5px;
        }
        .contacto {
            background: #000;
            color: #fff;
            text-align: center;
            padding: 20px;
            font-size: 18px;
        }
        .contacto a {
            color: #fff;
            font-weight: bold;
        }
    </style>
</head>
<body>

<header>
    <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABAAAAAQACAIAAADwf7zUAADomGNhQlgAAOiYanVtYgAAAB5qdW1kYz" style="height:120px; display:block; margin:0 auto 10px;"/>
    Creaciones Molina
</header>
<p style="text-align:center; font-size:18px; margin-top:10px;">Diseño y confección de ropa</p>

<h2 style="text-align:center; margin-top:30px;">Polos</h2>
<section class="contenedor">
    <div class="producto">
        <img src="https://via.placeholder.com/300x260" alt="Producto 1">
        <h3>Polos </h3>
        <p>Material: algodón 100%<br>Precio: $00</p>
    </div>

    <div class="producto">
        <img src="https://via.placeholder.com/300x260" alt="Producto 2">
        <h3>Pantalón </h3>
        <p>Material: drill premium<br>Precio: $00</p>
    </div>

    <div class="producto">
        <img src="https://via.placeholder.com/300x260" alt="Producto 3">
        <h3>Hoodie Unisex</h3>
        <p>Material: algodón térmico<br>Precio: $00</p>
    </div>
</section>

<h2 style="text-align:center; margin-top:40px;">Chamarras</h2>
<section class="contenedor">
    <div class="producto">
        <img src="https://via.placeholder.com/300x260" alt="Chamarra 1">
        <h3>Chamarra </h3>
        <p>Material: jean<br>Precio: $00</p>
    </div>
</section>

<h2 style="text-align:center; margin-top:40px;">Pantalones</h2>
<section class="contenedor">
    <div class="producto">
        <img src="https://via.placeholder.com/300x260" alt="Pantalón 1">
        <h3>Pantalón de trabajo </h3>
        <p>Material: algodón premium<br>Precio: $00</p>
    </div>
</section>

<h2 style="text-align:center; margin-top:40px;">Ropa de Trabajo</h2>
<section class="contenedor">
    <div class="producto">
        <img src="https://via.placeholder.com/300x260" alt="Ropa Trabajo 1">
        <h3>Overol de Trabajo</h3>
        <p>Material: lona industrial<br>Precio: $00</p>
    </div>
</section>


<div class="contacto">
    Si quieres comprar, contáctate al número <strong>+591 77699920</strong><br>
    o al correo: <a href="mailto:isabel.osinaga.molina@gmail.com">ejemplo@gmail.com</a>
</div>

</body>
</html>
