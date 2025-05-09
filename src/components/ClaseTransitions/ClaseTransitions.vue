<template>
  <button @click="show = !show">Transition</button>
  <transition name="fade">
    <Menu v-show="show" />
  </transition>
</template>

<script>
import Menu from './Components/Menu.vue'

export default {
  name: 'ClaseTransitions',
  components: { Menu },
  data() {
    return {
      show: true,
    }
  },
}
</script>

<style>
.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}

.fade-leave-active,
.fade-enter-active {
  transition: opacity 0.5s ease;
}
</style>
