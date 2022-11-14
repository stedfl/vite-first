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
    <div class="main-wrap">
      <h1>Hello World!</h1>
      <AppTitle/>
    </div>
  </div>
  
</template>



<style>
.main-wrap {
  text-align: center;
}

</style>