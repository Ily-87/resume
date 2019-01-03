

<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App" :datum="new Date().toString()"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Future from '@/components/Future.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
