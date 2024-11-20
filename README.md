# Vinzx_Ecommerce
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Commerce Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">
        <div class="logo">MyStore</div>
        <nav class="nav">
            <a href="#">Home</a>
            <a href="#products">Products</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h1>Welcome to MyStore</h1>
            <p>Your one-stop shop for everything you need.</p>
        </section>
        <section id="products" class="product-grid">
            <article class="product">
                <img src="placeholder.jpg" alt="Product Image">
                <h2>Product 1</h2>
                <p>$19.99</p>
                <button onclick="window.location.href='product.html'">View Details</button>
            </article>
            <article class="product">
                <img src="placeholder.jpg" alt="Product Image">
                <h2>Product 2</h2>
                <p>$29.99</p>
                <button onclick="window.location.href='product.html'">View Details</button>
            </article>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 MyStore. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
