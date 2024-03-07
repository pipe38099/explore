<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Comida Rápida - Ordena Ahora</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #666;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: #fff;
        }
        .product {
            border: 1px solid #ccc;
            padding: 10px;
            margin-bottom: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .product img {
            max-width: 100px;
            max-height: 100px;
        }
        .product-info {
            margin-left: 20px;
        }
        .product-info h3 {
            margin: 0;
        }
        .product-info p {
            margin: 5px 0;
        }
        .btn {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 8px 20px;
            cursor: pointer;
        }
        .btn:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Comida Rápida - Ordena Ahora</h1>
    </header>
    <nav>
        <a href="#">Inicio</a>
        <a href="#">Menú</a>
        <a href="#">Carrito</a>
    </nav>
    <section>
        <div class="product">
            <img src="hamburguesa.jpg" alt="Hamburguesa">
            <div class="product-info">
                <h3>Hamburguesa</h3>
                <p>Deliciosa hamburguesa con queso, lechuga y tomate.</p>
                <p>Precio: $5.99</p>
                <button class="btn">Agregar al Carrito</button>
            </div>
        </div>
        <div class="product">
            <img src="pizza.jpg" alt="Pizza">
            <div class="product-info">
                <h3>Pizza</h3>
                <p>Pizza recién horneada con pepperoni y queso fundido.</p>
                <p>Precio: $7.99</p>
                <button class="btn">Agregar al Carrito</button>
            </div>
        </div>
        <!-- Aquí puedes agregar más productos -->
    </section>
    <footer>
        <p>Derechos de autor © 2024 - Comida Rápida</p>
    </footer>
</body>
</html>