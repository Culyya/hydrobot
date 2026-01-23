<template>
  <div class="page">

    <!-- NAVBAR -->
    <nav class="navbar">
      <div class="nav-container">
        <div class="logo">Hydrobot</div>
        <ul class="nav-menu">
          <li>Home</li>
        </ul>
      </div>
    </nav>

    <!-- HERO -->
    <section class="hero">
      <div class="hero-text">
        <h1 class="font-black text-gray-800">Hydrobot</h1>
        <p>Robot Pemantau Kualitas Air & Pembersih Sampah Permukaan Berbasis Remote Control</p>
      </div>

      <model-viewer
        src="/hy2.glb"
        auto-rotate
        interaction-prompt="none"
        disable-zoom
        disable-pan
        disable-tap
        camera-controls="false"
        scale="20 20 20"
        camera-orbit="0deg 75deg 1.2m"
        field-of-view="28deg"
        class="model-hero"
      ></model-viewer>
    </section>

    <!-- SECTION DESKRIPSI -->
    <section class="section section-split">
      <div class="text">
        <h2>Tentang Robot Air</h2>
        <p>
          Robot Air adalah sistem otomatisasi modern yang dirancang untuk mendukung
          kebutuhan industri masa depan dengan performa tinggi dan efisiensi maksimal.
        </p>
      </div>

      <div class="viewer">
        <model-viewer src="/hy2.glb" auto-rotate interaction-prompt="none" class="model-card"></model-viewer>
      </div>
    </section>

    <!-- SECTION FITUR -->
    <section class="section features">
      <h2>Fitur Unggulan</h2>

      <div class="feature-grid">
        <div class="feature-card">
          <h3>AI Terintegrasi</h3>
          <p>Mampu menganalisis dan mengambil keputusan secara otomatis.</p>
        </div>

        <div class="feature-card">
          <h3>Desain Aerodinamis</h3>
          <p>Meningkatkan efisiensi dan stabilitas saat beroperasi.</p>
        </div>

        <div class="feature-card">
          <h3>Material Ringan</h3>
          <p>Kuat, ringan, dan tahan terhadap kondisi ekstrem.</p>
        </div>
      </div>
    </section>

    <!-- SECTION PENGUJIAN -->
    <section class="section section-split reverse">
      <div class="text">
        <h2>Pengujian Product</h2>
        <p>
          Robot Air telah melalui serangkaian pengujian ketat untuk menjamin kualitas
          dan keamanan pengguna.
        </p>

        <ul>
          <li>Uji tekanan tinggi</li>
          <li>Uji suhu ekstrem</li>
          <li>Uji ketahanan material</li>
          <li>Uji stabilitas operasional</li>
        </ul>
      </div>

      <div class="viewer">
        <model-viewer src="/hy2.glb" auto-rotate interaction-prompt="none" class="model-card"></model-viewer>
      </div>
    </section>

    <!-- SECTION SPESIFIKASI -->
    <section class="section specs">
      <h2>Spesifikasi Teknis</h2>

      <div class="spec-grid">
        <div><strong>Dimensi:</strong> 120cm x 80cm x 60cm</div>
        <div><strong>Berat:</strong> 18 Kg</div>
        <div><strong>Material:</strong> Carbon Fiber</div>
        <div><strong>Tenaga:</strong> Baterai Lithium 48V</div>
        <div><strong>Durasi Operasi:</strong> 12 Jam</div>
        <div><strong>Kontrol:</strong> Otomatis & Remote</div>
      </div>
    </section>

  </div>
</template>

<script>
export default {
  name: "Product3D"
};
</script>

<style scoped>
/* PAGE */
.page {
  background: #ffffff;
  color: #222;
  font-family: Inter, system-ui, sans-serif;
}

/* NAVBAR */
.navbar {
  position: sticky;
  top: 0;
  background: rgba(255,255,255,0.9);
  backdrop-filter: blur(10px);
  border-bottom: 1px solid #eee;
  z-index: 100;
}

.nav-container {
  max-width: 1200px;
  margin: auto;
  padding: 18px 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-weight: 800;
  font-size: 22px;
}

.nav-menu {
  display: flex;
  gap: 30px;
  list-style: none;
}

.nav-menu li {
  cursor: pointer;
  font-weight: 500;
}

/* HERO */
.hero {
  padding: 100px 8%;
  margin-top: -4rem;
  text-align: center;
}

.hero-text h1 {
  font-size: 56px;
  margin-bottom: 15px;
}

.hero-text p {
  font-size: 22px;
  color: #666;
  margin-bottom: 40px;
}

.model-hero {
  width: 100%;
  height: 520px;
}

/* SECTION BASE */
.section {
  padding: 100px 8%;
}

/* SPLIT */
.section-split {
  display: flex;
  align-items: center;
  gap: 60px;
}

.reverse {
  flex-direction: row-reverse;
}

.text {
  flex: 1;
}

.text h2 {
  font-size: 42px;
  margin-bottom: 20px;
}

.text p {
  font-size: 20px;
  color: #555;
  line-height: 1.8;
}

.text ul {
  margin-top: 20px;
  padding-left: 20px;
}

.text li {
  font-size: 18px;
  margin-bottom: 10px;
}

/* VIEWER */
.viewer {
  flex: 1;
}

.model-card {
  width: 100%;
  height: 420px;
}

/* FEATURES */
.features {
  background: #f8f9fc;
  text-align: center;
}

.features h2 {
  font-size: 42px;
  margin-bottom: 60px;
}

.feature-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 40px;
}

.feature-card {
  padding: 40px;
  border-radius: 20px;
  background: white;
  box-shadow: 0 10px 30px rgba(0,0,0,0.05);
}

.feature-card h3 {
  font-size: 24px;
  margin-bottom: 15px;
}

/* SPECS */
.specs {
  background: #111827;
  color: white;
  text-align: center;
}

.specs h2 {
  font-size: 42px;
  margin-bottom: 50px;
}

.spec-grid {
  max-width: 800px;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 25px;
  font-size: 18px;
}

/* RESPONSIVE */
@media (max-width: 900px) {
  .section-split {
    flex-direction: column;
    text-align: center;
  }

  .feature-grid {
    grid-template-columns: 1fr;
  }

  .spec-grid {
    grid-template-columns: 1fr;
  }

  .hero-text h1 {
    font-size: 40px;
  }

  .model-hero {
    height: 360px;
  }

  .model-card {
    height: 300px;
  }
}
</style>
