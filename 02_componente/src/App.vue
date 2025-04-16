<script>
  import TemplateCard from './components/TemplateCard.vue'

  export default {
    components: {
      TemplateCard
    }
  }
</script>

<template>
  <div>
    <h1>Componentes</h1>
    <hr>
    <div>
      <h2>Redes Sociales</h2>
    </div>
    <div class="grid">
      <TemplateCard
      url="https://www.google.com"
      title="Google"
      description="Google es un motor de búsqueda"
      img="https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_92x30dp.png"
      />
      <TemplateCard
      url="https://www.google.com"
      title="Google"
      description="Google es un motor de búsqueda"
      img="https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_92x30dp.png"
      />
      <TemplateCard
      url="https://www.google.com"
      title="Google"
      description="Google es un motor de búsqueda"
      img="https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_92x30dp.png"
      />
      <TemplateCard
      url="https://www.google.com"
      title="Google"
      description="Google es un motor de búsqueda"
      img="https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_92x30dp.png"
      />
    </div>
    <div>
      <h2>Frameworks</h2>
    </div>
    <div class="grid">
      <TemplateCard
      url="https://vuejs.org/"
      title="Vue"
      description="Vue es un framework de JavaScript"
      img="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRX6VVTo4D3bBuqZKHEsCdqIUeKoleEGJuNCQ&s"
      />
      <TemplateCard
      url="https://vuejs.org/"
      title="Vue"
      description="Vue es un framework de JavaScript"
      img="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRX6VVTo4D3bBuqZKHEsCdqIUeKoleEGJuNCQ&s"
      />
      <TemplateCard
      url="https://vuejs.org/"
      title="Vue"
      description="Vue es un framework de JavaScript"
      img="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRX6VVTo4D3bBuqZKHEsCdqIUeKoleEGJuNCQ&s"
      />
      <TemplateCard
      url="https://vuejs.org/"
      title="Vue"
      description="Vue es un framework de JavaScript"
      img="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRX6VVTo4D3bBuqZKHEsCdqIUeKoleEGJuNCQ&s"
      />
    </div>
  </div>
</template>

<style scoped>
.grid {
  display: flex;
  flex-wrap: wrap;
}
</style>
