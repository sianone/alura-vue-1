<template>
  <div>
    <h1>{{ titulo }}</h1>
    <ul>
      <li v-for="foto of fotos">
        <img :src="foto.url" :alt="foto.titulo">
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      titulo: 'Alurapic',
      fotos: [
        {
          url: 'https://blog.casadoprodutor.com.br/wp-content/uploads/2018/06/papagaio-1024x576.jpg',
          titulo: 'Papagaio'
        },
        {
          url: 'https://blog.casadoprodutor.com.br/wp-content/uploads/2018/06/papagaio-1024x576.jpg',
          titulo: 'Papagaio2'
        }
      ]
    }
  }
}
</script>

<style>

</style>
