<template>
  <in-construction section="AEIO" />
</template>

<script lang="ts">
import InConstruction from '~/components/extras/in-construction.vue'

export default {
  name: 'Aeio',
  components: { InConstruction },
  setup () {
    useHead({
      title: 'Asociación : AEIO'
    })
  }
}
</script>

<style scoped lang="scss">

</style>
