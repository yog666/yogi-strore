# yogi-strore
toko online
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yogi Store | Elektronik Terbaik</title>
    <style>
        /* Gaya Sederhana untuk Tampilan */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            margin: 15px;
            width: 250px;
            text-align: center;
            padding: 15px;
        }
        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 5px;
        }
        .price {
            color: #e67e22;
            font-weight: bold;
            font-size: 1.2rem;
        }
        button {
            background-color: #27ae60;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }
        button:hover {
            background-color: #219150;
        }
    </style>
</head>
<body>

<header>
    <h1>Yogi Store</h1>
    <p>Menyediakan Perangkat Elektronik Masa Kini</p>
</header>

<div class="container">
    <div class="card">
        <img src="tv-yogi.jpg" alt="TV Merk Yogi">
        <h3>Smart TV Yogi 4K</h3>
        <p>Layar jernih, suara menggelegar.</p>
        <p class="price">Rp 3.500.000</p>
        <button>Beli Sekarang</button>
    </div>

    <div class="card">
        <img src="hp-yogi.jpg" alt="HP Merk Yogi">
        <h3>Yogi Phone Pro Max</h3>
        <p>RAM Besar, Kamera Super Jernih.</p>
        <p class="price">Rp 2.800.000</p>
        <button>Beli Sekarang</button>
    </div>
</div>

</body>
</html>


