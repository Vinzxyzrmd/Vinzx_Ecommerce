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
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f3f4f6;
    color: #333;
}

.header {
    background-color: #232f3e;
    color: white;
    padding: 1em;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.header .logo {
    font-size: 1.5em;
    font-weight: bold;
}

.nav a {
    color: white;
    margin: 0 1em;
    text-decoration: none;
}

.hero {
    text-align: center;
    padding: 2em;
    background-color: #febd69;
    color: #232f3e;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1em;
    padding: 1em;
}

.product {
    background-color: white;
    border: 1px solid #ddd;
    padding: 1em;
    text-align: center;
    border-radius: 5px;
}

.product img {
    max-width: 100%;
    height: auto;
}

.product-detail {
    display: flex;
    gap: 2em;
    padding: 2em;
}

.product-detail img {
    max-width: 300px;
    border-radius: 10px;
}

button {
    background-color: #232f3e;
    color: white;
    border: none;
    padding: 0.5em 1em;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #febd69;
    color: #232f3e;
}

footer {
    background-color: #232f3e;
    color: white;
    text-align: center;
    padding: 1em;
}
function addToCart() {
    alert("Product added to cart!");
}
