# website-peternakan-ayam
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Toko Ayam Pak Dimas</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background-color: #fffaf0;
      animation: fadeIn 1s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    header {
      position: sticky;
      top: 0;
      z-index: 10;
      background: linear-gradient(90deg, #ff9933, #ff6600);
      padding: 20px;
      text-align: center;
      color: white;
      box-shadow: 0px 4px 8px rgba(0,0,0,0.2);
    }

    h1 {
      margin: 0;
      font-size: 2rem;
    }

    main {
      padding: 20px;
      max-width: 1200px;
      margin: auto;
    }

    h2 {
      text-align: center;
      color: #ff6600;
      margin-bottom: 20px;
      font-size: 1.8rem;
    }

    .produk {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .card {
      background-color: white;
      border-radius: 12px;
      padding: 15px;
      width: 260px;
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      box-shadow: 0px 4px 12px rgba(0,0,0,0.1);
      animation: zoomIn 0.5s ease-in-out;
    }

    @keyframes zoomIn {
      from { transform: scale(0.85); opacity: 0; }
      to { transform: scale(1); opacity: 1; }
    }

    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0px 10px 25px rgba(0,0,0,0.15);
    }

    .card img {
      width: 100%;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }

    .card img:hover {
      transform: scale(1.05);
    }

    .card h3 {
      color: #ff6600;
      margin: 12px 0 5px 0;
      font-size: 1.2rem;
    }

    .card p {
      font-size: 14px;
      color: #555;
    }

    .price {
      font-size: 18px;
      font-weight: bold;
      margin: 8px 0;
      color: #333;
    }

    .btn-beli {
      display: inline-block;
      padding: 10px 18px;
      background: linear-gradient(90deg, #ff6600, #ff3300);
      color: white;
      font-weight: 600;
      text-decoration: none;
      border-radius: 6px;
      transition: all 0.3s ease;
    }

    .btn-beli:hover {
      background: linear-gradient(90deg, #e65c00, #cc2900);
      transform: scale(1.05);
    }

    footer {
      text-align: center;
      padding: 15px;
      background: linear-gradient(90deg, #ff9933, #ff6600);
      color: white;
      font-size: 14px;
      margin-top: 30px;
    }

    @media (max-width: 600px) {
      .card {
        width: 90%;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>🐔 Toko Ayam Pak Dimas 🐔</h1>
  </header>

  <main>
    <h2>Produk Kami</h2>
    <div class="produk">
      <div class="card">
        <img src="https://ayamkita.com/wp-content/uploads/2019/03/cara-ternak-ayam-potong-1152x830.jpg" alt="Ayam Potong">
        <h3>Ayam Potong Segar</h3>
        <p>Segar langsung dari peternakan.</p>
        <div class="price">Rp 35.000 / Kg</div>
        <a href="#" class="btn-beli">Beli Sekarang</a>
      </div>
      <div class="card">
        <img src="https://4.bp.blogspot.com/-2Coa3axg_Ts/VsujqaNJONI/AAAAAAAAAH0/HoC9FLuBroM/s1600/ayam-pelung-jago.jpg" alt="Ayam Kampung">
        <h3>Ayam Kampung</h3>
        <p>Rasa gurih alami dan sehat.</p>
        <div class="price">Rp 50.000 / Kg</div>
        <a href="#" class="btn-beli">Beli Sekarang</a>
      </div>
      <div class="card">
        <img src="https://i.pinimg.com/736x/e0/d0/d9/e0d0d9d5d6cf9ca406eda0b49b589a60.jpg" alt="Ayam Bertelur">
        <h3>Ayam Bertelur</h3>
        <p>Cocok untuk ternak atau konsumsi telur.</p>
        <div class="price">Rp 45.000 / Kg</div>
        <a href="#" class="btn-beli">Beli Sekarang</a>
      </div>
    </div>
  </main>

  <footer>
    &copy; 2025 Toko Ayam Pak Dimas | 📞 0822-4478-7808 | ✉ dimasturu75@gmail.com
  </footer>

</body>
</html>
