<template>
  <HomeScriptSetup first-name="Ricky" last-name="Cortés"></HomeScriptSetup>
</template>

<script>
import HomeScriptSetup from './components/HomeScriptSetup.vue'
import { provide } from 'vue'

export default {
  name: 'ClaseScriptSetup',
  components: {
    HomeScriptSetup,
  },
  setup() {
    provide('username', 'RickyBv1')
  },
}
</script>
