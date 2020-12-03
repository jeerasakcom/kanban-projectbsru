<template>
 <div id="app"><Kanban :data="data"/></div>
</template>

<script>
import Kanban from "./components/Kanban"
export default {
  name: 'App',
  components: {
    Kanban
  },
  data (){
    return{
      data:[
          {
            name:"todo",
            color:"#73edff",
            tasks:[]
            
          },
          {
             name:"todo",
             color:"#28adff",
             tasks:[]
          },
          {
             name:"todo",
            color:"#74caff",
             tasks:[]
          }

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