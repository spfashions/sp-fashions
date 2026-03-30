<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SP FASHIONS</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #fff0f5;
}

header {
    background: #c2185b;
    color: white;
    text-align: center;
    padding: 20px;
}

nav {
    background: #880e4f;
    text-align: center;
    padding: 10px;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    text-align: center;
    padding: 40px;
    background: url('https://images.unsplash.com/photo-1610030469983-98e550d6193c') no-repeat center/cover;
    color: white;
}

.section {
    padding: 30px;
    text-align: center;
}

.products {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.card {
    background: white;
    padding: 15px;
    width: 250px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.card img {
    width: 100%;
    height: 300px;
    object-fit: cover;
}

.button {
    display: inline-block;
    margin-top: 10px;
    padding: 10px;
    background: #c2185b;
    color: white;
    text-decoration: none;
}

footer {
    background: #880e4f;
    color: white;
    text-align: center;
    padding: 15px;
}
</style>
</head>

<body>

<header>
    <h1>SP FASHIONS</h1>
    <p>Trendy Sarees Online</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#products">Sarees</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero">
    <h2>Elegant Sarees Collection</h2>
    <p>Shop Latest Designs Online</p>
</div>

<div class="section" id="products">
    <h2>Our Saree Collection</h2>

    <div class="products">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1610030469983-98e550d6193c">
            <h3>Silk Saree</h3>
            <p>Premium quality silk saree</p>
            <a class="button" href="https://wa.me/918088388290">Buy Now</a>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1603252109303-2751441dd157">
            <h3>Designer Saree</h3>
            <p>Modern stylish design</p>
            <a class="button" href="https://wa.me/918088388290">Buy Now</a>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1583391733956-6c78276477e2">
            <h3>Party Wear Saree</h3>
            <p>Perfect for special occasions</p>
            <a class="button" href="https://wa.me/918088388290">Buy Now</a>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1593032465175-481ac7f401a0">
            <h3>Cotton Saree</h3>
            <p>Comfortable daily wear</p>
            <a class="button" href="https://wa.me/918088388290">Buy Now</a>
        </div>

    </div>
</div>

<div class="section" id="contact">
    <h2>Contact Us</h2>
    <p><strong>Owner:</strong> H Gujjaragowda</p>
    <p><strong>Phone:</strong> 8088388290</p>
    <p>Order via WhatsApp for quick delivery</p>
</div>

<footer>
    <p>© 2026 SP FASHIONS | All Rights Reserved</p>
</footer>

</body>
</html>
