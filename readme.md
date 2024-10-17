<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Flipkart - Home</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="navbar">
            <div class="logo">
                <a href="#">
                    <img src="https://static-assets-web.flixcart.com/batman-returns/batman-returns/p/images/fkheaderlogo_plus-055f80.svg" alt="Flipkart Logo">
                </a>
            </div>
            <div class="search-bar">
                <input type="text" placeholder="Search for products, brands, and more">
                <button type="submit">Search</button>
            </div>
            <div class="user-options">
                <button>Login</button>
                <button>Cart</button>
            </div>
        </div>
    </header>
    <section class="banner">
        <img src="https://rukminim2.flixcart.com/fk-p-flap/1600/270/image/96a1d024c98baae8.jpeg?q=20" alt="Flipkart Banner">
    </section>
    <section class="products">
        <h2>Featured Products</h2>
        <div class="product-grid">
            <div class="product">
                <img src="https://rukminim2.flixcart.com/fk-p-flap/450/280/image/2456cb1ee191a2f1.jpeg?q=20" alt="Product 1">
                <p>Speakers</p>
                <p>From &#8377;5,999</p>
            </div>
            <div class="product">
                <img src="https://rukminim2.flixcart.com/fk-p-flap/450/280/image/23dbc6fb933c6899.jpeg?q=20" alt="Product 2">
                <p>RO Water</p>
                <p>From &#8377;2,999</p>
            </div>
            <div class="product">
                <img src="https://rukminim2.flixcart.com/fk-p-flap/450/280/image/93896be1e4b9116e.jpeg?q=20" alt="Product 3">
                <p>Perfumes</p>
                <p>Min 20% Off</p>
            </div>
            <div class="product">
                <img src="https://rukminim2.flixcart.com/fk-p-flap/450/280/image/0ec962296ef46223.jpeg?q=20" alt="Product 4">
                <p>Travel Bags</p>
                <p>Min 10% Off</p>
            </div>
        </div>

    </section>
    <footer>
        <div class="footer-container">
            <div class="footer-section">
                <h4>ABOUT</h4>
                <ul>
                    <li><a href="#">Contact Us</a></li>
                    <li><a href="#">About Us</a></li>
                    <li><a href="#">Careers</a></li>
                    <li><a href="#">Flipkart Stories</a></li>
                    <li><a href="#">Press</a></li>
                    <li><a href="#">Flipkart Wholesale</a></li>
                    <li><a href="#">Corporate Information</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h4>HELP</h4>
                <ul>
                    <li><a href="#">Payments</a></li>
                    <li><a href="#">Shipping</a></li>
                    <li><a href="#">Cancellation & Returns</a></li>
                    <li><a href="#">FAQ</a></li>
                    <li><a href="#">Report Infringement</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h4>POLICY</h4>
                <ul>
                    <li><a href="#">Return Policy</a></li>
                    <li><a href="#">Terms Of Use</a></li>
                    <li><a href="#">Security</a></li>
                    <li><a href="#">Privacy</a></li>
                    <li><a href="#">Sitemap</a></li>
                    <li><a href="#">EPR Compliance</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h4>SOCIAL</h4>
                <ul>
                    <li><a href="#">Facebook</a></li>
                    <li><a href="#">Twitter</a></li>
                    <li><a href="#">YouTube</a></li>
                </ul>
            </div>
            

        
    </footer>

</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f1f3f6;
}

header {
    background-color: #2874f0;
    padding: 10px;
    color: white;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo img {
    height: 40px;
}

.search-bar {
    flex: 1;
    margin: 0 20px;
}

.search-bar input {
    width: 80%;
    padding: 8px;
    border: none;
    border-radius: 4px;
}

.search-bar button {
    padding: 8px 16px;
    background-color: #ffeb3b;
    border: none;
    cursor: pointer;
    border-radius: 4px;
}

.user-options button {
    background-color: white;
    color: #2874f0;
    border: none;
    padding: 8px 16px;
    margin-left: 10px;
    border-radius: 4px;
    cursor: pointer;
}

.banner {
    margin: 20px auto;
    text-align: center;
}

.banner img {
    width: 100%;
    max-width: 1200px;
}

.products {
    padding: 20px;
    background-color: white;
}

.products h2 {
    text-align: center;
    margin-bottom: 20px;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
}

.product {
    text-align: center;
    padding: 10px;
    background-color: white;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.product img {
    width: 100px;
    height: 100px;
    object-fit: contain;
}

footer {
    background-color: #172337;
    color: white;
    padding: 40px 20px;
    font-size: 14px;
}

.footer-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.footer-section {
    flex: 1;
    min-width: 180px;
    margin: 20px;
}

.footer-section h4 {
    margin-bottom: 20px;
    font-size: 16px;
    color: #f0c14b;
}

.footer-section ul {
    list-style: none;
    padding: 0;
}

.footer-section ul li {
    margin-bottom: 10px;
}

.footer-section ul li a {
    text-decoration: none;
    color: #b0bec5;
}

.footer-section ul li a:hover {
    color: #f0c14b;
    text-decoration: underline;
}

.download-app p, .footer-section p {
    color: #b0bec5;
    line-height: 1.6;
}

.footer-bottom {
    text-align: center;
    padding: 20px;
    border-top: 1px solid #b0bec5;
    margin-top: 20px;
}

.footer-bottom p {
    margin: 0;
    color: #b0bec5;
}
