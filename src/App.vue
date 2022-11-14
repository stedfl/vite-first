<script>
import AppTitle from './components/AppTitle.vue';
export default {
  name: 'App',
  components: {
    AppTitle
  },
  data() {
    return {
      generalTitle: 'Hello World!'
    }
  }
}
</script>

<template>
  <div class="container">
    <div class="main-wrap">
      <h1 class="hello">{{generalTitle}}</h1>
      <AppTitle/>
    </div>
  </div>
  
</template>



<style>
.main-wrap {
  text-align: center;
  border: 1px solid white;
  padding: 2rem;
  border-radius: 10px;
}

h1 {
  font-size: 5rem;
}

</style>