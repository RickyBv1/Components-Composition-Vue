<template>
  <div class="card">
    <div>{{ text }}</div>
    <div>{{ secondText }}</div>
  </div>
</template>

<script>
import base from './mixins/base'

export default {
  name: 'ClaseMixins',
  mixins: [base],
  data() {
    return {
      text: 'Clase Mixins',
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
