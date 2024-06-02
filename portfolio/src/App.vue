<template>
  <div id="app" class="d-flex">
    <PortfolioSidebar />
    <div class="main-content">
      <PortfolioAbout />
      <PortfolioExperience />
      <PortfolioProjects />
      <PortfolioSkills />
      <PortfolioContact />
    </div>
  </div>
</template>

<script>
import PortfolioSidebar from './components/PortfolioSidebar.vue';
import PortfolioAbout from './components/PortfolioAbout.vue';
import PortfolioExperience from './components/PortfolioExperience.vue';
import PortfolioProjects from './components/PortfolioProjects.vue';
import PortfolioSkills from './components/PortfolioSkills.vue';
import PortfolioContact from './components/PortfolioContact.vue';

export default {
  name: 'App',
  components: {
    PortfolioSidebar,
    PortfolioAbout,
    PortfolioExperience,
    PortfolioProjects,
    PortfolioSkills,
    PortfolioContact
  }
}
</script>

<style>
body {
  font-family: 'Roboto', sans-serif;
  background-color: #0a192f;
  color: #ccd6f6;
  margin: 0;
  padding: 0;
}

#app {
  display: flex;
}

.main-content {
  margin-left: 25%; /* Correspond à la largeur de la barre latérale */
  width: 75%;
  padding: 20px;
  overflow: auto;
}

/* Responsive Design */
@media (max-width: 768px) {
  #app {
    flex-direction: column;
  }
  
  .main-content {
    margin-left: 0;
    width: 100%;
  }
}
</style>
