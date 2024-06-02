<template>
    <div class="sidebar">
      <div class="sidebar-content">
        <h1>Donal NGAHAN</h1>
        <p>Étudiant en Architecture Systèmes, Réseaux et Cybersécurité</p>
        <nav>
          <ul>
            <li><a href="about">À propos de moi</a></li>
            <li><a href="experience">Expérience</a></li>
            <li><a href="projects">Projets</a></li>
            <li><a href="skills">Compétences</a></li>
            <li><a href="contact">Contact</a></li>
          </ul>
        </nav>
        <div class="social-icons">
          <a href="https://github.com" target="_blank"><i class="fab fa-github"></i></a>
          <a href="https://www.linkedin.com/in/donal-ngahan" target="_blank"><i class="fab fa-linkedin"></i></a>
          <a href="mailto:donalngahan466@gmail.com"><i class="fas fa-envelope"></i></a>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'PortfolioSidebar'
  }
  </script>
  
  <style scoped>
  .sidebar {
    position: fixed;
    top: 0;
    left: 0;
    width: 25%;
    height: 100%;
    background-color: #0a192f;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    color: #ccd6f6;
    padding: 20px;
  }
  
  .sidebar-content {
    text-align: center;
  }
  
  .sidebar h1 {
    color: #64ffda;
    font-size: 2rem;
    margin-bottom: 0.5rem;
  }
  
  .sidebar p {
    color: #8892b0;
    margin-bottom: 1.5rem;
  }
  
  .sidebar nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
  }
  
  .sidebar nav ul li {
    margin-bottom: 1rem;
  }
  
  .sidebar nav ul li a {
    color: #8892b0;
    text-decoration: none;
    font-size: 1.1rem;
  }
  
  .sidebar nav ul li a:hover {
    color: #64ffda;
  }
  
  .social-icons {
    display: flex;
    justify-content: center;
    margin-top: 1.5rem;
  }
  
  .social-icons a {
    color: #ccd6f6;
    font-size: 1.5rem;
    margin: 0 0.5rem;
  }
  
  .social-icons a:hover {
    color: #64ffda;
  }
  </style>
  