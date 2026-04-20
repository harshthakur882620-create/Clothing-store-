# Clothing-store-
It's my first repository on github
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Fashion Store</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>🔥 Trendy Wear Store</h1>
  <nav>
    <a href="#">Home</a>
    <a href="#">Shop</a>
    <a href="#">Contact</a>
  </nav>
</header>

<section class="hero">
  <h2>New Fashion Collection 2026</h2>
  <p>Best clothes at best price</p>
  <button>Shop Now</button>
</section>

<section class="products">
  <div class="card">
    <img src="https://via.placeholder.com/200" alt="">
    <h3>T-Shirt</h3>
    <p>₹499</p>
  </div>

  <div class="card">
    <img src="https://via.placeholder.com/200" alt="">
    <h3>Hoodie</h3>
    <p>₹999</p>
  </div>

  <div class="card">
    <img src="https://via.placeholder.com/200" alt="">
    <h3>Jacket</h3>
    <p>₹1499</p>
  </div>
</section>

<footer>
  <p>© 2026 Trendy Wear Store</p>
</footer>

</body>
</html>
body {
  font-family: Arial;
  margin: 0;
  background: #f5f5f5;
}

/* Header */
header {
  background: black;
  color: white;
  padding: 15px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}

/* Hero */
.hero {
  text-align: center;
  padding: 60px;
  background: linear-gradient(135deg, #ff4e50, #f9d423);
  color: white;
}

.hero button {
  padding: 10px 20px;
  border: none;
  background: black;
  color: white;
  cursor: pointer;
}

/* Products */
.products {
  display: flex;
  justify-content: center;
  gap: 20px;
  padding: 30px;
}

.card {
  background: white;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  box-shadow: 0 0 10px rgba(0,0,0,0.2);
  transition: 0.3s;
}

.card:hover {
  transform: scale(1.05);
}

/* Footer */
footer {
  text-align: center;
  background: black;
  color: white;
  padding: 10px;
}
console.log("Website Loaded!");
