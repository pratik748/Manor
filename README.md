<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manor - The Future of Technology</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            text-align: center;
            color: #fff;
            background-color: #000;
        }
        nav {
            display: flex;
            justify-content: space-between;
            padding: 20px;
            background: #111;
            box-shadow: 0 4px 6px rgba(255, 255, 255, 0.1);
        }
        nav ul {
            list-style: none;
            display: flex;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            padding: 100px 20px;
            background: #000;
            animation: fadeIn 2s ease-in-out;
        }
        .hero-img {
            width: 100%;
            max-width: 800px;
            display: block;
            margin: 0 auto 20px;
            opacity: 0;
            animation: slideUp 1.5s ease-in-out forwards;
        }
        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background: #fff;
            color: #000;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            transition: transform 0.3s;
        }
        .btn:hover {
            transform: scale(1.05);
        }
        .features, .about, .contact {
            padding: 50px 20px;
            animation: fadeIn 2s ease-in-out;
        }
        .feature img {
            width: 100%;
            max-width: 400px;
            display: block;
            margin: 0 auto 10px;
            transition: transform 0.5s;
        }
        .feature img:hover {
            transform: scale(1.1);
        }
        .about img {
            width: 100%;
            max-width: 600px;
            display: block;
            margin: 0 auto 10px;
            animation: slideUp 1.5s ease-in-out forwards;
        }
        footer {
            background: #111;
            padding: 20px;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">Manor</div>
            <ul>
                <li><a href="#features">Features</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <img src="hero.jpg" alt="Graphene Tech" class="hero-img">
        <h1>Manor: The Future of Technology</h1>
        <p>Ultra-fast, ultra-efficient, and built for the next generation.</p>
        <a href="#features" class="btn">Learn More</a>
    </section>
    <section id="features" class="features">
        <div class="feature">
            <img src="conductive.jpg" alt="Ultra Conductive">
            <h2>Ultra Conductive</h2>
            <p>Manor ensures maximum efficiency and speed for all applications.</p>
        </div>
        <div class="feature">
            <img src="cooling.jpg" alt="Next-Gen Cooling">
            <h2>Next-Gen Cooling</h2>
            <p>Revolutionary thermal management for high-performance computing.</p>
        </div>
        <div class="feature">
            <img src="eco.jpg" alt="Eco-Friendly">
            <h2>Eco-Friendly</h2>
            <p>Sustainable and highly durable material for a greener future.</p>
        </div>
    </section>
    <section id="about" class="about">
        <img src="about.jpg" alt="About Manor">
        <h2>About Manor</h2>
        <p>Manor is pushing the boundaries of what's possible with advanced nanotechnology. Our mission is to deliver groundbreaking materials for the future of computing and beyond.</p>
        <p>We are committed to revolutionizing processors with cutting-edge graphene-based technology, enabling ultra-fast, energy-efficient computing for AI, gaming, and high-performance applications.</p>
        <p>We are open to investments and collaborations to accelerate the development of our dream processors. Join us in shaping the future of technology.</p>
        <h3>Meet the Founder</h3>
        <p>Manor was founded by <strong>Pratik</strong>, a visionary entrepreneur dedicated to advancing graphene and chip technology. His mission is to create ultra-fast, energy-efficient processors that redefine the computing industry.</p>
    </section>
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Get in touch for collaborations, investments, or inquiries.</p>
        <a href="mailto:info@manor.com" class="btn">Email Us</a>
    </section>
    <footer>
        <p>&copy; 2025 Manor. All rights reserved.</p>
    </footer>
</body>
</html>
