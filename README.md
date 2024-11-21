<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>D'Necesa Quarters</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f5f0;
            color: #333;
        }
        header {
            background: #1e1e1e;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 36px;
            font-weight: bold;
        }
        header p {
            font-size: 16px;
            color: #d3a86b;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #d3a86b;
            padding: 10px 0;
        }
        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
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
        .collections {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .collections a {
            text-decoration: none;
            color: #333;
            text-align: center;
            cursor: pointer;
        }
        .collections img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .collections h3 {
            margin: 10px 0 5px;
        }
        .products {
            display: none;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .product-grid div {
            text-align: center;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .product-grid img {
            width: 100%;
            border-radius: 10px;
        }
        button {
            margin-top: 10px;
            padding: 10px 15px;
            background: #d3a86b;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        footer {
            background: #1e1e1e;
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
    <p>D'Necesa Quarters provides elegant and stylish jewelry for upwardly mobile individuals. Our mission is to inspire confidence and sophistication in every client. Explore our exclusive collections to enhance your personal style.</p>
</section>
<section id="collections">
    <h2>Our Collections</h2>
    <div class="collections">
        <div onclick="showProducts('earrings')">
            <img src="https://via.placeholder.com/300" alt="Earrings">
            <h3>Earrings</h3>
        </div>
        <div onclick="showProducts('necklaces')">
            <img src="https://via.placeholder.com/300" alt="Necklaces">
            <h3>Necklaces</h3>
        </div>
        <div onclick="showProducts('rings')">
            <img src="https://via.placeholder.com/300" alt="Rings">
            <h3>Rings</h3>
        </div>
        <div onclick="showProducts('bracelets')">
            <img src="https://via.placeholder.com/300" alt="Bracelets">
            <h3>Bracelets</h3>
        </div>
    </div>
</section>
<section id="products" class="products">
    <h2 id="product-title"></h2>
    <div class="product-grid" id="product-grid"></div>
</section>
<section id="blog">
    <h2>Our Blog</h2>
    <p>Coming Soon...</p>
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
    <p><a href="#home">Back to Top</a></p>
</footer>
<script>
    const products = {
        earrings: [
            { name: "Elegant Earrings", price: "$50", img: "https://via.placeholder.com/300" },
            { name: "Classic Earrings", price: "$40", img: "https://via.placeholder.com/300" },
        ],
        necklaces: [
            { name: "Pearl Necklace", price: "$80", img: "https://via.placeholder.com/300" },
            { name: "Gold Necklace", price: "$100", img: "https://via.placeholder.com/300" },
        ],
        rings: [
            { name: "Diamond Ring", price: "$150", img: "https://via.placeholder.com/300" },
            { name: "Wedding Band", price: "$120", img: "https://via.placeholder.com/300" },
        ],
        bracelets: [
            { name: "Gold Bracelet", price: "$70", img: "https://via.placeholder.com/300" },
            { name: "Charm Bracelet", price: "$60", img: "https://via.placeholder.com/300" },
        ],
    };
    function showProducts(category) {
        const productGrid = document.getElementById("product-grid");
        const productTitle = document.getElementById("product-title");
        const productsSection = document.getElementById("products");
        productTitle.textContent = category.charAt(0).toUpperCase() + category.slice(1);
        productGrid.innerHTML = "";
        products[category].forEach((product) => {
            productGrid.innerHTML += `
                <div>
                    <img src="${product.img}" alt="${product.name}">
                    <h3>${product.name}</h3>
                    <p>${product.price}</p>
                    <button onclick="alert('Payment gateway coming soon!')">Buy Now</button>
                </div>
            `;
        });
    productsSection.style.display = "block";
        window.scrollTo(0, productsSection.offsetTop);
    }
</script>
</body>
</html>
