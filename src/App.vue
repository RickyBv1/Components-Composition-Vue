<script>
import ClaseTransitions from './components/ClaseTransitions/ClaseTransitions.vue'
import ClaseTeleports from './components/ClaseTeleports/ClaseTeleports.vue'
import ClaseCicloDeVida from './components/ClaseCicloDeVida/ClaseCicloDeVida.vue'

export default {
  name: 'App',
  components: { ClaseTransitions, ClaseTeleports, ClaseCicloDeVida },
}
</script>

<template>
  <ClaseTransitions class="card" />

  <ClaseTeleports class="card" />

  <ClaseCicloDeVida class="card" />
</template>

<style>
.card {
  margin-top: 2rem;
  border: 1px dotted white;
}
</style>
