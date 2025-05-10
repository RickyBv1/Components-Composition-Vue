<script>
import ClaseTransitions from './components/ClaseTransitions/ClaseTransitions.vue'
import ClaseTeleports from './components/ClaseTeleports/ClaseTeleports.vue'
import ClaseCicloDeVida from './components/ClaseCicloDeVida/ClaseCicloDeVida.vue'
import ClaseMixins from './components/ClaseMixins/ClaseMixins.vue'
import ClaseVariablesReactivas from './compositions/ClaseVariablesReactivas/ClaseVariablesReactivas.vue'
import ClaseWatch from './compositions/ClaseWatch/ClaseWatch.vue'
import ClaseComputed from './compositions/ClaseComputed/ClaseComputed.vue'
import ClaseProps from './compositions/ClaseProps/ClaseProps.vue'
import ClaseProvideInject from './compositions/ClaseProvideInject/ClaseProvideInject.vue'

export default {
  name: 'App',
  components: {
    ClaseTransitions,
    ClaseTeleports,
    ClaseCicloDeVida,
    ClaseMixins,
    ClaseVariablesReactivas,
    ClaseWatch,
    ClaseComputed,
    ClaseProps,
    ClaseProvideInject,
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

    <ClaseWatch class="card" />

    <ClaseComputed class="card" />

    <ClaseProps class="card" />

    <ClaseProvideInject />
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
