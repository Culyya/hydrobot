<template>
  <div
    class="text-gray-800 relative h-screen overflow-auto [-ms-overflow-style:none] [scrollbar-width:none] font-poppins">

    <!-- Navbar -->
    <header class="absolute top-0 left-0 w-full flex justify-between items-center px-6 sm:px-12 lg:px-20 py-6 z-50">
      <img src="https://iteba.ac.id/wp-content/uploads/2022/12/logo-iteba.png" class="h-10"/>
      <div class="flex  text-3xl font-bold text-gray-800">
        <span className="">Hydrobot</span>
      </div>
    </header>

    <!-- HERO SECTION -->
    <section class="relative min-h-screen flex items-center overflow-hidden bg-white">
      <!-- BACKGROUND IMAGE -->
      <div class="absolute inset-0 z-0 left-92 top-20 w-full">
        <img src="/hydrobot.png" alt="Hydrobot Background" class="object-cover object-top" />
        <!-- Overlay -->
        <div class="absolute inset-0 bg-gradient-to-r from-white via-white/10 to-white/60"></div>
      </div>

      <!-- CONTENT -->
      <div class="relative z-10 w-full  px-6 sm:px-12 lg:px-20 py-28">
        <div class="space-y-6 md:space-y-8">
          <span class="inline-block text-sm font-semibold text-blue-600 bg-blue-100 px-3 py-1 rounded-full">
            Teknologi Lingkungan
          </span>

          <h1 class="text-[36px] pt-2 md:text-5xl font-extrabold leading-tight text-gray-900">
            Robot Pemantau Kualitas Air
            <br class="hidden sm:block" />
            & Pembersih Sampah Permukaan
            <br class="hidden sm:block" />
            Berbasis
            <span class="text-blue-600 pl-2">Remote Control</span>
          </h1>

          <p class="text-gray-600 pt-4 pb-4  text-sm sm:text-lg leading-relaxed max-w-2xl">
            <strong>Hydrobot</strong> adalah robot cerdas yang dirancang untuk
            memantau kualitas air melalui pengukuran pH dan suhu, sekaligus
            membersihkan sampah di permukaan air secara efisien menggunakan sistem
            kendali jarak jauh.
          </p>

          <div class="flex items-center justify-start">
            <router-link to="/" class="bg-gradient-to-r from-blue-600 to-blue-700
                 text-white px-8 py-3 rounded-full font-semibold
                 shadow-md hover:shadow-lg inline-flex items-center gap-2
                 transition duration-300 hover:scale-105">
              <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24"
                class="w-5 h-5 sm:w-6 sm:h-6">
                <path
                  d="M3.478 2.404a.75.75 0 0 0-.926.941l2.432 7.905H13.5a.75.75 0 0 1 0 1.5H4.984l-2.432 7.905a.75.75 0 0 0 .926.94 60.519 60.519 0 0 0 18.445-8.986.75.75 0 0 0 0-1.218A60.517 60.517 0 0 0 3.478 2.404Z" />
              </svg>
              Mulai Eksplorasi Hydrobot
            </router-link>
          </div>
        </div>
      </div>
    </section>

    <section class="relative py-28 bg-white overflow-hidden px-6 flex flex-col items-center justify-center">

      <div class="relative max-w-6xl mx-auto text-center flex flex-col items-center justify-center ">
        <span class="inline-block mb-4 text-sm font-semibold text-blue-600 bg-blue-100 px-4 py-1 rounded-full">
          Visi Produk
        </span>

        <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold text-gray-900 pt-4 pb-6">
          Solusi Teknologi untuk <br class="hidden sm:block" />
          Lingkungan Perairan Berkelanjutan
        </h2>

        <p class="max-w-3xl mx-auto text-gray-600 text-lg leading-relaxed">
          Hydrobot dikembangkan sebagai solusi robotik modern untuk membantu
          pemantauan kualitas air dan pembersihan sampah permukaan secara
          efisien, ramah lingkungan, dan mudah dioperasikan pada berbagai
          jenis perairan.
        </p>

        <div class="pt-16 grid grid-cols-1 sm:grid-cols-3 gap-8">
          <div class="bg-white border rounded-2xl p-8 shadow-sm hover:shadow-md transition">
            <h3 class="font-semibold text-lg text-gray-900 mb-2">
              Pemantauan Berkelanjutan
            </h3>
            <p class="text-gray-600 text-sm">
              Mengukur pH dan suhu air secara real-time untuk mendukung
              pengambilan keputusan berbasis data.
            </p>
          </div>

          <div class="bg-white border rounded-2xl p-8 shadow-sm hover:shadow-md transition">
            <h3 class="font-semibold text-lg text-gray-900 mb-2">
              Pembersihan Efisien
            </h3>
            <p class="text-gray-600 text-sm">
              Membersihkan sampah permukaan air secara efektif tanpa
              mengganggu ekosistem alami.
            </p>
          </div>

          <div class="bg-white border rounded-2xl p-8 shadow-sm hover:shadow-md transition">
            <h3 class="font-semibold text-lg text-gray-900 mb-2">
              Operasi Aman
            </h3>
            <p class="text-gray-600 text-sm">
              Sistem kendali jarak jauh memungkinkan penggunaan
              yang aman dan fleksibel.
            </p>
          </div>
        </div>
      </div>
    </section>


    <!-- CARA KERJA -->
    <section
      class="relative py-32 bg-gradient-to-b from-white via-blue-50 to-white overflow-hidden px-6 flex flex-col items-center ">

      <!-- BACKGROUND GRID -->
      <div class="absolute inset-0 pointer-events-none opacity-30
           bg-[linear-gradient(to_right,rgba(59,130,246,0.15)_1px,transparent_1px),
               linear-gradient(to_bottom,rgba(59,130,246,0.15)_1px,transparent_1px)]
           bg-[size:40px_40px]">
      </div>

      <div class="relative max-w-7xl mx-auto flex flex-col items-center">

        <!-- HEADER -->
        <div class="text-center pb-28">
          <span class="inline-block mb-4 text-sm font-semibold tracking-wide
               text-blue-600 bg-blue-100 px-4 py-1 rounded-full">
            System Workflow
          </span>

          <h2 class="text-4xl md:text-5xl pt-4 font-bold text-gray-900">
            Cara Kerja <span class="text-blue-600">Hydrobot</span>
          </h2>

          <p class="pt-6 text-gray-600 max-w-3xl mx-auto text-lg">
            Hydrobot bekerja melalui alur sistem robotik cerdas yang mengintegrasikan
            sensor, mekanisme pembersihan, dan kendali jarak jauh secara efisien.
          </p>
        </div>

        <!-- FLOW STEPS -->
        <div class="relative max-w-5xl mx-auto">

          <!-- VERTICAL LINE -->
          <div class="absolute left-1/2 -translate-x-1/2 top-0 h-full w-[2px]
               bg-gradient-to-b from-blue-500 via-purple-500 to-blue-500">
          </div>

          <!-- STEP 1 -->
          <div class="relative flex items-center mb-28">
            <div class="w-1/2 pr-16 text-right">
              <h3 class="text-xl font-semibold text-gray-900 mb-2">
                Pemantauan Kualitas Air
              </h3>
              <p class="text-gray-600">
                Sensor pH dan suhu memantau kondisi air secara real-time untuk
                mendeteksi perubahan kualitas dan potensi pencemaran.
              </p>
            </div>

            <div class="z-10 w-14 h-14 rounded-full bg-blue-600 text-white
                 flex items-center justify-center font-bold shadow-lg">
              1
            </div>

            <div class="w-1/2 pl-16"></div>
          </div>

          <!-- STEP 2 -->
          <div class="relative flex items-center mb-28">
            <div class="w-1/2 pr-16"></div>

            <div class="z-10 w-14 h-14 rounded-full bg-purple-600 text-white
                 flex items-center justify-center font-bold shadow-lg">
              2
            </div>

            <div class="w-1/2 pl-16 text-left">
              <h3 class="text-xl font-semibold text-gray-900 mb-2">
                Pembersihan Sampah Permukaan
              </h3>
              <p class="text-gray-600">
                Mekanisme mekanis mengangkat sampah ringan seperti plastik
                dan daun tanpa merusak ekosistem perairan.
              </p>
            </div>
          </div>

          <!-- STEP 3 -->
          <div class="relative flex items-center">
            <div class="w-1/2 pr-16 text-right">
              <h3 class="text-xl font-semibold text-gray-900 mb-2">
                Kendali & Navigasi Jarak Jauh
              </h3>
              <p class="text-gray-600">
                Operator mengendalikan pergerakan Hydrobot menggunakan
                remote control dari jarak aman.
              </p>
            </div>

            <div class="z-10 w-14 h-14 rounded-full bg-blue-600 text-white
                 flex items-center justify-center font-bold shadow-lg">
              3
            </div>

            <div class="w-1/2 pl-16"></div>
          </div>

        </div>
      </div>
    </section>

    <!-- PERANCANGAN SISTEM -->
    <section class="relative py-20 bg-white px-6 overflow-hidden flex flex-col items-center">

      <!-- HEADER -->
      <div class="text-center max-w-4xl mx-auto pb-28">
        <span class="inline-block text-sm font-semibold text-blue-600 bg-blue-100 px-4 py-1 rounded-full mb-4">
          Perancangan Sistem
        </span>
        <h2 class="text-4xl md:text-5xl pt-4 font-bold text-gray-900">
          Desain & Komponen Hydrobot
        </h2>
        <p class="pt-6 text-gray-600 text-lg">
          Perancangan Hydrobot dilakukan dengan mengintegrasikan komponen elektronik,
          aktuator, dan sistem kendali untuk mendukung pemantauan serta pembersihan perairan.
        </p>
      </div>

      <!-- CONTAINER -->
      <div class="relative max-w-6xl mx-auto space-y-32">

        <!-- ITEM 1 : KIRI GAMBAR -->
        <div class="flex flex-col md:flex-row items-center gap-12">
          <div class="md:w-72">
            <img src="https://joy-it.net/files/files/Produkte/SBC-NodeMCU-ESP32/SBC-NodeMCU-ESP32-01.png"
              alt="ESP32 Devkit C" class="rounded-3xl  hover:scale-105 transition duration-300" />
          </div>
          <div class="md:w-1/2">
            <h3 class="text-2xl font-semibold text-gray-900 mb-4">
              ESP32 Devkit C
            </h3>
            <p class="text-gray-600 leading-relaxed">
              ESP32 berfungsi sebagai pusat kendali utama Hydrobot.
              Mikrokontroler ini mengolah data dari sensor,
              mengontrol aktuator, serta mengatur komunikasi sistem
              secara efisien dan real-time.
            </p>
          </div>
        </div>

        <!-- ITEM 2 : KANAN GAMBAR -->
        <div class="flex flex-col md:flex-row-reverse items-center gap-12">
          <div class="md:w-72">
            <img src="https://down-id.img.susercontent.com/file/ccf9ea84ba4f83ed4aad6576292ed0e8_tn.webp"
              alt="Sensor Suhu DS18B20" class="rounded-3xl  hover:scale-105 transition duration-300" />
          </div>
          <div class="md:w-1/2">
            <h3 class="text-2xl font-semibold text-gray-900 mb-4">
              Sensor Suhu DS18B20
            </h3>
            <p class="text-gray-600 leading-relaxed">
              Sensor DS18B20 digunakan untuk mengukur suhu air secara akurat.
              Data suhu ini menjadi indikator penting dalam pemantauan
              kualitas perairan dan kondisi lingkungan.
            </p>
          </div>
        </div>

        <!-- ITEM 3 : KIRI GAMBAR -->
        <div class="flex flex-col md:flex-row items-center gap-12">
          <div class="md:w-72">
            <img
              src="https://ecadio.com/image/cache/catalog/modulsensor/sensor-ph-meter/modul-sensor-ph-arduino-800x800.jpg"
              alt="Sensor pH PH-4502C" class="rounded-3xl  hover:scale-105 transition duration-300" />
          </div>
          <div class="md:w-1/2">
            <h3 class="text-2xl font-semibold text-gray-900 mb-4">
              Sensor pH PH-4502C
            </h3>
            <p class="text-gray-600 leading-relaxed">
              Modul pH PH-4502C berfungsi untuk mengukur tingkat keasaman air.
              Sensor ini membantu mendeteksi pencemaran air
              serta menjaga kondisi perairan tetap aman.
            </p>
          </div>
        </div>

        <!-- ITEM 4 : KANAN GAMBAR -->
        <div class="flex flex-col md:flex-row-reverse items-center gap-12">
          <div class="md:w-72">
            <img src="https://www.ricmotor.com/wp-content/uploads/775-Brushed-dc-motor.png"
              alt="Motor DC RS-775 & Servo SG90" class="rounded-3xl  hover:scale-105 transition duration-300" />
          </div>
          <div class="md:w-1/2">
            <h3 class="text-2xl font-semibold text-gray-900 mb-4">
              Sistem Penggerak Motor
            </h3>
            <p class="text-gray-600 leading-relaxed">
              Motor DC RS-775 digunakan sebagai penggerak utama Hydrobot,
              sedangkan motor servo SG90 berfungsi untuk mekanisme kontrol
              tambahan seperti pengarah atau pengangkat sampah.
            </p>
          </div>
        </div>

        <!-- ITEM 5 : KIRI GAMBAR -->
        <div class="flex flex-col md:flex-row items-center gap-12">
          <div class="md:w-72">
            <img src="https://down-id.img.susercontent.com/file/id-11134207-7r98y-lmh4arncq1sef2"
              alt="Baterai & Driver Motor" class="rounded-3xl hover:scale-105 transition duration-300" />
          </div>
          <div class="md:w-1/2">
            <h3 class="text-2xl font-semibold text-gray-900 mb-4">
              Catu Daya & Driver Motor
            </h3>
            <p class="text-gray-600 leading-relaxed">
              Baterai 12V 9000mAh sebagai sumber daya utama,
              LM2596 sebagai penurun tegangan,
              serta BTS7960 sebagai driver motor untuk memastikan
              sistem bekerja stabil dan aman.
            </p>
          </div>
        </div>

      </div>
    </section>

    <!-- OUR TEAM -->
    <section class="relative py-24 bg-white overflow-hidden flex flex-col items-center ">
      <!-- DECORATION -->
      <div class="absolute -top-24 -right-24 opacity-20 pointer-events-none">
        <svg width="420" height="420" viewBox="0 0 420 420" fill="none">
          <circle cx="210" cy="210" r="200" stroke="#000" stroke-opacity="0.15" />
          <circle cx="210" cy="210" r="160" stroke="#000" stroke-opacity="0.12" />
          <circle cx="210" cy="210" r="120" stroke="#000" stroke-opacity="0.1" />
          <circle cx="210" cy="210" r="80" stroke="#000" stroke-opacity="0.08" />
        </svg>
      </div>

      <div class="max-w-7xl mx-auto px-6 lg:px-20">
        <!-- HEADER -->
        <div class="max-w-5xl pb-16">
          <h2 class="text-2xl md:text-4xl font-bold leading-tight text-gray-900">
            Kenali tim kami — sekelompok mahasiswa yang berkolaborasi
            mengembangkan solusi teknologi lingkungan
          </h2>

          <p class="pt-6 text-gray-600 text-lg">
            Hydrobot dikembangkan oleh tim multidisiplin yang berfokus pada
            teknologi robotika, pemantauan kualitas air, dan solusi lingkungan
            berkelanjutan.
          </p>
        </div>

        <!-- TEAM GRID -->
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-12">
          <div v-for="member in team" :key="member.name" class="group text-left">
            <!-- IMAGE -->
            <div class="relative overflow-hidden rounded-2xl bg-gray-100 aspect-[3/4]">
              <img :src="member.image" :alt="member.name"
                class="w-full h-full object-cover object-center transition duration-500 group-hover:scale-105" />

              <!-- subtle overlay pattern -->
              <div
                class="absolute inset-0 bg-[radial-gradient(circle_at_center,rgba(0,0,0,0.08)_1px,transparent_1px)] bg-[length:18px_18px] opacity-0 group-hover:opacity-100 transition">
              </div>
            </div>

            <!-- INFO -->
            <div class="mt-4">
              <h3 class="text-lg font-semibold text-gray-900">
                {{ member.name }}
              </h3>
              <p class="text-sm text-gray-500 italic">
                {{ member.role }}
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>


    <!-- FAQ -->
    <section class="py-20 bg-white px-4 flex flex-col items-center justify-center">
      <div class="w-3xl mx-auto">
        <h2 class="text-3xl font-bold text-center pb-10">
          Pertanyaan yang Sering Diajukan
        </h2>

        <details class="p-4 border rounded-xl pb-4">
          <summary class="font-semibold cursor-pointer">
            Apa saja parameter yang diukur Hydrobot?
          </summary>
          <p class="mt-2 text-gray-600 text-sm">
            Hydrobot mengukur pH dan suhu air secara real-time.
          </p>
        </details>

        <details class="p-4 border rounded-xl b-4">
          <summary class="font-semibold cursor-pointer">
            Apakah Hydrobot ramah lingkungan?
          </summary>
          <p class="mt-2 text-gray-600 text-sm">
            Ya, Hydrobot tidak menggunakan bahan kimia dan hanya membersihkan
            sampah di permukaan air.
          </p>
        </details>

        <details class="p-4 border rounded-xl">
          <summary class="font-semibold cursor-pointer">
            Di mana Hydrobot dapat digunakan?
          </summary>
          <p class="mt-2 text-gray-600 text-sm">
            Hydrobot dapat digunakan di sungai, danau, kolam, dan perairan tenang.
          </p>
        </details>
      </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-gray-900 text-gray-300 pt-8 pb-6">
      <div class="px-6 sm:px-16 text-center text-sm">
        <p>
          © 2025 Hydrobot — Robot Cerdas Pemantau Kualitas Air & Pembersih Sampah
        </p>
      </div>
    </footer>
  </div>
</template>

<script setup>
const team = [
  { name: "Muhammad Miqdad", role: "Project Leader", image: "/miqdad.jpeg" },
  { name: "Fernandi Lucky Putra", role: "Hardware Engineer", image: "/fernadi.jpeg" },
  { name: "I Gusti Bagus Agung Dharmaya", role: "Hardware Engineer", image: "/agung.jpeg" },
  { name: "Alim Pranoto ", role: "Embedded System Engineer", image: "/rizky.jpg" },
  { name: "Fajar Nugroho", role: "Mechanical Designer", image: "/fajar.jpg" },
  { name: "Kukuh enggal pratama", role: "Programmer", image: "https://media.licdn.com/dms/image/v2/D5635AQFBxx9eW-bbWg/profile-framedphoto-shrink_800_800/B56ZtFR5xGHYAg-/0/1766393879910?e=1767337200&v=beta&t=TqzT0sWRF07cXV0IG8pwmnAIw9_UJXNf5xbhDkZLMLQ" },
  { name: "Surya Tirta Chandra", role: "Programmer", image: "/surya.JPG" },
  { name: "Fakhri Aprianza", role: "Programmer", image: "/fakhri.jpeg" },
  { name: "Conita Khairunisa Gunawan", role: "Documentation", image: "/ahmad.jpg" },
  { name: "Alfindra", role: "Embedded System Engineer", image: "/dinda.jpg" },
  { name: "ghanang harisya ubra ", role: "Mechanical Designer", image: "/ilham.jpg" },
  { name: "Samuel Enrico sitompul", role: "Mechanical Designer", image: "/ilham.jpg" },
  { name: "Natasya nur hadi", role: "Documentation", image: "https://media.licdn.com/dms/image/v2/D4E03AQF1T1jQJFScoA/profile-displayphoto-crop_800_800/B4EZmVYw5_KkAM-/0/1759147924999?e=1768435200&v=beta&t=tjqZcrw0Ew-5EwLYg4OTAiZcMgpO_kCIkkQ518CTi8Y" },
];
</script>
