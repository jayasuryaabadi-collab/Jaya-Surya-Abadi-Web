<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
PT Nusantara Supply Indonesia
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>PT NUSANTARA SUPPLY INDONESIA</h1>
<p>Supplier Kopi • Minyak Sawit • Wood Pellet • Pakaian</p>
</header>

<section class="hero">
<h2>Solusi Supply Lokal & Ekspor</h2>
<p>Kami melayani pembelian retail, grosir, hingga ekspor internasional.</p>

<a href="produk.html"><button>Lihat Produk</button></a>
<a href="ekspor.html"><button>Ekspor Wood Pellet</button></a>
</section>

<section class="about">
<h2>Tentang Perusahaan</h2>
<p>
Kami adalah perusahaan supply berbasis di Indonesia yang melayani kebutuhan
produk konsumsi dan energi biomassa. Fokus utama kami adalah kualitas produk,
ketepatan pengiriman, serta kemitraan jangka panjang.
</p>
</section>

<section class="kontak">
<h2>Kontak Bisnis</h2>
<p>Email: sales@nusantarasupply.co.id</p>
<p>WhatsApp: +62 812-xxxx-xxxx</p>
</section>

<footer>
© 2026 PT Nusantara Supply Indonesia
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ekspor Wood Pellet Indonesia</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h2>EKSPOR WOOD PELLET INDONESIA</h2>
<p>Supplier Biomass Fuel untuk Pasar Global</p>
</header>

<div class="container">

<h3>Spesifikasi Produk</h3>

<ul>
<li>Diameter: 6mm & 8mm</li>
<li>Moisture: < 10%</li>
<li>Calorific Value: 4,200+ kcal/kg</li>
<li>Material: Kayu campuran hardwood</li>
<li>Packing: Jumbo bag / bulk</li>
<li>Kapasitas: 1.000 – 5.000 ton/bulan</li>
</ul>

<h3>Keunggulan Kami</h3>
<ul>
<li>Harga kompetitif pabrik langsung</li>
<li>Kualitas stabil ekspor</li>
<li>Dukungan dokumen ekspor lengkap</li>
<li>Pengiriman via pelabuhan Indonesia</li>
</ul>

<h3>Permintaan Penawaran (RFQ)</h3>

<form onsubmit="kirimRFQ(event)">
<input id="nama" placeholder="Nama Perusahaan" required>
<input id="negara" placeholder="Negara Tujuan" required>
<input id="qty" placeholder="Kebutuhan ton per bulan" required>
<button type="submit">Kirim Permintaan</button>
</form>

</div>

<script>
function kirimRFQ(e){
e.preventDefault();

let nama=document.getElementById("nama").value;
let negara=document.getElementById("negara").value;
let qty=document.getElementById("qty").value;

let pesan=`Hello, we are interested in Wood Pellet supply.%0ACompany: ${nama}%0ACountry: ${negara}%0AQuantity: ${qty} ton/month`;

window.open(`https://wa.me/6281234567890?text=${pesan}`,"_blank");
}
</script>

</body>
</html>
