<template>
  <div id='root'>
    <img src='./logo.png' />
    <div id='nav'>
      <router-link to='/'> Home</router-link>
      <router-link to='/contact'>Contact </router-link>
    </div>
    <router-view />
  </div>
</template>

<script>
export default {
  setup() {
  }
}
</script>

<style scoped>
img {
  width: 200px;
}
h1 {
  font-family: Arial, Helvetica, sans-serif;
}
</style>