<template>
  <section class="darksouls">
    <h2>Dark Souls</h2>
    <img src="@/assets/darksouls.jpg" alt="Dark Souls portada" class="game-cover" />
    <p>
      Dark Souls es un juego de rol de acción conocido por su dificultad extrema, 
      combates estratégicos y un mundo oscuro y misterioso que desafía a cada jugador.

      (Recomentado por Uriel :)
    </p>
    <button @click="verMas">Ver más</button>
  </section>
</template>

<script>
export default {
  name: "Darksouls",
  methods: {
    verMas() {
      alert("Prepárate para morir 💀⚔️");
    }
  }
};
</script>

<style scoped>
.darksouls {
  text-align: center;
  margin: 2rem;
  padding: 1rem;
  border: 2px solid #444;
  border-radius: 12px;
  background: #111;
  color: #eee;
  font-family: 'Arial', sans-serif;
}

.game-cover {
  width: 250px;
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
