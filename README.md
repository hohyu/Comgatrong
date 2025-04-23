# Comgatrong
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FastFood Việt</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff8f0;
      color: #333;
    }
    header {
      background-color: #ff6600;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #ffa64d;
      display: flex;
      justify-content: center;
      padding: 10px;
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
      background-image: url('https://example.com/hero-image.jpg'); /* Thay thế bằng URL hình ảnh thực tế */
      background-size: cover;
      background-position: center;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 4px #000;
      font-size: 2em;
    }
    .menu {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .menu-item {
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 8px;
      margin: 10px;
      width: 200px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .menu-item img {
      width: 100%;
      border-bottom: 1px solid #ddd;
    }
    .menu-item h3 {
      margin: 10px 0;
    }
    .menu-item p {
      color: #ff6600;
      font-weight: bold;
      margin-bottom: 10px;
    }
    .menu-item button {
      background-color: #ff6600;
      color: white;
      border: none;
      padding: 10px;
      margin-bottom: 10px;
      cursor: pointer;
      border-radius: 4px;
    }
    .menu-item button:hover {
      background-color: #e65c00;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .social-icons a {
      margin: 0 10px;
      color: white;
      text-decoration: none;
    }
    .social-icons a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>FastFood Việt</h1>
    <p>Ngon - Nhanh - Chuẩn vị Việt</p>
  </header>
  <nav>
    <a href="#menu">Thực đơn</a>
    <a href="#order">Đặt hàng</a>
    <a href="#contact">Liên hệ</a>
  </nav>
  <div class="hero">
    <div>Chào mừng đến với FastFood Việt!</div>
  </div>
  <section id="menu" class="menu">
    <div class="menu-item">
      <img src="https://example.com/burger.jpg" alt="Burger"/>
      <h3>Burger Bò</h3>
      <p>50.000₫</p>
      <button>Đặt ngay</button>
    </div>
    <div class="menu-item">
      <img src="https://example.com/fried-chicken.jpg" alt="Gà Rán"/>
      <h3>Gà Rán</h3>
      <p>45.000₫</p>
      <button>Đặt ngay</button>
    </div>
    <div class="menu-item">
      <img src="https://example.com/spaghetti.jpg" alt="Mì Ý"/>
      <h3>Mì Ý</h3>
      <p>55.000₫</p>
      <button>Đặt ngay</button>
    </div>
    <!-- Thêm các món khác tại đây -->
  </section>
  <section id="order" style="text-align:center; padding:20px;">
    <h2>Đặt hàng ngay</h2>
    <p>Gọi ngay: <a href="tel:0935660048">0935 660 048</a></p>
    <p>Hoặc đặt hàng qua ứng dụng của chúng tôi.</p>
    <!-- Thêm liên kết đến ứng dụng nếu có -->
  </section>
  <footer id="contact">
    <p>Liên hệ với chúng tôi:</p>
    <div class="social-icons">
      <a href="https://facebook.com/yourpage" target="_blank">Facebook</a>
      <a href="https://tiktok.com/@yourpage" target="_blank">TikTok</a>
      <a href="https://youtube.com/yourchannel" target="_blank">YouTube</a>
    </div>
    <p>Hotline: <a href="tel:0935660048" style="color: white;">0935 660 048</a></p>
    <p>&copy; 2025 FastFood Việt</p>
  </footer>
</body>
</html>
