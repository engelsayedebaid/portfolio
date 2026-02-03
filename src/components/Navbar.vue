<template>
  <nav class="navbar">
    <div class="navbar-container">
      <div class="navbar-logo">
        <a href="#home">Portfolio</a>
      </div>
      <ul class="navbar-menu">
        <li class="navbar-item">
          <a href="#home" class="navbar-link">Home</a>
        </li>
        <li class="navbar-item">
          <a href="#projects" class="navbar-link">Projects</a>
        </li>
        <li class="navbar-item">
          <a href="#contact" class="navbar-link">Contact</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar'
};
</script>

<style scoped>
.navbar {
  background-color: #333;
  padding: 1rem 0;
  position: sticky;
  top: 0;
  z-index: 100;
}

.navbar-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.navbar-logo a {
  color: white;
  font-size: 1.5rem;
  font-weight: bold;
  text-decoration: none;
}

.navbar-menu {
  display: flex;
  list-style: none;
  gap: 2rem;
}

.navbar-link {
  color: white;
  text-decoration: none;
  transition: color 0.3s ease;
}

.navbar-link:hover {
  color: #61dafb;
}
</style>