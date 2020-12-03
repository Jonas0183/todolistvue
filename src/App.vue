<template>
  <div id="app">
    <Head/>
    <TasksListBody/>
  </div>
</template>

<script>
import Head from '@/components/Head.vue';
import TasksListBody from './components/TasksListBody.vue';

export default {
  name: 'App',
  components:{
    Head,
    TasksListBody
  }
};
</script>
<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Signika&display=swap');
#app {
  height: 100%;
  background-color: #a3837f;
  max-width:800px;
  margin-top: 1vh;
  margin: auto;
  text-align: center;
  font-family: 'Signika', sans-serif;
}
</style>
