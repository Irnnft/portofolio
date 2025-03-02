<script>
export default{

    name: "galery"
}
</script>

<template>

<div id="desain" class="container mt-5">
  <h2 class="text-center text-white mb-4" style="font-family: 'Times New Roman', Times, serif;">Hasil Desain Poster</h2>
  <div class="row row-cols-1 row-cols-md-2 g-4">
    <div class="col">
      <div class="card shadow-lg border-0 rounded-4 overflow-hidden bg-transparent">
        <img src="/src/assets/poster VOID.jpg" class="card-img-top img-fluid poster-img" alt="Poster 1">
      </div>
    </div>
    
    <div class="col">
      <div class="card shadow-lg border-0 rounded-4 overflow-hidden bg-transparent">
        <img src="/src/assets/poster love.jpg" class="card-img-top img-fluid poster-img" alt="Poster 4">
      </div>
    </div>
  </div>
</div>

</template>

<style>
.poster-img {
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    border-radius: 10px;
  }
  
  .poster-img:hover {
    transform: scale(1.05);
    box-shadow: 0 0 15px rgba(255, 255, 255, 0.5);
  }

  #desain{
    padding-top: 5rem;
  }
</style>