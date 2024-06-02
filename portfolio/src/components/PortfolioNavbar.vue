<template>
  <nav class="navbar navbar-expand-lg fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">Donal NGAHAN</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#about">À propos de moi</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#experience">Expérience</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#projects">Projets</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#skills">Compétences</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'PortfolioNavbar'
}
</script>

<style scoped>
.navbar {
  background-color: #0a192f;
  border-bottom: 1px solid #233554;
}
.navbar-brand {
  color: #64ffda;
}
.nav-link {
  color: #8892b0;
}
.nav-link:hover {
  color: #64ffda;
}
</style>
