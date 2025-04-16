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
    <img src="../src/assets/logo.svg" width="125" alt="Logo Vue">
    <small>
      <h1>Contador en Vue js</h1>
      <p>Desarrollado por: <a>Jean16</a></p>
    </small>
    <hr>
    <h2>Contador: {{ contador }}</h2>
    <button @click="incrementar()">+1</button>
    <button @click="decrementar()">-1</button>
    <button @click="resetear()">Reset</button>
  </div>
</template>

<style scoped>
.container {
  text-align: center;
  margin-block-start: 20px;
  border: 1px solid #ccc;
  padding: 20px;
}

h1{
  font-weight: bolder;
  font-size: 2.5rem;
}

small {
  font-size: 1.5rem;
  color: #2c3e50;
}

a{
  text-decoration: none;
  color: #42b983;
}

button {
  cursor: pointer;
  font-size: 1.2rem;
  padding: 5px 5px;
  margin: 0 8px;
  border-radius: .5rem;
  color: #fff;
  background: #42b983;

}
</style>
