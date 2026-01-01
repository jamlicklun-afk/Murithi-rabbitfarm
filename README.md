
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NEXORA - Buy Healthy Rabbits</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<style>
  body { font-family: 'Roboto', sans-serif; margin:0; padding:0; background:#f9f9f9; }
  header { background:#fff; text-align:center; padding:20px; box-shadow:0 2px 5px rgba(0,0,0,0.1);}
  header img { max-width:200px; }
  nav { margin-top:10px; }
  nav a { margin:0 10px; text-decoration:none; color:#555; font-weight:700; cursor:pointer; }
  .hero { text-align:center; padding:50px 20px; background:#dff0f7; }
  .hero h1 { font-size:36px; color:#333; margin-bottom:10px; }
  .hero p { font-size:18px; color:#666; margin-bottom:20px; }
  .hero a { background:#4CAF50; color:#fff; padding:15px 30px; text-decoration:none; border-radius:5px; font-weight:700; cursor:pointer; }
  .categories, .products, .best-sellers, .footer { padding:40px 20px; text-align:center; }
  h2 { margin-bottom:20px; color:#333; }
  .category-list { display:flex; justify-content:center; gap:20px; flex-wrap:wrap; margin-bottom:40px; }
  .category-card { background:#fff; padding:20px; border-radius:10px; box-shadow:0 2px 10px rgba(0,0,0,0.1); width:180px; cursor:pointer; }
  .category-card img { width:100%; border-radius:10px; margin-bottom:10px; }
  .category-card p { font-weight:700; color:#555; }
  .product-grid { display:flex; justify-content:center; flex-wrap:wrap; gap:20px; }
  .product-card { background:#fff; border-radius:10px; width:220px; box-shadow:0 2px 10px rgba(0,0,0,0.1); padding:15px; text-align:center; }
  .product-card img { width:100%; border-radius:10px; margin-bottom:10px; }
  .product-card h3 { color:#333; margin:5px 0; }
  .product-card p { color:#666; font-size:14px; }
  .product-card .price { font-weight:700; color:#4CAF50; margin:10px 0; }
  .product-card a { background:#4CAF50; color:#fff; padding:10px 20px; text-decoration:none; border-radius:5px; display:inline-block; margin-top:10px; cursor:pointer; }
  .footer { background:#333; color:#fff; }
  .footer p { margin:5px 0; }
  .social-icons { margin-top:10px; }
  .social-icons a { margin:0 10px; color:#fff; text-decoration:none; font-size:20px; }
</style>
</head>
<body>

<header>
  <img src="https://i.imgur.com/yourLogo.png" alt="NEXORA Logo">
  <nav>
    <a onclick="scrollToSection('categories')">Categories</a>
    <a onclick="scrollToSection('products')">Rabbits</a>
    <a onclick="scrollToSection('best-sellers')">Best Sellers</a>
    <a onclick="scrollToSection('contact')">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>Healthy Rabbits, Delivered to You</h1>
  <p>Easy, Safe, and Reliable Rabbit Buying Experience</p>
  <a onclick="scrollToSection('products')">Buy a Rabbit Now</a>
</section>

<section class="categories" id="categories">
  <h2>Rabbit Categories</h2>
  <div class="category-list">
    <div class="category-card" onclick="filterCategory('Young')">
      <img src="https://upmarketsellers.co.ke/wp-content/uploads/2025/01/Young-Rabbits-1024x769.jpg" alt="Young Rabbits">
      <p>Young Rabbits</p>
    </div>
    <div class="category-card" onclick="filterCategory('Middle-Age')">
      <img src="https://graduatefarmer.co.ke/wp-content/uploads/2016/03/rabbit-farming-in-Kenya.png" alt="Middle-Age Rabbits">
      <p>Middle-Age Rabbits</p>
    </div>
    <div class="category-card" onclick="filterCategory('Adult')">
      <img src="https://medilinkvet.wordpress.com/wp-content/uploads/2013/07/rabit.jpg?w=616" alt="Adult Rabbits">
      <p>Adult Rabbits</p>
    </div>
  </div>
</section>

<section class="products" id="products">
  <h2>All Rabbits</h2>
  <div class="product-grid" id="productGrid">
    <!-- Young Rabbits 7 -->
    <div class="product-card" data-category="Young">
      <img src="https://upmarketsellers.co.ke/wp-content/uploads/2025/01/Young-Rabbits-1024x769.jpg" alt="Young Rabbit">
      <h3>Kienyeji Young Rabbit 1</h3>
      <p>Age: 2 months / Weight: 2 kg</p>
      <p class="price">500 KSh</p>
      <p>Healthy, disease-free, perfect starter rabbit.</p>
      <a href="tel:0116227696">Buy Now</a>
    </div>
    <div class="product-card" data-category="Young">
      <img src="https://thecapecoop.com/wp-content/uploads/2021/01/IMG_8341-1024x768.jpg" alt="Young Rabbit">
      <h3>Kienyeji Young Rabbit 2</h3>
      <p>Age: 2 months / Weight: 2 kg</p>
      <p class="price">500 KSh</p>
      <p>Healthy, disease-free, perfect starter rabbit.</p>
      <a href="tel:0116227696">Buy Now</a>
    </div>
    <!-- Repeat 5 more young rabbit cards with different photos -->
    
    <!-- Middle-Age Rabbits 6 -->
    <div class="product-card" data-category="Middle-Age">
      <img src="https://graduatefarmer.co.ke/wp-content/uploads/2016/03/rabbit-farming-in-Kenya.png" alt="Middle-Age Rabbit">
      <h3>Kienyeji Middle-Age Rabbit 1</h3>
      <p>Age: 2 months / Weight: 2 kg</p>
      <p class="price">800 KSh</p>
      <p>Healthy, disease-free, ideal for breeding.</p>
      <a href="tel:0116227696">Buy Now</a>
    </div>
    <!-- Repeat 5 more middle-age rabbit cards with different photos -->

    <!-- Adult Rabbits 7 -->
    <div class="product-card" data-category="Adult">
      <img src="https://medilinkvet.wordpress.com/wp-content/uploads/2013/07/rabit.jpg?w=616" alt="Adult Rabbit">
      <h3>Kienyeji Adult Rabbit 1</h3>
      <p>Age: 2 months / Weight: 2 kg</p>
      <p class="price">1250 KSh</p>
      <p>Healthy, premium quality breed.</p>
      <a href="tel:0116227696">Buy Now</a>
    </div>
    <!-- Repeat 6 more adult rabbit cards with different photos -->
  </div>
</section>

<section class="best-sellers" id="best-sellers">
  <h2>Best-Selling Rabbits</h2>
  <div class="product-grid">
    <div class="product-card">
      <img src="https://medilinkvet.wordpress.com/wp-content/uploads/2013/07/rabit.jpg?w=616" alt="Best Adult Rabbit">
      <h3>Adult Rabbit</h3>
      <p>Age: 2 months / Weight: 2 kg</p>
      <p class="price">1250 KSh</p>
      <p>Top seller! Healthy and disease-free.</p>
      <a href="tel:0116227696">Buy Now</a>
    </div>
  </div>
</section>

<section class="footer" id="contact">
  <h2>Contact & Payment</h2>
  <p>Call or WhatsApp to buy your rabbit: <strong>0116227696</strong></p>
  <div class="social-icons">
    <a href="https://www.facebook.com/yourpage" target="_blank"><img src="https://img.icons8.com/ios-filled/50/ffffff/facebook-new.png" width="24"/></a>
    <a href="https://www.instagram.com/yourpage" target="_blank"><img src="https://img.icons8.com/ios-filled/50/ffffff/instagram-new.png" width="24"/></a>
    <a href="https://wa.me/0116227696" target="_blank"><img src="https://img.icons8.com/ios-filled/50/ffffff/whatsapp.png" width="24"/></a>
  </div>
  <p>&copy; 2026 NEXORA</p>
</section>

<script>
  function scrollToSection(id) {
    document.getElementById(id).scrollIntoView({behavior: 'smooth'});
  }

  function filterCategory(category) {
    const products = document.querySelectorAll('.product-card');
    products.forEach(p => {
      if (category === 'All' || p.getAttribute('data-category') === category) {
        p.style.display = 'block';
      } else {
        p.style.display = 'none';
      }
    });
  }
</script>

</body>
</html>
