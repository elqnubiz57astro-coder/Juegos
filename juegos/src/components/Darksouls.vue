<template>
  <section class="darksouls">
    <h2>Dark Souls</h2>
    <img src="@/assets/darksouls.jpg" alt="Dark Souls portada" class="game-cover" />
    <p>
      Dark Souls es un juego de rol de acción conocido por su dificultad extrema, 
      combates estratégicos y un mundo oscuro y misterioso que desafía a cada jugador.
    </p>
    <button @click="verMas">Ver más</button>
  </section>
</template>

<script>
export default {
  name: "Darksouls",
  methods: {
    verTrailer(juego) {
      if (juego === "dark") {
        window.open("https://www.youtube.com/watch?v=8FgP4EY66Xg", "_blank"); // Dark Souls trailer
      } else if (juego === "elden") {
        window.open("https://www.youtube.com/watch?v=E3Huy2cdih0", "_blank"); // Elden Ring trailer
      }
    }
  }
};
</script>

<style scoped>
.games {
  text-align: center;
  margin: 2rem auto;
  max-width: 900px;
  padding: 1rem;
}

.game-card {
  border: 2px solid #444;
  border-radius: 12px;
  background: #111;
  color: #eee;
  font-family: 'Arial', sans-serif;
  padding: 1rem;
  margin: 1.5rem 0;
  box-shadow: 0 0 12px rgba(255, 255, 255, 0.2);
}

.game-card h3 {
  margin-bottom: 0.5rem;
  color: #ffcc00;
}

.game-cover {
  width: 300px;
  border-radius: 8px;
  margin: 1rem 0;
}

button {
  background: #ff4500;
  color: #fff;
  border: none;
  padding: 10px 20px;
  margin-top: 1rem;
  border-radius: 6px;
  cursor: pointer;
  font-weight: bold;
  transition: 0.3s;
}

button:hover {
  background: #e63e00;
}
</style>
