<template>
  <UserRepositories :user="'Ricky'"></UserRepositories>
</template>

<script>
import UserRepositories from './components/UserRepositories.vue'

export default {
  name: 'CompositionAPI',
  components: { UserRepositories },
}
</script>
