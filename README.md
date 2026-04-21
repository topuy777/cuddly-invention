<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Landing Jualan - Neon Style</title>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Segoe UI', sans-serif;
    }

    body {
        background: radial-gradient(circle at center, #2b0000, #0a0000);
        color: #fff;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        overflow: hidden;
    }

    .container {
        text-align: center;
        position: relative;
    }

    /* Lingkaran Glow */
    .glow-circle {
        width: 500px;
        height: 500px;
        border-radius: 50%;
        border: 6px solid #ffcc00;
        box-shadow: 0 0 40px #ff3300, inset 0 0 30px #ff6600;
        display: flex;
        justify-content: center;
        align-items: center;
        background: radial-gradient(circle, #400000, #100000);
    }

    /* Card Tengah */
    .card {
        background: rgba(0,0,0,0.6);
        padding: 30px;
        border-radius: 20px;
        box-shadow: 0 0 20px rgba(255, 0, 0, 0.8);
        width: 300px;
    }

    .card h1 {
        font-size: 28px;
        color: #ffcc00;
        margin-bottom: 10px;
        text-shadow: 0 0 10px #ff6600;
    }

    .card p {
        font-size: 14px;
        margin-bottom: 20px;
        color: #ddd;
    }

    /* Tombol */
    .btn {
        display: block;
        padding: 12px;
        margin: 10px 0;
        border-radius: 30px;
        text-decoration: none;
        font-weight: bold;
        transition: 0.3s;
    }

    .btn-primary {
        background: #ffcc00;
        color: #000;
        box-shadow: 0 0 15px #ffcc00;
    }

    .btn-primary:hover {
        background: #ffd633;
        transform: scale(1.05);
    }

    .btn-secondary {
        border: 2px solid #ffcc00;
        color: #ffcc00;
    }

    .btn-secondary:hover {
        background: #ffcc00;
        color: #000;
    }

    /* Background dekorasi bulat */
    .bubble {
        position: absolute;
        border-radius: 50%;
        background: radial-gradient(circle, #ff4d4d, #660000);
        box-shadow: 0 0 20px #ff0000;
        animation: float 6s infinite ease-in-out;
    }

    .bubble:nth-child(1) { width: 40px; height: 40px; top: 10%; left: 20%; }
    .bubble:nth-child(2) { width: 60px; height: 60px; bottom: 15%; right: 25%; }
    .bubble:nth-child(3) { width: 30px; height: 30px; top: 70%; left: 10%; }

    @keyframes float {
        0% { transform: translateY(0); }
        50% { transform: translateY(-20px); }
        100% { transform: translateY(0); }
    }

    footer {
        margin-top: 20px;
        font-size: 12px;
        color: #888;
    }
</style>
</head>

<body>

<div class="container">

    <!-- Dekorasi -->
    <div class="bubble"></div>
    <div class="bubble"></div>
    <div class="bubble"></div>

    <div class="glow-circle">
        <div class="card">
            <h1>Brand Jualan</h1>
            <p>Produk terbaru & promo terbaik untuk Anda</p>

            <a href="#" class="btn btn-primary">BELI SEKARANG</a>
            <a href="#" class="btn btn-secondary">LIHAT PRODUK</a>

            <a href="#" class="btn btn-secondary">WHATSAPP</a>
        </div>
    </div>

    <footer>
        © 2026 Brand Anda
    </footer>

</div>

</body>
</html>
