<template>
  <section id="projects" class="container">
    <h2>Projets</h2>
    <div class="row">
      <div class="col-md-4" v-for="project in projects" :key="project.id">
        <div class="card mb-4 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">{{ project.title }}</h5>
            <p class="card-text">{{ project.description }}</p>
            <a :href="project.link" class="btn btn-primary" target="_blank">Voir le projet</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'PortfolioProjects',
  data() {
    return {
      projects: [
        {
          id: 1,
          title: 'Système de détection d\'intrusion',
          description: 'Développement d\'un système de détection d\'intrusion pour PME.',
          link: 'https://github.com/votre-projet'
        },
        // Ajoutez d'autres projets ici
      ]
    }
  }
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
.card {
  background-color: #233554;
  color: #ccd6f6;
  border: none;
}
.card-title {
  color: #64ffda;
}
.btn-primary {
  background-color: #64ffda;
  border: none;
}
</style>
