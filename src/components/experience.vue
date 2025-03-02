<script>
export default{
    name : "experience"
}
</script>

<template>

<div id="pengalaman" class="container mt-5">
  <h2 class="text-center text-white mb-4" style="font-family: 'Times New Roman', Times, serif;" >Pengalaman</h2>

  <div class="row row-cols-1 row-cols-md-3 g-4">
    <div class="col">
      <div class="card h-100 shadow-sm border-0 bg-dark rounded-4 text-white">
        <div class="card-body">
          <h5 class="card-title">Pekerja di Foto Copy</h5>
          <h6 class="card-subtitle mb-2 text-secondary">Februari 2017 - Agustus 2017</h6>
          <p class="card-text">Membantu dalam pelayanan foto copy dan lain-lain.</p>
        </div>
      </div>
    </div>

    <div class="col">
      <div class="card h-100 shadow-sm border-0 bg-dark rounded-4 text-white">
        <div class="card-body">
          <h5 class="card-title">Pelayan di Toko Big Army</h5>
          <h6 class="card-subtitle mb-2 text-secondary">April 2023 - Agustus 2023</h6>
          <p class="card-text">Bekerja sebagai pelayan dan kasir di Toko Big Army.</p>
        </div>
      </div>
    </div>

    <div class="col">
      <div class="card h-100 shadow-sm border-0 bg-dark rounded-4 text-white">
        <div class="card-body">
          <h5 class="card-title">Freelance Desain Grafis</h5>
          <h6 class="card-subtitle mb-2 text-secondary">Januari 2025 - Sekarang</h6>
          <p class="card-text">Membuat poster, logo, dan konten visual dengan pendekatan desain kreatif.</p>
        </div>
      </div>
    </div>
  </div>
</div>


<div class="container mt-5">
  <h2 class="text-center text-white mb-4" style="font-family: 'Times New Roman', Times, serif;">Keahlian</h2>
  <div class="table-responsive">
    <table class="table table-dark table-hover text-center shadow-lg rounded-4 overflow-hidden">
      <thead class="bg-gradient text-white">
        <tr>
          <th scope="col" class="py-3">Keahlian</th>
          <th scope="col" class="py-3">Deskripsi</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="fw-bold text-info">
            <i class="bi bi-file-code-fill"></i> HTML, CSS, JavaScript
          </td>
          <td>Menguasai dasar-dasar pengembangan web dengan fokus pada tampilan responsif dan interaktif.</td>
        </tr>
        <tr>
          <td class="fw-bold text-primary">
            <i class="bi bi-bootstrap-fill"></i> Vue.js dan Bootstrap
          </td>
          <td>Membangun antarmuka dinamis dan responsif menggunakan framework modern.</td>
        </tr>
        <tr>
          <td class="fw-bold text-warning">
            <i class="bi bi-palette-fill"></i> Desain Poster dan Grafis
          </td>
          <td>Menggunakan kreativitas dalam menciptakan desain visual yang menarik dan efektif.</td>
        </tr>
        <tr>
          <td class="fw-bold text-success">
            <i class="bi bi-code-slash"></i> Pemrograman Web
          </td>
          <td>Mengembangkan aplikasi web interaktif dengan pendekatan yang efisien dan efektif.</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

</template>

<style>

body {
    color: white;
    font-family: 'Poppins', sans-serif;
  }

  .pengalaman-card {
    background: rgba(255, 255, 255, 0.15);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.2);
    border-radius: 16px;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.25);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    padding: 20px;
  }

  .pengalaman-card:hover {
    transform: scale(1.05);
    box-shadow: 0 15px 30px rgba(218, 216, 216, 0.386);
  }

  .card-title {
    font-size: 1.2rem;
    font-weight: 600;
  }

  .card-text {
    font-size: 0.9rem;
    opacity: 0.9;
  }

  .card-subtitle {
    font-size: 0.85rem;
    opacity: 0.75;
  }

  #pengalaman{
    padding-top: 5rem;
  }

  
  .table-hover tbody tr:hover {
    background-color: rgba(255, 255, 255, 0.2) !important;
    transition: all 0.3s ease-in-out;
  }

 

</style>