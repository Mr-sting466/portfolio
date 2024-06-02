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
  margin-right: 0%;
  margin-left: 40%; 
  width: 100%;
  padding: 20px;
  overflow: auto;
}
</style>
