<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ร้านขายรหัสออนไลน์</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>💻 ร้านขายรหัสออนไลน์</h1>
    <nav>
      <a href="#">หน้าแรก</a>
      <a href="#">สินค้า</a>
      <a href="#">ติดต่อ</a>
    </nav>
  </header>

  <main>
    <h2>สินค้า</h2>
    <div class="product-list">

      <!-- สินค้าตัวอย่าง -->
      <div class="product">
        <h3>รหัส Netflix Premium</h3>
        <p>ใช้งานได้ 1 เดือน</p>
        <span class="price">ราคา: 150฿</span>
        <button onclick="buyProduct('Netflix Premium')">ซื้อเลย</button>
      </div>

      <div class="product">
        <h3>รหัส YouTube Premium</h3>
        <p>ใช้งานได้ 1 เดือน</p>
        <span class="price">ราคา: 120฿</span>
        <button onclick="buyProduct('YouTube Premium')">ซื้อเลย</button>
      </div>

    </div>
  </main>

  <footer>
    <p>© 2025 ร้านขายรหัสออนไลน์</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
