# miniatur-makanan.
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Menu Miniatur Makanan</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: url('https://images.unsplash.com/photo-1556740749-887f6717d7e4') no-repeat center center fixed;
      background-size: cover;
      color: #333;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 800px;
      margin: auto;
      background-color: rgba(255,255,255,0.9);
      padding: 20px;
      border-radius: 15px;
      margin-top: 40px;
    }
    h1 {
      text-align: center;
      color: #4b3d2a;
    }
    .menu-item {
      display: flex;
      align-items: center;
      margin-bottom: 20px;
    }
    .menu-item img {
      width: 150px;
      border-radius: 10px;
      margin-right: 20px;
    }
    .menu-item h3 {
      margin: 0;
    }
    .suggestions {
      margin-top: 30px;
    }
    textarea {
      width: 100%;
      height: 100px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Miniatur Ramen Menu</h1>
    <div class="menu-item">
      <img src="ramen.jpg" alt="Ramen Lezat" />
      <div>
        <h3>Ramen Shoyu</h3>
        <p>Harga: Rp35.000</p>
      </div>
    </div>
    <div class="suggestions">
      <h2>Kritik & Saran</h2>
      <form>
        <textarea placeholder="Tulis saran atau pesan di sini..."></textarea><br><br>
        <button type="submit">Kirim</button>
      </form>
    </div>
  </div>
</body>
</html>
