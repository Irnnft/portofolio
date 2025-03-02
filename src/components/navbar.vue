<script>
export default {
    name: 'NavbarComponent'
}
</script>;

<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark shadow-sm fixed-top">
  <div class="container">
    <a class="navbar-brand fw-bold" href="#">My Profile</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link" href="#about">About Me</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#hobby">Hobby</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#pengalaman">Experience & Skills</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#desain">Poster Design</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#sosmed">Sosmed</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

</template>

<style>

.navbar {
    transition: background-color 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
  }

  .navbar.scrolled {
    background: rgba(0, 0, 0, 0.9);
    box-shadow: 0px 4px 10px rgba(255, 255, 255, 0.1);
  }

  .nav-link {
    position: relative;
    color: #f8f9fa !important;
    font-weight: 500;
    transition: color 0.3s ease-in-out;
  }

  .nav-link::after {
    content: "";
    display: block;
    width: 0;
    height: 2px;
    background: #f8d210;
    transition: width 0.3s;
    position: absolute;
    left: 50%;
    bottom: -5px;
    transform: translateX(-50%);
  }

  .nav-link:hover::after {
    width: 80%;
  }

  .nav-link:hover {
    color: #f8d210 !important;
    text-shadow: 0px 0px 10px rgba(255, 223, 0, 0.6);
  }

</style>