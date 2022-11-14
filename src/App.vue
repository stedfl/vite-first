<script>
import AppTitle from './components/AppTitle.vue';
export default {
  name: 'App',
  components: {
    AppTitle
  }
}
</script>

<template>
  <div class="container">
    <h1>Hello!</h1>
    <AppTitle/>
  </div>
  
</template>



<style>
.container {
  width: 70%;
  margin: 0 auto;
}

</style>