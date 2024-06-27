<template>
  <div class="container">
    <Headercomponents />
  </div>
  
</template>

<script>
  import { store } from './store';
  import Headercomponents from './components/HeaderComponent.vue';
  export default {
    components: {
      Headercomponents
    },
    name: 'App',
  }
</script>

<style lang="scss" scoped>
  .container {
    margin: 0 auto;
    margin-top: 20px;
  }
</style>