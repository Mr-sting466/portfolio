<template>
  <div id="app">
    <header>
      <h1>Donal NGAHAN</h1>
      <p>Étudiant en Architecture Systèmes, Réseaux et Cybersécurité</p>
    </header>
    <nav>
      <ul>
        <li><a href="#about">À propos de moi</a></li>
        <li><a href="#projects">Projets</a></li>
        <li><a href="#skills">Compétences</a></li>
        <li><a href="#experience">Expérience</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <section id="about">
      <h2>À propos de moi</h2>
      <p>Je suis étudiant en Master 2 à l'École IT de Paris, spécialisé en cybersécurité et réseaux. Je suis passionné par la protection des données et l'infrastructure réseau.</p>
    </section>
    <section id="projects">
      <h2>Projets</h2>
      <div class="project">
        <h3>Système de détection d'intrusion</h3>
        <p>Développement d'un système de détection d'intrusion pour PME.</p>
        <a href="https://github.com/votre-projet">Voir le projet</a>
      </div>
    </section>
    <section id="skills">
      <h2>Compétences</h2>
      <ul>
        <li>Cybersécurité : Metasploit, NMAP, Suricata, Snort</li>
        <li>Programmation : Python, JavaScript, React.JS, OpenSSL, GitLab</li>
        <li>Systèmes d'exploitation : Microsoft, Linux</li>
        <li>Réseaux : Cisco DNA, Wireshark, VPN, IPsec, TCP, SSL</li>
        <li>Bases de données : MySQL</li>
        <li>Virtualisation & Monitoring : VMware, Docker, Nagios, SolarWinds</li>
        <li>Cloud Computing : AWS</li>
      </ul>
    </section>
    <section id="experience">
      <h2>Expérience</h2>
      <p>Assistant Sécurité Informatique chez B.E.C La Routière, Ingénieur Réseaux Informatiques chez INFO-SERVICE, Assistant Cloud Computing chez CENADI.</p>
    </section>
    <section id="contact">
      <h2>Contact</h2>
      <p>Email : donalngahan466@gmail.com</p>
      <p>LinkedIn : <a href="http://www.linkedin.com/in/donal-ngahan">linkedin.com/in/donal-ngahan</a></p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}
header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}
nav ul {
    list-style: none;
    padding: 0;
}
nav ul li {
    display: inline;
    margin-right: 10px;
}
nav ul li a {
    color: #333;
    text-decoration: none;
}
section {
    padding: 20px;
    margin: 20px 0;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
</style>
