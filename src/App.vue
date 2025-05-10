<script>
import ClaseTransitions from './components/ClaseTransitions/ClaseTransitions.vue'
import ClaseTeleports from './components/ClaseTeleports/ClaseTeleports.vue'
import ClaseCicloDeVida from './components/ClaseCicloDeVida/ClaseCicloDeVida.vue'
import ClaseMixins from './components/ClaseMixins/ClaseMixins.vue'
import ClaseVariablesReactivas from './compositions/ClaseVariablesReactivas/ClaseVariablesReactivas.vue'

export default {
  name: 'App',
  components: {
    ClaseTransitions,
    ClaseTeleports,
    ClaseCicloDeVida,
    ClaseMixins,
    ClaseVariablesReactivas,
  },
}
</script>

<template>
  <div id="components">
    <ClaseTransitions class="card" />

    <ClaseTeleports class="card" />

    <ClaseCicloDeVida class="card" />

    <ClaseMixins />
  </div>

  <div id="composition">
    <ClaseVariablesReactivas class="card" />
  </div>
</template>

<style>
#components {
  margin: 1rem;
  border: 1px solid royalblue;
}

.card {
  margin: 1rem;
  border: 1px dotted white;
}

#composition {
  margin: 1rem;
  border: 1px solid rosybrown;
}
</style>
