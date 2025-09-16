<template>
  <nav class="menu">
    <ul>
      <li><a href="#">Inicio</a></li>
      <li><a href="#darksouls">Dark Souls</a></li>
      <li><a href="#eldenring">Elden Ring</a></li>
      <li><a href="#portal">Portal</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "Menu"
};
</script>

<style scoped>
.menu {
  background: #222;
  padding: 0.8rem;
}
.menu ul {
  display: flex;
  justify-content: center;
  gap: 1.5rem;
  list-style: none;
  margin: 0;
  padding: 0;
}
.menu a {
  text-decoration: none;
  color: #eee;
  font-weight: bold;
  transition: 0.3s;
}
.menu a:hover {
  color: #ff4500;
}
</style>