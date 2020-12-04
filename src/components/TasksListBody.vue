<template>
    <div>
        <tasks-list/>
        <new-task-input/>
    </div>
</template>

<script>
import NewTaskInput from '@/components/NewTaskInput.vue'
import TasksList from '@/components/TasksList.vue'
export default {
  components: { TasksList, NewTaskInput },
  props:{
    tasksArray:{
      type : Array,
      required: true,
      default(){
        return []
      }
    } 
  }
    
}
</script>

<style lang="scss">
    
</style>