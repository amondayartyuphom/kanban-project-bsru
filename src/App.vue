<template>
  <div id="app">
    <Kanban :data="data"/>
  </div>
</template>

<script>
import Kanban from "./components/Kanban"
export default {
  name: 'App',
  components: {
    Kanban
  },
data(){
  return{
    data:[
      {
        name:"todo",
        color:"#ff89d5",
        tasks:[]
      },
      {
        name:"todo",
        color:"#e0d572",
        tasks:[]
      },
      {
        name:"todo",
        color:"#F61E81",
        tasks:[]
      },
    ]
  }
}
}
</script>

<style>
#app {
  height: 100vh;
}
</style>
