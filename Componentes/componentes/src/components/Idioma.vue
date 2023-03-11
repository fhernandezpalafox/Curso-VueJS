<template>
    <div>
      <p v-if="idioma === 'castellano'">Hola mundo</p>
      <p v-if="idioma === 'ingles'">Hello world</p>
    </div>
  </template>
  
  <script>
  export default {
    name: 'AppIdioma',
    props: {
      idioma: String
    }
  }
  </script>
  