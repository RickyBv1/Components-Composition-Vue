<script>
import ClaseTransitions from './components/ClaseTransitions/ClaseTransitions.vue'
import ClaseTeleports from './components/ClaseTeleports/ClaseTeleports.vue'
import ClaseCicloDeVida from './components/ClaseCicloDeVida/ClaseCicloDeVida.vue'
import ClaseMixins from './components/ClaseMixins/ClaseMixins.vue'
import CompositionAPI from './compositions/CompositionAPI/CompositionAPI.vue'

export default {
  name: 'App',
  components: { ClaseTransitions, ClaseTeleports, ClaseCicloDeVida, ClaseMixins, CompositionAPI },
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
    <CompositionAPI class="card" />
  </div>
</template>

<style>
#components {
  margin: 1rem 0;
  border: 1px solid royalblue;
}

.card {
  margin: 1rem 0;
  border: 1px dotted white;
}

#composition {
  margin: 1rem 0;
  border: 1px solid rosybrown;
}
</style>
