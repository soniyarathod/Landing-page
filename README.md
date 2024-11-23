# Landing-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfume Collection</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header">
        <nav class="navbar">
            <a href="#" class="logo">Perfume Collection</a>
            <ul class="nav-menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <div class="header-content">
            <h1>Welcome to Our Perfume Collection</h1>
            <p>Discover the essence of luxury with our exclusive range of perfumes.</p>
            <a href="#products" class="btn">Explore Collection</a>
            <img src="home.jpg">
        </div>
    </header>

    <section id="about" class="about-section">
        <div class="about-img">
            <img src="img1.jpeg">
            <img src="img2.avif">
            <img src="img3.jpg">
            <img src="img4.jpg">
        </div>
        <h2>About Us</h2>
        <p>At Perfume Collection, we offer a wide variety of fragrances crafted from the
             finest ingredients. Explore our range and find the perfect scent that defines you.</p>
    </section>

    <section id="products" class="products-section">
        <h2>Our Products</h2>
        <div class="product-container">
            <div class="product-item">
                <img src="prd1.jpg" >
                <h3>L'Élégance</h3>
                <p>A blend of enchanting floral notes with musk and amber.</p>
            </div>
            <div class="product-item">
                <img src="prd2.jpeg">
                <h3>La Vie</h3>
                <p>A fusion of citrus and woody scents.</p>
            </div>
            <div class="product-item">
                <img src="prd3.jpg">
                <h3>Serenity</h3>
                <p>Notes of lavender and vanilla for relaxation.</p>
            </div>
            <div class="product-item">
                <img src="prd4.jpg">
                <h3>Enchanted Rose</h3>
                <p>A romantic scent with rose and jasmine.</p>
            </div>
            <div class="product-item">
                <img src="prd5.jpeg">
                <h3>Ocean Breeze</h3>
                <p>A refreshing blend of sea salt and driftwood.</p>
            </div>
            <div class="product-item">
                <img src="PRD6.jpeg">
                <h3>Mystic Oud</h3>
                <p>Rich and smoky oud with a touch of spice.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact-section">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit" class="btn">Send Message</button>
        </form>
    </section>

    <footer class="footer">
        <p>&copy; 2024 Perfume Collection. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
