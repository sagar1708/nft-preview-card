<template>
  <div >
    <div class="container-fluid">
      <div class="row justify-content-center align-items-center" style="height: 100vh">
        <div class="col-4">
          <Card msg="Welcome to Your Vue.js App"/>
        </div>
      </div>
    </div>
    
  </div>
</template>

<script>
import Card from './components/Card.vue'

export default {
  name: 'App',
  components: {
    Card 
  }
}
</script>

<style>
#app {
  height: 100vh;
}
</style>
