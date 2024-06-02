<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
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
            <a class="nav-link" href="#projects">Projets</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#skills">Compétences</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#experience">Expérience</a>
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
  margin-bottom: 20px;
}
</style>
