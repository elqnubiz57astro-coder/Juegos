<template>
  <footer class="footer">
    <p>© 2025 Gaming Zone | Todos los derechos reservados</p>
    <p>
      Síguenos en 
      <a href="https://twitter.com" target="_blank">Twitter</a> | 
      <a href="https://facebook.com" target="_blank">Facebook</a> | 
      <a href="https://instagram.com" target="_blank">Instagram</a>
    </p>
  </footer>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style scoped>
.footer {
  background: #111;
  color: #aaa;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
  border-top: 3px solid #444;
}
.footer a {
  color: #ffcc00;
  text-decoration: none;
}
.footer a:hover {
  color: #ff4500;
}
</style>