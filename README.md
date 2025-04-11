# Rahi-Bag
Website for Rahi Bag
<!DOCTYPE html><html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rahi Bag</title>
    <link rel="stylesheet" href="style.css">
</head><body>
    <header>
        <img src="images/rahi-bag-logo.png" alt="Rahi Bag Logo" class="logo">
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header><section id="home">
    <h1>Welcome to Rahi Bag</h1>
    <p>Your one-stop shop for stylish and durable bags.</p>
</section>

<section id="about">
    <h2>About Us / हमारे बारे में</h2>
    <p>Rahi Bag provides handcrafted, durable, and affordable bags. Based in Jaipur, we deliver across India.</p>
</section>

<section id="products">
    <h2>Our Products / हमारे उत्पाद</h2>
    <div class="product">
        <img src="images/ladies-sling-bag.jpg" alt="Ladies Sling Bag">
        <p>Ladies Sling Bag - ₹1500</p>
    </div>
    <div class="product">
        <img src="images/lunch-box-bag.jpg" alt="Lunch Box Bag">
        <p>Lunch Box Bag - ₹899<br>Color: Black and Brown</p>
    </div>
    <div class="product">
        <img src="images/laptop-bag.jpg" alt="Laptop Bag">
        <p>Laptop Bag - ₹1299<br>Color: Black and Brown</p>
    </div>
    <div class="product">
        <img src="images/genuine-leather.jpg" alt="Genuine Leather Bag">
        <p>Genuine Leather Bag - ₹11999</p>
    </div>
</section>

<section id="gallery">
    <h2>Gallery / गैलरी</h2>
    <div class="gallery">
        <img src="images/ladies-sling-bag.jpg" alt="Gallery 1">
        <img src="images/lunch-box-bag.jpg" alt="Gallery 2">
        <img src="images/laptop-bag.jpg" alt="Gallery 3">
        <img src="images/genuine-leather.jpg" alt="Gallery 4">
    </div>
</section>

<section id="contact">
    <h2>Contact Us / संपर्क करें</h2>
    <p>WhatsApp: <a href="https://wa.me/919654428948">+91-9654428948</a>, <a href="https://wa.me/919570749370">+91-9570749370</a></p>
    <p>Email: rahibag@gmail.com</p>
    <img src="images/upi-qr.png" alt="UPI QR for Payment" class="qr">
    <p>UPI ID: 9654428948@ybl</p>
</section>

<footer>
    <p>Free Delivery in Jaipur. Extra charges apply for other cities.</p>
    <p>Returns only within 24 hours for damaged or wrong items.</p>
    <p>&copy; 2025 Rahi Bag. All Rights Reserved.</p>
</footer>

</body></htm)

body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; padding: 0; background: #111; color: #f4f4f4; }

header { background: linear-gradient(to right, #1a1a1a, #333); display: flex; justify-content: space-between; align-items: center; padding: 10px 20px; box-shadow: 0 2px 8px rgba(0, 0, 0, 0.8); }

.logo { height: 60px; }

nav ul { list-style: none; display: flex; gap: 20px; }

nav a { text-decoration: none; color: gold; font-weight: bold; transition: color 0.3s; }

nav a:hover { color: #ffcc00; }

section { padding: 40px 20px; max-width: 1000px; margin: auto; text-align: center; }

h1, h2 { color: gold; margin-bottom: 20px; }

.product, .gallery img { border: 1px solid #555; border-radius: 8px; padding: 10px; margin: 10px; background-color: #222; box-shadow: 0 0 10px rgba(255, 215, 0, 0.2); }

.product img, .gallery img { width: 250px; height: auto; border-radius: 8px; }

.gallery { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; }

.qr { width: 150px; margin-top: 10px; }

footer { background: #000; padding: 20px; text-align: center; font-size: 14px; color: #aaa; }

