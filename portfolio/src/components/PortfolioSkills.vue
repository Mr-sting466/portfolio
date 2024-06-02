<template>
  <section id="skills" class="container skills-section">
    <h2>Mes Compétences</h2>
    <p class="skills-intro">
      Passionné par les systèmes et réseaux, je suis compétent en cybersécurité et gestion des incidents. 
      Maîtrise des techniques de cryptographie et des protocoles de sécurité pour garantir la protection des données sensibles.
      Transformez vos données en informations précieuses pour améliorer la sécurité et l'efficacité de votre infrastructure.
    </p>
    <div class="skills-cards">
      <div class="card-skill devops">
        <i class="fas fa-tools"></i>
        <h3>Sécurité des Réseaux</h3>
        <p>Analyse des vulnérabilités, gestion des incidents et configuration des pare-feux.</p>
      </div>
      <div class="card-skill development">
        <i class="fas fa-code"></i>
        <h3>Programmation</h3>
        <p>Développement en Python, implémentation d'algorithmes de chiffrement et développement web.</p>
      </div>
      <div class="card-skill database">
        <i class="fas fa-database"></i>
        <h3>Cloud Computing</h3>
        <p>Mise en place de cloud privé, archivage et sauvegarde des données.</p>
      </div>
      <div class="card-skill cms">
        <i class="fas fa-shield-alt"></i>
        <h3>Test de Pénétration</h3>
        <p>Utilisation d'outils comme Metasploit et Nmap pour tester la sécurité des systèmes.</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'PortfolioSkills'
}
</script>

<style scoped>
.skills-section {
  text-align: center;
  color: #ccd6f6;
  margin: 50px 0;
}

.skills-intro {
  font-size: 1.2rem;
  color: #8892b0;
  margin-bottom: 2rem;
}

.skills-cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.card-skill {
  background-color: #112240;
  border-radius: 10px;
  padding: 20px;
  width: 250px;
  text-align: center;
  transition: transform 0.3s, box-shadow 0.3s;
}

.card-skill i {
  font-size: 3rem;
  margin-bottom: 10px;
}

.card-skill h3 {
  color: #64ffda;
  margin-bottom: 10px;
}

.card-skill p {
  color: #8892b0;
  font-size: 1rem;
}

.card-skill:hover {
  transform: translateY(-10px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.devops {
  background-color: #6c63ff;
}

.development {
  background-color: #007bff;
}

.database {
  background-color: #38a1db;
}

.cms {
  background-color: #ffd700;
}
</style>
