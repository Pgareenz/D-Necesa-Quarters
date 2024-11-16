<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>D'Necesa Quarters</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background: #222;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 16px;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background: url('https://via.placeholder.com/1600x400') no-repeat center center/cover;
            color: white;
        }
        .hero h1 {
            font-size: 50px;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 20px;
        }
        section {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        section h2 {
            font-size: 28px;
            margin-bottom: 15px;
            text-align: center;
        }
        .about, .collections, .blog, .contact {
            background: white;
            margin-bottom: 20px;
            border-radius: 5px;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            margin-bottom: 10px;
        }
        .newsletter {
            text-align: center;
            padding: 20px;
            background: #f4f4f4;
        }
        .newsletter input {
            padding: 10px;
            font-size: 16px;
            margin-right: 10px;
        }
        footer {
            background: #222;
            color: #fff;
            text-align: center;
            padding: 15px 0;
        }
        footer a {
            color: #1e90ff;
            text-decoration: none;
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
<section id="about" class="about">
    <h2>About Us</h2>
    <p>D’Necesa Quarters Enterprises provides young men and women who are upwardly mobile, working-class, CEOs, business owners, and couples aged 25-65 with high-quality and stylish pieces of jewelry that exude confidence and sophistication.</p>
    <h3>What We Do</h3>
    <ul>
        <li>Earrings</li>
        <li>Necklaces</li>
        <li>Engagement & Fashion Rings</li>
        <li>Bracelets & Bangles</li>
        <li>Brooches</li>
        <li>Cufflinks</li>
        <li>Bridal Accessories</li>
    </ul>
    <h3>Mission Statement</h3>
    <p>To adorn our customers with a fine collection of high-quality and stylish jewelry that not only suits their personal style and identity but also tells a story about who they are.</p>
    <h3>Vision Statement</h3>
    <p>To be the one-stop destination for unique pieces of jewelry and bridal accessories.</p>
</section>
<section id="collections" class="collections">
    <h2>Our Collections</h2>
    <ul>
        <li>Earrings</li>
        <li>Necklaces</li>
        <li>Rings</li>
        <li>Bracelets and Bangles</li>
        <li>Brooches</li>
        <li>Jewelry Boxes</li>
    </ul>
</section>
<section id="blog" class="blog">
    <h2>Our Blog</h2>
    <ul>
        <li><a href="#">Why is Jewelry Important?</a></li>
        <li><a href="#">Combining Different Jewelry</a></li>
        <li><a href="#">Things to Look Out for When Choosing a Jewelry Design</a></li>
        <li><a href="#">How to Care for Your Jewelry</a></li>
    </ul>
</section>
<section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> 08163665229</p>
    <p><strong>Email:</strong> dnecesaqtrs@gmail.com</p>
    <p><strong>Follow us on:</strong></p>
    <ul>
        <li><a href="https://instagram.com/dnecesaqtrs" target="_blank">Instagram</a></li>
        <li><a href="https://facebook.com/dnecesaqtrs" target="_blank">Facebook</a></li>
    </ul>
</section>
<section class="newsletter">
    <h2>Join Our Newsletter</h2>
    <p>Subscribe to get firsthand information about our special offers, giveaways, and combo deals!</p>
    <input type="email" id="email" placeholder="Enter your email">
    <button onclick="subscribeNewsletter()">Subscribe</button>
    <p id="newsletter-msg"></p>
</section>
<footer>
    <p>&copy; 2024 D'Necesa Quarters. All Rights Reserved.</p>
    <p><a href="#home">Back to Top</a></p>
</footer>
<script>
    function subscribeNewsletter() {
        const email = document.getElementById('email').value;
        const message = document.getElementById('newsletter-msg');
        if (email) {
            message.textContent = "Thank you for subscribing!";
            message.style.color = "green";
        } else {
            message.textContent = "Please enter a valid email address.";
            message.style.color = "red";
        }
    }
</script>
</body>
</html>
