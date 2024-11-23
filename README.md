<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>D'Necesa Quarters</title>
    <style>
        /* General Styling */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fdf8f2;
            color: #333;
        }
        header {
            background: #d3a86b;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 36px;
        }
        header p {
            font-size: 16px;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #333;
            padding: 10px 0;
        }
        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #d3a86b;
        }
        .hero {
            text-align: center;
            background: url('https://via.placeholder.com/1600x500') no-repeat center center/cover;
            padding: 100px 20px;
            color: white;
        }
        .hero h1 {
            font-size: 50px;
        }
        .hero p {
            font-size: 20px;
        }
        section {
            padding: 30px;
            max-width: 1200px;
            margin: 0 auto;
        }
        section h2 {
            font-size: 30px;
            color: #d3a86b;
            margin-bottom: 20px;
            text-align: center;
        }
        .what-we-do {
            text-align: center;
            line-height: 1.8;
        }
        .collections {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .collections div {
            text-align: center;
        }
        .collections img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .collections h3 {
            margin: 10px 0;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        footer a {
            color: #d3a86b;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
        .newsletter {
            background: #f4f4f4;
            text-align: center;
            padding: 20px;
            margin: 30px auto;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .newsletter form {
            margin: 15px 0;
        }
        .newsletter input, 
        .newsletter textarea {
            width: 90%;
            max-width: 400px;
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .newsletter button {
            padding: 10px 20px;
            background: #d3a86b;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .newsletter button:hover {
            background: #333;
        }
        .newsletter textarea {
            resize: none;
        }
    </style>
</head>
<body>
<header>
    <h1>D'Necesa Quarters</h1>
    <p>Confidence & Sophistication in Every Piece</p>
</header>
<nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#collections">Collections</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact Us</a>
</nav>
<section id="home" class="hero">
    <h1>Welcome to D'Necesa Quarters</h1>
    <p>Your One-Stop Destination for Stylish Jewelry and Bridal Accessories</p>
</section>
<section id="about">
    <h2>About Us</h2>
    <p>D'Necesa Quarters provides young, upwardly mobile individuals and couples with high-quality, stylish jewelry. Our products exude confidence and sophistication while matching personal style and identity.</p>
    <p><strong>Mission:</strong> To adorn our customers with fine, stylish jewelry that tells their story.</p>
    <p><strong>Vision:</strong> To be the leading destination for unique jewelry and bridal accessories.</p>
</section>
<section id="what-we-do">
    <h2>What We Do</h2>
    <p class="what-we-do">We offer a variety of jewelry products that exude confidence and sophistication, including:</p>
    <ul class="what-we-do">
        <li>Earrings</li>
        <li>Necklaces</li>
        <li>Engagement & Fashion Rings</li>
        <li>Bracelets & Bangles</li>
        <li>Brooches</li>
        <li>Cufflinks</li>
        <li>Bridal Accessories</li>
    </ul>
</section>
<section id="collections">
    <h2>Our Collections</h2>
    <div class="collections">
        <div>
            <img src="https://via.placeholder.com/300" alt="Earrings">
            <h3>Earrings</h3>
        </div>
        <div>
            <img src="https://via.placeholder.com/300" alt="Necklaces">
            <h3>Necklaces</h3>
        </div>
        <div>
            <img src="https://via.placeholder.com/300" alt="Rings">
            <h3>Rings</h3>
        </div>
        <div>
            <img src="https://via.placeholder.com/300" alt="Bracelets">
            <h3>Bracelets</h3>
        </div>
    </div>
</section>
<section id="blog">
    <h2>Our Blog</h2>
    <p>Coming Soon...</p>
</section>
<section class="newsletter">
    <h2>Subscribe to Our Newsletter</h2>
    <p>Get exclusive offers, giveaways, and updates delivered straight to your inbox!</p>
    <form action="https://formspree.io/f/{your-email-endpoint}" method="POST">
        <input type="email" name="email" placeholder="Enter your email" required>
        <button type="submit">Subscribe</button>
    </form>
    <h2>Contact Us</h2>
    <p>Have a question? Send us an inquiry below!</p>
    <form action="https://formspree.io/f/{your-email-endpoint}" method="POST">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" placeholder="Your Message" rows="4" required></textarea>
        <button type="submit">Send Inquiry</button>
    </form>
</section>
<section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> 08163665229</p>
    <p><strong>Email:</strong> dnecesaqtrs@gmail.com</p>
    <p>Follow us:</p>
    <p>
        <a href="https://instagram.com/dnecesaqtrs" target="_blank">Instagram</a> |
        <a href="https://facebook.com/dnecesaqtrs" target="_blank">Facebook</a>
    </p>
</section>
<footer>
    <p>&copy; 2024 D'Necesa Quarters. All Rights Reserved.</p>
</footer>
</body>
</html>
