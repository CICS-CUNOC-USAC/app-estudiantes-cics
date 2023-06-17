<template>
  <v-container class="mt-4">
    <p>
      La Asociacion de Estudiantes de Ingenieria de Occidente es la asociacion de estudiantes de la Division de Ciencias de la Ingenieria del CUNOC.
      Su objetivo es la promocion y coordinacion de planes, programas y proyectos en busca del beneficio y el bienestar de la comunidad.
    </p>
    <br>
    <h2>
      Directiva de la Asociacion
    </h2>
    <v-divider thickness="3" />
    <p>
      Los miembros del comite de la AEIO-2023 son:
      <br>
      <br>
      ● Julio Fernando Ixcoy (Secretario General)
      <br>
      ● Devir Augusto Moreno (Subsecretario General)
      <br>
      ● Angel Antonio Lopez (Secretario de Finanzas)
      <br>
      ● William Alejandro Castillo (Secretario de Actas)
      <br>
      ● Abner Alberto Hernandez (Secretario de Informatica)
      <br>
      ● Miguel Osvaldo Gonzales (Subsecretario de Informatica)
      <br>
      ● Allan Jose Lopez (Secretario de Asuntos Estudiantiles)
      <br>
      ● Gregorio Anderson Paxtor (Secretario de Biblioteca)
      <br>
      ● Daniel Clemente Peneleu (Secretario de Relaciones Publicas)
      <br>
      ● Vicente Anddy Yac (Secretario de Asuntos Nacionales)
      <br>
      ● Victor Sebastian Zapil (Secretario de Actividades Deportivas)
      <br>
      ● Christopher Neftali Mendez (Secretario de Cultura)
      <br>
      ● Dafny Teresita de Jesus Valenzuela (Representante de Primer Ingreso)
      <br>
      ● Allan Josue Leon (Representante de Primer Ingreso)
    </p>
    <br>
    <h2>
      Contacto
    </h2>
    <v-divider thickness="3" />
    <p>
      ● Correo Electronico (aeiocunoc2016@gmail.com)
      <br>
      ● <a
        href="https://www.facebook.com/AEIO.CUNOC/"
        target="_blank"
      >Facebook</a>.
    </p>
    <br>
    <h2>
      Reglamento
    </h2>
    <v-divider thickness="3" />
    <v-container>
      <InConstruction :section="'Reglamento'" />
    </v-container>
  </v-container>
</template>

<script lang="ts">
import InConstruction from '~/components/extras/in-construction.vue'

export default {
  name: 'Aeio',
  components: { InConstruction },
  emits: ['currentPage'],
  created () {
    this.$emit('currentPage', 'AEIO')
  }
}
</script>

<style scoped lang="scss">

</style>
