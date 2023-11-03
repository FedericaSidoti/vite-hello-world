<script>
import Apphero from '../src/components/Apphero.vue';
export default {
  data() {
    return {
      message: 'La mia prima app con Vite!'
    }
  },
  components : {
  Apphero
  }
}
</script>

<template>
  <h1> {{ message }}</h1>
      <Apphero/>
</template>

<style scoped>

</style>
