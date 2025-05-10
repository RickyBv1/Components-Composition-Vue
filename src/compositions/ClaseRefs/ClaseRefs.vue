<template>
  <HomeRefs first-name="Ricky" last-name="Cortés"></HomeRefs>
</template>

<script>
import HomeRefs from './components/HomeRefs.vue'
import { provide } from 'vue'

export default {
  name: 'ClaseRefs',
  components: {
    HomeRefs,
  },
  setup() {
    provide('username', 'RickyBv1')
  },
}
</script>
