<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Wilson’s Lane</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html {
      scroll-behavior: smooth;
    }
    :root {
      --tw-bg-opacity: 1;
      --primary: rgba(236, 72, 153, var(--tw-bg-opacity));
    }
  </style>
</head>
<body class="bg-pink-50">

  <!-- Navbar -->
  <nav class="bg-white shadow-md fixed w-full z-10">
    <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
      <div class="text-xl font-bold text-pink-600">The Wilson’s Lane</div>
      <div class="hidden md:flex space-x-6">
        <a href="#beranda" class="text-gray-700 hover:text-pink-600">Beranda</a>
        <a href="#tentang" class="text-gray-700 hover:text-pink-600">Tentang</a>
        <a href="#layanan" class="text-gray-700 hover:text-pink-600">Layanan</a>
        <a href="#menu" class="text-gray-700 hover:text-pink-600">Menu</a>
        <a href="#galeri" class="text-gray-700 hover:text-pink-600">Galeri</a>
        <a href="#testimoni" class="text-gray-700 hover:text-pink-600">Testimoni</a>
        <a href="#kontak" class="text-gray-700 hover:text-pink-600">Kontak</a>
      </div>
      <div class="md:hidden">
        <button id="menu-btn" class="text-gray-700 text-2xl">&#9776;</button>
      </div>
    </div>
    <div id="mobile-menu" class="hidden md:hidden bg-white px-4 pb-4">
      <a href="#beranda" class="block py-2">Beranda</a>
      <a href="#tentang" class="block py-2">Tentang</a>
      <a href="#layanan" class="block py-2">Layanan</a>
      <a href="#menu" class="block py-2">Menu</a>
      <a href="#galeri" class="block py-2">Galeri</a>
      <a href="#testimoni" class="block py-2">Testimoni</a>
      <a href="#kontak" class="block py-2">Kontak</a>
    </div>
  </nav>

  <!-- Tentang Kami -->
  <section id="tentang" class="pt-32 pb-16 bg-white">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold text-pink-600 mb-4">Tentang The Wilson’s Lane</h2>
      <p class="text-gray-700">The Wilson’s Lane adalah kafe bergaya taman urban yang terletak di jantung Menteng, Jakarta. Dikenal karena atmosfernya yang sejuk dan nyaman, The Wilson’s Lane menyatukan nuansa santai dengan sajian istimewa yang memanjakan selera. Dari kopi pilihan hingga menu makanan khas, tempat ini menjadi tujuan utama untuk bersantai, bekerja, atau berbagi momen bersama orang terdekat.</p>
    </div>
  </section>

  <!-- Layanan -->
  <section id="layanan" class="py-16 bg-pink-100">
    <div class="max-w-5xl mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold text-pink-600 mb-10">Layanan Kami</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-white p-6 rounded shadow">
          <h3 class="text-xl font-semibold mb-2 text-pink-600">Kopi & Minuman</h3>
          <p class="text-gray-600">Kopi pilihan single origin dan minuman spesial buatan barista.</p>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h3 class="text-xl font-semibold mb-2 text-pink-600">Makanan Sehat</h3>
          <p class="text-gray-600">Menu sehat, vegetarian, vegan dan pilihan sarapan lengkap.</p>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h3 class="text-xl font-semibold mb-2 text-pink-600">Acara & Workshop</h3>
          <p class="text-gray-600">Live music, komunitas, dan event kreatif mingguan.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Menu -->
  <section id="menu" class="py-16 bg-white">
    <div class="max-w-5xl mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold text-pink-600 mb-10">Signature & Menu Utama</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-6">
        <div class="bg-pink-100 p-6 rounded shadow">
          <h3 class="text-xl font-semibold text-pink-700 mb-2">Arsik Salmon (Signature)</h3>
          <p class="text-gray-700">Salmon khas Batak yang dimasak dengan bumbu arsik istimewa, disajikan dengan nasi hangat dan lalapan segar.</p>
        </div>
        <div class="bg-pink-100 p-6 rounded shadow">
          <h3 class="text-xl font-semibold text-pink-700 mb-2">Nasi Goreng Jambal</h3>
          <p class="text-gray-700">Nasi goreng dengan potongan jambal roti gurih, disajikan dengan telur dan acar.</p>
        </div>
        <div class="bg-pink-100 p-6 rounded shadow">
          <h3 class="text-xl font-semibold text-pink-700 mb-2">Egy Rice</h3>
          <p class="text-gray-700">Nasi dengan rempah-rempah khas Timur Tengah, ayam suwir, dan saus yoghurt segar.</p>
        </div>
        <div class="bg-pink-100 p-6 rounded shadow">
          <h3 class="text-xl font-semibold text-pink-700 mb-2">Chicken Butter Milk</h3>
          <p class="text-gray-700">Ayam krispi dengan saus butter milk creamy yang gurih dan menggoda.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Galeri -->
  <section id="galeri" class="py-16 bg-white">
    <div class="max-w-5xl mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold text-pink-600 mb-10">Galeri Foto</h2>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
        <img src="https://source.unsplash.com/300x300/?wilson,cafe" class="rounded shadow">
        <img src="https://source.unsplash.com/300x300/?garden,cafe" class="rounded shadow">
        <img src="https://source.unsplash.com/300x300/?outdoor,seating" class="rounded shadow">
        <img src="https://source.unsplash.com/300x300/?latte,art" class="rounded shadow">
      </div>
    </div>
  </section>

  <!-- Testimoni -->
  <section id="testimoni" class="py-16 bg-pink-100">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold text-pink-600 mb-10">Apa Kata Mereka</h2>
      <div class="space-y-6">
        <blockquote class="text-gray-600 italic">"Tempatnya nyaman banget, kopinya enak, staff-nya ramah. Highly recommended!" - Rina, Jakarta</blockquote>
        <blockquote class="text-gray-600 italic">"Saya suka suasana tamannya. Cocok buat kerja remote atau santai sore." - Budi, Bekasi</blockquote>
      </div>
    </div>
  </section>

  <!-- Kontak -->
  <section id="kontak" class="py-16 bg-white">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold text-pink-600 mb-4">Hubungi Kami</h2>
      <p class="text-gray-600 mb-6">Jl. Tegal No.4, Menteng, Jakarta Pusat<br>Email: info@wilsonslane.com | WA: <a href="https://wa.me/6281234567890" class="text-pink-600 underline">0812-3456-7890</a></p>
      <form class="grid grid-cols-1 md:grid-cols-2 gap-4 text-left">
        <input type="text" placeholder="Nama" class="p-3 rounded border" required>
        <input type="email" placeholder="Email" class="p-3 rounded border" required>
        <textarea placeholder="Pesan Anda" rows="4" class="p-3 rounded border md:col-span-2" required></textarea>
        <button class="bg-pink-600 hover:bg-pink-700 text-white py-2 rounded md:col-span-2">Kirim Pesan</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-pink-100 py-6 text-center text-pink-700">
    &copy; 2025 The Wilson’s Lane. All rights reserved.
  </footer>

  <!-- JS Mobile Menu -->
  <script>
    document.getElementById("menu-btn").addEventListener("click", function () {
      document.getElementById("mobile-menu").classList.toggle("hidden");
    });
  </script>

</body>
</html>
