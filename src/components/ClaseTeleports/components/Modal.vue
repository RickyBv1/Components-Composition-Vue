<template>
  <div>
    <button @click="toggle">Open</button>
    <teleport to="body">
      <div v-show="show" class="card">
        <h1>Title</h1>
        <p>lorem ipsum...</p>
        <button @click="toggle">Close</button>
      </div>
    </teleport>
  </div>
</template>

<script>
export default {
  data() {
    return {
      show: false,
    }
  },
  methods: {
    toggle() {
      this.show = !this.show
    },
  },
}
</script>
