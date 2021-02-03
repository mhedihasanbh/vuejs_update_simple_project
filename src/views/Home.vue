<template>
  <div class="home">
    <Introduction></Introduction>
    <Dream></Dream>
    
  </div>
</template>

<script>
// @ is an alias to /src
import Introduction from '../components/home/Intudaction.vue'
import Dream from '../components/home/Dream.vue'


export default {
  name: 'Home',
  components: {Introduction,Dream}
   
  
}
</script>
