<script>
export default{
    name:" sosmed"
}

</script>

<template>

<!-- Sosial Media -->
<div id="sosmed" class="container mt-5">
  <h2 class="text-center text-white mb-4" style="font-family: 'Times New Roman', Times, serif;">Sosial Media</h2>
  <div class="border-top border-secondary mb-4" style="width: 50px; margin: auto;"></div>

  <div class="row text-white text-center">
    <div class="col-md-4 text-start">
      <a href="https://www.instagram.com/irn.nft" target="_blank" class="text-decoration-none text-light fs-5">
        <i class="bi bi-instagram text-danger fs-3 me-2"></i> <span class="fw-bold">irn.nft</span>
      </a>
    </div>
    <div class="col-md-4">
      <a href="https://www.tiktok.com/@lilllpann" target="_blank" class="text-decoration-none text-light fs-5">
        <i class="bi bi-tiktok text-light fs-3 me-2"></i> <span class="fw-bold">lilllpann</span>
      </a>
    </div>
    <div class="col-md-4 text-end">
      <a href="https://wa.me/6282212345678" target="_blank" class="text-decoration-none text-light fs-5">
        <i class="bi bi-whatsapp text-success fs-3 me-2"></i> <span class="fw-bold">0822-1234-5678</span>
      </a>
    </div>
  </div>

  <div class="border-top border-secondary mt-4"></div>
</div>



<!-- Alamat -->
  <div class="container mt-5">
  <div class="row">
    <div class="col-md-6">
      <h5 class="fw-bold text-white">Alamat</h5>
      <p class="text-white mb-0">
        Riau, Pekanbaru, Kec. Kampar Kiri Tengah <br>
        Kab. Kampar, Dusun Lubuk Baru <br>
        Desa Mekar Jaya, Jalur Blok D
      </p>
    </div>
  </div>
</div>

<!-- resume download -->
<div class="container mt-5 text-center">
  <a href="/src/assets/resume.pdf" class="btn btn-outline-primary rounded-3 px-4 py-2 shadow-sm fw-bold" download>
    <i class="bi bi-file-earmark-arrow-down"></i> Download Resume
  </a>
</div>

<div class="container mt-5 text-center">
  <blockquote class="blockquote">
    <p class="mb-0 text-light" style="font-family: 'Times New Roman', Times, serif; font-size: 1.5rem;">
      "Code is my canvas, creativity is my brush."
    </p>
    <footer class="blockquote-footer mt-2 text-white">
      Irfan Nurfathoni Putra
    </footer>
  </blockquote>
</div>

</template>

<style>
/* sosmed */
#sosmed a {
    transition: color 0.3s ease-in-out;
  }

  #sosmed a:hover {
    color: #0dcaf0 !important;
  }

  #sosmed .border-top {
    height: 2px;
  }

  #alamat {
    position: absolute;
    bottom: 20px;
    left: 20px;
    max-width: 300px;
    padding: 10px;
  }

  #alamat p {
    font-size: 14px;
  }

  #alamat i {
    transition: transform 0.3s ease-in-out;
  }

  #alamat:hover i {
    transform: scale(1.2);
  }

  #sosmed{
    padding-top: 5rem;
  }

</style>