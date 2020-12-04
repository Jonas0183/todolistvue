<template>
    <div>
        <form @submit.prevent="saveTask">
            <input v-model="newTask" placeholder="Escribe tarea pendiente">
        </form>
    </div>
</template>

<script>
import tasksArray  from '@/components/TasksListBody.vue';
export default {
    Components:{
        tasksArray
    },
    data() {
        return {
            newTask:''
        }
    },
    methods(){
        const saveTask = () => {
            this.tasksArray.push(this.newTask);
            this.newTask = '';
            return tasksArray;
        }
    }
};
</script>

<style lang="scss">
    
</style>