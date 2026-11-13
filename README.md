# Vedya-wear-

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>VEDYA WEAR | Premium Fashion</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background: #080808;
  color: white;
  font-family: Arial, sans-serif;
}

header {
  text-align: center;
  padding: 25px 10px;
  border-bottom: 1px solid #c9a45c;
}

.logo {
  color: #d8b66b;
  font-size: 32px;
  font-weight: bold;
  letter-spacing: 5px;
}

header p {
  color: #aaa;
  font-size: 11px;
  letter-spacing: 3px;
  margin-top: 8px;
}

.hero {
  text-align: center;
  padding: 75px 15px;
  background:
  linear-gradient(#0009,#000b),
  url('https://images.unsplash.com/photo-1483985988355-763728e1935b?w=1200')
  center/cover;
}

.hero h1 {
  color: #e4c477;
  font-size: 38px;
}

.hero p {
  margin: 15px 0 25px;
}

.hero a {
  background: #d8b66b;
  color: black;
  padding: 13px 25px;
  text-decoration: none;
  font-weight: bold;
}

.heading {
  text-align: center;
  color: #d8b66b;
  margin: 35px 0 20px;
  letter-spacing: 2px;
}

.products {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 15px;
  padding: 15px;
}

.product {
  background: #171717;
  border: 1px solid #66512d;
  padding: 10px;
  text-align: center;
  border-radius: 8px;
}

.product img {
  width: 100%;
  height: 190px;
  object-fit: cover;
  border-radius: 5px;
}

.product h3 {
  margin: 12px 0;
  font-size: 16px;
}

.price {
  color: #e4c477;
  font-size: 22px;
  font-weight: bold;
  margin-bottom: 14px;
}

.buy {
  display: block;
  background: #d8b66b;
  color: #080808;
  text-decoration: none;
  padding: 12px 5px;
  font-weight: bold;
  border-radius: 4px;
}

.buy:active {
  background: white;
}

footer {
  text-align: center;
  padding: 30px 10px;
  margin-top: 30px;
  border-top: 1px solid #66512d;
  color: #aaa;
}

footer h3 {
  color: #d8b66b;
  margin-bottom: 10px;
}

@media(max-width:350px) {
  .products {
    grid-template-columns: 1fr;
  }

  .hero h1 {
    font-size: 27px;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">VEDYA WEAR</div>
  <p>STYLE • QUALITY • CLASS</p>
</header>

<section class="hero">
  <h1>WEAR YOUR STYLE</h1>
  <p>Premium Fashion. Timeless Looks.</p>
  <a href="#collection">EXPLORE COLLECTION</a>
</section>

<h2 class="heading" id="collection">
  OUR COLLECTION
</h2>

<section class="products">

  <div class="product">
    <img
    src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?w=600"
    alt="Oversized T-shirt">

    <h3>Oversized T-Shirt</h3>
    <div class="price">₹299</div>

    <a class="buy"
    href="https://wa.me/91XXXXXXXXXX?text=Hello%20VEDYA%20WEAR%2C%20I%20want%20to%20order%20Oversized%20T-Shirt">
    BUY NOW
    </a>
  </div>

  <div class="product">
    <img
    src="https://images.unsplash.com/photo-1523381210434-271e8be1f52b?w=600"
    alt="Regular Fit T-shirt">

    <h3>Regular Fit T-Shirt</h3>
    <div class="price">₹299</div>

    <a class="buy"
    href="https://wa.me/917558364115text=Hello%20VEDYA%20WEAR%2C%20I%20want%20to%20order%20Regular%20Fit%20T-Shirt">
    BUY NOW
    </a>
  </div>

</section>

<footer>
  <h3>VEDYA WEAR</h3>
  <p>Thanks for visiting our store.</p>
  <p>© 2026 VEDYA WEAR</p>
</footer>

</body>
</html>
