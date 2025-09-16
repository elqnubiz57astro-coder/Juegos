<template>
  <header class="header">
    <img src="@/assets/logo_game.jpg" alt="Logo Gaming Zone" class="logo" />
    <h1>Gaming Zone</h1>
    <p>Recopilación de juegos favoritos 🎮🔥</p>
  </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
.header {
  text-align: center;
  background: #111;
  color: #ffcc00;
  padding: 1.5rem;
  border-bottom: 3px solid #444;
}
.logo {
  width: 80px;
  margin-bottom: 0.5rem;
}
</style>