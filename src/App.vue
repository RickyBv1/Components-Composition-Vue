<script>
import ClaseTransitions from './components/ClaseTransitions/ClaseTransitions.vue'
import ClaseTeleports from './components/ClaseTeleports/ClaseTeleports.vue'
import ClaseCicloDeVida from './components/ClaseCicloDeVida/ClaseCicloDeVida.vue'
import ClaseMixins from './components/ClaseMixins/ClaseMixins.vue'

export default {
  name: 'App',
  components: { ClaseTransitions, ClaseTeleports, ClaseCicloDeVida, ClaseMixins },
}
</script>

<template>
  <ClaseTransitions class="card" />

  <ClaseTeleports class="card" />

  <ClaseCicloDeVida class="card" />

  <ClaseMixins />
</template>

<style>
.card {
  margin-top: 2rem;
  border: 1px dotted white;
}
</style>
