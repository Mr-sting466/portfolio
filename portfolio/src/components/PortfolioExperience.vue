<template>
  <section id="experience" class="container">
    <h2>Expérience</h2>
    <ul>
      <li>
        <h3>Assistant Sécurité Informatique</h3>
        <p>B.E.C La Routière, Mai à Juillet 2023</p>
        <p>Implémentation et configuration des systèmes de détection d'intrusion avec Snort et Wireshark.</p>
      </li>
      <li>
        <h3>Ingénieur Réseaux Informatiques</h3>
        <p>INFO-SERVICE, Janvier 2021 à Janvier 2022</p>
        <p>Gestion de la configuration et de l'optimisation des pare-feux et des systèmes de prévention d'intrusion.</p>
      </li>
      <li>
        <h3>Assistant Cloud Computing</h3>
        <p>CENADI, Juin à Août 2020</p>
        <p>Collaboration avec les équipes cybersécurité pour élaborer des plans d'intervention en cas d'incidents majeurs.</p>
      </li>
    </ul>
  </section>
</template>

<script>
export default {
  name: 'PortfolioExperience'
}
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: auto;
  padding: 60px 20px;
}
h2 {
  color: #64ffda;
  font-size: 2rem;
  margin-bottom: 1rem;
}
ul {
  list-style: none;
  padding: 0;
}
li {
  margin-bottom: 20px;
}
h3 {
  color: #ccd6f6;
}
p {
  color: #8892b0;
}
</style>
