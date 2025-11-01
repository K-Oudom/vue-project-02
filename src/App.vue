<script>
  import Header from './views/Header.vue';
  export default{
    name:'App',
    components: {Header},
    setup(){

    },
  }
</script>

<template>
    <Header />
    <router-view />
</template>

<style scoped></style>