<template>
<div>
    <div :key="task.id" v-for="task in task">
  <h3>{{task.text}}</h3>
</div>
</div>

   
</template>

<script>
export default {
    name: 'Tasks',
    props: {
        tasks: Array,
    }
    
}

</script>