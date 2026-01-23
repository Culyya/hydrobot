<template>
  <div
    class="text-gray-800 relative h-screen overflow-auto [-ms-overflow-style:none] [scrollbar-width:none] font-poppins">

    <!-- Navbar -->
    <header class="absolute top-0 left-0 w-full flex justify-between items-center px-6 sm:px-12 lg:px-20 py-6 z-50">
      <img src="https://iteba.ac.id/wp-content/uploads/2022/12/logo-iteba.png" class="h-8 md:h-10" />
      <div class="flex text-lg  md:text-3xl font-bold text-gray-800">
        <span className="">Hydrobot</span>
      </div>
    </header>

    <!-- HERO SECTION -->
    <section class="relative flex items-center overflow-hidden bg-white py-10 md:py-32">
      <!-- BACKGROUND IMAGE -->
      <div class="absolute inset-0 z-0 md:left-96 2xl:left-[40rem] left-32 top-20 md:top-20  w-full">
        <img src="/hydrobot.png" alt="Hydrobot Background" class="object-cover object-top h-full" />
        <!-- Overlay -->
        <div class="absolute inset-0 bg-gradient-to-r from-white via-white/10 to-white/60"></div>
      </div>

      <!-- CONTENT -->
      <div class="relative z-10 w-full  px-6 sm:px-12 lg:px-20 py-28">
        <div class="space-y-6 md:space-y-8">
          <span class="inline-block text-sm font-semibold text-blue-600 bg-blue-100 px-3 py-1 rounded-full">
            Teknologi Lingkungan
          </span>

          <h1 class="text-[30px] pt-2 md:text-5xl font-extrabold leading-tight text-gray-900">
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

        </div>
      </div>
    </section>


    <section class="relative flex w-full flex-col items-center justify-center
               overflow-hidden  pb-20 py-10 md:py-24">

      <div class="max-w-7xl mx-auto px-6">
        <div class="flex flex-col md:flex-row items-center gap-10 md:gap-14
             rounded-3xl p-6 md:p-10">
          <!-- TEXT / SCRIPT -->
          <div class="md:w-1/2 text-center md:text-left">
            <span class="inline-block mb-3 px-4 py-1 text-xs font-semibold tracking-wide
                 text-gray-700 bg-white border border-gray-200 rounded-full">
              VIDEO DOKUMENTASI
            </span>

            <h2 class="text-2xl md:text-3xl font-bold text-gray-900 leading-tight">
              Dokumentasi Pengembangan & Pengujian Hydrobot
            </h2>

            <p class="mt-5 hidden sm:block text-sm md:text-base text-gray-600 leading-relaxed">
              Video ini menampilkan proses perancangan, perakitan, hingga pengujian
              <span class="font-medium text-gray-800">Hydrobot</span> sebagai solusi
              pemantauan kualitas air berbasis robotika. Setiap tahap dikembangkan
              secara kolaboratif oleh tim mahasiswa dengan pendampingan dosen
              pengampu, mengintegrasikan teknologi sensor, embedded system,
              serta analisis data lingkungan.
            </p>
          </div>

          <!-- VIDEO -->
          <div class="md:w-1/2 w-full">
            <div class="relative overflow-hidden rounded-2xl bg-black aspect-video shadow-lg">
              <!-- NOTE: YouTube harus iframe -->
              <iframe class="w-full h-full" src="https://www.youtube.com/embed/tTihlJCEe6M"
                title="Video Dokumentasi Hydrobot" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen>
              </iframe>
            </div>
          </div>
        </div>
      </div>
    </section>



    <section class="relative flex w-full flex-col items-center justify-center
               overflow-hidden bg-gradient-to-bt from-slate-100 to-cyan-50
               px-6 pb-20 py-10  md:py-24 ">
      <!-- TITLE -->
      <div class="pb-8 text-center">
        <span
          class="inline-block rounded-full text-blue-600 bg-blue-100 px-4 py-1 text-sm font-semibold tracking-wide ">
          Design
        </span>
        <h1 class="pt-3 text-3xl font-extrabold tracking-tight text-gray-900 sm:text-4xl">
          Hydrobot
        </h1>
      </div>

      <!-- 3D MODEL -->
      <div class="relative w-full max-w-6xl">
        <!-- glow -->
        <div class="absolute inset-0 bg-cyan-200/20 blur-3xl"></div>

        <model-viewer src="/hy2.glb" auto-rotate interaction-prompt="none" disable-zoom disable-pan disable-tap
          camera-controls="false" scale="20 20 20" camera-orbit="0deg 80deg 1.2m" field-of-view="30deg"
          class="relative h-[420px] w-full sm:h-[520px]"></model-viewer>
      </div>
    </section>



    <section class="relative md:py-14 bg-white overflow-hidden px-6 flex flex-col items-center justify-center">

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
      class="relative py-20 md:py-32 bg-gradient-to-b from-white via-blue-50 to-white overflow-hidden px-6 flex flex-col items-center ">

      <!-- BACKGROUND GRID -->
      <div class="absolute inset-0 pointer-events-none opacity-30
           bg-[linear-gradient(to_right,rgba(59,130,246,0.15)_1px,transparent_1px),
               linear-gradient(to_bottom,rgba(59,130,246,0.15)_1px,transparent_1px)]
           bg-[size:40px_40px]">
      </div>

      <div class="relative max-w-7xl mx-auto flex flex-col items-center">

        <!-- HEADER -->
        <div class="text-center pb-10 md:pb-28">
          <span class="inline-block mb-4 text-sm font-semibold tracking-wide
               text-blue-600 bg-blue-100 px-4 py-1 rounded-full">
            System Workflow
          </span>

          <h2 class="text-2xl md:text-5xl pt-4 font-bold text-gray-900">
            Cara Kerja <span class="text-gray-900">Hydrobot</span>
          </h2>

          <p class="pt-6 text-gray-600 max-w-3xl mx-auto text-lg">
            Hydrobot bekerja melalui alur sistem robotik cerdas yang mengintegrasikan
            sensor, mekanisme pembersihan, dan kendali jarak jauh secara efisien.
          </p>
        </div>

        <!-- FLOW STEPS -->

        <!-- MOBILE VERSION -->
        <div class="max-w-md mx-auto px-6 space-y-8 md:hidden">

          <!-- STEP 1 -->
          <div class="flex gap-4  p-4 ">
            <div class="w-10 h-10 rounded-full bg-blue-600 text-white
         flex items-center justify-center font-bold shrink-0">
              1
            </div>

            <div>
              <h3 class="text-base font-semibold text-gray-900 pb-1">
                Pemantauan Kualitas Air
              </h3>
              <p class="text-gray-600 text-sm leading-relaxed">
                Sensor pH dan suhu memantau kondisi air secara real-time untuk
                mendeteksi perubahan kualitas dan potensi pencemaran.
              </p>
            </div>
          </div>

          <!-- STEP 2 -->
          <div class="pb-4 pt-4">
            <div class="flex gap-4  rounded-xl   p-4 ">
              <div class="w-10 h-10 rounded-full bg-purple-600 text-white
         flex items-center justify-center font-bold shrink-0">
                2
              </div>

              <div>
                <h3 class="text-base font-semibold text-gray-900 pb-1">
                  Pembersihan Sampah Permukaan
                </h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                  Mekanisme mekanis mengangkat sampah ringan seperti plastik
                  dan daun tanpa merusak ekosistem perairan.
                </p>
              </div>
            </div>
          </div>

          <!-- STEP 3 -->
          <div class="flex gap-4  p-4">
            <div class="w-10 h-10 rounded-full bg-blue-600 text-white
         flex items-center justify-center font-bold shrink-0">
              3
            </div>

            <div>
              <h3 class="text-base font-semibold text-gray-900 pb-1">
                Kendali & Navigasi Jarak Jauh
              </h3>
              <p class="text-gray-600 text-sm leading-relaxed">
                Operator mengendalikan pergerakan Hydrobot menggunakan
                remote control dari jarak aman.
              </p>
            </div>
          </div>

        </div>


        <!-- DESKTOP VERSION -->
        <div class="relative max-w-5xl mx-auto hidden md:block">

          <!-- VERTICAL LINE -->
          <div class="absolute left-1/2 -translate-x-1/2 top-0 h-full w-[2px]
       bg-gradient-to-b from-blue-500 via-purple-500 to-blue-500"></div>

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
    <section class="relative md:py-20 bg-white px-6 overflow-hidden flex flex-col items-center">

      <!-- HEADER -->
      <div class="text-center max-w-4xl mx-auto pb-28">
        <span class="inline-block text-sm font-semibold text-blue-600 bg-blue-100 px-4 py-1 rounded-full mb-4">
          Perancangan Sistem
        </span>
        <h2 class="text-2xl md:text-5xl pt-4 font-bold text-gray-900">
          Desain & Komponen Hydrobot
        </h2>
        <p class="pt-6 text-gray-600 text-md md:text-lg">
          Perancangan Hydrobot dilakukan dengan mengintegrasikan komponen elektronik,
          aktuator, dan sistem kendali untuk mendukung pemantauan serta pembersihan perairan.
        </p>
      </div>

      <!-- CONTAINER -->
      <div class="relative max-w-6xl mx-auto space-y-32">

        <!-- ITEM 1 : KIRI GAMBAR -->
        <div class="flex flex-col md:flex-row items-center gap-12">
          <div class="w-54 md:w-72">
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
          <div class="w-54 md:w-72">
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
          <div class="w-54 md:w-72">
            <img
              src="data:image/jpeg;base64,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ERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQERED/9k="
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
          <div class="w-54 md:w-72">
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
          <div class="w-54 md:w-72">
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
    <section class="relative py-20 md:py-24 bg-white overflow-hidden flex flex-col items-center ">
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
        <div class="max-w-5xl sm:pb-16">
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

        <!-- DOSEN PENGAMPU -->

        <div class="relative md:pt-16  pb-10 md:pb-24">
          <!-- subtle divider -->
          <div class="absolute inset-x-0 -top-8 h-px bg-gradient-to-r from-transparent via-gray-200 to-transparent">
          </div>

          <div class="max-w-6xl mx-auto px-6">
            <div class="flex flex-col md:flex-row items-center md:items-start gap-8 md:gap-12
             bg-gray-50/70 rounded-3xl p-6 md:p-10">
              <!-- IMAGE -->
              <div class="relative flex-shrink-0">
                <div class="relative overflow-hidden rounded-2xl bg-gray-100 w-44 md:w-64 aspect-[3/4]">
                  <img src="../../public/dp.JPG" alt="Dosen Pengampu"
                    class="w-full h-full object-cover transition duration-500 hover:scale-105" />
                </div>
              </div>

              <!-- CONTENT -->
              <div class="text-center md:text-left">
                <span class="inline-block mb-2 px-4 py-1 text-xs font-semibold tracking-wide
                 text-gray-700 bg-white border border-gray-200 rounded-full">
                  DOSEN PENGAMPU
                </span>

                <h3 class="text-xl md:text-2xl font-bold text-gray-900">
                  Deosa Putra Caniago, S.Kom., M.Kom.
                </h3>

                <p class="pt-4 text-xs md:text-base text-gray-600 leading-relaxed">
                  Dosen Program Studi Teknik Komputer dengan latar belakang Magister
                  Komputer. Memiliki minat dan keahlian pada bidang
                  <span class="font-medium text-gray-800">
                    Artificial Intelligence (AI), Embedded System, Robotics,
                  </span>
                  dan <span class="font-medium text-gray-800">Data Mining</span>.
                  Aktif dalam penelitian dan pengabdian masyarakat, termasuk penerima
                  Hibah PDP Ristekdikti (2022 & 2023) serta Hibah PKM Ristekdikti (2023).
                  Aktif dalam publikasi jurnal terakreditasi SINTA.
                  Mengajar di Program Studi Teknik Komputer serta menjabat sebagai
                  Koordinator Laboratorium Elektronika dan pembina UKM Robotika ITEBA.
                </p>
              </div>
            </div>
          </div>
        </div>



        <!-- TEAM GRID -->
        <div class="grid grid-cols-2 md:grid-cols-4 gap-6 sm:gap-8 md:gap-12">
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
            <div class="mt-3 md:mt-4">
              <h3 class="text-base md:text-lg font-semibold text-gray-900">
                {{ member.name }}
              </h3>
              <p class="text-xs md:text-sm text-gray-500 italic">
                {{ member.role }}
              </p>
            </div>
          </div>
        </div>

      </div>
    </section>


    <!-- FAQ -->
    <section class="py-20 pb-32 bg-white px-4 flex flex-col items-center justify-center">
      <div class="max-w-3xl mx-auto px-4 sm:px-6 lg:px-0">
        <h2 class="text-2xl sm:text-3xl font-bold text-center pb-8 sm:pb-10">
          Pertanyaan yang Sering Diajukan
        </h2>

        <div class="space-y-4">
          <details class="p-4 sm:p-5 border rounded-xl">
            <summary class="font-semibold cursor-pointer text-sm sm:text-base">
              Apa saja parameter yang diukur Hydrobot?
            </summary>
            <p class="mt-2 text-gray-600 text-sm leading-relaxed">
              Hydrobot mengukur pH dan suhu air secara real-time.
            </p>
          </details>

          <details class="p-4 sm:p-5 border rounded-xl">
            <summary class="font-semibold cursor-pointer text-sm sm:text-base">
              Apakah Hydrobot ramah lingkungan?
            </summary>
            <p class="mt-2 text-gray-600 text-sm leading-relaxed">
              Ya, Hydrobot tidak menggunakan bahan kimia dan hanya membersihkan
              sampah di permukaan air.
            </p>
          </details>

          <details class="p-4 sm:p-5 border rounded-xl">
            <summary class="font-semibold cursor-pointer text-sm sm:text-base">
              Di mana Hydrobot dapat digunakan?
            </summary>
            <p class="mt-2 text-gray-600 text-sm leading-relaxed">
              Hydrobot dapat digunakan di sungai, danau, kolam, dan perairan tenang.
            </p>
          </details>
        </div>
      </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-gray-900 text-gray-300 pt-8 pb-6">
      <div class="px-6 sm:px-16 text-center text-sm">
        <p>
          © 2026 Hydrobot — Robot Cerdas Pemantau Kualitas Air & Pembersih Sampah
        </p>
      </div>
    </footer>
  </div>
</template>

<script setup>
const team = [
  { name: "Muhammad Miqdad", role: "Project Leader", image: "/miqdad.png" },
  { name: "Fernandi Lucky Putra", role: "Hardware Engineer", image: "/fernandi.png" },
  { name: "I Gusti Bagus Agung Dharmaya", role: "Hardware Engineer", image: "/agung.png" },
  { name: "Alim Pranoto ", role: "Embedded System Engineer", image: "/alim.png" },
  { name: "Kukuh enggal pratama", role: "Programmer", image: "/kukuh.png" },
  { name: "Surya Tirta Chandra", role: "Programmer", image: "/surya.png" },
  { name: "Fakhri Aprianza", role: "Programmer", image: "/fakhri.png" },
  { name: "Conita Khairunisa Gunawan", role: "Documentation", image: "/conita.png" },
  { name: "Alfindra", role: "Embedded System Engineer", image: "/alfin.png" },
  { name: "ghanang harisya ubra ", role: "Mechanical Designer", image: "/ghanang.png" },
  { name: "Samuel Enrico sitompul", role: "Mechanical Designer", image: "/samuel.png" },
  { name: "Natasya nur hadi", role: "Documentation", image: "/tasya.png" },
];
</script>
