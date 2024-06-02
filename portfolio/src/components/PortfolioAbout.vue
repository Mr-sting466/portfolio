<template>
  <section id="about" class="about-section container">
    <div class="about-text">
      <h2>Donal NGAHAN</h2>
      <h3>Étudiant en Architecture Systèmes, Réseaux et Cybersécurité</h3>
      <p>Je construis des expériences numériques engageantes et accessibles.</p>
    </div>
    <div class="about-links">
      <a href="#experience">Expérience</a>
      <a href="#projects">Projets</a>
      <a href="#skills">Compétences</a>
      <a href="#contact">Contact</a>
    </div>
  </section>
</template>

<script>
export default {
  name: 'PortfolioAbout'
}
</script>

<style scoped>
.about-section {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.about-text {
  flex: 1;
}
.about-links {
  display: flex;
  flex-direction: column;
}
.about-links a {
  color: #64ffda;
  text-decoration: none;
  margin-bottom: 1rem;
}
.about-links a:hover {
  text-decoration: underline;
}
</style>
