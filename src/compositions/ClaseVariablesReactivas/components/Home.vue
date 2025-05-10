<template>
  <div>{{ obj.counter }}</div>
</template>

<script>
import { reactive } from 'vue'

export default {
  setup() {
    const obj = reactive({ counter: 0 })

    setInterval(() => obj.counter++, 1000)

    return {
      obj,
    }
  },
}
</script>
