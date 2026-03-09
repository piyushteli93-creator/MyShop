# MyShop
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Shop</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:#f4f4f4;
}

header{
    background:#111;
    color:white;
    padding:15px;
    text-align:center;
}

nav{
    background:#333;
    padding:10px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-size:18px;
}

nav a:hover{
    color:orange;
}

.hero{
    background:url("https://images.unsplash.com/photo-1441986300917-64674bd600d8") center/cover;
    height:300px;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
    font-size:35px;
    font-weight:bold;
}

.container{
    padding:30px;
}

.products{
    display:flex;
    gap:20px;
    flex-wrap:wrap;
    justify-content:center;
}

.card{
    background:white;
    width:220px;
    border-radius:10px;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
    text-align:center;
    padding:15px;
}

.card img{
    width:100%;
    border-radius:10px;
}

.price{
    color:green;
    font-weight:bold;
}

button{
    background:orange;
    border:none;
    padding:10px 15px;
    color:white;
    cursor:pointer;
    border-radius:5px;
}

button:hover{
    background:darkorange;
}

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:15px;
    margin-top:30px;
}
</style>
</head>

<body>

<header>
<h1>My Shop 🛒</h1>
<p>Best Products at Best Price</p>
</header>

<nav>
<a href="Home.html">Home</a>
<a href="Product.html">Products</a>
<a href="about.html">About</a>
<a href="Contact.html">Contact</a>
</nav>

<div class="hero">
Welcome to Our Shop
</div>

<div class="container">

<h2 style="text-align:center;">Our Products</h2>

<div class="products">

<div class="card">
<img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30">
<h3>Smart Watch</h3>
<p class="price">₹1999</p>
<button>Buy Now</button>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff">
<h3>Shoes</h3>
<p class="price">₹1499</p>
<button>Buy Now</button>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1523381294911-8d3cead13475">
<h3>T-Shirt</h3>
<p class="price">₹799</p>
<button>Buy Now</button>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9">
<h3>Smartphone</h3>
<p class="price">₹15999</p>
<button>Buy Now</button>
</div>

</div>
</div>

<footer>
<p>© 2026 My Shop | All Rights Reserved</p>
</footer>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Shop - Home</title>

<style>

body{
margin:0;
font-family:Arial, sans-serif;
background:#f4f4f4;
}

header{
background:#222;
color:white;
padding:15px;
text-align:center;
}

nav{
background:#444;
padding:10px;
text-align:center;
}

nav a{
color:white;
margin:0 15px;
text-decoration:none;
font-size:18px;
}

nav a:hover{
color:orange;
}

.hero{
background:#333;
color:white;
height:300px;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
}

.hero h1{
font-size:40px;
}

.hero p{
font-size:18px;
}

.btn{
background:orange;
color:white;
padding:10px 20px;
text-decoration:none;
border-radius:5px;
}

.container{
padding:30px;
text-align:center;
}

.products{
display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;
}

.card{
background:white;
width:200px;
padding:15px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.1);
}

.card img{
width:100%;
border-radius:10px;
}

footer{
background:#222;
color:white;
text-align:center;
padding:15px;
margin-top:30px;
}

</style>
</head>

<body>

<header>
<h1>My Shop 🛒</h1>
<p>Best Products at Best Price</p>
</header>

<nav>
<a href="Home.html">Home</a>
<a href="Product.html">Products</a>
<a href="about.html">About</a>
<a href="Contact.html">Contact</a>
</nav>

<div class="hero">
<h1>Welcome to My Shop</h1>
<p>Find the best products here</p>
<a href="products.html" class="btn">Shop Now</a>
</div>

<div class="container">
<h2>Featured Products</h2>

<div class="products">

<div class="card">
<img src="https://images.unsplash.com/photo-1523381294911-8d3cead13475">
<h3>T-Shirt</h3>
<p>₹799</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff">
<h3>Shoes</h3>
<p>₹1499</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30">
<h3>Smart Watch</h3>
<p>₹1999</p>
</div>

</div>
</div>

<footer>
<p>© 2026 My Shop | All Rights Reserved</p>
</footer>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Shop - Products</title>

<style>

body{
margin:0;
font-family:Arial, sans-serif;
background:#f4f4f4;
}

header{
background:#222;
color:white;
text-align:center;
padding:15px;
}

nav{
background:#444;
padding:10px;
text-align:center;
}

nav a{
color:white;
margin:0 15px;
text-decoration:none;
font-size:18px;
}

nav a:hover{
color:orange;
}

.container{
padding:30px;
text-align:center;
}

.products{
display:flex;
flex-wrap:wrap;
gap:20px;
justify-content:center;
}

.card{
background:white;
width:220px;
padding:15px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.1);
text-align:center;
}

.card img{
width:100%;
border-radius:10px;
}

.price{
color:green;
font-weight:bold;
}

button{
background:orange;
border:none;
padding:10px 15px;
color:white;
border-radius:5px;
cursor:pointer;
}

button:hover{
background:darkorange;
}

footer{
background:#222;
color:white;
text-align:center;
padding:15px;
margin-top:30px;
}

</style>
</head>

<body>

<header>
<h1>Our Products 🛍️</h1>
</header>

<nav>
<a href="Home.html">Home</a>
<a href="Product.html">Products</a>
<a href="about.html">About</a>
<a href="Contact.html">Contact</a>
</nav>

<div class="container">

<h2>Available Products</h2>

<div class="products">

<div class="card">
<img src="https://images.unsplash.com/photo-1523381294911-8d3cead13475">
<h3>T-Shirt</h3>
<p class="price">₹799</p>
<button>Buy Now</button>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff">
<h3>Shoes</h3>
<p class="price">₹1499</p>
<button>Buy Now</button>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30">
<h3>Smart Watch</h3>
<p class="price">₹1999</p>
<button>Buy Now</button>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9">
<h3>Mobile</h3>
<p class="price">₹64999</p>
<button>Buy Now</button>
</div>

<footer>
<p>© 2026 My Shop | All Rights Reserved</p>
</footer>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Contact Us - My Shop</title>

<style>

body{
margin:0;
font-family:Arial, sans-serif;
background:#f4f4f4;
}

header{
background:#222;
color:white;
text-align:center;
padding:15px;
}

nav{
background:#444;
padding:10px;
text-align:center;
}

nav a{
color:white;
margin:0 15px;
text-decoration:none;
font-size:18px;
}

nav a:hover{
color:orange;
}

.container{
max-width:700px;
margin:40px auto;
background:white;
padding:30px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.1);
}

h2{
text-align:center;
}

input, textarea{
width:100%;
padding:10px;
margin:10px 0;
border-radius:5px;
border:1px solid #ccc;
}

button{
background:orange;
color:white;
border:none;
padding:10px 15px;
border-radius:5px;
cursor:pointer;
}

button:hover{
background:darkorange;
}

.contact-info{
margin-top:20px;
text-align:center;
}

footer{
background:#222;
color:white;
text-align:center;
padding:15px;
margin-top:30px;
}

</style>
</head>

<body>

<header>
<h1>Contact Us</h1>
</header>

<nav>
<a href="Home.html">Home</a>
<a href="Product.html">Products</a>
<a href="about.html">About</a>
<a href="Contact.html">Contact</a>
</nav>

<div class="container">

<h2>Send Us a Message</h2>

<form>
<input type="text" placeholder="Your Name" required>
<input type="email" placeholder="Your Email" required>
<textarea rows="5" placeholder="Your Message"></textarea>
<button type="submit">Send Message</button>
</form>

<div class="contact-info">
<h3>Shop Contact Details</h3>
<p>📍 Address: Mumbai, India</p>
<p>📞 Phone: +91 9876543210</p>
<p>✉ Email: myshop@email.com</p>
</div>

</div>

<footer>
<p>© 2026 My Shop | All Rights Reserved</p>
</footer>

</body>
</html>
