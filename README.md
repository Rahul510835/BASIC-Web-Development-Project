# BASIC-Web-Development-Project
Task-1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Landing Page</title>
    <style>
        /* CSS Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav a {
            color: #fff;
            margin: 0 10px;
            text-decoration: none;
        }

        .hero {
            text-align: center;
            padding: 50px 20px;
            background-color: #f4f4f4;
        }

        .hero img {
            max-width: 100%;
            height: auto;
        }

        .features-grid {
            display: flex;
            justify-content: space-around;
            padding: 20px;
        }

        .feature-item {
            background-color: #ddd;
            padding: 20px;
            width: 30%;
            text-align: center;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Product Name</h1>
        <nav>
            <a href="#features">Features</a>
            <a href="#testimonials">Testimonials</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="hero">
            <img src="product-image.jpg" alt="Product Image">
            <h2>Your Product's Best Feature</h2>
            <p>Short description about the product and why it's great.</p>
            <button>Buy Now</button>
        </section>

        <!-- Features Section -->
        <section id="features">
            <h2>Features</h2>
            <div class="features-grid">
                <div class="feature-item">Feature 1</div>
                <div class="feature-item">Feature 2</div>
                <div class="feature-item">Feature 3</div>
            </div>
        </section>

        <!-- Testimonials Section -->
        <section id="testimonials">
            <h2>Testimonials</h2>
            <p>"This product is amazing!" - Customer A</p>
            <p>"It changed my life!" - Customer B</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Your Company Name. All rights reserved.</p>
    </footer>
</body>
</html>
