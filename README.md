<!DOCTYPE html><html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Warung Rakyat Perindo Kab. Karawang</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #fff;
            color: #000;
        }
        header {
            background-color: #d32f2f;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header img {
            width: 80px;
            display: block;
            margin: 0 auto;
        }
        nav {
            background-color: #002984;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        nav a {
            color: white;
            padding: 15px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #1565c0;
        }
        section {
            padding: 30px;
        }
        .product img, .gallery img {
            width: 150px;
            height: auto;
            margin: 10px;
        }
        form input, form textarea {
            display: block;
            margin-bottom: 10px;
            padding: 8px;
            width: 100%;
            max-width: 400px;
        }
        footer {
            background-color: #002984;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo-perindo.png" alt="Logo Partai Perindo">
        <h1>WARUNG RAKYAT PERINDO KAB. KARAWANG</h1>
        <p><em>"Bersama Koperasi, Kuatkan Ekonomi Rakyat!"</em></p>
    </header><nav>
    <a href="#beranda">Beranda</a>
    <a href="#tentang">Tentang Kami</a>
    <a href="#produk">Produk Kami</a>
    <a href="#mitra">Pendaftaran Mitra</a>
    <a href="#berita">Berita & Kegiatan</a>
    <a href="#galeri">Galeri Foto</a>
    <a href="#testimoni">Testimoni</a>
    <a href="#kontak">Kontak Kami</a>
</nav>

<section id="tentang">
    <h2>Tentang Kami</h2>
    <p>Koperasi Warung Rakyat Perindo Kabupaten Karawang merupakan inisiatif ekonomi kerakyatan yang didukung penuh oleh Partai Perindo. Kami hadir sebagai bentuk nyata perjuangan untuk kesejahteraan rakyat melalui penguatan ekonomi dari bawah. Dengan semangat gotong royong dan solidaritas, kami percaya bahwa koperasi adalah kunci menuju masa depan ekonomi yang lebih adil dan berkelanjutan.</p>
</section>

<section id="produk">
    <h2>Produk Kami</h2>
    <div class="product">
        <img src="sembako.jpg" alt="Sembako">
        <p>Sembako - Kebutuhan pokok rakyat</p>
        <img src="snack.jpg" alt="Makanan Ringan">
        <p>Makanan Ringan - Produk UMKM lokal</p>
        <img src="kopi.jpg" alt="Kopi">
        <p>Kopi - Rasa nusantara yang khas</p>
    </div>
</section>

<section id="mitra">
    <h2>Pendaftaran Mitra Warung</h2>
    <form action="https://wa.me/6283893486044" method="get">
        <input type="text" name="nama" placeholder="Nama" required>
        <input type="text" name="hp" placeholder="Nomor HP" required>
        <input type="text" name="alamat" placeholder="Alamat" required>
        <input type="text" name="jenis_usaha" placeholder="Jenis Usaha" required>
        <textarea name="alasan" placeholder="Alasan Bergabung" required></textarea>
        <button type="submit">Kirim ke WhatsApp</button>
    </form>
</section>

<section id="berita">
    <h2>Berita & Kegiatan</h2>
    <p>Sedang disiapkan... Nantikan informasi terbaru seputar koperasi, program partai, dan kegiatan rakyat.</p>
</section>

<section id="galeri">
    <h2>Galeri Foto</h2>
    <div class="gallery">
        <img src="kegiatan1.jpg" alt="Kegiatan 1">
        <img src="pelatihan.jpg" alt="Pelatihan">
        <img src="bantuan.jpg" alt="Penyerahan Bantuan">
    </div>
</section>

<section id="testimoni">
    <h2>Testimoni</h2>
    <blockquote>"Bergabung dengan Warung Perindo membuat usaha saya lebih berkembang." - Ibu Sari, Mitra Warung</blockquote>
    <blockquote>"Koperasi ini memberikan semangat baru bagi kami pelaku UMKM." - Pak Deni, Anggota</blockquote>
</section>

<section id="kontak">
    <h2>Kontak Kami</h2>
    <p>WhatsApp: <a href="https://wa.me/6283893486044">083893486044</a></p>
    <form>
        <input type="text" name="nama" placeholder="Nama">
        <input type="email" name="email" placeholder="Email">
        <textarea name="pesan" placeholder="Pesan Anda"></textarea>
        <button type="submit">Kirim Pesan</button>
    </form>
</section>

<footer>
    <p>&copy; 2025 Warung Rakyat Perindo Kab. Karawang. Semua hak dilindungi.</p>
</footer>

</body>
</html>
