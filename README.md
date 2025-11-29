<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1.0"/>
  <title>Landing Page dapurfurniture</title>
  <!-- Tailwind CDN (production only, dev direkomendasikan build custom) -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 min-h-screen">

  <!-- Hero Section -->
  <section class="relative min-h-screen pt-20">
    <div class="absolute inset-0">
      <img src="/kitchen-hero.jpg" alt="Interior Design" class="w-full h-full object-cover" />
      <div class="absolute inset-0 bg-gradient-to-r from-black/85 via-black/70 to-black/50"></div>
    </div>
    <div class="relative max-w-7xl mx-auto px-4 py-8 lg:py-24 min-h-screen flex items-center">
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 lg:gap-12 items-center w-full">
        <div>
          <h1 class="text-4xl lg:text-5xl font-bold text-white leading-tight mb-4 lg:mb-6">
            Desain Interior Terbaik untuk Hunianmu
          </h1>
          <div class="flex items-center gap-4 mb-6 lg:mb-8">
            <div class="text-center">
              <span class="text-5xl font-bold text-yellow-300">1000+</span>
              <p class="text-white/70 text-sm mt-1">hunian impian telah terwujud</p>
            </div>
          </div>
          <div class="block">
            <div class="flex flex-wrap gap-4">
              <span class="px-4 py-2 bg-white/10 backdrop-blur-sm rounded-full text-white/90 text-sm">Desain Interior</span>
              <span class="px-4 py-2 bg-white/10 backdrop-blur-sm rounded-full text-white/90 text-sm">Kitchen Set</span>
              <span class="px-4 py-2 bg-white/10 backdrop-blur-sm rounded-full text-white/90 text-sm">Backdrop TV</span>
              <span class="px-4 py-2 bg-white/10 backdrop-blur-sm rounded-full text-white/90 text-sm">Lemari Pakaian</span>
            </div>
          </div>
        </div>
        <div class="w-full max-w-md mx-auto lg:ml-auto lg:max-w-md bg-white/80 rounded-xl p-6 shadow-xl">
          <div class="flex items-center gap-3 mb-6">
            <div class="w-10 h-10 rounded-full bg-green-200 flex items-center justify-center">
              <span class="text-green-700 font-bold text-xl">✓</span>
            </div>
            <h2 class="text-xl font-bold text-gray-800">
              Konsultasi Gratis
            </h2>
          </div>
          <form id="hero-form" class="space-y-4">
            <div>
              <label for="name" class="text-gray-700">Nama</label>
              <input id="hero-name" type="text" name="name" placeholder="Masukkan nama Anda" required class="mt-1.5 w-full px-3 py-2 rounded border border-gray-300" />
            </div>
            <div>
              <label for="phone" class="text-gray-700">No. Telepon (WhatsApp)</label>
              <div class="flex gap-2 mt-1.5">
                <div class="flex items-center px-3 bg-gray-200 rounded-md border border-gray-300">
                  <span class="text-sm text-gray-500">+62</span>
                </div>
                <input id="hero-phone" type="tel" name="phone" placeholder="8123456789" required class="flex-1 px-3 py-2 rounded border border-gray-300" />
              </div>
            </div>
            <div>
              <label for="email" class="text-gray-700">Email (Optional)</label>
              <input id="hero-email" type="email" name="email" placeholder="email@example.com" class="mt-1.5 w-full px-3 py-2 rounded border border-gray-300" />
            </div>
            <button type="submit" class="w-full bg-green-600 hover:bg-green-700 text-white text-lg py-3 rounded font-semibold transition">Tanya Harga</button>
          </form>
          <div id="hero-form-success" class="hidden mt-3 text-green-700 font-semibold text-center">Terkirim! Kami akan menghubungi Anda.</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ServiceGrid -->
  <section class="py-16 bg-white">
    <div class="max-w-7xl mx-auto px-4">
      <div class="text-center mb-12">
        <h2 class="text-2xl font-bold text-gray-900 mb-2">Desain Interior Sesuai Kebutuhanmu</h2>
        <p class="text-sm text-gray-500 max-w-2xl mx-auto">Ragam Desain Interior untuk Setiap Kebutuhan Gaya Hidup</p>
      </div>
      <div class="grid grid-cols-2 lg:grid-cols-5 gap-4">
        <div class="bg-white rounded-lg shadow p-3 text-center">
          <img src="/service-kitchen.jpg" class="rounded mb-2 mx-auto h-28 object-cover" alt="">
          <div class="font-bold">Kitchen Set</div>
          <div class="text-gray-500 text-xs">Desain dapur modern dengan kualitas premium.</div>
        </div>
        <div class="bg-white rounded-lg shadow p-3 text-center">
          <img src="/service-interior-showroom-clean.png" class="rounded mb-2 mx-auto h-28 object-cover" alt="">
          <div class="font-bold">Desain Interior</div>
          <div class="text-gray-500 text-xs">Desain interior custom untuk setiap ruangan sesuai gaya dan kebutuhan Anda.</div>
        </div>
        <div class="bg-white rounded-lg shadow p-3 text-center">
          <img src="/service-wardrobe.jpg" class="rounded mb-2 mx-auto h-28 object-cover" alt="">
          <div class="font-bold">Lemari Pakaian</div>
          <div class="text-gray-500 text-xs">Lemari custom sesuai kebutuhan ruang Anda.</div>
        </div>
        <div class="bg-white rounded-lg shadow p-3 text-center">
          <img src="/service-bedroom.jpg" class="rounded mb-2 mx-auto h-28 object-cover" alt="">
          <div class="font-bold">Backdrop TV</div>
          <div class="text-gray-500 text-xs">Backdrop TV modern untuk ruang keluarga yang elegan.</div>
        </div>
        <div class="bg-white rounded-lg shadow p-3 text-center">
          <img src="/service-office.png" class="rounded mb-2 mx-auto h-28 object-cover" alt="">
          <div class="font-bold">Ruang Kerja</div>
          <div class="text-gray-500 text-xs">Desain ruang kerja produktif dan nyaman untuk kantor modern.</div>
        </div>
      </div>
    </div>
  </section>

  <!-- WhyChooseUs -->
  <section class="py-16 bg-gray-100">
    <div class="max-w-7xl mx-auto px-4">
      <h2 class="text-2xl font-bold text-gray-900 text-center mb-12">Mengapa memilih dapurfurniture?</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="flex flex-col items-center p-6 rounded-xl bg-white shadow text-center">
          <span class="bg-green-100 text-green-600 rounded-full p-4 mb-3 text-2xl">🎨</span>
          <div class="font-bold text-lg mb-2">Desain Custom</div>
          <div class="text-gray-500 text-sm">Desain interior sesuai keinginan dan kebutuhan ruangan Anda</div>
        </div>
        <div class="flex flex-col items-center p-6 rounded-xl bg-white shadow text-center">
          <span class="bg-yellow-100 text-yellow-600 rounded-full p-4 mb-3 text-2xl">💸</span>
          <div class="font-bold text-lg mb-2">Harga Terjangkau</div>
          <div class="text-gray-500 text-sm">Harga kompetitif dengan kualitas terbaik untuk budget Anda</div>
        </div>
        <div class="flex flex-col items-center p-6 rounded-xl bg-white shadow text-center">
          <span class="bg-blue-100 text-blue-600 rounded-full p-4 mb-3 text-2xl">👥</span>
          <div class="font-bold text-lg mb-2">Dikerjakan oleh Tim Profesional</div>
          <div class="text-gray-500 text-sm">Tim ahli berpengalaman yang siap mewujudkan interior impian Anda</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ProcessSteps -->
  <section class="py-16 bg-gray-900">
    <div class="max-w-7xl mx-auto px-4">
      <h2 class="text-2xl font-bold text-white text-center mb-12">6 Langkah Menuju Interior Impianmu</h2>
      <div class="flex flex-col md:flex-row md:justify-between md:items-center gap-6">
        <div class="flex-1">
          <ol class="relative border-l border-gray-700">
            <li class="mb-10 ml-6">
              <span class="absolute -left-3 flex items-center justify-center w-6 h-6 bg-green-500 rounded-full ring-8 ring-gray-900">📞</span>
              <h3 class="font-semibold text-white">Hubungi Kami <span class="bg-green-700 text-white rounded px-2 text-xs ml-2">Gratis</span></h3>
              <p class="text-sm text-gray-300">Hubungi kami melalui telepon, WhatsApp, atau isi formulir konsultasi untuk memulai perjalanan desain Anda.</p>
            </li>
            <li class="mb-10 ml-6">
              <span class="absolute -left-3 flex items-center justify-center w-6 h-6 bg-green-500 rounded-full ring-8 ring-gray-900">📍</span>
              <h3 class="font-semibold text-white">Survei &amp; Konsultasi <span class="bg-green-700 text-white rounded px-2 text-xs ml-2">Gratis</span></h3>
              <p class="text-sm text-gray-300">Tim kami akan melakukan survei lokasi dan berkonsultasi untuk memahami kebutuhan serta budget Anda.</p>
            </li>
            <li class="mb-10 ml-6">
              <span class="absolute -left-3 flex items-center justify-center w-6 h-6 bg-green-500 rounded-full ring-8 ring-gray-900">🎨</span>
              <h3 class="font-semibold text-white">Desain Custom</h3>
              <p class="text-sm text-gray-300">Kami membuat desain custom yang sesuai dengan visi Anda dan memberikan multiple pilihan.</p>
            </li>
            <li class="mb-10 ml-6">
              <span class="absolute -left-3 flex items-center justify-center w-6 h-6 bg-yellow-500 rounded-full ring-8 ring-gray-900">✅</span>
              <h3 class="font-semibold text-white">Approval &amp; Penawaran</h3>
              <p class="text-sm text-gray-300">Setujui desain dan terima penawaran harga dengan detail lengkap untuk furniture dan instalasi.</p>
            </li>
            <li class="mb-10 ml-6">
              <span class="absolute -left-3 flex items-center justify-center w-6 h-6 bg-blue-500 rounded-full ring-8 ring-gray-900">🚚</span>
              <h3 class="font-semibold text-white">Produksi &amp; Pengiriman</h3>
              <p class="text-sm text-gray-300">Furniture diproduksi dengan quality control ketat dan dikirim ke lokasi Anda dengan aman.</p>
            </li>
            <li class="mb-10 ml-6">
              <span class="absolute -left-3 flex items-center justify-center w-6 h-6 bg-gray-500 rounded-full ring-8 ring-gray-900">🔧</span>
              <h3 class="font-semibold text-white">Instalasi &amp; Finishing</h3>
              <p class="text-sm text-gray-300">Tim profesional kami melakukan instalasi dan memastikan semuanya sempurna sesuai desain.</p>
            </li>
          </ol>
        </div>
      </div>
    </div>
  </section>

  <!-- TestimonialSection -->
  <section class="py-16 bg-gray-100">
    <div class="max-w-7xl mx-auto px-4">
      <div class="text-center mb-12">
        <h2 class="text-2xl font-bold text-gray-900 mb-2">Apa Kata Pelanggan Kami</h2>
        <p class="text-sm text-gray-500">Ribuan pelanggan telah mempercayakan kebutuhan furniture dan desain mereka kepada Dapur Furniture</p>
      </div>
      <div class="flex gap-6 overflow-x-auto pb-4">
        <!-- Satu kotak testimoni per pelanggan (copy-paste sesuai data di JS) -->
        <div class="bg-white rounded-xl shadow p-5 min-w-[320px]">
          <div class="flex items-center gap-3 mb-2">
            <div class="w-12 h-12 rounded-full bg-green-200 flex items-center justify-center font-semibold text-lg text-green-800">MH</div>
            <div>
              <div class="font-semibold text-gray-900">Mira Hartono</div>
              <div class="text-gray-500 text-sm">Bogor</div>
              <div class="flex text-yellow-400 text-xs">★★★★★</div>
            </div>
          </div>
          <div class="text-gray-700 italic mb-2">"Desain interior custom dari Dapur Furniture benar-benar melebihi ekspektasi saya. Tim sangat profesional dan hasil akhirnya sempurna! Proses dari awal sampai akhir sangat terorganisir dan transparan."</div>
          <div class="text-xs text-gray-400">Layanan: <span class="font-medium text-gray-800">Desain Interior</span></div>
        </div>
        <!-- Tambahkan testimoni lain sesuai kebutuhan -->
      </div>
    </div>
  </section>

  <!-- CoverageArea -->
  <section class="py-16 bg-white" id="coverage-area">
    <div class="max-w-7xl mx-auto px-4">
      <div class="text-center mb-12">
        <h2 class="text-2xl font-bold text-gray-900 mb-3">Area Jangkauan</h2>
        <p class="text-gray-500">Layanan dapurfurniture tersedia di wilayah Bogor dan sekitarnya</p>
      </div>
      <div class="max-w-3xl mx-auto">
        <div class="p-6 rounded-xl bg-gray-100 border border-gray-200">
          <div class="flex items-center gap-2 mb-6">
            <span class="inline-block text-xl text-green-500">📍</span>
            <h3 class="font-semibold text-gray-900 text-xl">Bogor & Sekitarnya</h3>
          </div>
          <div class="flex flex-wrap gap-2">
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Bogor Kota</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Bogor Barat</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Bogor Timur</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Bogor Selatan</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Bogor Tengah</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Bogor Utara</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Tanah Sareal</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Cibinong</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Citeureup</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Gunung Putri</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Jonggol</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Parung</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Ciawi</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Cigombong</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Cisarua</span>
            <span class="px-3 py-1 bg-green-100 text-green-700 rounded-full text-xs">Megamendung</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA Banner -->
  <section class="py-16 bg-green-700">
    <div class="max-w-7xl mx-auto px-4">
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 items-center">
        <div>
          <h2 class="text-2xl lg:text-4xl font-bold text-green-100 mb-4">Wujudkan Furniture Impianmu Bersama dapurfurniture</h2>
          <p class="text-base text-green-200 mb-6 max-w-md">Dapatkan konsultasi gratis dari tim profesional kami dan desain custom sesuai keinginanmu dengan harga terjangkau.</p>
          <div class="flex flex-col sm:flex-row flex-wrap gap-4">
            <div class="flex items-center gap-2 text-green-100">
              <span class="text-lg">✅</span>
              <span class="text-sm">Konsultasi Gratis</span>
            </div>
            <div class="flex items-center gap-2 text-green-100">
              <span class="text-lg">✅</span>
              <span class="text-sm">36x Cicilan</span>
            </div>
            <div class="flex items-center gap-2 text-green-100">
              <span class="text-lg">✅</span>
              <span class="text-sm">Garansi 2 Tahun</span>
            </div>
          </div>
        </div>
        <div class="bg-white/20 backdrop-blur-sm rounded-2xl p-6">
          <form id="cta-form" class="space-y-4">
            <div>
              <label for="cta-name" class="text-green-950">Nama</label>
              <input id="cta-name" type="text" placeholder="Masukkan nama Anda" required class="mt-1.5 w-full px-3 py-2 rounded border border-gray-300" />
            </div>
            <div>
              <label for="cta-phone" class="text-green-950">No. Telepon</label>
              <div class="flex gap-2 mt-1.5">
                <div class="flex items-center px-3 bg-white rounded-md">
                  <span class="text-sm text-gray-500">+62</span>
                </div>
                <input id="cta-phone" type="tel" placeholder="8123456789" required class="flex-1 px-3 py-2 rounded border border-gray-300" />
              </div>
            </div>
            <button type="submit" class="w-full bg-green-800 hover:bg-green-900 text-white text-lg py-3 rounded font-semibold transition">Hubungi Saya</button>
          </form>
          <div id="cta-form-success" class="hidden mt-3 text-green-800 font-semibold text-center">Terkirim! Kami akan menghubungi Anda.</div>
        </div>
      </div>
    </div>
  </section>

  <!-- Script Hero Form WhatsApp -->
  <script>
    document.getElementById('hero-form').onsubmit = function(e) {
      e.preventDefault();
      var name = document.getElementById('hero-name').value;
      var phone = document.getElementById('hero-phone').value;
      var email = document.getElementById('hero-email').value;
      var message = 'Halo Dapur Furniture, nama saya ' + name +
        '. No telepon: ' + phone +
        (email ? ', Email: ' + email : '') +
        '. Saya ingin tanya harga.';
      var whatsappUrl = 'https://wa.me/6208195144441?text=' + encodeURIComponent(message);
      window.open(whatsappUrl, '_blank');
      // Alert Success
      document.getElementById('hero-form-success').classList.remove('hidden');
      setTimeout(function() {
        document.getElementById('hero-form-success').classList.add('hidden');
      }, 3000);
    };
    // CTA form dummy success (no real WA integration)
    document.getElementById('cta-form').onsubmit = function(e) {
      e.preventDefault();
      document.getElementById('cta-form-success').classList.remove('hidden');
      setTimeout(function() {
        document.getElementById('cta-form-success').classList.add('hidden');
      }, 3000);
    };
  </script>
</body>
</html>
