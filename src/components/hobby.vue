<script>
export default{

    name : "hobby",

}
</script>

<template>
    <div id="hobby" class="container mt-5">
  <h2 class="text-center text-white mb-4" style="font-family: 'Times New Roman', Times, serif; font-weight: 600;">Hobi</h2>

  <div class="row row-cols-1 row-cols-md-3 g-4">
    <div class="col">
      <div class="card hobby-card h-100 border-0">
        <img src="/src/assets/dumble.jpg" class="card-img-top" style="object-fit: contain; height: 250px; background-color: #222;">
        <div class="card-body">
          <h5 class="card-title fw-bold text-white">Work Out</h5>
          <p class="card-text text-light" style="font-size: 0.9rem;">Saya sangat menikmati work out sebagai cara untuk menjaga kesehatan fisik dan mental. Work out membantu meningkatkan kebugaran tubuh, mengurangi stres, dan meningkatkan fokus.</p>
        </div>
        <div class="card-footer border-0 bg-transparent">
          <small class="text-light">Hobby sejak lama</small>
        </div>
      </div>
    </div>

    <div class="col">
      <div class="card hobby-card h-100 border-0">
        <img src="/src/assets/poster VOID.jpg" class="card-img-top" style="object-fit: contain; height: 250px; background-color: #222;">
        <div class="card-body">
          <h5 class="card-title fw-bold text-white">Membuat Poster</h5>
          <p class="card-text text-light" style="font-size: 0.9rem;">Saya menyukai desain grafis dan senang mengekspresikan kreativitas dalam membuat poster yang menarik secara visual dan informatif.</p>
        </div>
        <div class="card-footer border-0 bg-transparent">
          <small class="text-light">Hobby yang baru ditekuni</small>
        </div>
      </div>
    </div>

    <div class="col">
      <div class="card hobby-card h-100 border-0">
        <img src="/src/assets/catur.jpg" class="card-img-top" style="object-fit: contain; height: 250px; background-color: #222;">
        <div class="card-body">
          <h5 class="card-title fw-bold text-white">Catur</h5>
          <p class="card-text text-light" style="font-size: 0.9rem;">Catur melatih berpikir strategis dan analitis. Saya menikmati tantangan dalam menyusun strategi untuk memenangkan permainan.</p>
        </div>
        <div class="card-footer border-0 bg-transparent">
          <small class="text-light">Sudah sejak lama</small>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<style>
 body {
    background: #111; 
    color: white;
  }

  .hobby-card {
    background: rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(10px);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    border-radius: 16px;
    overflow: hidden;
  }

  .hobby-card:hover {
    transform: scale(1.05);
    box-shadow: 0 10px 20px rgba(238, 238, 238, 0.568);
  }

  .card-body {
    padding: 20px;
  }

  .card-text {
    text-shadow: 1px 1px 2px rgba(54, 52, 52, 0.7);
  }

  .card-footer small {
    font-weight: 500;
  }

  #hobby{
    padding-top: 5rem;
  }
</style>