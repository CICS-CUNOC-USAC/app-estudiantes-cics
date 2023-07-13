<template>
  <v-container>
    <ContentDoc />
  </v-container>
<!--      ● ¿Como reproducir el error?-->
<!--      <br>-->
<!--      &emsp;Por ejemplo:-->
<!--      <br>-->
<!--      &emsp;&emsp;1. Abrir la seccion "Pensums"-->
<!--      <br>-->
<!--      &emsp;&emsp;2. Ingresar al Pensum de Ingenieria Civil-->
<!--      <br>-->
<!--      &emsp;&emsp;3. Pulsar "X" boton-->
<!--      <br>-->
<!--      &emsp;&emsp;4. Pulsar Enter-->
<!--      <br>-->
<!--      ● El comportamiento que se esperaba que ocurriera-->
<!--      <br>-->
<!--      ● Capturas de pantalla del error-->
<!--      <br>-->
<!--      ● Contexto adicional-->
<!--    </p>-->
<!--  </v-container>-->
</template>
<script lang="ts">
export default {
  emits: ['currentPage'],
  created () {
    this.$emit('currentPage', 'Acerca de')
  }
}
</script>
