<template>
  <div id="app">
    <Head/>
  </div>
</template>

<script>
import Head from '@/components/Head.vue';

export default {
  name: 'App',
  components:{
    Head,
  }
};
</script>
<style lang="scss">
#app {
  height: 100%;
  background-color: #a3837f;
  max-width:1200px;
  margin-top: 1vh;
  margin: auto;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
}
</style>
