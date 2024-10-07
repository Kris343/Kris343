<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Продаємо одяг високої якості за найкращими цінами">
    <title>Одяг за найкращими цінами</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff5f6d;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #ffc371;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 20px;
            background-color: #ffffff;
        }
        .products {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .product {
            background-color: #fff3cd;
            border: 1px solid #ffecb3;
            padding: 15px;
            width: 30%;
            margin: 10px;
            text-align: center;
        }
        .product img {
            width: 100%;
            height: auto;
        }
        footer {
            background-color: #ff5f6d;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Магазин одягу</h1>
    <p>Висока якість та доступні ціни!</p>
</header>

<nav>
    <a href="#home">Головна</a>
    <a href="#products">Продукція</a>
    <a href="#contact">Контакти</a>
</nav>

<section id="products">
    <h2>Наші товари</h2>
    <div class="products">
        <div class="product">
            <img src="tshirt.jpg" alt="Футболка">
            <h3>Футболка</h3>
            <p>Ціна: 250 грн</p>
        </div>
        <div class="product">
            <img src="jeans.jpg" alt="Джинси">
            <h3>Джинси</h3>
            <p>Ціна: 700 грн</p>
        </div>
        <div class="product">
            <img src="jacket.jpg" alt="Куртка">
            <h3>Куртка</h3>
            <p>Ціна: 1200 грн</p>
        </div>
    </div>
</section>

<footer>
    <p>Зв'яжіться з нами: +38 0632179093 | email@example.com</p>
</footer>

</body>
</html>
