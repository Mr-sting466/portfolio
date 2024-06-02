<template>
  <div id="app">
    <PortfolioNavbar />
    <PortfolioAbout />
    <PortfolioProjects />
    <PortfolioSkills />
    <PortfolioExperience />
    <PortfolioContact />
  </div>
</template>

<script>
import PortfolioNavbar from './components/PortfolioNavbar.vue';
import PortfolioAbout from './components/PortfolioAbout.vue';
import PortfolioProjects from './components/PortfolioProjects.vue';
import PortfolioSkills from './components/PortfolioSkills.vue';
import PortfolioExperience from './components/PortfolioExperience.vue';
import PortfolioContact from './components/PortfolioContact.vue';

export default {
  name: 'App',
  components: {
    PortfolioNavbar,
    PortfolioAbout,
    PortfolioProjects,
    PortfolioSkills,
    PortfolioExperience,
    PortfolioContact
  }
}
</script>

<style>
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  margin: 0;
  padding: 0;
}
</style>
