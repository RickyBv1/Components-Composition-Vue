<template>
  <HomeProvideInject first-name="Ricky" last-name="Cortés" other="something"></HomeProvideInject>
</template>

<script>
import HomeProvideInject from './components/HomeProvideInject.vue'
import { provide } from 'vue'

export default {
  name: 'ClaseProvideInject',
  components: {
    HomeProvideInject,
  },
  setup() {
    provide('Username', 'RickyBv1')
  },
}
</script>
