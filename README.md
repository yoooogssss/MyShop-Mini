
<!-- PROJECT LOGO -->

<br  />

<p  align="center">

<a  href="https://github.com/WarMac4964/ShopUI-Concept">

</a>

<h3  align="center">MyShop-Mini</h3>
<h3 align="center">UI sederhana dan modern untuk aplikasi e-commerce berbasis Flutter.
Proyek ini menampilkan layout halaman beranda dengan banner promo, kategori produk, list produk, dan section “Special for You”</h3>


<p float="left">
<img  width="200" src="readme/screenshot.png"/>
<img  width="200" src="readme/screenshot2.png"/>

  </p>

<p  align="center">



📱 Fitur Utama

      Tampilan Home Page modern dan responsif
      
      Banner promo dengan gambar & tombol aksi
      
      Kategori produk (All, Recommended, Popular, dll)
      
      Grid produk lengkap dengan gambar, nama, harga, dan tombol add-to-cart (+)
      
      Section "Special for You" dengan list horizontal
      
      Mendukung berbagai ukuran layar menggunakan SafeArea, GridView, dan ScrollView

📂 Struktur UI & Widget yang Digunakan

🏗️ Struktur Dasar

      Scaffold — kerangka utama satu halaman
      
      SafeArea — mencegah konten tertutup notch / status bar
      
      SingleChildScrollView — membuat halaman dapat discroll

🔶 Header / AppBar

      Widget yang digunakan:
      
      Row — menyusun ikon menu, jam, dan tombol search
      
      IconButton / Icon — ikon Search, Menu Grid, Keranjang
      
      SizedBox — jarak antar elemen

🔶 Banner Promo / Produk Utama

      Widget yang digunakan:
      
      Container — background hitam, rounded corner
      
      ClipRRect — membuat gambar memiliki radius
      
      Image.asset / Image.network — menampilkan gambar
      
      Column — menyusun label New Product, judul, dan tombol
      
      ElevatedButton / TextButton — tombol Buy Now!

🔶 Section “Our Products”

      Widget:
      
      Padding — jarak kiri kanan
      
      Text — judul dan label kategori
      
      Row — menampilkan kategori secara horizontal
      
      GestureDetector / InkWell — kategori dapat ditekan (onTap)
      
      Container + BoxDecoration — kategori aktif (gradient)

🔶 Grid Produk

      Widget:
      
      GridView.builder — menampilkan list produk
      
      childAspectRatio — menjaga proporsi card
      
      Card / Container — membungkus item produk
      
      Column — gambar, nama, harga
      
      Stack + Positioned — tombol “+” di pojok kanan bawah

🔶 Section “Special for You”

      Widget:
      
      Container — kartu background hitam lengkung
      
      Row — judul + tombol “See All”
      
      ListView horizontal — item spesial dalam bentuk list
      
      Row + Expanded — gambar + nama produk + harga + tombol “+”

🎨 Styling

      BoxDecoration — warna, gradient, border radius, shadow
      
      LinearGradient — warna tombol & kategori
      
      BoxShadow — bayangan lembut
      
      CircleAvatar / Container (circle) — tombol add (+)
