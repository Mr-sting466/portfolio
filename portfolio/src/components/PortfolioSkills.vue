<template>
  <section id="skills" class="container bg-light">
    <h2>Compétences</h2>
    <ul class="list-unstyled">
      <li>Cybersécurité : Metasploit, NMAP, Suricata, Snort</li>
      <li>Programmation : Python, JavaScript, React.JS, OpenSSL, GitLab</li>
      <li>Systèmes d'exploitation : Microsoft, Linux</li>
      <li>Réseaux : Cisco DNA, Wireshark, VPN, IPsec, TCP, SSL</li>
      <li>Bases de données : MySQL</li>
      <li>Virtualisation & Monitoring : VMware, Docker, Nagios, SolarWinds</li>
      <li>Cloud Computing : AWS</li>
    </ul>
  </section>
</template>

<script>
export default {
  name: 'PortfolioSkills'
}
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: auto;
  padding: 60px 0;
}
ul {
  padding: 0;
}
li {
  list-style-type: none;
  color: #8892b0;
  margin-bottom: 10px;
}
</style>
