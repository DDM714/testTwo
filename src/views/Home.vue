<template>
  <div class="home">
    父页
    <Hello></Hello> 
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
import Hello from '../../sub/testOne/Hello.vue'

export default {
  name: 'Home',
  components: {
    Hello
  }
}
</script>
