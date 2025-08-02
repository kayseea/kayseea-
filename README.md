# <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Premium hair products for curls, waves, and relaxed hair. Shop curl activators, relaxers, and more.">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GlowHair Essentials</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #2a2a2a;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            background: url('https://images.unsplash.com/photo-1519415943484-c3ee80040063?auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
            color: white;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        .hero h2 {
            background-color: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 10px;
        }

        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .product {
            background: white;
            padding: 20px;
            border-radius: 10px;
            width: 250px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }

        footer {
            background: #2a2a2a;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        @media (max-width: 600px) {
            .products {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>GlowHair Essentials</h1>
        <p>Where Healthy Hair Begins</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="hero">
        <h2>Transform Your Hair with Science and Care</h2>
    </div>

    <section id="about">
        <h2>About Us</h2>
        <p>GlowHair Essentials is a leading brand in natural and professional haircare. We specialize in curl activators, coldwave relaxers, and nourishing hair treatments. Our mission is to bring confidence and shine to every strand.</p>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <div class="products">
            <div class="product">
                <img src="https://images.unsplash.com/photo-1600185365279-c8e6db2c1ef6?auto=format&fit=crop&w=500&q=80" alt="Curl Activator">
                <h3>Curl Activator</h3>
                <p>Defines and moisturizes curls with a soft hold. Ideal for natural textures.</p>
            </div>
            <div class="product">
                <img src="https://images.unsplash.com/photo-1600185365386-70f89bd3edc4?auto=format&fit=crop&w=500&q=80" alt="Coldweave Relaxer">
                <h3>Coldweave Relaxer</h3>
                <p>Gently straightens hair with ammonium thiosulfate for lasting smoothness.</p>
            </div>
            <div class="product">
                <img src="https://images.unsplash.com/photo-1614356351318-51fb7ac8c06d?auto=format&fit=crop&w=500&q=80" alt="Hair Moisturizer">
                <h3>Leave-In Moisturizer</h3>
                <p>Hydrates dry hair and protects from damage using natural oils and carbomer blends.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@glowhair.com</p>
        <p>Phone: +123-456-7890</p>
        <p>Address: 123 Shine Street, Hairville, HA 45678</p>
    </section>

    <footer>
        <p>&copy; 2025 GlowHair Essentials. All rights reserved.</p>
    </footer>

</body>
</html>
