# Wt
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Shopping Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #0078D7;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 30px;
        }

        .product {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
            width: 250px;
            margin: 15px;
            text-align: center;
            padding: 20px;
        }

        .product img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
        }

        .product h3 {
            margin: 10px 0;
        }

        .product p {
            font-size: 14px;
            color: #666;
        }

        .btn {
            background-color: #0078D7;
            color: white;
            border: none;
            padding: 10px 15px;
            margin-top: 10px;
            border-radius: 5px;
            cursor: pointer;
        }

        .btn:hover {
            background-color: #005fa3;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Online Shopping Store</h1>
        <p>Your one-stop shop for all your needs!</p>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Products</a>
        <a href="#">Deals</a>
        <a href="#">Contact</a>
    </nav>

    <section class="products">
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product 1">
            <h3>Smartphone</h3>
            <p>$499.99</p>
            <button class="btn">Add to Cart</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product 2">
            <h3>Headphones</h3>
            <p>$79.99</p>
            <button class="btn">Add to Cart</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product 3">
            <h3>Wrist Watch</h3>
            <p>$199.99</p>
            <button class="btn">Add to Cart</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product 4">
            <h3>Sneakers</h3>
            <p>$89.99</p>
            <button class="btn">Add to Cart</button>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Online Shopping Store | All Rights Reserved</p>
    </footer>

</body>
</html>
