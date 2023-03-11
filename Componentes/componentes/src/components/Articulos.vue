<template>
  <div>
    <table border="1">
      <tr>
        <td>Código</td>
        <td>Descripción</td>
        <td>Precio</td>
      </tr>
      <tr v-for="art in datos" :key="art.codigo">
        <td>{{art.codigo}}</td>
        <td>{{art.descripcion}}</td>
        <td>{{art.precio}}</td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  name: 'Articulos',
  props: {
    datos: Array
  }
}
</script>
