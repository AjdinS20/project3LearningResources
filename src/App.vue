<template>
  <div>
    <the-header title="RememberMe"></the-header>
    <the-resources></the-resources>
  </div>
</template>

<script>
import TheHeader from './components/page-layout/TheHeader.vue';
import TheResources from './components/learning-resources/TheResources.vue';
export default {
  name: 'App',

  components:{
    TheHeader,
    TheResources
  }
  
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap");
*{
  box-sizing: border-box;
}
html{
  font-family: 'Roboto', sans-serif;
}
body{
  margin: 0;
}
</style>
