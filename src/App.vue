<script>
import ClaseTransitions from './components/ClaseTransitions/ClaseTransitions.vue'
import ClaseTeleports from './components/ClaseTeleports/ClaseTeleports.vue'

export default {
  name: 'App',
  components: { ClaseTransitions, ClaseTeleports },
}
</script>

<template>
  <ClaseTransitions class="card" />

  <ClaseTeleports class="card" />
</template>

<style scoped>
.card {
  margin-top: 2rem;
  border: 1px dotted white;
}
</style>
