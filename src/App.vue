<template>
  <div class="fond">
  <center><h1>Salut tout le monde. Je suis un developpeur web</h1></center>
  <center><img src="./images/Bizoux.jpg" alt="Bizoux"></center>
  <HelloWorld/>
</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>
  
<style scoped>
  .fond{
    background: rgb(21, 108, 148);
    height: auto;
  }
</style>
