<script>
export default {
  data() {
    return {
      contador: 0
    }
  },
  methods: {
    incrementar() {
      this.contador++;
    },
    decrementar() {
      this.contador--;
    },
    resetear() {
      this.contador = 0;
    }
  },
}
</script>

<template>
  <div class="container">
    <img class="logo" src="../src/assets/logo.svg" width="125" alt="Logo Vue">
    <div class="header">
      <h1>Contador en Vue js</h1>
      <p>Desarrollado por: <a>Jean16</a></p>
    </div>
    <hr>
    <div class="counter-container">
      <h2>Contador: {{ contador }}</h2>
      <div class="buttons-container">
        <button class="btn incremet" @click="incrementar()">+1</button>
        <button class="btn decrement" @click="decrementar()">-1</button>
        <button class="btn reset" @click="resetear()">Reset</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  text-align: center;
  margin: 2rem auto;
  padding: 2rem;
  max-width: 600px;
  background-color: #f8f9fa;
  border-radius: 1rem;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.logo {
  margin-bottom: 1.5rem;
  transition: transform 0.3s ease;
}

.logo:hover {
  transform: scale(1.1);
}

.header {
  margin-bottom: 2rem;
}

h1{
  font-weight: 700;
  font-size: 2.5rem;
  color: #2e3e58;
  margin-bottom: .5rem;
}

a{
  text-decoration: none;
  color: #42b983;
  font-weight: 600;
  transition: color 0.3s ease;
}

a:hover{
  color: #3aa876;
}

hr{
  border: none;
  height: 2px;
  background-color: #e3ecef;
}

.counter-container {
  padding: 1rem;
}

.counter-value {
  color: #42b983;
  font-size: 3rem;
  font-weight: 700;
}

.buttons-container {
  display: flex;
  justify-content: center;
  gap: 1rem;
  margin-top: 2rem;
}

.btn {
  cursor: pointer;
  font-size: 1.2rem;
  padding: 0.3rem 1.5rem;
  border: none;
  border-radius: .5rem;
  color: #fff;
  font-weight: 600;
  transition: transform 0.2s ease, opacity 0.2s ease;
}

.btn:hover {
  transform: translateY(-2px);
  opacity: 0.9;
}

.incremet {
  background-color: #42b983;
}
.decrement {
  background-color: #e74c3c;
}
.reset {
  background-color: #3498db;
}
</style>
