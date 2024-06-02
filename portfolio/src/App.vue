<template>
  <div id="app" class="pt-5">
    <PortfolioNavbar />
    <PortfolioAbout />
    <PortfolioExperience />
    <PortfolioProjects />
    <PortfolioSkills />
    <PortfolioContact />
  </div>
</template>

<script>
import PortfolioNavbar from './components/PortfolioNavbar.vue';
import PortfolioAbout from './components/PortfolioAbout.vue';
import PortfolioExperience from './components/PortfolioExperience.vue';
import PortfolioProjects from './components/PortfolioProjects.vue';
import PortfolioSkills from './components/PortfolioSkills.vue';
import PortfolioContact from './components/PortfolioContact.vue';

export default {
  name: 'App',
  components: {
    PortfolioNavbar,
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
  padding-top: 70px; /* Ajustez cette valeur si nécessaire */
}
</style>
