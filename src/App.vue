<script setup>
import NavbarComponent from './components/navbar.vue';
import about from './components/about.vue';
import hobby from './components/hobby.vue';
import experience from './components/experience.vue';
import galeri from './components/galeri.vue';
import sosmed from './components/sosmed.vue';

window.addEventListener("scroll", function () {
    let navbar = document.querySelector(".navbar");
    if (window.scrollY > 50) {
      navbar.classList.add("scrolled");
    } else {
      navbar.classList.remove("scrolled");
    }
  });

</script>

<template>

  <section id="welcome" class="d-flex align-items-center justify-content-center vh-100 text-center text-light">
  <div>
    <h1 class="display-3 fw-bold" id="welcome-text">Welcome to My Portofolio</h1>
    <a href="#about" class="btn btn-outline-light mt-3 px-4 py-2">Explore</a>
  </div>
</section>


<NavbarComponent/>
<about/>
<hobby/>
<experience/>
<galeri/>
<sosmed/>

</template>

<style>
  /* welcome */
  .welcome-section {
    text-align: center;
  }

  .animate-text {
    opacity: 0;
    transform: translateY(20px);
    animation: fadeInUp 1.5s ease-out forwards;
  }

  @keyframes fadeInUp {
    0% {
      opacity: 0;
      transform: translateY(20px);
    }
    100% {
      opacity: 1;
      transform: translateY(0);
    }
  }

  .bg-transparent {
    background: rgba(100, 98, 98, 0.1);
    backdrop-filter: blur(10px);
    border-radius: 16px;
    padding: 20px;
  }

  .shadow-lg {
    box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.2);
  }

  #about{
    padding-top: 5rem;
  }
 
</style>
