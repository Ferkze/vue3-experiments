<template>
  <div>
    <h1>Hello Vue 3 Home!</h1>
    <button @click="inc">Clicked {{ count }} times.</button>
  </div>
</template>

<script>
import { ref } from 'vue'
export default {
  setup() {
    const count = ref(0)
    const inc = () => {
      count.value++
    }
    return {
      count,
      inc
    }
  }
}
</script>

<style>

</style>