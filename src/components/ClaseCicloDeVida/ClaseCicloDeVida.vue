<template>
  <div>{{ text }}</div>
</template>

<script>
export default {
  name: 'ClaseCicloDeVida',
  data() {
    return {
      text: 'Ciclo de vida',
    }
  },
  beforeCreate() {
    console.log('beforeCreate', this.$data, this.$el)
  },
  created() {
    console.log('created', this.$data, this.$el)
  },
  mounted() {
    console.log('mounted', this.$data, this.$el)
  },
}
</script>
